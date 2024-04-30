---
aliases: 
tags: []
---
- A digital event-driven implementation of [[Cognitive Tinker Frame|an idea]] I had in 2022
- It can be thought of as a novel form of **personal digital assistant**
	- that is **voice-driven** thanks to OpenAI Whisper
	- that utilizes my plaintext (Markdown) [[personal knowledge management system]]
	- with rudimentary natural language processing (no LLM integration completed or planned at the time of this writing)
- I think of it as an augmented intelligence platform with different potential [[Thinking with Code|application]]s
	- Not "AI" in the sense that it is intended to support a human, not operate fully without supervision
- Implementation
	- [Akka 2.6](https://doc.akka.io/docs/akka/2.6/typed/guide/actors-motivation.html) -
		- "cast" is word play with the [actor model](https://en.wikipedia.org/wiki/Actor_model) 
		- ...and the feeling of casting/"magic" that using a voice-driven interface can inspire
	- OpenAI Whisper (audio transcription)
	- Rasa open source (natural language processing)
	- Inspired by [[Maps of Content (MOCs)]]
