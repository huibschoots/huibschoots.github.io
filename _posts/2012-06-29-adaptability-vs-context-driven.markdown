---
title: Adaptability vs Context-Driven
date: 2012-06-29 00:00:00 +0100
categories: [skills]
tags: skills # TAG names should always be lowercase
image:
    path: /assets/img/adaptorcdt.png
---

TL;DR: the post itself isn't that long... the comments make it a long (but fun) read. 

Last week Rik Marselis send me an email pointing me to an article with the title “The adaptability of a perceptive tester”.  He added: “Have you read this article? Should appeal to you!”. The article is written by a couple of Dutch (Sogeti) testers. And they, so the introduction tells me, get together once in a while to discuss the profession of testing and quality assurance. This time they discussed some remarkable examples of their experience that perceptive testers (who are aware of the specific situation they’re in) adapt their approach to fit the specific needs.

I replied to Rik with the following email:

<blockquote class="prompt-info">Hey Rik,<br>
Nice article, I had already seen it. But adaptive or perceptive is not context-driven. I also totally disagree with the conclusion:<br>
“Together we concluded that although TMap NEXT was introduced some six years ago it still has a solid foundation for any testing project since the essence of adaptiveness makes sure that any perceptive tester can collaborate in doing the right things at the right moment in any project and ensure that the proper quality is delivered to solve the problem of the stakeholders.”<br>
<br>
TMap Next contains a number of dogmas (or rather is based on a number of dogmas) like: testing can be scheduled, the number of test cases is predictable, content of a test case is predictable, sequence of process, etc.
Therefore I think TMap Next is not usable in every situation. At least not effectively and efficiently. Being adaptive is good, but I can imagine situations that TMap Next has to be adjusted rigorously that the result is no longer recognizable as TMap. In addition: TMap Next says that ET is a technique: a good example of another dogma. And it shows me that TMap is not about testing but about a process and deliverables … Maybe I should write a blog about this.<br>
<br>
Regards,<br>
Huib</blockquote>

Rik replied with this email:

<blockquote class="prompt-info">Hi Huib,<br>
We really need to reserve some time to discuss this from different sides because some things that you say I totally disagree with. A conscious tester can handle any situation with TMap. I think whether ET is a technique or approach is really a non-discussion. TMap calls it a technique so you can approach testing in different ways in different situations. And since TMap itself is a method you cannot call ET a method too.<br>
<br>
I think Context-driven means you choose your approach depending on the situation.<br>
I think Adaptive means you choose your approach depending on the situation.<br>
<br>
Perceptive means conscious, as you are aware of the situation, you can choose an appropriate approach. Well, it is worth discussing.<br>
<br>
Regards,<br>
Rik</blockquote>

Okay, so let’s discuss!

### Exploratory testing
Let’s start with the ET discussion. What does TMap say about this? ET is a test design technique. And the definition of a test design technique (on page 579 of the book “TMap Next for result driven testing”): “a test design technique is a standard method to derive, from a specific test basis, test cases that realise a specific coverage”. Test cases are described on page 583 of the same book: “a test case must therefore contain all of the ingredients to cause that system behaviour and determine wheter or not is it correct … Therefore the following elements must be recognisable in EVERY test case regardless of the test design technique is used: Initial situaion, actions, predicted result”.

Let’s connect the dots: ET is called a test design technique. A test design technique is defined as: a method used to derive test cases. But ET doesn’t use test cases, not in the way TMap defines them. It can, but most of the time it doesn’t… Mmm, an inconsistency with image, a claim, expectations, the product, statues & standards. I would say: a blinking <span style="color:red">red</span> zero! Or in other words, there /is/ something wrong here!

What is Exploratory Testing? Paul Carvalho wrote an excellent blog post simply titled [“What is Exploratory Testing?”](https://swtester.blogspot.com/2012/05/what-is-exploratory-testing.html){:target="_blank"} on this topic and I suggest people to read this if they what to understand what ET is. Elisabeth Hendrickson says: “Exploratory Testing is simultaneously learning about the system while designing and executing tests, using feedback from the last test to inform the next.”

Michael Bolton and the context-driven school like to define it as: “a style of software testing that emphasizes the personal freedom and responsibility of the individual tester to optimize the quality of his or her work by treating test design, test execution, test interpretation, and test-related learning as mutually supportive activities that continue in parallel throughout the project.”. Michael has a collection of interesting resources about ET and it can be found [here](https://developsense.com/resources){:target="_blank"}.

So Rik, your argument “since TMap itself is a method you cannot call ET a method too” is total bullshit! It sounds to me as “there is only one God…”.

### Context-driven testing
Don’t get me wrong, being adaptive and perceptive is great, but that doesn’t make testing context-driven. A square is a rectangle but a rectangle is not a square! Please have a look at the [context-driven testing website](https://context-driven-testing.com/){:target="_blank"} by Cem Kaner. Also read the text of the key note [“Context-Driven Testing”](https://www.developsense.com/presentations/2011-08-CAST-ContextDrivenTesting.pdf){:target="_blank"} Michael Bolton gave last year at CAST 2011. In his story you will see that adaptive (paragraph 4.3.4) is only a part of being context-driven. I admit, it is not easy to really comprehend context-driven testing.

Do you think it was TMap Next that was the common success factor in the stories shared in the article… I doubt it!

---

## Comments from the original Wordpress blog:

> <code style="color : lightskyblue">Rik Marselis - July 15, 2012 at 10:28 pm</code>
> Dear testers,

> I really enjoy this discussion because it brings deeper insight, at least to me, but judging from the reactions, on- and off-line, also to other people. And that’s what discussions are all about, isn’t it?

> An observation on both the CDT approach as well as the TMap approach: it takes perceptive and creative people to make it work well. People that only hold a certificate in testing are not by definition good testers. Actually, as a trainer I differentiate, during my training courses, in the part that helps the trainees in becoming better testers and the part that helps them pass the exam. And I agree people should get more training and coaching on actual testing. Some managers only seem to see value in passing exams.

> On this matter Jan Jaap asks about my company, do our testers learn anything else than TMap? Well actually YES! They also learn about Agile testing (OK, we have a TMap way of Agile testing ;-), ISTQB, LEAN, personal skills and many more. Above that we are currently setting up an extended coaching scheme to actively help testers improve their testing. A coincidence? Who knows. Maybe it’s just the way history goes. At some point in time many arrows start pointing in the same direction 😉

> Some people in the CDT school of testing seem to me to advocate that each and every tester has to find out everything for themselves. Well sorry, I have a different opinion: our civilization is based on putting together knowledge of others and putting on top of that, new insights, new approaches etcetera. And sometimes we will find that knowledge of others has become outdated or not relevant. But reusing knowledge that is out there is exactly why human beings are more civilized than other animals. (oops I’m getting philosophical right now, isn’t that one of the virtues of a context driven tester 😉

> Huib was talking about the pesticide paradox as an example why factory school would not be good. If I understand the pesticide paradox well this is used to explain why you should not use the same testset in both (for example) a system test and an acceptance test because then the only value of the test is to verify if there are no differences in the test environment.
But the pesticide paradox does not relate to regression testing. Since here the regression test is a remedy to detect failures that were not there before and were caused by changes to the test object. So a regression test does not suffer from this paradox.

> Huib also poses the question how much of TMap should be used to be allowed to call it TMap-based testing. Well I really don’t care. As I have stated before TMap has helped me in any situation. In some situations I was able to use a previously created template and apply it. In many situations I adapted, I used all sorts of bits and pieces of TMap and added some other flavours to it. Does it then matter how to call it?
Oh, and one thing: TMap does not restrict what you want to use to what is described in the book. For example at page 636 (section 14.4.1) you will read: “This section offers a varied set of test design techniques that most organizations can apply immediately. The list is not exhaustive. To supplement it, a test organization could consult the literature, such as [Beizer, 1990] and [Copeland, 2003], or even create new techniques, as described at the end of this introduction.” So more is described in “Creating new test design techniques” at page 637. I won’t go in details, may be interesting for a later part of this discussion.
A perceptive person thinks about the situation he is in and uses all knowledge and experience available, combined with new insights gained from the situation, to do the most effective and efficient job possible in that situation.

> Johan stated that CDT and TMap are at different ends of a spectrum. Following this reasoning I would say that TMap (as an example of a method of structured testing) is very well applicable in large organizations where people are expected to conform to a common way of working to keep things organized. And as long as it’s about testing existing information systems that are slightly changed in regularly scheduled releases due to daily improvements of the process that can be presented in bitesize chunks, I think this so-called factory approach is very well applicable.
If however there is a unique situation full of uncertainties and unknowns then I can easily imagine that CDT makes you automatically think about what the best way of working in that situation would be. CDT (if properly followed) does not let you the room to do mediocre work and hide behind the method if it doesn’t bring success.

> My conclusion is that in a situation full of uncertainties people that are aware they follow a CDT approach will be more often successful than people that by habit follow a factory approach.
Whilst in a situation where many standard activities (like regression tests) have to be done a factory approach will make it easier to have an efficient situation and sometimes even more effective than when CDT was applied.
How do I get to this conclusion? Firstly thanks to Huibs examples. Secondly the thing is that for the Jedi’s, the real good testers, it doesn’t matter so much what approach they follow. Real good people will do a good job in any situation regardless of what they call their approach. Real good people by nature select the basic principles that fit their current situation most.
It’s the 9-to-5 testers that make me worry. They already have difficulty to grasp a well documented and broadly spread and long known method like TMap. Let me dig into this a little:

> Bart stated that (and forgive me for not quoting the exact wording): it is strange that experts like Rik don’t get it.
Well there are 2 answers to that.
– The first is that I (and I don’t know about the others but I assume it goes for them as well) keep on asking questions as long as I remain of the opinion that I don’t totally understand. And thus may cause the impression that I don’t get it. Actually I have been looking into CDT for 2 months now and have gained quite some insight.
– The other reason for “experts like Rik” not to get it is different. One thing I talked about before is that it is quite hard to learn about CDT since you will have to gather all information from a wide variety of sources. And you never know whether what you read is actually the good thing to read. Especially since within CDT there is a lot of debate about what actually is proper context driven testing.
What also makes it difficult is that some of the well-known CDT evangelists use such a strong voice and sometimes such a strong language that some other experts don’t feel like discussing any more and just let it go. Which might wrongly give the impression they don’t care or don’t get it.

> If it is already difficult for experts to understand CDT, how will the thousands of 9-to-5 testers get it? For them it’s not a hobby. It’s just their job. They don’t want to spend weekend-hours on testing. And their managers won’t let them study many hours of their time during work-hours (if those managers are good or bad managers is worth a different disucussion 😉

> I think CDT is mainly for Pioneers. The entrepreneurs that explore new horizons.
I see a parallel here with cooking. A real good cook looks in the refrigerator, takes out a variety of ingredients and from the top of his mind creates a delicious meal. Based on experience, hints and tips of others and (mostly adjusted) recipes from books. An average cook takes a recipe, gathers the ingredients that are listed and follows the recipe to create a good diner. A bad cook mistakes on the ingredients, misunderstands the recipe, blames the book for the disaster and goes out for a take-away diner.
We can try to make the bad cook an average cook. We’ll probably succeed. But he will never become a great cook.
And actually that’s how it always was. It takes few chiefs and many Indians to win.

> In testing not everybody is able to (and/or willing to) grasp what CDT is all about. And I think not everybody has to. As long as some do understand it. Amongst others I am trying. I have again read a lot on CDT on the various websites you all pointed to.

> Bart, thank you for the links. I found some very interesting statements:
James Bach says about the factory school tester: “the idea that people are the most important part of the context will not be a value that he holds to. The Factory mentality is about minimizing reliance on people, not exalting them.” Hmm. I have a different opinion. I know that people make the difference. Methods and tools just help them. On the other hand, I have been in situations where the best way to exalt specific people is to give them a fit-for-purpose template and instruct them how to apply a technique. But I must admit that the factory school is not emphasizing this (yet).

> Huib, thank you for welcoming me to the bright side of the future. Indeed these slides are very good food for thought. I will point them out to other testers.
One phrase of course particularly pleases me, it’s where Michael Bolton states “Adaptability over repeatability”.

> Oh Huib, about a glossary. Even in this thread of discussion we already saw why having a common terminology is good. That helped to quickly fix the misunderstanding between structured versus scripted testing. And because everybody on this blog uses a common set of terminology it didn’t need a lot of explanation and discussion. So actually a glossary is a very efficient tool. But of course we must always be cautious of possible confusion.

> Whether or not CDT is a proper approach also has to do with scale. In very large scale projects it is difficult to use the CDT approach because you can’t oversee everything as one person, so you need to work together with a (large) group and that makes it difficult to keep the pioneering angle. Most 9-to-5 testers that you will have in such large scale project are not philosophical about their job. Actually many of these people don’t understand why people like us spend so much time on a discussion like this. (for us it’s a hobby so we don’t mind spending half of a rainy Sunday on reading, investigating, thinking and formulating). So for these testers some basic structure is often better than to let them think for themselves, if you want to keep it effective and efficient.

> A wise remark of James Bach: “Polarization can be a problem when people need to live together and work together”. I agree, let’s continue to try to look at both sides of the coin and see how we can learn from each other and exalt the testing profession as a whole.

> Cem Kaner also has an interesting statement: “Progress on my path to better understanding and practice of testing (and of anything else that I’m serious about) includes discovering what needs to be changed in my thinking, and changing it.” This is exactly why people from the “factory school” of testing keep on adapting, evolving and improving. And yes, TMap people also do this and extend the TMap method with new insights to make it fit to new ways of working.
Cem goes on: “So where does progress come from? Some will come from trying things out and watching them fail (and inquiring into how they fail). Some will come from learning new skills, new facts, new models and new theoretical insights. And a lot of it will come from struggling to understand ideas that seem to directly contradict mine. Some of my best insights have come when I realized what was right about an idea that I had repeatedly rejected as wrong. (…)” Now that’s what learning is all about.

> To finish another great quote of Cem: “Controversy GOOD, Polarization BAD”.

> I’ll wear my Polaroid sunglasses agains polarization and I look forward to the continuation of learning about CDT but for now I will take a break and spend some weeks on other hobbies.

> Enjoy the summer!
> Rik
> P.s. I’m still interested whether there is (or should be) a Context Driven Development approach.

> <code style="color : lightskyblue">Rik Marselis - July 13, 2012 at 5:05 pm</code><br>

> Hi Huib,
> A quick response. In my opinion it’s not fair to say that TMap just collected valuable parts that were created by others. TMap gathered a lot of useful practices, introduced some new and welded everything together to a complete and balanced method. Also TMap added new things hadn’t been used in the testing world before. TMap doesn’t say other methods won’t work. My experience is that TMap has helped me in every situation I came accross. But in an earlier life TestFrame/RRBT used to help me in any situation. And now that I know of Context Driven Testing it also helps me. But knowing of CDT does NOT mean that TMap doesn’t help me no more.
I’m not trying to convince you to use TMap, you don’t have to if you don’t want to. But many people are very happy using TMap, as well as there are people happy with other methods and approaches. And I see that in some situations CDT might even be a smarter approach than TMap. But I also have the opinion that in some situations the CDT approach is not the best choice. I will extend on this opinion later.
I’ll also try to respond to some other things of this weeks discussion later.
(the positive thing is that this really is a discussion amongst a large group of interested people).
In the meantime have fun in California (better weather than in the Netherlands!!!)
Rik

> <code style="color : lightskyblue">Jeroen Mengerink - July 13, 2012 at 7:42 am</code><br>

> I’ve been reading this thread a while and must admit that I can’t remember all the details. What strikes me is that the CDT group mostly seems to strike on TMap when they try to make their point. From what I remember, Rik only tries to understand how CDT works and gives examples from his experience. Of course his terminology is from TMap, since this is the test language that made some definitions and allow us to talk about topics with a common basic understanding of it.

> Rik, as well as many others that have learned (or even written) TMap, know that completely applying everything that is in TMap is not the way to go. It’s seen as a toolkit from which you use the parts that can help you. Let’s not focus this discussion on making the other party look bad, but more on getting clear what are the good elements of each approach.

> By the way CDT talks about “no best practices”, but all people that favor CDT see CDT as a best practice. That’s why some people see CDT as a religious cult, like people see TMappers as a religious cult too. Let’s just try learn from each other without pointing fingers.

>> <code style="color : lightskyblue">Johan Jonasson - July 13, 2012 at 9:18 am</code><br>

>> Jeroen,
I have tried reasonably hard to not strike against TMap when making my points. In fact, I’ve tried to stress the point that when I’m making a comparison between CDT and TMap, you could exchange TMap for any other practice. However, TMap was what was being analysed when I entered the conversation and so it seemed appropriate to talk about.

>> Which brings me to your second paragraph… The conversation (to me) is about comparing TMap as an adaptable practice (or any other adaptable practice) to the context-driven principles to see if there are similarities. Or to argue that TMap (in this case) , when used correctly, seems closely related to CDT. The point I’ve been trying to make is to show that there are fundamental differences between “adaptable” and “context-driven”. It’s not been about making any adaptable approach seem bad (can’t do that without context), but to show that it’s not the same as CDT.

>> “All people that favor CDT see CDT as a best practice.”? That’s a very sweeping statement and one that risk insulting some people, although I can see that that is not your intention. For me, CDT is a set of principles and a way of approaching testing problems that generally work well for me. Does it come completely without extra baggage? No, it doesn’t. Is it often misunderstood as a best practice? Yes, it is. There are practices that the CDT people usually favor/disfavor, to a degree where we need to be careful not to fall into the best practices trap, but we aim for continuous learning and improvement and we reject the notion that we’ve ever found “the best way” to do anything. In fact, I would say that one of the core attitudes of a context-driven tester is that we do try to learn from everything around us, without rejecting any “toolbox” until we’ve evaluated the context in which it might be used. However, we don’t start to solve a testing problem by looking inside the toolbox.

>> “Best practices” are silly because the term implies that they are better than everything else. It’s a marketing tool. It’s a term that limits critical thinking and creativity (if we have something that’s “best”, why not use it).

>>> <code style="color : lightskyblue">Jeroen Mengerink - July 13, 2012 at 10:40 am</code><br>

>>> “All people that favor CDT see CDT as a best practice.” was a mistake on my side. I was typing and needed to edit some parts of the text and I was in a hurry. I meant to say that it seems that a lot of people who favor CDT, see CDT as a best practice. A lot of discussions then end up in bashing on other practices like TMap.

>>> For myself, I try to do what fits in the context. Sometimes this has TMap aspects and sometimes it doesn’t. Does this make me a context driven tester? That is what I am reading from Rik’s arguments, when are you context driven?

>>>> <code style="color : lightskyblue">Johan Jonasson - July 13, 2012 at 11:00 am</code><br>

>>>> You’re context-driven when you let the context drive your strategic decisions. You’re context-aware when you let the context suggest ways to adapt a practice that you tend to favor as your “default toolkit” to solve testing problems. You’re context-imperial if you attempt to change the context to fit that same favored practice.

>>>> That is my interpretation of (parts of) the context-driven principles. Others might have other interpretations.

>>>> Are you context-driven in this sense? You probably know that better than anybody else yourself.

>>>> <code style="color : lightskyblue">Joep Schuurkes - July 13, 2012 at 11:32 am</code><br>

>>>> In my opinion, one of the important aspects of being context-driven is having a somewhat philosophical approach to testing. Asking questions, being skeptical, questioning the validity (‘validity’ as in construct validity) of wat is being said by you and others.

>>>> This means you have to own your approach to testing – in two different ways. First of all, it is your personal, custom appraoch and no one else’s. There is no external authorityte refer to; you are your own authority when it comes to explaining and defending your test approach. Secondly, you know your approach it inside out. What’s in there is there, because you decided so. And you can explain why. You can describe your approach in three sentences, three hours or three days depending on the situation.

>>>> As a result context-driven discussions about testing need few references to definitions (except for clarifications, e.g. “By ‘test plan’ I mean the actual plan, not the document.”) or books. They are about explaining how certain tools and processes result in valuable information in specific contexts and how they do not in other contexts. This means participants not only need to how they test; they also need to have insight into the why. And that is exactly what I miss in TMap: it gives you plenty of tools to test, but no tools to think about testing.

>>>>> <code style="color : lightskyblue">Jesper L Ottosen - August 27, 2012 at 9:24 pm</code><br>

>>>>> What a debate – thanks all.

>>>>> Joeps description of CDT is great. Context-driven testing is personal – [https://jlottosen.wordpress.com/2012/08/27/context-driven-testing-is-personal/](https://jlottosen.wordpress.com/2012/08/27/context-driven-testing-is-personal/){:target="_blank"}

>>>>> I usually say I’m as context driven as the context allows. I learn about the context every day to understand it, and to try not only to do it right – but also to do the right things.

>>>> <code style="color : lightskyblue">Huib Schoots (Post author) - July 13, 2012 at 4:14 pm</code><br>

>>>> @Jeroen: I am not bashing TMap, I am bashing people who claim TMap is /the/ method. TMap is just a process description to me. It is not a valuable toolbox, since the valuable parts are created by other, TMap just collected them.

>>>> Joep made a good statement: one of the important aspects of being context-driven is having a somewhat philosophical approach to testing. Asking questions, being skeptical, questioning the validity (‘validity’ as in construct validity) of wat is being said by you and others. This means you have to own your approach to testing…

>>>> And TMap isn’t mine 🙂

>>>> I admire Rik that he asks the questions, tries to find out what context-driven testing is. But, as said earlier, he keeps saying that TMap is usable and valuable in /any/ situation. I think we don’t agree there…

> <code style="color : lightskyblue">Bart Fessl - July 13, 2012 at 12:56 pm</code><br>

> My contribution may also have given the impression that I was pounding on TMap, but let me assure you: as a trainer of TMap Next Test Engineer and Test Manager, I highly value the content of TMap. I use parts of TMap almost on a daily basis. What I hoped to achieve was to ‘push’ the readers who reason from their knowledge of TMap to try to step out of the TMap context and view the world in a different way, hopefully to see that it is the other way around: TMap does not include every possibility in the Testing Universe, no: the Testing Universe includes, among many other methodologies and approaches, the TMap methodology. So if I did step on some toes, I do apologise for that.

> On the single-mindedness of the CDT-community, I am glad Jeroen has changed his initial statement. Quite recently it seems that a more ‘radical’ group has gone its separate way, where Cem Kaner and James Bach have their different points of view. Check out and James’ reply on for the details…
If you ask me: everybody is entitled to their own opinion, and thus there are no best practices (as clarified by Johan Jonasson; I agree with him). Every situation calls for a specific approach, and the more you know about available techniques, methods, approaches and most importantly: about your own personal experience and the possibility to consult others, you will hopefully choose a right set of tools to handle your situation. But yes: the starting point is the very situation you are in calling for a unique set of tools, and not a set of tools looking for a situation to solve…

>> <code style="color : lightskyblue">Bart Fessl - July 13, 2012 at 1:01 pm</code><br>

>> The links seem to have disappeared… Cem Kaner explains his story on [https://context-driven-testing.com/?page_id=9](https://context-driven-testing.com/?page_id=9){:target="_blank"} and James Bach replies on [https://www.satisfice.com/blog/archives/724#comments](https://www.satisfice.com/blog/archives/724#comments){:target="_blank"}

> <code style="color : lightskyblue">Bart Fessl - July 9, 2012 at 11:56 am</code><br>

> I’ve read the blog, the statements, the comments, the counter-comments, the ‘attacks’ and the ‘defences’, and it strikes me that a well-known test expert as Rik and probably many more are not able to grasp the whole idea of CDT. It seems to me a bit like the ‘Flatland’ story… imagine creatures living in a 2-dimensional world, and from below (a concept which is totally unfamiliar in Flatland) you are looking up to these creatures and you want to tell them you are there. They here you, but your voice comes literally out of nowhere. Then you stick your finger through their Flatland, and suddenly an aparition is there; the Flatlanders cannot understand where the aparition comes from, but suddenly it is there, and suddenly it is gone again! And you can explain whatever you want, but as the 3rd dimension is totally unknown, the Flatlanders will not be able to understand what just happened.
Now, there is hope for the TMap community… Don’t be annoyed that I compare you to a Flatlander, but try to understand where you miss the link with the whole concept of CDT. Jan Jaap is right: TMap IS a hammer in the overall toolbox, and that is exactly where you miss the concept when you say that TMap is a toolbox, and the whole toolbox. It is not. It is a tool in the greater toolbox we have available for testing.

> As many are now trying to convince the TMap supporters, I would contribute by making another comparison. I have joined a training from James Back recently, and during one of the coffee breaks I shortly discussed with him an insight I had during his training. I wondered how it is possible that the Rapid Software Testing training has started over 10 years ago, and for some reason it has only recently attracted some attention in The Netherlands. Some critics will immediately point out that a couple of enthousiasts have joined the CDT community and RST from the start, but even though I am quite intensely involved in testing, it was new to me. How did this happen? And then it hit me: The Netherlands is some sort of Albania, or North Korea if you will, when it comes to testing… Everybody in the testing community in The Netherlands is told about TMap from the very start. And even most clients know about TMap. So whenever you want to discuss testing with a client, you start using the common language, which is TMap. Another misunderstanding: most clients know about the existence of TMap, but ‘understanding’ TMap is something different. Still, project plans are created with a section ‘testing’, where the TMap vocabulary is used and the phases are introduced. And projects start testing using TMap. Everybody ‘knows’ TMap, everybody ‘practices’ TMap and most of the testers ‘defend’ TMap. And some say: wait a second, but in my situation, testing with TMap leads to the wrong conclusions, or is even totally inefficient! And they start thinking critically about what they are doing. And realise: TMap is not covering all possible situations you can encounter. It does offer a way to handle those situations though… In the Scope and Strategy section, define what you are going to do and what not… So nobody can say to you that you didn’t do your job right when something shows up in production!

> Well, RST, ET and CDT all look up to Flatland and say: your starting point, your assumptions, is / are wrong. By structured testing what is known about what the client wants, you admit you are blind to all the rest of the world, to be more precise: the unknown, the non-described part of the world, the changing circumstances. Yes, the techniques described in TMap are usefull in some situations, but without documentation and without certainty about the future, there will certainly be more effective ways to find defects and create an understanding about the quality of the product. Structured testing is on one end of the scale, and totally unstructured testing (when there is nothing available to use for creating any structure, NOT because we do not understand TMap, RUP, Agile or any other concept!) is on the other end! TMap focuses on structured testing, and for some reason it closes its eyes mostly for situations where less structured testing is necessary, except for introducing the ‘test technique’ Exploratory Testing (where I agree with the previous comments about the wrong interpretation). On the other end of the scale, there is Exploratory Testing. In the unlikely situation that NO INFORMATION AT ALL is available, there is nothing left to the tester then to sit down, and start testing. Any plan you make, any commitment to which techniques you will use, to the number or retests that are necessary, any estimation of hours needed are a complete waist of time: you just don’t know…
And that is where my explanation of our situtation being in the North Korea of testing comes from: clients don’t want us to say we don’t know. They rather have us lie to them and say we can make an educated guess. So we plan to cover the unknown, using the language the client claims to understand: TMap. And most testers are also feeling very uncomfortable, not knowing what to expect and not knowing where they are going, so it feels like ‘safe’ to plan and document what you WANT to do. But is that a real situation? Looking back, I have NEVER been in a project that went exactly as planned, and I have NEVER found bugs that I had predicted upfront.

> So I am currently quite confident: I know my clients do not completely understand what I am doing, but should they? They don’t completely understand what programmers are doing, but do they even try to? No, they trust in the craftmanship of the programmers! It is time for us testers to convince our clients that we are a breed of craftsman as well! That we have the knowledge, experience, expertise and most important: common sense to test their products! By using our complete toolbox (yes, including the bits and pieces of TMap that can be used), directed by the constantly changing context of the project, using common sense to pick techniques wherever applicable, and using common sense to use different techniques when it turns out that the previously used techniques did not lead to the expected results. As James explained: focus when you suspect a problem area, defocus when you feel you are not on the right path, use heuristics, know your oracles…

> I realise I should have started my own blog… but maybe this is the trigger for some more interesting comments, and hopefully Rik will reply with ‘NOW I understand…’ 🙂

>> <code style="color : lightskyblue">Johan Jonasson - July 10, 2012 at 11:47 pm</code><br>

>> Hi Bart,

>> Good comment (yes, you should start a blog) 🙂

>> Question: What do you mean by “structured testing”? You said that TMap focuses on structured testing, so how does that compare to other testing practices and frameworks in terms of “structuredness”?

>>> <code style="color : lightskyblue">Bart Fessl - July 11, 2012 at 9:10 am</code><br>

>>> Hi Johan,

>>> unfortunately I have to admit I should have doublechecked my text before submitting… I found some typing errors, but the biggest mistake is that wherever I wrote ‘structured’ it should have stated ‘scripted’.
Still, your question may remain the same, as other practices and frameworks also use scripts to execute the tests. So if you don’t mind, I’ll answer the question: “what do you mean by ‘scripted testing’?. What I meant to say is that on one side of the spectrum there is scripted testing, where TMap Next is one of the methods stating that you have to prepare your tests by planning what you are going to do, find the required supporting information (whether this being documents, messages, spoken information), use this information to set up your testscripts and only then start executing the prepared tests. And on the other side of the spectrum is Exploratory Testing, which states that even in the most extreme situation you CAN start testing without any information at all.
And this is where my statement may have caused confusion: also ET can (and in most occasions: will) use some sort of structure in order to test as efficient as possible. But where ET and TMap do differ in their approach is: ET does NOT set up testscripts upfront, because new information and growing knowledge are almost certain to make these scripts subject to change, or worse: useless. TMap Next states that you can, and should, make scripts before starting your testing, and change the scripts while your information changes (call it ‘adaptability’, or in more bureaucratic environments: use change request procedures as we agreed upfront that we would only use the available information…).

>>> So I hope this additional explanation tells you what you want to know, and my appologies for wrongly using ‘structured’ when I meant to say ‘scripted’.

>>>> <code style="color : lightskyblue">Johan Jonasson - July 11, 2012 at 10:54 am</code><br>

>>>> Bart, Thanks for clearing that up, then we basically agree I think.

>>>> I asked because I know that quite a few people equate scripted and structured in a way that would imply that the opposite of scripted testing (ET) would have to be “unstructured”. I believe virtually all testing practices can be made highly structured or less structured, highly rigorous or less rigorous, etc. which is why I am reluctant to say that TMap (or just plain old scripted testing) is a more structured way of testing than exploratory testing is. It /can/ be, but it can also be the other way around.

>>>> Oh, and another reason why I often react to the word “structured” is that it is often used in a way that it implies that structured = good. I’m not saying that structure is bad, but I would suggest that, sometimes, introducing just a little bit of chaos is just what’s needed to move forward.

> <code style="color : lightskyblue">Jan Jaap Cannegieter - July 9, 2012 at 9:29 am</code><br>

> A short reaction from my side to Rik’s respond. I don’t tread TMap as the enemy, certainly not. I think TMap is a very valuable approach in some situations. Especially for unexperienced testers TMap is very usefull because it gives them guidence how to structure a test project. And when the assumptions I wrote in my first contribution to this discussion are met I will still use TMap. The only thing I’m saying is that there are (a lot of) situations that another approach can be better and a good, experienced tester should consider another approach. And I know YOU are familiar with different approaches and I’m happy to read that you want to study another. But be honest: knows everybody in the ‘TMap-camp’ know and study other approaches? Are all employees of Sogeti trained in other approaches of only in TMap? I’m not talking about another technique like state-transition diagrams. I’m talking about a fundamental other approach. To often I hear people who favor TMap say ‘There is only one approach, and that is TMap’. And I oppose that thought.

> <code style="color : lightskyblue">Rik Marselis - July 8, 2012 at 11:42 pm</code><br>

> Hi testers,
> Some extra remarks.

> Well I have stated with examples that in my opinion there is a big difference between how TMap is perceived and (ab)used, and how it is meant. I try to make clear to people how it is meant. But everyone should have an open eye for the world around them. TMap is not the one and only practice.

> So I want to learn to be a Context Driven Tester.
I have now understood that adhering to the 7 principles is not enough (in the article that started this discussion my colleagues and I showed that we do our jobs in a way that fits with those principles).
So what more do I have to do?

> I get the impression that Context Driven Testing seems to try to solve problems that originate “upstream”. Requirements engineers, Designers and Developers do a bad job, the CDT-tester comes to fix it. My belief is that we shouldn’t solve that problem by testing but by improving the entire lifecycle activities.

> So I have various questions about CDT. And I think many people have these kinds of questions. Imagine you were the IT-manager of a mid-sized company and you need a tester. You don’t know anything about testing itself and you interview some people for a job as a tester. One has a nice certificate and a book. The other has a nice story about context. Which of them is the best tester? You simply won’t know.

> In my opinion efficient work starts with understanding each other. For that a common glossary of terms is very useful. What glossary of terms is used in CDT?

> That’s where my greatest concern about Context Driven Testing is. Over the years I have seen that people did unstructured and chaotic testing and called it TMap. Nowadays quite a lot of people know when TMap is correctly used and when it isn’t. So the chaotic people looked for a new excuse to mess around. They found RUP. Nowadays most people know about proper RUP. So the chaotic people switched to Agile as their latest excuse for unstructured and (a speciality in Agile) undocumented testing. But more and more the IT world knows how to distinguish between good and bad Agile.

> And here comes my concern: The next excuse for these chaotic testers will be “I do Context Driven Testing”.
And how can we prove they are not? There is no definitive book (at least I couldn’t find it on Amazon), there is no common glossary (at least, I couldn’t find it yet) and there are many websites with stories on CDT that quite often don’t align or even contradict. Also even Cem Kaner in a reply to the post of Markus Gaertner expresses his concern about CDT being not used as it is meant.
How can we together prevent chaotic people from starting to take CDT as their latest excuse for bad testing? Instead of arguing whether good testing according to CDT is better than good testing according to TMap? Your approach has good things, our approach has good things. Let’s join forces against bad testing !!!

> My hope is that people from the Context Driven school of Testing will recognize that TMap is a valuable toolbox that can be used in a context where it’s suited. Please don’t treat TMap as an enemy but as a good neighbor you can have a chat with. You don’t always have to agree to respect each others value.

> I, for that matter, continue to search for the value of CDT in my situation. And will share that with my colleagues.
Let’s learn more from each other.

> With kind regards,
> Rik

>> <code style="color : lightskyblue">Huib Schoots (Post author) - July 9, 2012 at 9:08 am</code><br>

>> @Rik,

>> Adhering to the principles is good, but doesn’t make you context-driven yet. Context-driven is a paradigm, an approach and a community. Read the links form my reply earlier.

>> You get the impression that Context Driven Testing seems to try to solve problems that originate “upstream”. What gives you that impression?

>> How to decide which of them is the best tester? Thank you for bringing that up. That is what bugs me a lot! Why are we giving the power to hire people to (fake) managers who cannot recognize value? If you can’t distinguish a real tester from a fake tester, find someone who can! The whole certification business is based this…

>> Context-driven testers do not value glossaries. See [my reaction to Rex Black here](https://how-do-i-test.blogspot.com/2012/07/magic-medallion-of-testing-keynote-from.html){:target="_blank"}: I am telling Rex that we do not need a common language. Maybe you also should read the blog [Common Languages Ain’t So Common](https://developsense.com/blog/2011/06/common-languages-aint-so-common){:target="_blank"} by Michael Bolton about this. A common language will only create more assumptions and less communication. Context matters so let’s talk about that in stead of assuming we know what others are trying to tell us.

>> You know a lot of people who know how to use TMap correctly? First: what is correctly? How do you define that? And second: show me!

>> These chaotic testers will always find an excuse. The real concern is the fake-managers hiring these idiots. Where did you read that concern? I know [this reaction by Cem to Markus](https://www.shino.de/2012/02/29/lessons-learned-from-context-driven-testing/){:target="_blank"} where Cem says: “we have a diversity of views. I think we should embrace the diversity”. And that is exactly how I see it: there is no definitive book or Glossary. A real context-driven tester doesn’t need that. Context-driven is more than an approach. It is a mindset, a paradigm, a community…

>> Your hope is that people from the Context Driven school of Testing will recognize that TMap is a valuable toolbox that can be used in a context where it’s suited? TMap has too many dogmas to be valuable for me. I cannot think of many contexts where it can be used (or better where it can add value). The valuable parts of TMap are test design techniques and other stuff that is not originally TMap.

>> <code style="color : lightskyblue">Johan Jonasson - July 9, 2012 at 10:50 am</code><br>

>> Hi Rik,

>> Let me reply to this one:
"So I want to learn to be a Context Driven Tester. I have now understood that adhering to the 7 principles is not enough (in the article that started this discussion my colleagues and I showed that we do our jobs in a way that fits with those principles). So what more do I have to do?"

>> If you want to learn to be context-driven then what more you need to do is to stop thinking that using any method in an adaptive way is the same as being context-driven. To me that’s one of the unwritten principles. Also, see my reply to your second latest comment above for more on this. I stress again, any method. It’s not about context-driven vs. TMap.

>> I also want to address this:
"And here comes my concern: The next excuse for these chaotic testers will be “I do Context Driven Testing”.
And how can we prove they are not? […] How can we together prevent chaotic people from starting to take CDT as >their latest excuse for bad testing?

>> That’s easy. Bad testing is bad testing, regardless of the excuse. If my stakeholders aren’t getting the information they need to make informed decisions about quality, then the strategy needs to change. No CDT tester can get away by saying “I’m a context-driven tester, so I must be doing a good job”. I can be the most context-driven tester in the world and still not have the skills needed to do a good job. It’s not good testing if your testing doesn’t hold up to scrutiny, no matter what you label it.

> <code style="color : lightskyblue">Rik Marselis - July 8, 2012 at 11:33 pm</code><br>

> Dear testers,

> Again nice to see so many discussion. I can’t find the time to go into each and every reaction on the various blogs so I will put my replays here, where the discussion started.

> My overall opinion is that, after all, our views don’t differ as much as some people think. I keep seeing some misunderstandings about TMap. And I realize the Context Driven Testing-picture is still not totally clear to me.

> First a few details:
Johan Jonasson states that TMap doesn’t take the context as a starting point. In my penguin dictionary context is defined as “general setting, surrounding and connected circumstances”. The TMap book states (start of chapter 3): “The first essential of TMap can be related directly to the fact that the business case of IT is becoming ever more important ot organisations. The BDTM approach provides content that addresses this fact in TMap and can therefore be seen as the leading thread of the structured TMap test process.” So TMap uses the Business Case as a starting point. The business case is defined in the TMap glossary as “The business case provides the justification for the project and answers the questions: why do we do this project, which investments are needed, what does the client want to achieve with the result?”.
This sounds to me like taking into account the general setting and the surrounding and connected circumstances. I can’t fully judge whether this may be called context driven.

> I can’t check it in a book since I have no book on Context Driven Testing.

> What is the best book for me to buy? because I really want to learn more.

> Coming back to the Jedi analogy. I agree we would like to see passionate testers only. But the fact is for many people it’s just a 9-to-5 job. And I know quite some bosses who don’t want testers that ask questions all the time. I agree that’s not a desired situation. But testers in those situations choose something that will help them keep their boss happy, whether we like it or not. Both CDT and TMap do their best to help testers improve their situation.

> Jan Jaap Cannegieter raises the question if a tester should only master one approach or method. Well, in my opinion it is very good if testers know more than one.

> And as Jan Jaap knows I know 3 methods/approaches/frameworks in-depth, indeed all factory-school as you call them. That’s why I want to learn more on CDT.

> For Jan Jaaps statement on Exploratory testing I would like to refer to my answer to Ray. I agree it’s not well-described in the book, especially because it’s spread over 3 chapters. But the basic idea of ET is the same in CDT as in TMap. Only the word “technique” may be worth discussing.

> Jan Jaap compares TMap to the hammer from the toolbox. Please check the 4th essential of TMap NEXT. That is the toolbox, the entire toolbox. However, as you have probably learned with your own toolbox with hammers, screwdrivers etcetera, a toolbox is never complete. You can always come in a situation where you need an extra tool. For example State Transition Testing is not described in the TMap NEXT book. (it is however described in the TMap embedded book). A good tester will extend his toolbox with the proper tools he needs. If I give a TMap training course I make this clear but I can’t guarantee all trainers will. So this may still be improved.

> Iain Mccowatt states that testers should learn from experience. I couldn’t agree more. But it’s a waste of time if everybody tries to invent the wheel again. Iain disagrees that TMap can be used in any situation.

> So let me ask you a question: can you apply Context Driven Testing in any situation? And if so: Is Context Driven Testing the best approach in any situation?

> Testing is about discovery. Well yes, part of it is. But testing is also about confirmation and reassuring. And a lot of testing is regression testing, which should be structured and automated and it is very wise to measure the coverage of a regression test. There is hardly any exploration in regression testing.
A lot of bosses hate the idea of testing being about exploration. Because exploring is difficult to plan. And they want a plannable project.

> Ilari Henrik Aegerter writes about why factory schoolers duck and cover. He argues that this is not a good approach. I agree. But here the problems start earlier in the lifecycle. Testers often can’t do much more than show the problems and try to make the best of it. Of course they also should use their skills and contacts to improve the entire lifecycle. I agree that TMap is used by some testers to “cover their ass”. But that is not the starting point of TMap, it’s an example of how it is used, maybe better to say “abused”. But that is not specific to TMap, I see the same thing with Prince2, CMMI, RUP, Agile etcetera. And I think there will be examples of CDT used in the same way.

> IIari uses a definition of “test” that is in his opinion the definition used in the factory school. The definition of “testing” in TMap NEXT is: “Testing is a process that provides insight into, and advice on, quality and the related risks.” So it is a process. Not just test cases. And the process provides insight. In quality and risks. To show whether the problem is solved well enough.

> Recently there are many presentations, articles and blogs about the theme “testing is dead”. And “get rid of the “fixing phase” that testing often is”. We don’t want to test at the end, we want quality right from the start. So one of my questions is: is there already a Context Driven Development approach?? Because that to me would be the real improvement.

> Also good testing needs various activities. I assume that CDT-ers do some sort of planning and control. I also assume CDT-ers do need infrastructure. And when a CDT-er is testing he does prepare, specify and execute tests, doesn’t he (being it sequential or in parallel, these activities will be there). And once in a while he will evaluate the results and adapt his way of working whenever necessary. (these are the phases from TMap, but in my opinion they represent the activities you will always find when testing).

> My hope is that people from the Context Driven school of Testing will recognize that TMap is a valuable toolbox that can be used in a context where it’s suited. Please don’t treat TMap as an enemy but as a good neighbor you can have a chat with. You don’t always have to agree to respect each others value.

> I, for that matter, continue to search for the value of CDT in my situation. Let’s learn more from each other.

> With kind regards,
> Rik

>> <code style="color : lightskyblue">Huib Schoots (Post author) - July 9, 2012 at 9:23 am</code><br>

>> Rik,

>> You keep seeing some misunderstandings about TMap. Which misunderstandings are you talking about here?

>> I wouldn’t call this context-driven because you are using the business case as a starting point not call this context-driven because of that. Maybe you should read more about context-driven, context-aware and context-specific [here](https://context-driven-testing.com/){:target="_blank"}.

>> There is no book (yet). But a good start would be “[Lesssons learned in software testing](https://www.amazon.com/Lessons-Learned-Software-Testing-Approach/dp/0471081124){:target="_blank"}” by Kaner, Bach and Pettichord.

>> This Jedi stuff and bosses who do not like people asking questions hasn’t anything to do with testing directly but with culture! I consider these bosses as fake-managers. Testers who choose “something to keep their boss happy are consider fake-testers to me.

>> Jan Jaap Cannegieter raised the question if a tester should only master one approach or method. You say it is very good if testers know more than one. To me it is ESSENTIAL to be considered as a real tester.

>> Exploratory testing is not-well described in the book, but it is also fairly misunderstood by the writers. And they are not alone. ET is misunderstood by the majority of the test population. So everybody who truly understands ET, will not call it a technique.

>> Why is TMap (or the people who use it) trying so hard to be complete? To be the one and only approach/method? Rik do you truly believe that TMap can be used in /any/ situation?

>> Context-driven isn’t the best approach in any situation. Let me give you 3 examples (which can be found in the slides of the presentation James and Michael did for TestNet):
* When someone else is entirely responsible for the quality of your work.
* When you’re working in a single, specific, well-established and unchanging context (e.g a car-factory).
* When your goal is to change the context.

>> Why is regression testing not about exploration? Even ISTQB acknowledges the pesticide paradox. And because (fake-)managers find something hard to plan, they hate it? Testing is hard to plan, any testing is! But we like to think that testing is planable. That is why testers and their fake-managers like test cases counting and planning. Because it gives them the (fake) feeling of being in control…

>> There probably will be examples of CDT used in the wrong way. But does that make it right?

>> IIari uses a definition of “test” that is in his opinion the definition used in the factory school. The definition of “testing” in TMap NEXT is: “Testing is a process that provides insight into, and advice on, quality and the related risks.” So it is a process. Not just test cases. And the process provides insight. In quality and risks. To show whether the problem is solved well enough.

>> You say that TMap is a process. And that might be the problem: it is too much considered as a process.

>> Context-driven is not (only) an approach, it is much more than that! It is a paradigm, an approach and a community. Read this pdf containing a mindmap plus explanation made by Michael Bolton and James Bach. It was used to prepare the TestNet presentation and is published on the [DEWT website](https://dewt.wordpress.com/){:target="_blank"}. You might also want to read the [Q&A from the CDT presentation at TestNet](https://dewt.wordpress.com/2012/02/09/context-driven-testing-testnet/){:target="_blank"} on the same website.

>> I fully agree with you here Rik: TMap is a valuable toolbox that can be used in a context where it’s suited. But I think we disagree about the how often that context will be found. How much can be changed to still call an approach TMap? I think TMap (as described in the book) is only efficient and effective useable in maybe 10% of all situations. I all other we need to adapt so much, that I can’t call it TMap anymore.

>> I will be happy to help you find your way in the context-driven world 🙂 I think you are a great tester, your only downside is that you still think TMap can be used in any context… But you are learning. Welcome to [the bright side of the future](https://www.developsense.com/presentations/2011-05-TestNet-TwoFuturesOfSoftwareTesting.pdf){:target="_blank"}!

>> <code style="color : lightskyblue">Johan Jonasson - July 9, 2012 at 10:24 am</code><br>

>> Quick comment regarding the comparison between context and business case: The business case is part of the context. Considering only the business case is a start, but not enough. Huib’s link suggestion is the same I would give if you want some good examples on (e.g.) the differences between context-driven and context-aware. And the Kaner/Bach/Pettichord book is also a great book to get in close to more context-driven thinking (but, as with “Agile”, understanding the principles is the key).

>> Context-driven testing isn’t a “method” of testing. It’s a way of thinking which starts with considering the context of the problem you’re trying to solve rather than using (and/or adapting) a preferred method. As a context-driven tester, I could use TMap to solve my testing problem if I went at the problem like “Hmm, given what I know about this context, it seems like TMap might be a good framework to use here”, but not if I came into the situation with a “Ok, let’s solve this pesky testing problem of yours, I’ve got TMap right here, ready and fired up. Tell me about the context so that I can adapt TMap to it.”

>> And it’s not about TMap vs. context-driven. You can swap out TMap in my statement above against any other framework. Try swapping in “session-based test management” for instance. It’s a go-to test framework for many testers in the CDT community, including myself. I love working with session-based testing and SBTM. But… If I go into a new context and I immediately start thinking about how I could apply SBTM to this context, then I wouldn’t be context-driven! (see [https://context-driven-testing.com/](https://context-driven-testing.com/){:target="_blank"} under “Contrasting context-driven with context-aware testing.” and “Contrasting context-driven with context-oblivious, context-specific, and context-imperial testing.”)

>> I can use any tool (TMap, session-based testing, test automation, HP Quality Center, Notepad, two dull rocks and a paper clip, etc.) and still be context-driven if the context suggested them to be the best tools, but I can’t look at the tool/method/practice first and the context second and still claim I’m context driven.

> <code style="color : lightskyblue">Jan Jaap Cannegieter - July 4, 2012 at 2:47 pm</code><br>

> Hi all,

> After following this interesting discussion for a while I would like to contribute to it. My contribution concerns the start of the discussion; is TMap usable in every situation, is TMap the only method a tester should master and how fits exploratory testing in this?
First, is TMap usable in every situation? It depends how you look at it. A datawarehouse project? You can use TMap. A financial application? You can use TMap. A web application? You can use TMap. Governmental applications? No problem. Logistics? Go ahead! So seen from this point of view you can use TMap in every situation. But you can look differently to this question. Is TMap the best choise in every situation? I think not, this thought lies on the assumptions on which TMap is based. Assumptions like a stable context (at least that the client of the project knows what he wants), that information about the future system is available (the specifications), that the tester is involvel early in the project and that you want to seperate test preparation (test case specification) and execution. By the way, I don’t pretend to be complete with the list of assumptions. But when these assomptions are not met approaches like exploratory testing, rapid software testing or session based testing or an other approach. Don’t get me wrong; I think TMap is a good, maybe even a very good method in some situations. But not all situations. And I think that a context driven tester masters different approaches and composes a specific approach that fits the specific situations. This context driven testers uses elements from the different approaches.
There is one other thing I would like to say and that is a little bit of criticism concerning TMapNext. I think the explanation of exploratory testing shows that the TMap authors don’t really understand exploratory testing. TMap(Next) is about scripted testing, exploratory testing can be called non-scripted testing and is based on completely different assumptions. But nevertheless, in certain situations I’m still a fan of TMap.
I tend to see another phenomenon. Some consultancy firms have there own method. And they tend to think that this method can solve every problem. To reuse the exampel Rik used: if you have a hammer, everythink looks like a nail. But with all due respect, for a screw you can better use a screwdriver. And for me TMap is the hammer, useful in the right situation.
My conclusion. There is more in testing then TMap, or as Huib says it: there is not only one god in testing. (Personally I think there is no god at all.) There are good ideas in a certain situation and bad ideas in a certain situation and I expect from a professional tester that he looks beyond one single method. That is context driven for me.
You know where to find me if you want to respond to this.

> <code style="color : lightskyblue">Rik Marselis - July 3, 2012 at 10:53 pm</code><br>

> Hi Guys,

> I’m happy to see so many people are interested in this discussion.
I’ll try to go into the subjects raised.
Now let me first straighten one thing. I am not arguing that TMap is the same as Context Driven Testing. I am also not arguing that Context Driven Testing is wrong, on the contrary I see many positive things in CDT (I actually read Cem Kaners website).

> But I am showing that the principles of CDT are not as unique as some people try to demonstrate. A lot is based on common sense and practical experience. Both CDT and TMap are based on common sense and practical experience.

> I know examples of TMap being not used as intended. I have met people who stated they were working according to TMap but had actually never even touched the book nor spoken to anyone that had read it.
That is not unique to TMap. That also goes for Prince2, for RUP, for SCRUM, and a lot of people that say they work agile don’t even know there is a manifesto.

> The thing I would like to point out is that there is a difference in a method as it is intended and a method as it is used. Some use it as intended, others don’t. If someone uses it in the wrong manner, should we say to all others to stop using it?

> A thing that I try to demonstrate is that there are a lot of wrong perceptions about the way TMap is intended. So I try to show you factual information as written in the book, that helps understand how TMap is meant.
And indeed in a book of 752 pages there are errors. And indeed we have come 6 years since the book was published so there are some new insights.
People that care about our beautiful testing profession do their best to communicate these new insights in presentations, blogs, articles and books. I think it’s pityfull when these people are called “hilarious”. What’s the difference of my colleagues and friends sharing their experiences from your colleagues and friends sharing their experiences? I try to treat you with respect, please treat me / us with the same respect.

> Let me go into some details:

> Hi Joep,

> You state that TMap says the requirements must be in a document.
I can’t find this statement in the book.
Let me expand a little on the goal of testing and the test basis.
The basic starting point in TMap about requirements is described in the principle as Business Driven Test Management (section 3.1). Among other things the definition says “ (…) what does the client wish to achieve with the result”. To me this is similar to what problem has to be solved.
On the next page (58): “At various moments in the testing programme, the client is involved in making choices. The advantage is that the test process matches the wishes and requirements – and therefore the expectations – of the organization as adequately as possible. (…)”
Requirements do not have to be in a document. Actually if you would say all requirements should be documented you would hardly ever end a project.
But there needs to be a clear view of the requirements, in one iteration or more.
The requirements are part of the test basis. In section 6.2.3 I read: “The test basis, or the gathering of all the written and unwritten requirements with which the test object should comply, can take various forms.” (for non-native speakers: the word “or” in this sentence does not indicate an alternative but an emphasis)
The term “test basis” as the TMap book uses it, can also be translated to “oracle” as for example the ISTQB glossary names it. The Test Basis consists of everything that can define what the expected behaviour of the test object should be. Including undocumented requirements, non-functional requirements, anything.

> Hi Johan,
I would suggest to put “ad hoc, unstructured, random, chaotic, unorganized testing” at one end of the spectrum. And after that let’s find some arguments how to put other views on testing in the spectrum. I hope you do agree that anything is better than the chaos that I (and you probably also) come across more often than we would think possible.
Somewhere in the spectrum people say you need a toolbox to pick your tools from. Both CDT and TMap do. (actually when I am training novice testers I actually bring a toolbox with me to demonstrate for example that an automated tool like a battery-powered-drill is no use if your problem is a nail that needs to be banged in a plank).

> Hi Ray,
I immediately admit that I am not totally happy with the way ET is described in the book. For example that it is at many different places in the book.
At page 191 we read “the (very free) “technique” of Exploratory Testing”. Which implies that the TMap authors know that ET is different than other techniques.
At page 293 we read “While exploratory testing (ET) is discussed in more detail in Chapter 14, it is actually not purely a test desing technique. With ET, the tester makes decision during the test execution as to which test he is going to execute. He designs a test on the spot, using his knowledge of test design techniques, without documenting them. As such, ET has no place in the specification phase, since everything takes place during test execution.” (after this session based testing is explained).
I won’t quote all of chapter 14’s description of ET, Huib has already referred to that.
But in section 14.4.5 you’ll read that exploratory testing and error guessing are “rather a strange technique among test design techniques”.
To me the fact remains that TMap acknowledges the value of using experience to enhance your testing.
And indeed CDT and ET are different things.

> And, finally, Hi Huib,
Some testers want to become a Jedi tester. Other testers don’t have the faintest idea what a Jedi is (some are simply too young to know ;-).
My point is that maybe the 80/20 rule applies here. 20 % of testers wants to be a Jedi tester, 80 % of testers want to be a 9-to-5 tester. They don’t give much about being the best in their profession. As long as the boss and the client are happy they are happy. And unfortunately some bosses are easily satisfied. Some bosses for example are happy when a tester shows a certificate. My opinion is that a certificate in itself has no use. But some companies select testers based on whether they have a certificate. So anyone that has to apply for a new assignment or a new job will be asked about this. And therefore testers take training courses that aim for passing an exam. On this part the difference between for example ISTQB and TMap is that ISTQB was started to create certificates and later books were added. TMap started to help testers to do a better job, and later certificates were added.
Now of course an exam-training doesn’t necessarily create better testers. A certificate at best shows that a tester knows some things about the profession.
On the other hand, being a trainer myself, I have seen proof that testers pay more attention to vital basic knowledge (say for example “what is a boundary value”) if they know they will have to pass an exam. What we call in dutch “a stick behind the door”.
But just like you I think certification-focussed training courses are at best a start towards better testing. Testers need to be challenged and helped. Currently I am organizing a big plea within my company to bring the principle of personal coaching to a higher level. And actually today made a move forward in that. Some testers are reluctant to ask for help. Other testers think they already know everything. For both help should be available to continuously improve their work (a principle also known as KAIZEN).
Maybe here we find the biggest difference between “Context Driven Testing” and “TMap testing”. CDT people have a force within them to become the Jedi tester. Many TMap testers just want to do their job properly. A Jedi tester may look down on an ordinary tester. But that does not imply that other testers are worthless. Not everybody can become a Jedi. Not everybody wants to be a Jedi.
But every tester should be aware of the situation they are in, and tune their work to fit the situation. CDT approaches this differently than TMap, but both have this goal.

> I see a parallel with Agile. I have listened to the Agile experts and if I sum up all qualifications they require for an Agile tester my conclusion is they need “above average” testers. Unfortunately at best 49% of the testers are “above average”. So what to do with the other 51% of testers? Forbid them to test? No, part of them can be trained and coached to become an agile tester. Some will never learn, no problem, waterfall still exists and will remain to exist. I know this, when I started as a COBOL programmer over 30 years ago people told me COBOL would be very soon extinct. But nowadays still new COBOL programmers are trained. So old approaches, methods and techniques remain valuable in some situations.

> So in my opinion there is room for every type of person. And in some situations one approach is best, in other situations another approach will work.

> My apologies if I forgot to comment on one or another remark, but even I need some sleep once in a while 😉

> With kind regards,
> Rik

>> <code style="color : lightskyblue">Johan Jonasson - July 4, 2012 at 11:41 am</code><br>

>> Hi Rik,

>> So many things are being discussed at the same time in these threads, not sure I’m replying to your core argument or not, but I’ll give it a go nonetheless.

>> You wrote that you were not trying to claim that TMap and CDT are the same. Fair enough. But earlier you were quoting the context-driven principles and compared them to how TMap encourages testers to think and act according to similar principles(?) So you are saying that when TMap is used as it is intended to be used, together with an adaptive mindset of a perceptive tester, it has similarities to context-driven testing, correct?

>> There are similarities between lots of things. I love learning more about testing through analogies. However, what I was trying to say when I claimed TMap and CDT are on different ends of the spectrum was that while TMap, used correctly(?), is a prescriptive framework that can be adapted to fit different contexts, it still uses TMap as a the starting point, instead of the context. That represents a huge difference in mindset, regardless of how adaptive TMap is.
(The “spectrum” I was referring to has nothing to do with TMap or CDT being more or less structured. Structure is a totally different spectrum and not what I was going for. In fact, I couldn’t place CDT on a structure spectrum/continuum, since the level of “structuredness” required depends on the context.)

>> As for the Jedi analogy in your reply to Huib. I agree that not everybody wants to become “great” and that’s fine. But I think every tester needs to want to become “better”, or they have chosen the wrong profession. There’s a big gap between aiming for greatness and being complacent and wanting to just learn enough about testing to get by without being fired. It doesn’t matter if one believes that CDT (or TMap) is great or crap, but the minute a tester thinks he/she knows enough to do their job properly is the moment they fail as testers in my opinion.

>> When we can’t learn more about the product we’re testing, we change the way we’re testing to learn more. To me, people who work well as testers seem to be able to apply that kind of thinking to all kinds of learning. And if we want our profession taken seriously, as one that requires skill, I don’t think there is room for testers who refuse to improve.

> <code style="color : lightskyblue">Johan Jonasson - July 2, 2012 at 12:11 pm</code><br>

> Thank you Huib and Rik for making this exchange public. The testing craft needs honest discussions like this. Please keep it going.

> To me, TMap and the context-driven school of thought are on opposite ends of the spectrum. One starts with a prescriptive toolbox, the other starts with the context. One adapts the toolbox to the context, the other selects whatever tools make sense from a number of toolboxes. It seems to me like we are comparing being context-aware to being context-driven, at best.

> I’ve laid out a slightly longer response here.

> Cheers,
> Johan

> <code style="color : lightskyblue">Joep Schuurkes - July 1, 2012 at 10:24 pm</code><br>

> Huib and Rik,

> Thank you very much for this discussion: it’s a great illustration of how difficult communication can be when the participants operate from a different paradigm.

> To take one example:
5 The product is a solution. If the problem isn’t solved, the product doesn’t work.
True. Section 2.1: “[…] it [testing] aims to establish the difference between the product and the previously set requirements. […]”
The usage of ‘previously set requirements’ is an example of the fact that “[…] TMap is not about testing but about a process and deliverables.” as Huib says above. According to TMap there is a process that delivers the requirements document and only the requirements in this document count. Never mind the requirements we didn’t think about, the ones we thought to be obvious, the ones we learn about during design, build and test.
In principle no.5, however, this distinction between the ‘previously set requirements’ and all the other ones is not made. If the problem isn’t solved, the product doesn’t work. Period. There are many reasons why the problem may not be solved. Coding errors or design errors are common causes. Forgotten requirements is another one. Or perhaps the problem changed. What then? What if the problem no longer corresponds to the previously set requirements, yet the product does solve the changed problem? According to principle no.5 we’re good to go to production, according to TMap we’re not? (One possible answer to that question: if the requirements document no longer matches with the problem, the requirements management process is having issues.)
To summarize: TMap focuses on the requirements document; context-driven testing on the requirements. As Michael Bolton likes to say: The requirements document is not the requirements!

> Now one might object I’m nitpicking, focusing on just two words, but I think that’s missing the point. These two words, ‘previously set’, point to the fact that TMap belongs to the factory school of testing. It wants to make testing a repeatable process which is plan-able and delivers clearly defined deliverables. The fact that TMap Next has adaptivity as one if it’s four essences, does make it context-conscious. And I do think that’s a big improvement over the old TMap. Context-driven, however, it is not and in parallel with what Huib said above: if you were to make TMap context-driven, it would no longer be recognizable as TMap. It would need to operate from a different paradigm.

> <code style="color : lightskyblue">Rik Marselis - July 1, 2012 at 10:57 am</code><br>

> Hi Huib,

> Your remarks on exploratory testing don’t focus on exploratory testing, they focus on test design techniques. I admit that ET is a special case. If you read section 14.4.6 of the TMap book you’ll find it starts with a definition of James Bach (the one who is known from context driven testing). So TMap acknowledges the value of exploratory testing.
In this section the TMap book also gives examples of adaptiveness: situations when to apply exploratory testing and situations that are less suitable to use it.

> Let’s focus on adaptiveness. TMap is method that can help in any situation. The book describes hundreds of things. And you know at least as well as anyone else that you should never do everything the book describes. You should pick the cherries so to say. That is adaptiveness. And in my opinion that’s what you call context driven. I’ll go in some more depth.

> Let’s look at the 7 basic principles of context driven testing (taken from : [https://context-driven-testing.com/](https://context-driven-testing.com/){:target="_blank"} )

> 1. The value of any practice depends on its context.
TMap section 3.4: TMap is an approach that can be applied in all test situations and in combination with any system development method. I offers the tester a range of elements fit his test. (…). Depending on the situation the tester selects the TMap elements that he will deploy. There are situations where only a limited number of elements need to be used.

> 2. There are good practices in context, but there are no best practices.
This is an interesting statement. To my experience most people that use the words “best practice” mean it in the way it is meant here, “a good practice in context”. So this is a discussion about words, not about being able to do a proper job.

> 3. People, working together, are the most important part of any project’s context.
I couldn’t agree more, we nowadays call this “collaboration”, a term that wasn’t common place yet 6 years ago when the book was written. Section 3.3 already describes qualities a tester should posses and more on this subject is in the vision document for using TMap in an agile development environment. Look for this document at: [https://www.tmap.net/tmap/downloads/testing-agile-software-development-environments-tmap-next](https://www.tmap.net/tmap/downloads/testing-agile-software-development-environments-tmap-next){:target="_blank"}
And the upcoming PointZERO book will describe much more on this.

> 4. Projects unfold over time in ways that are often not predictable.
Section 5.3.2 shows TMap agrees on this and gives help in managing this. I quote: “practice has shown that deviations from the original plan often occur. Such deviations may have a cause both inside and outside the test process. (…) The test manager must detect such events or trend as early on as possible. He can then take timely measures (…).” And keep in mind that “test manager” is a role, it’s not necessarily a separate individual person.

> 5. The product is a solution. If the problem isn’t solved, the product doesn’t work.
True. Section 2.1: “Put bluntly, the main aim of testing is to find defects: testing aims to bring to light the lack in quality, which reveals itself in defects. Put formally: it aims to establish the difference between the product and the previously set requirements. Put positively: it aims to create faith in the product.”
That the stakeholders should have faith in the product means they should have faith the product solves their problem.

> 6. Good software testing is a challenging intellectual process.
That’s why you need skilled and trained people that know what methods, tools, techniques exist and are conscious of their situation so based on their perception they can adapt their way of working. As we described in our article.
Section 8.6.4 “Training, creating work experience and a coaching programme are vital components”.
I must admit that many organizations especially forget to implement the coaching programme. So I agree that this is something the testing world should do better.
But having stated this I again think the similarities between context driven school of testing and the TMap way of testing are bigger than the differences.

> 7. Only through judgment and skill, exercised cooperatively throughout the entire project, are we able to do the right things at the right times to effectively test our products.
Indeed and therefore “Testing is a PROCESS that provides insight into, and advice on, quality and the related risks”.

> Let’s focus on the fact that we all feel that testers should understand their profession, have an open eye for the situation they are in and select the aspects from all available knowledge that they need in a specific situation.
I don’t mind when you say that many testers use TMap to hide themselves, blame TMap for not doing a proper job, I’ve seen this happening too. But that is something different than saying TMap in itself is no good. An adaptive tester as well as a context driven tester will find very many useful things in the TMap book, as well as in many other books. And a tester only gets good by falling and standing up again, then learning from mistakes, using experiences of himself and others.

> Enjoy your testing!!
Rik
p.s. did you notice that our article contains 7 sections, exactly 7 sections. Maybe you would like to read them again.

>> <code style="color : lightskyblue">Huib Schoots (Post author) - July 2, 2012 at 6:54 am</code><br>

>> The fact that you keep saying that TMap is an approach that can be applied in all test situations and in combination with any system development method, proves to me that TMap is not context-driven at all but to be considered as a best practise. By the way, the series of books and white papers written by Sogeti is hilarious. Trying to “stick” a TMap logo on every populair testing topic: agile, chain testing, cloud testing, infrastructure testing…

>> The fact that you keep saying that the similarities between context driven school of testing and the TMap way of testing (which I call factory school) are bigger than the differences, proves to me that you do not fully understand what context-driven is about. Please read the text of the key note “Context-Driven Testing” Michael Bolton, which you obviously haven’t done yet.

>> Some quick reactions on what you have written:
1. If only a limited number of elements are used, can you still call it TMap?
2. This is not a discussion about words, but about paradigma and mindset.
3. So 6 years ago people didn’t work together? I miss this skill in the list of important qualities a tester must have in TMap.
5. See the response by Joep.
6. That’s why you need skilled and trained people indeed. But the TMap courses I know do not train skills, they train theory!

>> James Bach wrote an interesting article about CDT. He says a couple of things that clearly mark the differences between TMap and Context-driven testing:
* The Context-Driven School of software testing is a way of thinking about testing
* CDT is not a style of testing. It’s not a toolbox of methods. It’s more fundamental than that. You could think of CDT partly as an ethical position about testing.
* Because testing (and any engineering activity) is a solution to a very difficult problem, it must be tailored to the context of the project, and therefore testing is a human activity that requires a great deal of skill to do well. That’s why we must study it seriously. We must practice our craft. Context-driven testers strive to become the Jedi knights of testing.

>> TMap is not a way of thinking about testing, it is an approach to testing, actoolbox of methods. TMap doesn’t aspire people to study it seriously, it strives to get people certified.

>> <code style="color : lightskyblue">Ray Oei - July 2, 2012 at 5:43 pm</code><br>

>> Hi Rik,

>> One thing that always struck me in the TMap Next section on ET is the fact that it warns for ‘the use of other sources than the system documentation has a big risk that the tester will trust on these other sources instead of the sysdoc.’ (roughly translated and summarized by me). This implies, at least to me, that /good testing/ according to TMap should /always/ be based on this ‘system documentation’.
And that is not context-driven.

>> I have more issues with the description of ET in TMap, well, with all points under the ‘Don’t use in case off’ section.
And last but not least: ET is not the same as context-driven!

>> Ray
