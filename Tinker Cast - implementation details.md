---
created: 2024-05-20T15:28:05-07:00
updated: 2024-05-20T15:28:14-07:00
---
- [Akka 2.6](https://doc.akka.io/docs/akka/2.6/typed/guide/actors-motivation.html) -
	- "cast" is word play with the [actor model](https://en.wikipedia.org/wiki/Actor_model) 
	- ...and the feeling of casting/"magic" that using a voice-driven interface can inspire
	- This is the basis for the [[Graph visuals]]
- [OpenAI Whisper](https://openai.com/research/whisper) (audio transcription)
	- Capture on Android via [Easy Recorder](https://play.google.com/store/search?q=easy%20recorder&c=apps&hl=en&gl=US)
	- Sync via [Syncthing](https://syncthing.net/)
	- [JVM folder watcher API](https://docs.oracle.com/javase/tutorial/essential/io/notification.html) detects sync'd files
	- Flask hosts Whisper for the Akka cast to access; I've looked into Docker, faster-whisper and other stuff but have stuck with my original
- [Rasa open source](https://rasa.com/docs/rasa/#rasa-open-source) (natural language processing, entity extraction)
	- Here's a good example of [[Idea Provenance]] where I spoke groggily ("the back litter box was dirty")
		- ![[Pasted image 20240528120816.png]]
- Inspired by [[Maps of Content (MOCs)]]
- [[Why my Tinker Cast is not open-source|Why is this not open source?]]
