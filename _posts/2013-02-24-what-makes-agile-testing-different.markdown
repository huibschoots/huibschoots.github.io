---
title: What makes agile testing different?
date: 2013-02-24 00:00:00 +0100
categories: [Agile]
tags: agile  # TAG names should always be lowercase
image:
    path: /assets/img/agiletesting.png
---

Last week [Pete Walen](https://rhythmoftesting.blogspot.com/){:target="_blank"} asked me the following question via twitter: The Question (read it carefully!): What is it that makes Agile Testing different from “other” testing?

### Agile vs agile?

What is agile testing? And what is agile? Let me first say that I do not distinguish agile and Agile. For me it is all the same. Agile is a mindset, a way of looking at the world. For me it is not a process or method. It is more a container than a way of working. [This blogpost](https://www.rodhilton.com/2010/09/10/agile-with-a-capital-a-vs-agile-with-a-lowercase-a/){:target="_blank"} discusses agile vs Agile and I like it. It describes agile as a mindset and Agile with a capital A as something commercial: “The problem here is that all of these sensible suggestions got formalized into “Agile”, with a Capital A. This set of suggestions for “things that seem to work” got boxed up into a package with a bow on top, to be sold to companies and managers.”

### Agile testing?

And agile testing? What is agile testing? I rather say testing in an agile context instead of agile testing. Good testing in an agile context is done by looking first to the details of the specific situation. Remember the 7th principle of [context-driven testing](https://context-driven-testing.com/){:target="_blank"}: “Only through judgment and skill, exercised cooperatively throughout the entire project, are we able to do the right things at the right times to effectively test our products.”

Testing is an essential part of software realization. Implementing testing in an agile context is a challenge. It comes with some interesting challenges for testers:

- by the iterative nature of working, there is less time to test compared to the testing most of us are used to in a more traditional (waterfall) context. It requires a different approach to testing. There is a different phasing to testing in an agile environment.
- how can I make sure that I can perform sufficient testing fast enough to keep up with the project?
- testers need to ensure that “self-managing teams” do enough testing
- cope with the changing team dynamics in which people work and where interaction is important
- integrating structured testing in an environment where change is common
- deliver added value as a tester when there is no software to test

Testers need to deliver immediate value. In an agile environment rapid feedback allows the team continuously forward. Testing should instantly provide useful and understandable information about the status of the products in development. It allows the team to deliver insightful value to the business continuously and to make maximum progress.

### Different?

So what is the difference? I think the testing itself is not so much different, it is the context in which you do the testing is different. If you are aiming on differences between waterfall and agile my list of most important differences would be:
- less time to prepare, execute and report (short sprints).
- iterative and incremental approach: excellent unit testing is essential.
- test automation (some rather call it automated checking or tool assisted testing) is essential for fast feedback and continuous integration.
- role change: less testing, more coaching. Testers become “test coaches” or “quality directors” to make sure the team is doing sufficient testing. Enough (not too much nor too little) and of good quality.
- cope with less certainty: change is common. Test documentation needs to deal with change by being transparent, using simple dashboards and light weight test documentation.
- team work: where many testers are used to work in TEST teams, they are now working in DEVELOPMENT teams.
- continuous critical thinking: testers need to help the team by thinking critical about the impact and risks. Where testers were used to do that upfront while writing documents like master test plans, they now have to do that continuously throughout the project: in refinement sessions, daily standups, planning sessions, etc. But also in their own work: making choices about what to cover: broad and depth.

Again: the testing itself is not so much different, it is the context in which you do the testing is different!

---

### Comments from the original Wordpress blog:

><code style="color : lightskyblue">Sofia Hunt - March 4, 2016 at 7:48 am</code>

>Very nice and interesting post. I also wrote similar lines on agile testing. Hope you would like it – [https://bit.ly/1Qr0ZAW](https://bit.ly/1Qr0ZAW){:target="_blank"}


><code style="color : lightskyblue">Prashant - July 23, 2013 at 1:16 pm</code>

>The scope of agile testing is definitely there unless you have sufficient resources and most appropriate automation tools to cope up with agile environment. You can see few traits of agile testing here [https://blog.testing-whiz.com/2013/05/how-to-become-resourceful-agile-tester.html}(https://blog.testing-whiz.com/2013/05/how-to-become-resourceful-agile-tester.html){:target="_blank"}

><code style="color : lightskyblue">Brindusa - April 3, 2013 at 6:13 pm</code>

>Love your point that “agile is a mindset, a way of looking at the world”; I would extrapolate it to agile testing as well: is a way of looking at testing. I’ve always used my skills and experiences as toolbox and drew from it what I needed at one time, in the specific situations. In my experience, in agile environments, your toolbox needs to be much wider than specific testing skills and techniques.

><code style="color : lightskyblue">Tony Bruce - March 31, 2013 at 7:37 pm</code>

>Good points Huib. My take: [https://dancedwiththetester.blogspot.co.uk/2013/03/explaining-testing-agile-testing.html](https://dancedwiththetester.blogspot.co.uk/2013/03/explaining-testing-agile-testing.html){:target="_blank"}

><code style="color : lightskyblue">Jeroen Mengerink - February 28, 2013 at 11:36 am</code>

>Nice post! I especially like that you mention the role change to more coaching. Since that is something that often misses in the teams that I have seen. The testers in the teams often want to do the testing themselves, not trusting the other team members to execute the tests.

>BTW I tend to use Agile in stead of agile to make the distinction between the English word and the term related to the mindset in the Agile Manifesto.


><code style="color : lightskyblue">duncan nisbet - February 25, 2013 at 12:49 pm</code>

>Hey Huib, great post. I’m also in the “Agile is a commercialized product” camp & now my approach to testing is more agile, as in flexible.

>One thing I’ve noticed from my (limited) experience is that I’m testing a lot sooner – I’m pairing with Programmers as we agree the test coverage & level and then receiving frequent demos of small changes in the production & test code as opposed to a load of changes in 1 hit (ties in with your quick preparation & slightly different to traditional methods).

>As you say, my testing isn’t that much different except I’m testing smaller changes which are more manageable & hopefully less risky. And as for fast feedback, I’m demoing the changes to the people who asked for them hours after development started on the changes as opposed to days or weeks. This is so helpful for ensuring we’re building the right thing (is that term cliche yet?)

>I find I’m adding more value sooner, helping into identify problems before the code is written (as with your delivering immediate value). As someone cleverer than I put it, we’re now more into the defect prevention game over the defect detection game.

>Thanks for sharing Huib, Duncs

><code style="color : lightskyblue">Mohinder Khosla - February 24, 2013 at 8:09 pm</code>

>The scope of agile testing is limited with focus immediate on feature completion. The challenge is to get the feature out of the door and in the hands of a customer. There is still to be testing done in parallel outside sprint by dedicated teams who take features from development teams and run integration and system level tests before UAT can begin. Encapsulating of UAT in a sprint is proving difficult to speed up delivery. Even security testing is left to the last due to the specialised skills required to complete them. Agile testing parallels traditional testing at unit level otherwise there isn’t distinction between traditional and agile testing apart from preparatory time, documentation and reporting. In agile environment, the bugs are fixed before they are reported while pairing with developers not so in traditional sense. This helps cut down wait time that fits nicely with lean approaches such as Kanban. I think testing done in an agile environment is no justification for it to be called agile testing rather the agility of the testing process within it that gives it the credence to be called agile testing. Nice post.