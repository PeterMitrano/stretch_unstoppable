# Stretch Unstoppable

Training a policy, by any means necessary, to make stretch do whatever I want really really well ... in simulation. 

If we succeed, we will beg Hello Robot to send a stretch so we can make it work in the real world.

# Tasks

This is a list of things I'd like my home robot to be able to do

 - [ ] Open and close my blinds
 - [ ] Tidy my bed
 - [ ] Pick up clothes off the floor and put them in the laundry basket
 - [ ] Make sure the fridge and freezer are closed
 - [ ] Make sure the front door is locked
 - [ ] Close & latch my windows

# Roadmap

Some vague notes for my own planning purposes

- [ ] Start by exploring existing open source projects, to pick and choose some tools to use. Althogh, I intend to write most things myself since this is an educational project.
- [ ] Choose some simple tasks not focusing on any one task for too long or worrying about optimizing speed or task performance pre-maturely. I think diversity is key to generaliztaion, and I don't want to get bored focusing on one thing for too long and have the project stop being fun!
- [ ] Transition from mediocre single-task policies to mediocre multi-task policies
- [ ] Focus on reducing the time-to-new-skill!

... many months later ...

- [ ] Get someone to give me a stretch so I can test it in the real world!

# Goals & Methods

I am not interested in any model-based methods, and I have a bias towards new methods that help me learn things.
I expect behavior cloning from teleop and human-in-the-loop RL to be the two primary learning algorithms used.
But more important than that is going to be design of the physics simulation, curriculum, environments, tasks, rewards, etc.
I plan to keep a detailed log of my work in the git messages.
I also plan to keep this whole endeavor open-source, but I do not intend to document extensively or publish anything.
Always keep asking the question "will this transfer to the real world?"

# Out-of-scope

- [ ] Other robots
- [ ] Simulators besides MuJoCo
- [ ] Speech commands, high level task orchestration, or "chat" interfaces
