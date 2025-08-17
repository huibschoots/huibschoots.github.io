---
title: Let’s stop talking about testing, let’s start thinking about value
date: 2018-10-18 00:00:00 +0100
categories: [Communication]
tags: agile conference rapidtesting skills communication reporting    # TAG names should always be lowercase
<!-- pin: true -->
image:
  path: /assets/img/stoptalking.png
---

<blockquote class="prompt-info">This is an Alex Schladebeck and Huib Schoots co-production and this blogpost was co-authored by Alex. So where you read I, you could read Alex and I.</blockquote>

This year [Alex Schladebeck](https://www.schladebeck.de/){:target="_blank"} and I did two keynotes titled “**Let’s stop talking about testing, let’s start thinking about value**” at QA Expo in Spain and TestNet in the Netherlands. This blogpost has the most important points we made in our talk.

The keynote was inspired by some of our frustrations: “**Testing is under appreciated**” (Alex) and “**Most testers are unable to explain what we do**” (Huib). Huib wrote about [his frustration](https://www.huibschoots.nl/wordpress/?p=2323){:target="_blank"} back in 2016 already. This blogpost is about Huibs frustration that most testers cannot come up with a decent definition of testing. And even worse: a big majority of the people who call themselves professional testers are not able to explain what testing is and how it works! They have trouble explaining what they are testing and why they are doing specifically the thing they are doing! How can anybody take a tester seriously who cannot explain what he is doing all day?


### Why are testers often not valued?
Alex’s frustration is that testing is not valued by others. Developers are seen as the rockstars of the project because they create the software that adds value. But why are testers often not valued?

- **Lowered expectations for testing expertise by stuff like ISO standards and ISTQB**: I wrote about [certification](/posts/does-certification-have-value-or-not){:target="_blank"} and [standards](https://www.huibschoots.nl/wordpress/?p=1800){:target="_blank"} before. ISTQB and standards put too much emphasis on process and documentation, rather than the real testing. By assuming there can be a standard, you say that there is one best way to organize and document your testing. But isn’t your test strategy heavily dependent on its context? When using standards we tend to focus on complying with the standard, and lose sight of the real goal. This sort of goal displacement is a familiar problem in many situations. Also, the idea that you can learn how to test is a couple of days of training is dangerous. Remember lesson 272: if you can get a black belt in only two weeks, avoid fights (Lessons Learned in Software Testing: A Context-Driven Approach by Bach, Kaner and Pettichord).
- **Avoiding controversy**: nowadays more and more people advocate to be nice! I think that we confuse being nice, with being kind! An [interesting article](https://www.huffpost.com/archive/ca/entry/why-you-should-stop-being-nice-and-start-being-kind_b_7142982){:target="_blank"} about this phenomenon is written by Marcia Sirota. Of course we need to respect other people, but to push the testing craft forward, we need to have firm discussions and disagree with others way more often. Being nice doesn’t help. Serious feedback does!
- **We devalue our own work by becoming tool jockeys**: unfortunately there are too many testers (and teams) out there who focus too much on automation as much as possible. Why? Because they can! The testers in those teams are often so busy doing automation that they do not have the time to test anything…
- **We do not stand up for our craft**: we do not fight back enough when other people say they do not need testers, or if they tell us how to do our jobs to name a few examples. We have to learn “testers self-defence: to stand up to people who try to dictate how do our jobs. We have to learn how to organize effective (and efficient) testing. And we need to learn how to talk about our work in a way others understand. This requires practice!
- **We do not learn or practice enough**: testing is difficult! We have to deal with complexity, ambiguity, change and people. Testing is a craft, not something you do as a hobby. To become a craftsperson, you have to practice (also see my blogpost: [a road to awesomeness](https://www.huibschoots.nl/wordpress/?p=2466){:target="_blank"}).
- **We don’t know how to talk about testing**: as said before: how can anybody take a tester seriously who cannot explain what he is doing all day? To be really valuable, testers need to learn to talk about their testing in a way others understand and find valuable.

So looking at these things, are we okay with this? I don’t think so. But what can we do about it? We are trapped in this vicious circle: we need to talk about testing! It is good for our soul to explain what I did and why, but we don’t know how to talk about our testing in a way that others understand.

![Slide from keynote: what are traps?](/assets/img/stop-talking-1.png){: width="600" .normal .shadow}

### Alex and I listed some traps

- **Stories decay into Numbers**: testing is about providing information to enable others to make informed decisions. The number of test cases or the number of bugs do not really matter. It is the story about the product and the risks involved. Those numbers might back up your story, but they do not tell the story!
- **A performance decays into Deliverables**: testing is about finding problems, collecting information, exploring and experimenting to discover new information. Sure, documents and stuff sometimes help us, but testing is a performance. (James Bach talks about that here: a test is a performance and here: Test cases are not testing: towards a culture of test performance).
- **Test strategy decays into Test execution**: when was the last time you saw a really good test strategy? In many cases I find master test plans where everything is described except the strategy. It is hard to create a test strategy and it is even harder to write it down or visualise it. Many testers I meet focus on test execution: creating test cases and scenarios and calling that the strategy.
- **Tool supported testing decays into Automation**: testing using tools is a great idea. It gives us more opportunities to test and improves testability. But as said earlier: it becomes a problem when we focus too much on automation or even try to automate all our work. We cannot automate testing.
- **Many kinds of coverage decays into One kind of coverage**: testing benefits from diversity! You find a certain type of bug with a certain test technique or approach. By using lots of different views, approaches and techniques, we find more problems.
- **Learning activity decays into Formalized static tasks**: testing is learning about the product for our stakeholders. It’s not about verification and validation, there is much more to it. I like to replace such words with challenge the belief that (verify) and investigate (validate). Those activities provide the valuable information we need.
- **Balance risk and uncertainty decays into Certainty**: people like to be comfortable and we like to give other comfort as well. But as testers we need to stay unsure, when others are sure. It is our job to keep asking critical questions. We are not here to give confidence or comfort, we are here to demolish unwarranted confidence! Also keep in mind that to find new unexpected problems, we have to go where nobody has thought of and nobody went before us. That will cause confusion which feels uncomfortable for many. I learned to be okay with confusion, since this is essential for learning new things.
- **Business Impact decays into Bugs**: some testers are frustrated when bugs aren’t fixed. But that is part of the deal: some things that bug us, are just not important enough.
- **Product story decays into Testing jargon**: I think this is the main problem for people not listening to testers. We talk jargon and about what we do in detail too much. We say stuff like: “We’ve executed 17 test cases in the system test, we’ve automated 50% of the test cases for area C and now have 30% code coverage. We found three major and five medium bugs”. And we are surprised that nobody will listen. We need to talk about the product! So you have found 8 bugs? Who cares? Talk about the risks involved, about the threats to the value of the product.

### So maybe testers need to stop talking about testing?
Well, not exactly. We need to remember that the information from testing enables other people to do better work! So the testing itself isn’t always interesting, but the story about the results and the impact on the business is!

Just imagine a conversation between a tester and the PO:
Tester: The testing is going well!
PO: Okay, great. How is the product?
Testers: It sucks!

### The role of testers

What is the role of testers? Testers see things for what they are. Testers help others make informed decisions about quality, because we think critically about software. This means creating awareness about the state of the product by staying sceptical when everybody else is sure. So we have to know what our clients want from testing. What information do they need to take these decisions? Project managers have one big question to be answered: are there problems that threaten the on-time, successful completion of the product?

### Product Risk Knowledge Gap

![Slide from keynote: Risk Knowledge Gap](/assets/img/stop-talking-2.png){: width="600" .normal .shadow}

I like to explain testing using the “Product Risk Knowledge Gap” like we teach in RST. Knowledge Gaps are the things that we need to learn in order to make good decisions. We need to learn about the product to close the knowledge gap. The more we know, the less risky our decisions will be. Testers should focus on questions like: what does the client need to know right now? What might hinder the successful completion of the product? What role do I need to take on in this situation to ensure we achieve our aims? Does this information matter? To whom?

But there is a way to avoid talking about testing. Just find enough questions and problems so that your stakeholders simply won’t have time to ask you questions back! Also, if you tell a credible story and give them the information they need, nobody cares how you got the information in the first place. In this case you need to stand your ground: tell people what they need to hear despite what they want to hear. Again: it’s your job to see things for what they are. If you give people the chance to doubt what you are doing, because you do not deliver the information they need, they will start asking questions about how you do your job. And if you have to talk about how you do your testing, then prepare to be able to tell a damned good story about your testing. Something they can understand and relate to.

### The testing story

The testing story by Rapid Software Testing can help you tell that story. Tell a story about the product, what you saw, what you did to gather that information and how valuable that information is. (See “[Braiding The Stories](https://www.developsense.com/blog/2012/02/braiding-the-stories/){:target="_blank"}” by Michael Bolton). The testing story contains three stories that feed into each other:

1. The **product** story: a qualitative report on how the product can work, how it fails, and how it might fail in ways that matter to our clients.
2. The **testing** story: to make the product story credible, the testing story is about how we configured, operated, observed, and evaluated the product; what we actually did and what we actually saw.
3. The **quality** story: to make the testing story credible, tell a story about the quality of the testing. Describe why the testing we’ve done has been good enough. It includes details on what made testing harder or slower and what we might need or recommend in order to provide better, more accurate, more timely information.

### Modern testing
As testers we do way more than only testing. We are enablers of testing by doing all kind of other things to be a service to the team and our clients. Researching this, Alex and I found the [Modern testing principles](https://moderntesting.org/){:target="_blank"} by Alan Page and Brent Jensen. There is a lot of good stuff in there, and yet we feel that there is not enough focus on the actual testing in their principles. Furthermore, we think that the seventh principle “We expand testing abilities and knowhow across the team; understanding that this may reduce (or eliminate) the need for a dedicated testing specialist.” is formulated too negatively. We do not talk about dedicated test specialist as a function. But we like to talk about testing skills. And although we think there should not be a need for a dedicated testing specialist, we see too many people in teams who do not like testing. Passion (or at least motivation) for what you do, is conditional to become good at anything. So we created our own testing principles (inspired by the modern testing principles of course):

![Slide from keynote: Our testing principles](/assets/img/stop-talking-3.png){: width="600" .normal .shadow}

1. Deliver insight into status of the product
2. Practice (and enact) critical thinking
3. Enable testing: lead, coach, teach, support
4. Discuss testability
5. Explore & experiment
6. Promote waste removal / avoidance
7. Help to accelerate the team
8. Advocate continuous improvement
9. Foster quality culture
10. Keep critical distance and close social distance

### Stop talking about testing?

So do we need to stop talking about testing? Not really. But we need to talk about the product, risks and value more. We can talk about actual testing only to back our story up or if they ask questions. And even then, we need to make our story understandable and relatable to others. Make sure you are a service to the team. We created our own testing principles to explain what value we add. We also have a pretty clear story on what testing is and how it adds value. We did this by practicing our stories many times. But we also figured out our own testing paradigm. That makes is easier to talk about what we do and how we add value.

Software Development is research & development: a series of experiments that ultimately lead to a suitable solution. We are dealing with customers who do not know exactly what they want. Furthermore, we are dealing with the complexity, confusion, changes, new insights and half answers. That requires research. As we team we are looking for what works and what doesn’t. Testing is of great importance for this! Testing provides insight and overview. Testing shines a light on the actual status of product and project. These insights enable others to make better decisions and eventually make better products.

### Here are the slides
<iframe src="/assets/files/Stop-talking-Alex-Schladebeck-Huib-Schoots.pdf" width="400" height="250">
</iframe>

---

### Comments from the original Wordpress blog:

> **AnonReader - October 29, 2018 at 5:17 pm**
Hi,
Just want to say that this was an interesting blog post. As a tester currently trying to figure out how to be better at what I do I have been reading more about the craft of testing. As far as the testing principles, what would be some ways to achieve the following:
3) Enable testing
4) Discuss testability
7) Accelerate the team
8) Advocate continuous improvement
9) Foster quality culture
10) Keep critical distance and close social distance

>> **Huib Schoots - October 29, 2018 at 8:57 pm**
Hi,
Good question!
>>3) Enable testing
We as testing experts, need to help others to test, by supporting them but also to teach and coach our team members and the users who test. More on coaching testers: [Coaching Software Testers}(https://www.youtube.com/watch?v=B_kARE3mzbM){:target="_blank"} by Anne-Marie Charrett and [this blogpost](https://katrinatester.blogspot.com/2017/04/test-coaching-competency-framework.html){:target="_blank"} by Katrina Clokie.

>>4) Discuss testability
Testability is how easy it is to test a product. So we have to discuss this with our team and ask them to make the product more testable. More on this topic in these videos by James Bach: [Heuristics of Testability](https://vimeo.com/78912852){:target="_blank"} and [How to Think about Efficiency in Software Testing](https://vimeo.com/10715536){:target="_blank"}

>>7) Accelerate the team
We help the team go faster by eliminating waste in everything the team does and stimulate learning. Testability helps us to test faster, but we can also remove useless testing, useless documentation and detect and discuss other waste in our projects. Since testing is learning, we can use our skills to stimulate learning and create more insight and overview so we know the status of the product and project.

>>8) Advocate continuous improvement
Testers can use their skills as critical thinking, asking good questions and analysis to help solve problems and help the team improve continuously.

>>9) Foster quality culture
Testers are not the defenders of quality. Everybody is! But if nobody feels responsible, this culture will never become reality. So we can help others to pay more attention to quality. Not only by testing, but in everything we do.

>>10) Keep critical distance and close social distance
Critical distance is using a different way of (critical) thinking to find problems. Close social distance means we have good relationships with others so we can collaborate better and easier. Have a look at the talk by James Bach here: [Don’t Think So Close to Me: Managing Critical and social Distance in Testing](https://www.uttv.ee/naita?id=27696){:target="_blank"}

> **@halperinko - Kobi Halperin - October 18, 2018 at 8:04 am**
Hey Huib – Thanks for insightful post!
And the great posters (Hope someone will actually print these so we could hang them in the office) (Would you give consent to print these in our coming issue of local IL Testing Magazine?)
As to “Lowered expectations for testing expertise” – it depends on where you look at these, when these were defined it was for having at least a minimal base of knowledge 20 years ago when most testers did not even went through a basic testing course – so it actually was higher expectations.
Of course since then we should have made our expectations even higher – and some people put an effort on that, and promote Quality & Testing courses in Universities – in IL ~60% of Uni & colleges teaching CS already include that after wide efforts by volunteers in last ~10 years.
Yours,
Kobi H.

>> **Huib Schoots - October 18, 2018 at 10:59 am**
If you credit us, feel free to use anything from the post!