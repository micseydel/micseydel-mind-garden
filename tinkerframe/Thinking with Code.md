## Example - how to deal with a headache?

Let's say you have the problem that you're not sure if naproxen or ibuprofen works better for you. The following would not be complicated:
* Flip a coin to pick which to take, then take it after [[Personal knowledge management systems (PKMS)|noting]] the severity, time and dose
* Set a timer to check-in on the severity after some amount of time, and update notes
* Use [math](https://arbital.com/p/bayes_rule/?l=1zq) to continuously [[Calibration|calibrate]] confidence level

Someone who has a headache is definitely going to be down to take copious notes, set one or more timers, take more notes, and then do the math, right? [Right??](https://knowyourmeme.com/memes/for-the-better-right)

## Automated science

I could in theory simply use [[My Mind Graph]] and any timer to accomplish the above. Realistically though my "second brain" is not enough, since I have to do all the effort around managing that data and I just can't consistently find the motivation. Surely apps exist that might help, but I would ultimately have to manually [[Integration|integrate]] their output into my personal notes.

What I need is an external system that can takeover as much of what I [[Encoding|described]] above as possible. I am lucky enough to be a software engineer so this situation could be improved with a chat bot. All I have to do is text it saying I have a headache, and then it can "flip a coin" for me, remind me what to do take notes on, set any timers, then use math and generate a (Markdown!) report for me.

## Always building

The above could be built by any competent coder. A mobile dev could eliminate the dependency on SMS infrastructure, and in fact I plan on using SMS first because I have more experience with it even though it wouldn't work during a hike.

Once I've built the SMS part of the code, I could connect that to a *different* chat bot. I could also continue developing the chat bot and leave the SMS code alone. Or I could replace SMS but still re-use the logic around doing the math and generating a report.

Once this system is in place, it's not hard to tinker on it. Instead of flipping a coin, it can weight the probability of its suggestions based on how confident it is the intervention will work. It could be expanded past just two interventions. I might add Alexa voice support so that I don't have to touch my phone.

In terms of [[Explore-exploit tradeoff]]s, I would say that I plan to be in a permanent explore phase, and [[My Cognitive Tinkerframe]] is what I want to build right now so that as I get busier later in life, I don't lose out on my ability to explore. [[What is Building a Second Brain (BASB)|Tiago Forte]] is someone who clearly did exploring in order to deal with his illness, but seems to focus on exploit for now.
