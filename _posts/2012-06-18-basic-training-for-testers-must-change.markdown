---
title: Basic training for software testers must change
date: 2012-06-18 00:00:00 +0100
categories: [Training]
tags: coaching conference exploratorytesting learning training # TAG names should always be lowercase
image:
    path: /assets/img/basictraining.png
---

<blockquote class="prompt-info">This blog post was originally written as an column for www.testnewsonline.com (English) and www.testnieuws.nl (Dutch).</blockquote>

On this blog I recently wrote about my meeting with James Bach with the provocative title: [“What they teach us in TMap Class and why it is wrong“](/posts/what-they-teach-us-in-tmap-class-and-why-it-is-wrong){:target="_blank"}. Mid July I go to San Jose for the [CAST conference](https://associationforsoftwaretesting.org/conference/cast-archive/cast-2012/){:target="_blank"}. During the weekend preceding I participate in [Test Coach Camp](https://associationforsoftwaretesting.org/conference/cast-archive/test-coach-camp/){:target="_blank"}. The title of the post is the title of a proposal that I submitted to discuss at Test Coach Camp.

### Training Experiences
In the past I have been a trainer for quite a few ISTQB and TMAP courses. The groups attending the training were often a mix of inexperienced and experienced testers. The courses cover topics like: the reason for testing, what is testing, the (fundamental) processes, the products that testers create, test levels, test techniques, etc. In these three-day courses all exercises are done on paper. Throughout the whole training not once actual software is tested!? I wonder if courses for developers exist where no single line of code is written.

In San Jose at Test Coach Camp I want to discuss the approach of these courses with my peers. How can we improve them? I feel these courses are not designed to prepare testers to test well. Let alone to encourage testers to become excellent in their craft.

### Dinner with James
During my dinner with James, I asked him what he would do if he would train novices to become good testers. He replied that he would let them test some software from the start. He would certainly not start with lectures on processes, test definitions and vocabulary. During a session the student will (unknowingly) use several techniques that will be named and can be further explained when stumbled upon. A beautiful exploratory approach I would like to try myself: learning by doing! But there are many more opportunities to improve testing courses. People learn by making mistakes, by trying new things. Testing is much more about skills than about knowledge. Imagine a carpenter doing a basic training. His training will mainly consist of exercises! My neighbour is doing a course to become furniture maker. She is learning the craft by many hours of practice creating work pieces. Practice is the biggest part of her training!

One of the comments on my blog opposed to the suggestion by James Bach. Peter Edmond says: *“I have been both a tester and trainer in ISTQB and TMap. Yes we can make testing fun but without a method that testing has no structure and more importantly has no measurable completion. How will those new people on “more practical” course know when they have finished? What tests did they do? What did they forget? What defect types did they target? Which ones did they not look for? What is the risk to the system? My view after 40 years as a developer and tester is that this idea might be fun but is not just WRONG but so dangerously wrong that I am sad that no one else has seen it.”*

What do you think?


---

## Comments from the original Wordpress blog:

> <code style="color : lightskyblue">Christopher Swain - June 21, 2012 at 10:46 am</code>

> Hello everyone. Last night Fiona did a talk at the London Tester Gathering, about this subject. Here is a link to the talk from my pinterest page: http://pinterest.com/pin/162059286561738121/

> <code style="color : lightskyblue">Keith Klain - June 20, 2012 at 6:33 pm</code>

> Clearly Peter is just protecting his business with such throwaway comments, as even the most cursory investigation into CDT (thanks, Michael) would prove all his statements to be false…as someone actively implementing CDT as our core test approach on a large scale in a high risk and heavily regulated environment, I can assure you that it is not a methodless, non-documented, and endless “let’s just have fun” approach to testing…I would be run out on a rail if it was…so let’s consider the source here – a principle trainer for a consultancy that sells ISTQB and TMap courses…enough said, so let’s hope Peter has the personal integrity to either defend or retract his statements…

> <code style="color : lightskyblue">Fiona Charles - June 20, 2012 at 2:45 pm</code>

> I learned to test by testing software for a living, as did everyone in my benighted generation when we had no formal training, no certifications, no testing courses. Oh yeah — and at some point fairly early on, I picked up Glenford Myers “Art of Software Testing”. I read other books later and (much later) took some courses. I still do those things.

> Did I say we were “benighted”? Nuts!! It was a terrific way to learn. Far from muddling in the dark, I was learning to shine a light on the system. I had already done things very much like this in my previous job as a self-taught technical writer. I was so ignorant that I thought it was a tech writer’s job to exercise the software inside and out to see what it did. I never learned to read Assembler in that tech writing job (unfortunately), but when the programmers learned COBOL and PL/6, I learned it with them. Later tech writers who went to tech writing school thought exploring the software and reading the code was the wrong way to get information about a system and they should just ask the programmers. I feel sorry for them, the idiots. They missed a lot.

> In 1984, I went to work as the sole official tester for a little Canadian company with very big-ticket customers. Our large software application was a manufacturing execution system for semiconductor manufacturers.

> I read what I could find about the system and about our customers. There wasn’t much. I asked questions. And I explored the system. When I found something that didn’t look right, I wandered over to talk with the senior programmer for that part of the system. When he (they were all guys at that point) had a moment, he’d clear a space and get me to sit down with him. I’d show him what I’d done and seen. Sometimes it looked okay to him and he’d explain why.

> If it didn’t look right to him, we’d go look at the FORTRAN code and we’d talk about what we saw and he’d show me the fix. Pretty soon I took a FORTRAN manual out of the library and learned to write and read FORTRAN. Then I could read the code before going to the programmer with an anomaly, so I could take more information along.

> I had to run batch jobs sometimes, so I read the manual and taught myself DCL (the much friendlier VAX version of JCL). The guys had written a scripting language to test the basics of the system, so I became an expert on that, and not incidentally learned some things about automated testing at a point when very few people practiced it. When we ported the system to IBM with an ORACLE database, I taught myself SQL. Eventually, I learned more about test techniques by reading some testing books and trying out the things I read, or at least giving a name to what I already did.

> One of my jobs was to organize all the programmers and the customer support people (when we got some) into one big team to test the system for each release. So I got to learn some things about test management, too.

> I think this was an excellent way to learn testing. Was it “unstructured”? I’d say no for many reasons, not least because I was testing for a living. I had responsibilities and I had the discipline of production releases. I also had the support of knowledgeable programmers and customer support people. We worked together to make our system the best we could.

> Reading this post plus Peter’s comments reminded me of my experience learning human, as opposed to programming, languages. I learned French and Latin in school primarily by learning and memorizing grammar: verb forms and paradigms. We read some, and we spoke less — French, that is — but an awful lot of our learning was divorced from the real human use of those languages. I liked grammar and I was good at it. But I never really learned to read either language well, and my spoken French is embarrassingly poor.

> Contrast that with how languages are taught now. You learn primarily by speaking and reading — exploring. You learn grammar too, but more by osmosis or because you need to use a particular form. I think if I’d learned this way, I could actually have learned to speak and read French, and at least read Latin.

> So how do we think people should learn to test? I don’t think it should be by rote. Nor on paper. (Does anyone learn to play the piano by learning theory first?)

> I think it should be by working with real software: exploring it, finding bugs, making mistakes and learning from them, working with knowledgeable people.

> <code style="color : lightskyblue">Christopher Swain - June 20, 2012 at 2:43 pm</code>
> I love the way you think and I love the way you talk.

> The people that seriously float my boat are those that ask very good questions. Good testers in my experience are not necessarily those who have passed an exam in testing but are those people with the awesome ability of asking the right quests, to the right people, at the right time. People mostly know the answers, or can work answers out fairly easily but there are few people who know the right questions to ask.

> Michael Bolton and Jonathan Kohl teach questioning skills really well. We also probably owe much to Gerald Weinberg for pointing us in the right direction.

> Do I really need to learn all about TDD, SCRUM, EXPLORATORY TESTING, TMMI, BDD, ABC, XYZ, CRITICAL PATH ANALYSIS, BOUNDARY VALUE ANALYSIS or do I simply need to learn the art of questioning and knowing which website or book to read when I am looking for the answer?

> Still, I love testing courses, I admire people who are advocates from the Weinberg camp and am always looking for good reference material. I dont try to remember everything I just try to remember where I can find the information when I need it most. And should anyone ask me if they will get a lot out of going on a Michael Bolton course: I will always say yes.

> Thank you.

> <code style="color : lightskyblue">Tim Western - June 20, 2012 at 1:58 pm</code>
> I’ve got to agree with James. The questions Peter asks seem like they come from someone that fears that which he doesn’t understand, so rather than try to learn and understand the solution is to attack the messenger or the message. I’ve been there, I’ve seen it on teams. Saying testing in the manner described in this blog would be unstructured, as if that’s an argument against it, is like making light of a great chef who has no written recipes but works with ingredients he has to make something marvelous for the Pallet. Don’t tell me that Chef doesn’t have a process even if it is unwritten, don’t tell me it is necessarily unstructured.

> In the end, I feel that we learn best when working with what we are learning. In ten years in this industry as a tester, a coder, a technical writer, and all sorts of other hats worn, I’ve learned best when I’ve been working and applying ideas to real software not just some abstract idea of a given software. This is how I’ve learned coding the best during College, and it is how I’ve improved as I’ve come to identify as a tester now.

> Excellent points!

> <code style="color : lightskyblue">Duncan nisbet - June 19, 2012 at 11:19 pm</code>
> Great thought & discussion proviking post Huib.

> I was happily proceeding down the istqb path until I actually started studying my craft & then BAM there was context driven!

> Are there any other crafts that learn solely though textbooks? I remember trying to learn the piano – I didn’t read one book. That said, I wasn’t very good…

> <code style="color : lightskyblue">Stephan - June 19, 2012 at 11:06 am</code>
> Great post & excellent answers.
> David mentioned it, and I’d like to know this: Huib, does Peter know about this post? (And if not, could you tell him? That’d be great).

> As for the ISTQB training: Educating people about whatever topic without letting them practice is wrong. When I think back to studying physics, those labs were definitely teaching us how extremely difficult it can be to get reliable and meaningful result of an experiment (Much the same in testing, BTW). However, the understanding lies in the combination of experimental evidence and theoretical models. If you have a model/theory, you can test it by running an experiment. If you have no model (that the exploratory part of physics) you can use the experimental data to create one. It works both ways.

> And if you’re still learning the trade, running well established experiments against equally well known models helps understanding the connections between the two – and setting up experiments well. (That would be a test lab in the world of testing.)

> As for the certification & learning: I got an English certificate long long ago. The guy who gave the (1 ½ year, IIRC) preparation course did it right in my opinion: The taught us English for the first & significantly larger part of the time (well over a year), and then after that he’d prepare us to get the best result in the exam (a few months).

> There’s is a significant and important difference between learning something & getting a certificate of one kind or other. Not everyone seems to accept that the learning & understanding part is more important than a certificate.

> <code style="color : lightskyblue">Tony H - June 19, 2012 at 10:48 am</code>
> Find it strange that none of the testers found the spelling mistake in the title.
> Magnificent stuff.

>> <code style="color : lightskyblue">Stephan - June 19, 2012 at 4:00 pm</code>
>> “Magnifiant”, yes that looks like a typo, however I assume Huib knows how he’s typing the title of the blog. But then… is there a ‘c’ missing? Or an explanation of this particular spelling?

>>> <code style="color : lightskyblue">huibschoots (Post author) - June 19, 2012 at 4:39 pm</code>
>>> There sure is an explanation: read the [first post](/posts/a-blog-about-testing-manifiant){:target="_blank"} on this blog.

> <code style="color : lightskyblue">Chris Millar - June 19, 2012 at 9:32 am</code>
> Hi Huib,

> Thanks for the post, I enjoyed it.

> This is my first post on a testing blog, the reason being……I do know Peter, although I wouldn’t say I know him well. He was the tutor on an ISEB Foundation Course I took at Sogeti in London last year.

> I agree wholeheartedly with the philosophy raised by yourself, Michael and James.

> However, from the way Peter talked about the ISEB syllabus and drifted off topic to discuss his experiences in software testing and his feelings about the industry I didn’t get the impression that he is someone with a closed mind who would be immune to ideas.

> From his appearance and odour I would venture that he came in to London on the tube, not a turnip truck.

> His entries on the Sogeti blog can be found here : https://blog.uk.sogeti.com/author/peter-edmondsogeti-com/

> Chris

>> <code style="color : lightskyblue">huibschoots (Post author) - June 19, 2012 at 5:03 pm</code>

>> Hey Chris, thanks for pointing out Peter’s blog. I will read it. If Peter is not immune to ideas, I do hope he will read some of the stuff Michael and others linked to.

>>> <code style="color : lightskyblue">Chris Millar - June 19, 2012 at 6:31 pm</code>

>>> Yes, it would be good, especially as he gets to meet a lot of testers who could therefore get to know about this stuff.

>>>> <code style="color : lightskyblue">Curtis Stuehrenberg - June 20, 2012 at 6:23 am</code>

>>>> This is purely based on baseless assumptions, but it would appear as through Mr Edmond has made a very nice career out of marketing specific testing frameworks, templates, and methodologies. People pay him a lot of money and pay for his travel to a lot of interesting places based on the assumption he has something of value to sell them. I would find is … refreshing … for some one in his position to support a type of testing that eschewed the very things he sells.

>>>> In his defence, he may very well be a true believer. I would hope he is not out there selling something in which he has no personal stake of faith. However this sort of situation does tend to render one less open to alternative pathways.

> <code style="color : lightskyblue">David Greenlees - June 19, 2012 at 2:55 am</code>
> I’m sitting here waiting to hear from Peter again… still waiting… waiting…

> Hmm, how unusual for a factory schooler to thrown in 2 cents then not return to throw in some real money!

> Why is it ALWAYS the CDTs that answer the critiques, only to not have those answered?

> Great post Huib. I hope you have loads of fun in the states! :0)

> <code style="color : lightskyblue">Chris G. - June 18, 2012 at 10:39 pm</code>

> “Basic training” is a general question about knowledge.
A Tester has three bubbles of knowledge:
– Method competency in testing (ISTQB…)
– Domain knowledge
– Experience/ knowledge from former work
The question about the basic training for testers can touch every of those three bubbles and not only the method competency. Important is also a good domain knowledge.

> In fact this leads to the question – should all testers be trained in the same way?
Or what is the best mix of knowledge in the test team?
To have a cutting edge test team there should be a lot of different knowledge, together they can solve every puzzle…

> <code style="color : lightskyblue">James Bach - June 18, 2012 at 10:23 pm</code>

> I don’t know who this “Peter” guy is (if he were well known you I assume you would have given his full name), but I bet you that he knows who I am, unless he has carefully avoided reading or learning anything about our craft for the last 15 or 20 years. I have been out there, making my demonstrations and my arguments and making MYSELF available to any and all who might argue with me.

> Now, how is it possible that I don’t know this man, with his 40 years in the business? How is it that I can have developed the science and discipline of exploratory testing for all this time, have it subjected to so much scrutiny by serious people, and YET this guy can comfortably dismiss all that work with a few words?

> I fear it’s because he’s a bumpkin. He’s been riding a turnip truck for forty years instead of studying his craft. What other plausible explanation could there be? We live in a connected world. My work and Michael’s work and Cem Kaner’s work is all over the web. We provide examples and evidence. People can disagree with us, but we cannot be dismissed.

> This merely demonstrates that you can have a long and obscure career as a fake tester. Congratulations on your obscurity and irrelevance, Peter. Now retire, already, so we can get on with fixing the mess you and your generation have made of the testing industry.

> — James

> <code style="color : lightskyblue">Curtis Stuehrenberg - June 18, 2012 at 8:46 pm</code>

> In all fairness to Peter, he does voice the feelings of a lot of people outside our little school of thought. I’m reminded of the problem my sifu had running a kung fu school here in the US after he immigrated from Hong Kong. He was one of the only recognized grand masters teaching on the West Coast yet he had constant issues with retaining students. His problem was his teaching style. He taught by doing and practising at his student’s own pace. There were no pretty coloured belts or trophies or shiny gold stars to say “Attaboy” when a student was progressing. The student was expected to guide their own training by incorporating what Mak Sifu showed him or her into their own way of moving and fighting. There were forms, but the student was expected to figure it out for themselves to a large extent because what worked for a 65 year old Chinese man weighing in at 130 pounds probably wouldn’t work for a 25 year old American who stands over six feet tall and weighed in at 22o pounds.

> In short traditional Chinese martial arts teaches like what James suggested. Unfortunately this meant most students would leave after a little while to go join one of the hundreds of other schools offering belts, certificates, patches, fancy uniforms, and fees for all of it.

> <code style="color : lightskyblue">Michael Bolton - June 18, 2012 at 5:45 pm</code>

> There are so many inconsistencies, begged questions, and outright errors in Peter’s arguments that it’s really difficult to know where to start.

> 1) No structure?
How about this? [https://www.developsense.com/resources.html#exploratory](https://www.developsense.com/resources.html#exploratory){:target="_blank"}<br>
Or this? [https://www.satisfice.com/tools/satisfice-tsm-4p.pdf](https://www.satisfice.com/tools/satisfice-tsm-4p.pdf){:target="_blank"}<br>
This? [https://www.satisfice.com/tools/satisfice-cm.pdf](https://www.satisfice.com/tools/satisfice-cm.pdf){:target="_blank"}<br>
This? [https://www.satisfice.com/tools/procedure.pdf](https://www.satisfice.com/tools/procedure.pdf){:target="_blank"}<br>
Or this? [https://www.satisfice.com/images/RapidTestingFramework.pdf](https://www.satisfice.com/images/RapidTestingFramework.pdf){:target="_blank"}

> Things that leave out a step-by-step set of instructions to follow have “no structure” if and only if you have exactly one notion of structure.

> 2) No measurable completion? Exactly the same pattern applies: if you have only one way of measuring completion, then anything that doesn’t fit with that one way has “no way of measuring completion”. However, there are lots of ways of measuring completion. I’ve catlogued at least thirteen, here ([https://www.developsense.com/blog/2009/09/when-do-we-stop-test/](https://www.developsense.com/blog/2009/09/when-do-we-stop-test/){:target="_blank"}) and here.

> 3) It’s a common error to confuse measuring completion and measuring coverage, an error that Peter appears to be making.

> [Got You Covered](https://www.developsense.com/articles/2008-10-GotYouCovered.pdf){:target="_blank"}: Excellent testing starts by questioning the mission. So, the first step when we are seeking to evaluate or enhance the quality of our test coverage is to determine for whom we’re determining coverage, and why.

> [Cover or Discover](https://www.developsense.com/articles/2008-11-CoverOrDiscover.pdf){:target="_blank"}: Excellent testing isn’t just about covering the “map”—it’s also about exploring the territory, which is the process by which we discover things that the map doesn’t cover.

> [A Map By Any Other Name](https://www.developsense.com/articles/2008-11-AMapByAnyOtherName.pdf){:target="_blank"}: A mapping illustrates a relationship between two things. In testing, a map might look like a road map, but it might also look like a list, a chart, a table, or a pile of stories. We can use any of these to help us think about test coverage.

> 4) The question of what tests people did and what they might have forgotten is part of the testing story. We cover that here ([https://www.developsense.com/blog/2011/12/what-exploratory-testing-is-not-part-5-undocumented-testing/](https://www.developsense.com/blog/2011/12/what-exploratory-testing-is-not-part-5-undocumented-testing/){:target="_blank"}).
> And here. ([https://www.developsense.com/blog/2012/02/braiding-the-stories/](https://www.developsense.com/blog/2012/02/braiding-the-stories/){:target="_blank"})

> I’ll let others chime in, but geez, Peter… you can either critique our stuff or ignore it, but you can’t do both and think we’ll take the critique seriously.

> —Michael B.

