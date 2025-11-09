---
title: What testing can learn from social science – Part 2
date: 2013-04-08 00:00:00 +0100
categories: [socialscience]
tags: context-driven exploratorytesting rapidtesting socialscience # TAG names should always be lowercase
image:
    path: /assets/img/thinkingtester.png
---

Testers need to do a lot of thinking. To me testing is an investigation, gathering and providing information about things that are important. I like the definition by Jerry Weinberg: “testing is gathering information with the intention of informing a decision”. Rikard Edgren recently wrote an excellent “[open letter](https://thetesteye.com/blog/2013/03/open-letter-to-eurostar-organizers-testing-introduction/){:target="_blank"}” to define testing. Testing is much more than finding bugs or checking if requirements are met.

### Systems thinking
We should not only investigate the “system under test” but also take related products in mind. What about the people using all these products or the organisations and processes in which the products are used? Testers should know more about systems thinking: the process of understanding how things, regarded as systems, influence one another within a whole (source: [wikipedia](https://en.wikipedia.org/wiki/Systems_thinking){:target="_blank"}).

A system is not just a collection of things. A system is an interconnected set of elements that is coherently organized in a way that achieves something. It must consist of three things; elements, interconnection and a function or purpose (source: “[thinking in systems: a primer – Donnella Meadows](https://www.amazon.com/Thinking-Systems-Donella-H-Meadows/dp/1603580557){:target="_blank"}”). If you want to learn more about systems thinking, you might want to watch this [youtube movie by Russel Ackhoff](https://youtu.be/OqEeIG8aPPk){:target="_blank"} and read [this post](https://flowoftesting.wordpress.com/2012/07/06/what-we-can-learn-from-russell-l-ackoff/){:target="_blank"} by Aleksis Tulonen about what you can learn form Ackhoff.

In one of my projects my client was moving a hospital from several old locations to a huge new building. It was logical that the location codes changed since it was a new building with a very different layout. But initially they forgot to oversee that this location code was actually used as department code in several information systems. And these systems used the codes to book costs (finance), plan staff (HR) and distribution of food and medicine (logistics). Moving to the new building without overseeing the full impact would have paralysed the whole information landscape. Defining a temporary coding and making minor changes to several systems solved the problem.

### Critical thinking
Testing can be seen as a form of research: investigating the system and finding information about it. In research critical thinking is important. Collecting, analysing and interpreting information requires critical thinking skills. Critical thinking to me is about thinking (critically) about your own personal thinking. Framing your own assumptions and using this to try to remove bias and hopefully clarifying your thoughts with reasoning.

In [this video](https://youtu.be/8TX6rzz60xQ){:target="_blank"} James Bach helps to gain quick understanding of critical thinking by asking three simple questions:

- Huh? What does this mean? What is the point?
- Really? Are you absolutely certain? How can I know?
- So? Where does this lead? So what?

<blockquote class="prompt-info">Update 2025: the current heuristic for critical thinking in RST is called "WHeReAS":<br>
- Who? Consider the source of the claim: what is their bias? Consider if YOU are qualified to judge: should you prepare?<br> 
- Huh? Look for alternative interpretations and expressions of it. Are they self-consistent? Consider if it all makes sense logically.<br> 
- Really? Check the facts. Gather evidence. Test it in practice. Consider the reliability of your sources.<br>
- And? Seek more sides to the story. Talk to more stakeholders. Discover more possibilities. Gather first-hand evidence.<br>
- So? What is the worst case scenario? Are there any offsetting benefits or silver-linings? Are protective measures available?<br>
 </blockquote>

These questions are very helpful for understanding and to think critical about anything. 

![Critical Thinking](/assets/img/critical.jpg){: width="400" .normal}

This picture (click to enlarge) is taken from the book “[Critical Thinking: a user’s manual](https://www.amazon.com/Critical-Thinking-A-Users-Manual/dp/0495814075){:target="_blank"}” by Debra Jackson and Paul Newberry. This book is a helpful source to learn about critical thinking.

Rule of Three

<blockquote class="prompt-tip">“If I can’t think of at least three different interpretations of what
I received,<br>I haven’t thought enough about what it might mean.”<br>
(Jerry Weinberg)</blockquote>

More on the rule of three is [here](https://s0ftwaretesting.livejournal.com/1430.html){:target="_blank"}.

### Creative thinking
At EuroStar in Amsterdam I met John Stevenson who has an excellent blog with the intriguing title: “[The expected result was 42. Now what was the test?](https://steveo1967.blogspot.com/){:target="_blank"}”. We talked about what testing can learn from social sciences and early this year we had some fantastic conversations via skype. John pointed me to some very interesting readings about qualitative research: “[Qualitative Data Analysis: a user-friendly guide for social scientists](https://www.amazon.com/Qualitative-Data-Analysis-Friendly-Scientists/dp/041505852X){:target="_blank"}“ by Ian Dey. On his blog he wrote some very interesting posts related to testing and social science you might want to read:

- [Are testers ethnographic researchers?](https://steveo1967.blogspot.com/2011/01/are-testers-ethnographic-researchers.html){:target="_blank"}
- [What You Believe Might Not Be True (Part 1)](https://steveo1967.blogspot.com/2011/01/what-you-believe-might-not-be-true-part.html){:target="_blank"}
- [Danger: confirmation bias](https://steveo1967.blogspot.com/2010/07/danger-confirmation-bias.html){:target="_blank"}

John is currently writing an awesome series of articles about creative and critical thinking. Part 1 of “Creative and Critical Thinking and Testing” can be found here. From there you can find the other parts about the different styles of thinking.

### So why is this important?
Systems thinking reminds us to look at the big picture and see systems as a whole. What is the purpose of the organisation we work for? And is the project we are doing contributing to that? Creative thinking helps us to solve problems in a creative way or come up with more things to test and how to do it effectively. Critical thinking helps you to really understand what you are doing. Like in research we have to process large amounts of data and make sense of it. But we also have to recognize, analyse and evaluate (see critical thinking diagram above) information, arguments and problems.

Thinking is an under appreciated subject. Thinking is very important for testers and we should learn from science: doing research, learn to design and perform experiments, collect, organize and analyse data and use the results to decide on the next steps in our work. Critical thinking helps us ask better questions in our projects and identify problems faster. It also helps avoid traps: biases and assumptions. More about that in my next post.
