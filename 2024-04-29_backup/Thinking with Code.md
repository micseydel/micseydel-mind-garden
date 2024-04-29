## Example - how to deal with a headache?

Let's say you have the problem that you're not sure if **naproxen** or **ibuprofen** works better for you. The following would not be complicated:
* Flip a coin to pick which to take, then take it after [[Externalized cognition|noting]] the severity, time and dose
* Set a timer to check-in on the severity after some amount of time, and update notes
* Use [math](https://arbital.com/p/bayes_rule/?l=1zq) to continuously [[Calibration|calibrate]] confidence level

Someone who has a headache is definitely going to be down to take copious notes, set one or more timers, take more notes, and then do the math, right? [Right??](https://knowyourmeme.com/memes/for-the-better-right)

## Automated science

I could in theory simply use [[Externalized cognition|my notes and any timer]] to accomplish the above. Realistically though my "second brain" is not enough, since I have to do all the effort around managing that data and I just can't consistently find the motivation. Surely apps exist that might help, but I would ultimately have to manually [[Integration|integrate]] their output into my personal notes, after researching, trying out, and getting comfortable with, apps that could [change at any time](https://techcrunch.com/2023/02/27/bending-spoons-lays-off-129-evernote-staffers/).

What I need is an external system that can takeover as much of what I described above as possible. I am lucky enough to be a software engineer so this situation could be improved with a chat bot. All I have to do is text it saying I have a headache, and then it can "flip a coin" for me, remind me what to do take notes on, set any timers, then use math and generate a (Markdown!) report for me.

## [[My Tinker Cast]]

The above has been lightly edited from a time before my tinker cast is what it is today. I now have a system in which I can take voice notes, and manually write code by hand that listens for particular notes and does whatever I want based on those voice memos -
- Control my smart lights
- Track things about my cats, create reports and reminders
- Send me a push notification to remind me to eat
- Anything relevant to a hypothesis or question
	- e.g.
		- "I want to bring the trash bins in more quickly" becomes "by what time are the bins typically emptied?"
		- A listener might collect "trash" or "garbage" or "recycling" notes
		- The result can be a list to be reviewed manually
		- Or listeners can update actors that generate reports, create reminders, etc.
