Building a game about teaching: Part 1

The Beta version is currently out and free to play here: https://classroom-simulator.vercel.app/

Recently I released the beta version of my game Classroom Simulator. It is a game about teaching. You play as a Professor teaching a free elective class at a university and the goal of the game is to keep your
students from failing the course. Each student is an AI agent that has their own distinct personality and interests. Teaching them their interests improves the relationship you have with that student. This is represented by
a mechanic in the game called trust. A low trust value results in the student being more skeptical of you and needing more time (a sparse resource) to be invested in order to teach them. A high trust value results in the opposite.
Less time needing to be invested and total belief in whatever you teach them. With gaining the students trust you will not have enough time to teach all of them which results in them failing.

Using LLMs models allows for the opportunity to explore a game mechanic that has not yet existed, teaching! Teaching at it's core is the statement of an idea and then the comprehending of that idea
or the lack of comprehending. LLMs allow for the generation of dialogue based on whatever the user decides to teach their students. Want to have a conversation with a student who now believes that Tom Cruise is a 
hippo who lives in the New York Zoo? Go ahead! Your students will hang onto every word of your teachings Professor! Simulate any idea that you want.

I started think about this idea back when GPT-3 was released. I had gone back to college at the tail end of the pandemic to finish a degree in Computer Science and was eager to explore new ideas with the technology. The seedling that grew into Classroom Simulator
was my experience with the online discussions happening in class during lockdown. The quality of the discussions happening was subpar and I thought GPT-3 might be able to simulate a more lively conversation.
Also during that time I would play Final Fanatasy 7 Remake every night and like any good software engineer I thought "What if I could discuss theory with Cloud and Tifa?", two characters in the game. This would 
be an interesting way to explore a topic since each character has their own distinct personalities. The bots could help guide the user through whatever topic they were learning helping them arrive at a conclusion.
Expanding on this I thought that maybe I could have a character who was intelligent and always provide correct interpretations of the topic and in contrast maybe there could be a character who was a bit of a dunce who
would try and mislead the user to a conslusion that was wrong. This would allow for more comical dialogue to play out while still being educational.

However, there was one problem. What if the LLM halucinates? If the character who is always suppose to be right halucinates and provides incorrect information this would not be a good user expereince. And on top of that,
I wanted the user to be able to explore any topic they were learning. What if they were learning something recently discovered past the LLMs last training. I decided this might not be the right direction
and continued experimenting with other ideas.

I was reading about training models and then that's when it hit me. Training the models...teaching the models! What if instead the user has to teach the characters in the game? I bring the interaction and engineer
would have with a model up to a user level. The models could just use the context the user provided on the subject to create dialogue. This would solve the issue with the training date and allow for hallucinations 
to not be a bug but a feature. On top of that teaching is a great way to learn a subject deeply. I noticed this in the students who became teaching assistants at the university. Going from being a student, grinding 
through the course work one semester and then teaching that subject the next is very empowering. Your perspective on the course work you were just struggling through as a student one semester has changed completely 
allowing for a deeper understand of the subject matter.


This changing of perspective is something everyone can benefit from. However, it is not something that has been scalable, until now with LLMs!
