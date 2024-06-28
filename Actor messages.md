This is the real code I used at the time of this writing for my [[H.A.L.T.-inspired neuron|H.A.L.T neuron]], which realistically just does
- Hungry
- Angry
- Tired
- CO2
Or HACT 🤷

Here's the highly-level but *real-code* set of events 

```scala
sealed trait Event {  
  def eventTime: ZonedDateTime  
}

case class ReceiveHungerState(state: HungerState) extends Event {
  override def eventTime: ZonedDateTime = state.lastAte.at
}

case class ReceiveFrustrationDetected(detected: FrustrationListener.DistressDetected) extends Event {
  override def eventTime: ZonedDateTime = detected.notedTranscription.capture.captureTime
}

case class ReceiveSleepReport(sleepReport: SleepReport) extends Event {
  override def eventTime: ZonedDateTime = sleepReport.sleep.map(_.endTime).max
}

case class ReceiveAranetResult(aranetResult: AranetResults) extends Event {
  override def eventTime: ZonedDateTime = aranetResult.meta.captureTime
}
```
