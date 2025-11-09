---
title: Testing Dojo
date: 2012-02-01 00:00:00 +0100
categories: [skills]
tags: skills # TAG names should always be lowercase
image:
    path: /assets/img/dojo.png
---

Last week I organized a Testing Dojo. I wanted to try a dojo for a long time and I was quite disappointed that [Markus Gärtner](https://www.linkedin.com/in/mgaertne/){:target="_blank"} was ill at Agile Testing Days so the testing dojos were cancelled. What do you do when you want to experience a testing dojo? Right! You just get a bunch of people in a room and try it yourself! To make this dojo a success I read the website Testingdojo.org (website doesn't exist anymore) from start to finish and scanned testing-challenges.org (website doesn't exist anymore) for a good challenge. I also skyped with Markus for an hour to discuss the dojo. For me the goals of the dojo were:

- Experience what a testing dojo is (useful? fun?)
- Learn from group
- Practice stuff we learned in RST last year

### Our dojo
At our dojo 20 people showed up: mostly testers but also a business analysts and a developer. After ordering pizza for all, I did a short intro presentation. I explained what a testing dojo is, what the rules are for the dojo and the mission for the evening. I wrote down the rules on a flip-over and put that on the wall:

- Work in pairs
- We recognize 3 roles:
    - Driver / tester
    - Recorder / note taker
    - Observers (audience)

Switch roles after 5 minutes:
1. Tester –> audience
2. Recorder –> tester
3. Audience –> recorder

- Everybody in audience (observers) take notes using checklist
- Audience does not interfere with testing, unless they are asked

### Mission
The mission for the dojo was:<br>
Test parking calculator Gerald R.Ford International Airport using SFDPOT and the [Test Heuristic Cheat Sheet](/assets/files/testheuristicscheatsheetv1.pdf){:target="_blank"}).

Observer checklist:
- What happened?
    - Testing
    - Communication
    - Collaboration
- How do they communicate?
- Are they listening to each other?
- Who is in charge?
- Also note emotions
- What path do the testers take?
    - Depth
    - Breadth
    - Explore first: what do we have?
    - When does what happen
    - What happens if they find a bug?

![Parking Calculator](/assets/img/parkinkcalc.png){: width="300" .right}
I gave the group a sneak preview of the parking calculator (original page is gone, but the calculator cab be found here on Markus website: [https://www.shino.de/parkcalc](https://www.shino.de/parkcalc){:target="_blank"}). I also showed them the webpage with the information on the car parking and the parking rates. While preparing the dojo I thought the participants would like to do some preparation while eating pizza. I figured they could think about their approach and maybe write down some test ideas or other stuff they thought that could be useful. But the group wanted to start right away. There were some questions about the exact purpose of testing this application. I told the group, while playing the role of product owner, the goal is to inform me if this calculator needs adjustments.

### Room setup
In the room the participants were sitting in a u-shape all facing the screen were the beamer projected the display of the laptop in front of the room. The pair behind the laptop was facing the group. I think it’s not easy to test when 20 people are watching you and you are sitting in front of the room. In the back of the room were 2 flip overs with the parking rates. 

We decided that everybody would have 3 minutes of testing time and after 3 minuted we would switch roles. After three pairs had finished their testing we stopped for a short retrospective to discuss the progress so far. We noticed that nobody was in charge really and communication between the pairs was minimal. They were trying stuff, without having a clear strategy or approach. The first pair could get away by telling they were exploring the application to see what they had in front of them, what it could do, etc. The other pairs had some sort of strategy but couldn’t explain. A discussion on the further approach took place and the group decided to create a list on a flip over with items that needed testing. I noticed that SFDPOT wasn’t used explicitly and the strategy followed by the group was almost fully focussed on testing functionality.

### Test strategy?
![Dojo flip](/assets/img/dojoflip.jpg){: width="200" .normal }
<br><br>
After a flip over with the “test strategy” was created by one of the participants, testing was more focussed. But still I noticed that it was difficult for the participants to test in pairs (communication) and keep focussed without scripted tests (structure). None of the pairs debriefed or communicated with the next group. To fill this “gap” I asked every pair after their time was up, if I could “tick off” one of the items from the test strategy. 

![Dojo Notes](/assets/img/dojonotes.jpg){: width="200" .right }
One of the participants created a list of test ideas before he took his place behind the laptop. It was fun to see a lot of different styles and approaches. I also noticed that being observer is a rather difficult job. Not a lot of notes were taken on observations despite the checklist on the wall. Most of the participants focussed their observations on the testing and the application being tested, rather then on the people testing and their communication and collaboration.

After all pairs had their go testing, we did a retrospective. Below the feedback from the group.

### Lessons learned:
- Group was too big, a group of up to 10 people is better.
- More time to test: with a smaller group it’s probably better.
- Give the group a bit more structure. It is helpful when the starting point is clear.
- Stop more often to evaluate. 
    Idea: 
        1. Mission
        2. Test
        3. Self debrief
        4. Group feedback
        5. Test again

It was a great evening, although it didn’t went as smoothly as I hoped. But we learned a lot about testing dojos and I think it was a successful evening. I hope the attendees went home with the same feeling. In a small group we discussed the dojo somewhat further and the reactions were enthusiastic. There is still enough room for improvement, as always: practice makes perfect! For a first time I think this was quite a successful evening. A second dojo is already planned. I am looking forward to it.

**Other notes made during the test dojo:**<br><br>
![Dojo Notes 1](/assets/img/dojonotes2.jpg){: .normal width="100"}
![Dojo Notes 2](/assets/img/dojonotes3.jpg){: .normal width="100"}
![Dojo Notes 3](/assets/img/dojonotes4.jpg){: .normal width="100"}

Click images to enlarge.

---

## Comments from the original Wordpress blog:

> <code style="color : lightskyblue">Christiaan - February 10, 2012 at 10:55 am</code><br>
> Great initiative! Good to read poeple still want to improve on their skills.
> Can anyone join? F.E. people with a minimal ammount of testing experience?

>> <code style="color : lightskyblue">huibschoots (Post author) - February 11, 2012 at 11:43 am</code><br>

>> Thank you, it was a lot of fun! The dojo’s at RI are not public, but at TestNet we will organize a public dojo. And yes, anyone can join! Managers, developers, analyst… anyone who wants to learn or improve his skills can join. Even if you have no (testing) experience, you can join. As long as you want to learn!

> <code style="color : lightskyblue">Sunil - February 2, 2012 at 7:46 am</code><br>

> Good topic to read, it will help people a lot to learn some thing on this.

> <code style="color : lightskyblue">Martijn Ruff - February 1, 2012 at 10:02 pm</code><br>

> First of all, I’d like to compliment Huib on a really fun and interesting testing dojo we had. Great job! Can’t wait for the next one 🙂

> I like Markus’ approach of different pairs testing simultaneously, as long as enough time will be available for feedback between the different pairs. Doing it like that will keep most contestants ‘busy’ during the cause of the dojo. Simultaneous testing can also bring a very interesting competition element into the dojo.

> However, one drawback is that you won’t have the change to really observe what is going well (and not so well) when others are busy. That’s maybe the part I personally liked most during the dojo we did with Huib. Just see how pairs are communicating, with each other but also with other pairs, is really a fun thing to do! It helps you think of how to approach your co-workers in the testing profession, since different people react in different ways. Where one co-worker might be helped with more structure, the other might be helped with a brainstorm, helping him/her think new thoughts.

> As Huib already mentioned, the group was quite big. Smaller groups will give you the chance to give more feedback and give the testing pair. It would be great to continue testing right after the feedback, so they can put any tips directly into action. In my opinion this will increase the learning factor. With smaller groups, the people are more likely to give feedback, while in bigger groups people will let others do the talking. You might even come up with a format like this:

> – groups of 8-10 people
– 1 pair testing for, let’s say, 5 minutes
– rest is observing
– small debrief of the pair: how did they think it went
– after 5 minutes, each observer names one tip (what can be done better) and one top (what was great!) and explains why
– another round of testing with the same pair, putting the feedback into practice
– debriefing of the pair: did the feedback help them improve their testing?
– handover to the next pair

> It would be fun to experiment a bit with different formats, just to see what works best in our situation. Of course, this might not be the way testing dojos should be done for every group in every situation any time, but it’s always good to come up with improvements. Organizing a testing dojo then becomes a bit like being in the dojo itself: constant feedback and improvement.

> <code style="color : lightskyblue">Rosie Sherry - February 1, 2012 at 11:35 am</code><br>

> I hear that Markus will be doing a TestingDojo at our TestBash - [https://www.ministryoftesting.com/training-events/testbash/](https://www.ministryoftesting.com/training-events/testbash/){:target="_blank} 🙂

> I wonder how possible it is to video it and share the process, would it be too much hassle?

> <code style="color : lightskyblue">Phil Kirkham - February 1, 2012 at 10:14 am</code><br>

> Thanks for the write-up, really interesting to read about how a dojo is organised and run and lessons learned

> <code style="color : lightskyblue">Markus Gärtner - February 1, 2012 at 12:13 am</code><br>

> Thanks for this write-up.

> One way to run a testing dojo which turned out successfully the past times, is by using a mix-in of session-based test management, and dojos. We excluded this because you didn’t seem to have enough laptops with you, but I would consider it for the next time.

> The approach is to have people work in pairs simultaneously on the same mission, and meet together at intervals to get in line with each other for a quick 5 minute debrief. In the past I have done such sessions at the WeekNight live testing session last year [(https://www.shino.de/2011/03/27/weeknight-testing-live/)](https://www.shino.de/2011/03/27/weeknight-testing-live/){:target="_blank}, the CAST testing challenge [(https://www.shino.de/2011/08/15/cast-2011-a-report-on-the-testing-competition/)](https://www.shino.de/2011/08/15/cast-2011-a-report-on-the-testing-competition/){:target="_blank}, and also at a client of ours [(https://www.shino.de/2011/07/31/testing-dojos-from-the-back-of-the-room/)](https://www.shino.de/2011/07/31/testing-dojos-from-the-back-of-the-room/){:target="_blank}. I still have to update the testingdojo.org wiki with this new setting.

> Additionally, I hope to get some of your ideas, and share them with other testing dojos around the globe. The Agile Finland group runs public testing dojos from time to time as well. So, you might want to plan for a public dojo as well once you received enough experience with different approaches.

> Thanks for reporting on your progress. Hope to read about the progress again soon.