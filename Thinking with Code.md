---
created: 2024-05-20T15:28:05-07:00
updated: 2024-05-20T15:28:14-07:00
---
## Example - how to deal with a headache?

Let's say you have the problem that you're not sure if **naproxen** or **ibuprofen** works better for you. The following would not be complicated:
* **Flip a coin** to pick which to take, then take it after [[Externalized cognition|noting]] the severity, time and dose
* **Set a timer** to check-in on the severity after some amount of time, and update notes
* Use [math](https://arbital.com/p/bayes_rule/?l=1zq) to **continuously calibrate** confidence level

Someone who has a headache is definitely going to be down to take copious notes, set one or more timers, take more notes, and then do the math, right? [Right??](https://knowyourmeme.com/memes/for-the-better-right)

## Example - picking OTC's with science

An easier flow than the above would be
- tell your personal digital assistant you have a headache
- it picks between the two options
- 30 or 60 (for example) minutes later, it can ask how your headache is doing
- update some knowledge store
	- ...by updating its model and confidence level based on the new data
	- ...then providing a report after a certain confidence level / datapoint count is hit

Further science might include
- More than two options, e.g. acetaminophen or meditation
- A "placebo" option - "take no action" and it follows ups as usual
- Other experiments like determining when trash collection typically happens

# LLMs can benefit as well

- https://arxiv.org/abs/2210.07128 (via [r/LocalLLAMA](https://www.reddit.com/r/LocalLLaMA/comments/14ajglx/comment/joazy4z/?utm_source=share&utm_medium=web2x&context=3))
	- > In this paper, we show that when we instead frame structured commonsense reasoning tasks as code generation tasks, ==pre-trained LMs of code are better structured commonsense reasoners than LMs of natural language==, **even when the downstream task does not involve source code at all**. Thus, our main insight is that large language models of code are good structured commonsense reasoners. Further, we show that Code-LLMs can be even better structured reasoners than NL-LLMs (LLMs of natural language).
