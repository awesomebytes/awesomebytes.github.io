---
published: true
---
## My experience at the Moveit Hackathon in Guiyang, China

![moveit hackathon web]({{site.baseurl}}/_posts/moveithackathon.png)


From the 09 to the 13 of March 2018 the event called [Moveit Hackathon](https://www.pixmoving.com/move-it) took part. I found about it at the [ROS discourse](https://discourse.ros.org/) channel as they chose to call it Move It, just like the [Motion planning framework](https://moveit.ros.org/) and it generated a bit of attention. Sounded cool, why not apply? I've participated in plenty of hackathons and robotics contests, so I should be fine.

It was defined as:

> Move-it is a hackathon for self-driving, aiming to build an affordable development platform(chassis) for self-driving, solving various engineering challenges along the process.

You can read more of what it was all about in the [website of the event](https://www.pixmoving.com/move-it) but my short description is:

> Get together a bunch of great engineers and hackers from all around the world to transform two platforms, a prototype car we called Coffee car and a Honda Civic 2016, from standard driven cars into fully autonomous self driven cars by using and publishing open source code and data. And more!

## The event day to day

### Day 1

#### Welcome event
The day started with a *Welcome event* where we discovered the **C-Zone Hackerspace**, a pretty cool place full of tools for us to use for this hackathon (3D printer, car tools, electronics...). It was a pretty big warehouse that some people said it may have been used in the past to manufacture pieces related to planes.

In the event some local figures gave a speech:
- Guiyang Hi-Tech Industrial Development Area representative
- Moveit developer community coordinator
- Vice mayor of Guiyang

They spoke in Chinese but were also translated just after for most of the participants that didn't speak Chinese.

Then [Scott C. Livingston](https://scottman.net/) (a participant that worked as a self driving engineer) gave a little speech trying to give some aim to the goals of the hackathon and describing the status of self driven cars. It seemed like he was going to be leading on what direction to go. (It wasn't in the end).

Then we had a few more speeches about:
- [Autoware](https://github.com/CPFL/Autoware) (by Prof. Yoshiki NINOMIYA), showed very cool results and status of the project
- [Apollo](https://github.com/ApolloAuto/apollo) (by Apollo Senior Software Architect Jinghao Miao), showed cool stuff about their platform, even tho we didn't even give it a try
- Velodyne, kinda promo about the sensors that we all know, promised lower prices
- [Chris Anderson](https://diyrobocars.com/about/) from DIY Robocars had a skype call with us talking about the project

#### Getting started
Once the welcome event was over and we started having some lunch, we, the participants, got to know each other. The event was gonna be about 10 people, distributed in two teams of 5 in principle (that was the initial proposal on the call of the event). But we ended up being around 20 participants with many additions of people that lived in China so they had it easy to participate. And having teams *competing* made no sense anymore.

So we started chatting in a random fashion and we looked around to see what we had.

Hardware:
- Coffee car, a prototype car with all pieces exposed, and mostly all the datasheets available somehow (some stuff was only in Chinese).
- Honda Civic 2016
- Our laptops
- Velodynes
- MindVision Cameras
- [PANDACAN](https://github.com/commaai/panda) boards
- CANalyst-2 boards

Key people description:
- 1 CAN expert
- 2 Autoware experts (one of them is one of the main developers)
- A few multifaceted hackers, everything from electronics to software (I'm one of them!)
- Software developers & engineers
- Machine learning experts
- A few students

Note that we had no real hardware/mechanichal engineer unfortunately. So we made no use of an awesome 3D printer!

The organization tried to push ourselves to divide in groups and to try to follow the view that Scott proposed previously. This resulted to be unfruitful for different reasons. First, there was a bit of chaos, we were a lot of people (more than 20 in the room) and a lot of people were talking at the same time. Also we had no clear goals. We also had no leaders.

The organizers gave us some forms to fill with our own description. They wanted to read them all (take into account they already had our descriptions from our bio's we sent to participate) and separate us by groups by themselves. This was kind of crazy if you ask me. The last question was something like: *Do you want to be a leader? [Yes/No]*

I answered writing next to it **Maybe?**. Funnily, my now mate, Edu, wrote exactly the same. Apparently the rest of the people answered *No*.

As engineers (& hackers!) we prefer to get our hands dirty coding stuff and being all awesome using sunglasses and a hoodie while staring at a black-and-green shell. Not really telling people what to do. But we had 5 days (4.5 at that moment) left and a lot of awesome stuff that we could do, so what the hell.

We had some general talking to know what our expertises were as a group, and what hardware we had to hack. This gave us a natural division of people working on:
- Deep learning/Machine learning for gesture recognition of policeman gestures, this was aligned to Scott's talk
- Autoware software stack for self driving cars, a pretty massive group of people
- Hardware hacking group (which was subsequently divided into the Coffee car and the Honda Civic)

Our logic was that if we got to work already and we saw what were people up to and what could be achieved in an easier or harder way, maybe we would be efficient self organizing and getting things done.

Up to this point... 

**Lesson learnt: engineers (like us) don't want to project manage**.


#### Separation in work groups
I initially went into the *Autoware* group of people. The Autoware experts gave us a crash course on the platform. As I'm extremely familiar with ROS and quite familiar with robot navigation topics, sensors and so, I found it very straightfoward. Also very interesting, easy to install and relatively easy to use (once you get the hang of their user interface). **Having a docker container that just works was awesome**.

**Lesson learnt: we need very good internet connection**. At this point we had lots of problems to download Autoware (I had it already, luckily) and anything else from the internet. The network went thru a VPN already, so we had no problem accessing any web/service... even tho it was slow. Dramatically slow. Moreover when you have 20 people using it at the same time. Via WIFI.


**Lesson learnt: next time, connect students (or inexperienced people in a specific field they want to learn) with mentors from the very start to maximize the usefulness of the event (and the fun!).** Thought of it a bit too late, even tho it happened naturally with some people, others were shy and some could have learnt even more, I think.

#### A few hours in
We separated further the Autoware group on some people working on making the sensors we had work (Velodyne, MindVision camera) and others focusing on learning more deeply about Autoware (what layers does it have? What is already there? What's missing?).

#### End of day 1, Dinner, Networking
We had a wonderful massive chinese food dinner next to the C-Hackerspace. We learnt a bit of cheering with these super tiny glasses with some local wine, pretty good if you ask me. Lots of spicy food. They took good care of me as I can't digest meat, I had plenty of dishes to eat anyways.

By the end of the night Edu & me decided that we need to organize a meeting at 09:00 the next day to better decide what to do with realistic goals on what we can achieve in the following 4 days. We would have a starting part where we'd explain the current state of the different parts, setting the next short-term goals and show the blockers everyone had and try to solve them.

### Day 2






### Wins!

### Failures...

### Lessons learnt (things we could have done better)
