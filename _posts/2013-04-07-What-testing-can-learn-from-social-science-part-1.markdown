---
title: What testing can learn from social science – Part 1
date: 2013-04-07 00:00:00 +0100
categories: [socialscience]
tags: context-driven exploratorytesting rapidtesting socialscience # TAG names should always be lowercase
image:
    path: /assets/img/socialscience.png
---

Last February and March I have had the privilege to talk at Belgium Testing Days in Brussel and [TestBash](https://www.ministryoftesting.com/memories/testbash-2-0-memories){:target="_blank"} in Brighton about what testing can learn from social science. In a series of blog posts I am going to write about this subject: why I choose this topic, what sources I studied and finally how I have applied this stuff to my work.

<iframe style="border: 1px solid #CCC; border-width: 1px 1px 0; margin-bottom: 5px;" src="https://www.slideshare.net/slideshow/embed_code/17687002?rel=0" height="291" width="342" allowfullscreen="" frameborder="0" marginwidth="0" marginheight="0" scrolling="no"></iframe>

### Rapid Software Testing
In the Rapid Software Testing Class I took in 2011 Michael Bolton talked about being empirical and a critical thinker as a tester. About collecting data from experiments using a heuristic and exploratory approach. About reporting by telling stories in testing instead of only reporting figures and numbers. Testing is about providing valuable information to inform management decisions. This awesome class empowered me to connect the dots of stuff I had been thinking about for years. It also pointed me towards a lot of books and information “outside” the IT and testing domain. It also triggered me to learn more about social science.

### Test reports
Do you recognize test reports like this? (click the report the enlarge).

![Test Report](/assets/img/testreport.png){: width="500" .normal}

I used to write test reports like that. I was counting test cases and issues and advising my clients to take applications in production. But what do these numbers tell us? What if we didn’t test the most important functionality is the software? Numbers don’t mean anything without context!

Another example was an assignment I did at a telecom company years ago. Testing was estimated by numbers of test cases. We have 8 weeks to test so we can do 800 test cases, was a normal way to plan and estimate testing. Somewhere along the project my project manager told me his budget had been cut 10%. He asked me to drop 80 test cases from our 800 test cases scope. What was he thinking? As if all test cases take equally long to create, execute and report?

### Exact or social science?
Testing and informatics ([the science of information](https://en.wikipedia.org/wiki/Informatics){:target="_blank"}) are often seen as exact or physical science. People perceive that computers always do exactly the same. This gets reflected in the way they think about testing: a bunch of repeatable steps to see if the program is working and the requirements are met, but is that really what testing is all about? I like to think of testing more as a social science. Testing is not only about technical computer stuff, it is also about human aspects and social interaction.

Traditionally the focus in testing is on technical and analytical skills, however testing requires a lot more! Testing is also about communication, human behaviour, collaboration, culture, social interaction and (critical, creative and systems) thinking. The seven basic principles of the [Context-Driven School](https://context-driven-testing.com/){:target="_blank"} tell us that people, working together, are the most important part of any project’s context. That good software testing is a challenging intellectual process and only through judgement and skill, exercised cooperatively throughout the entire project, are we able to do the right things at the right times to effectively test our products.

### Quality
Can we measure the quality of software? And can we do that objectively? When I ask people about quality they often refer to requirements. “Quality is compliance to functional and non-functional requirements”. In my experience I have never seen a document that contained all requirements for a software product. We can argue that requirement engineers have to do a better job. Are they doing a bad job? Can we solve the problem by writing better requirements? When discussing quality I like to use coffee as example. I like strong, black coffee without any sugar or milk. But what if you do not like coffee? For somebody who doesn’t drink coffee, my cup of coffee has no value at all. But is still the same cup. How can that be? And how about the taste? Why does coffee from an average office machine doesn’t taste very well while it meets the “requirements” I just mentioned. And what if I change my mind? Not so long ago I drank lots of cappuccino, nowadays I don’t like that any more. That is why I like the definition by Jerry Weinberg and the additions made by James Bach and Michael Bolton.

<blockquote class="prompt-tip">Quality is value to some person (Jerry Weinberg)<br>
Quality is value to some person who matters (James Bach) <br>
Quality is value to some person at some time (Michael Bolton)</blockquote>

I began to believe that there is much more to quality than requirements alone. I also believe that software quality is very subjective and will change over time. To better understand the subjective, human aspects of software quality I started to study social science in general and our thinking and qualitative research in particular.

### Qualitative and quantitative research
Quantitative research is about quantities and numbers. The results are based on numeric analysis and statistics. There is nothing wrong with numbers, but we need to understand the story behind these numbers! Like the test report example: what is the story behind these numbers? What did we test? And how good was our testing? That is where the qualitative aspects come in. Qualitative research is focused on differences in quality and is usually for more exploratory purposes. It is more open to different interpretations. Qualitative research accepts and deals with ambiguity, situational specific results and partial answers. When doing this, testers may be more prone to bias and personal subjectivity.


---

### Comments from the original Wordpress blog:

><code style="color : lightskyblue">Erik Davis - April 12, 2013 at 4:19 pm</code><br>
>This is an awesome series, with a huge collection of other material to investigate. I am excited to see the next post.
>Absolute must read for testers. In fact, I am posting links to this series on our internal testing forum today.

><code style="color : lightskyblue">Michael Rocha - April 10, 2013 at 12:52 pm</code><br>
>Awesome, just so freaking awesome! Looking forward to reading this series.

>><code style="color : lightskyblue">Huib Schoots (Post author) - April 10, 2013 at 1:21 pm</code><br>
>>Thanks!

><code style="color : lightskyblue">Darren Hails - April 7, 2013 at 10:51 pm</code><br>
>Great blog, and am looking forward to reading the next installment.

><code style="color : lightskyblue">Jean-Paul - April 7, 2013 at 7:58 pm</code><br>
>Hi Huib,
>Let me start with saying that I like your post. It rightly links the broader field of science to testing. There’s only one thing I can add. Why not expand this to the whole of software development. Isn’t it about time that not only testing is taken out of the exact science corner and to apply this to software development as a whole. Who can keep insisting that development is the same as engineering. Granted developers stil need to apply logic and consider technical /physical constraints to some extent. Even so development is mainly about providing solutions for user problems in such a way that they value and appreciate the solution. And nowadays developers do that by applying knowledge, information and interaction to one of the programming languages and not by steering electric current through wires or resistors. So let’s start and look at software as the result of applied natural and social science and use the knowledge base of both.
>Jean-Paul

><code style="color : lightskyblue">Phil Kirkham - April 7, 2013 at 7:42 pm</code><br>
>Looking forward to reading this series of posts if this first in the series is any indication, good stuff

><code style="color : lightskyblue">Markus Gärtner - April 7, 2013 at 7:35 pm</code><br>
>Thanks for mentioning my blog entry. I think that particular addition was based on a chat I had with Michael Bolton. I don’t think I originally came up with it, but more that Michael and probably also James already came up with it.


>><code style="color : lightskyblue">Huib Schoots (Post author) - April 7, 2013 at 7:39 pm</code><br>
>>Thanks Markus. Changed!