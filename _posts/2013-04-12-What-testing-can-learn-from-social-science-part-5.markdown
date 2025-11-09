---
title: What testing can learn from social science – Part 5
date: 2013-04-12 00:00:00 +0100
categories: [socialscience]
tags: context-driven exploratorytesting rapidtesting socialscience # TAG names should always be lowercase
image:
    path: /assets/img/anthropologist.png
---

### What can testing learn from social science?

Why is this important to testers? My conclusion is that testing and the social sciences are very much interconnected and there are many lessons that we could learn from this area. We should see what we can apply to our daily testing jobs. We should be more aware of what we do in testing: for example social research, making observations, doing critical thinking and most importantly continuing to learn. We should start learning from what people have done and are still doing in the social sciences. Testers should not only focus on quantitative analysis like bug counts or test case pass or fail, but also do qualitative research. Test reports should be stories about the product and the testing we did (see Michael Bolton’s article on [test reporting and the telling of the story](https://developsense.com/blog/2012/02/delivering-the-news-test-reporting-part-3){:target="_blank"}). We should use the numbers to support or backup our story. I often see it the wrong way around: lots of tables full of counts that do not tell us anything without the context. Managers do tend to draw their own conclusions and make decisions based upon this data, if we do not help them by telling the story. Again, testing is about collecting information for people who matter to enable them to make informed decisions.

### Coverage?
If a manager comes up to you and asks you:

“So what is the coverage?” or “How many test cases do you have?“

What do you say? It is really hard to talk to managers who are obsessed by numbers and think that testing is about the number of test cases, right and wrong, green and red.

Consider this next time you talk to them. Make a simple calculation of all the possible tests you could do for the project you are working on regardless of how simple or complex it is. Think of all the possible combination both positive and negative.

What number have you ended up with?

1 thousand?
1 million?
1 billion?
More?
The number of possible things that you can test are endless, exhaustive testing is futile. Even a simple requirement has infinite possibilities to test.

So what is the coverage if we do 1,000,000 test cases?

Coverage: 1,000,000 divided by infinite is very close to zero!
Coverage: 10,000.000 divided by infinite is still very close to zero!
So no matter how many test cases you have the coverage of all possible test cases you could have done is close to zero. This is why risk, priority and making choices become important for testing but that is a different topic.

### Be a scientist
Science is important. It gave us critical thinking and that helps us proving the theories we have about the product. Try to prove yourself wrong instead of proving yourself right.

Ask critical questions:
- Could it be something else?
- Is this what I expected?
- What did I do differently?
- What else can I do?
- How can I explain what I did?

While testing we should practice critical thinking: question things we encounter, make sure that what we see, is true (or not). While thinking we should be aware of fast conclusions, biases and fallacies. We often do it the wrong way around. If we focus too much on the numbers and the averages we miss the outliers: the unique random events that can do the most damage.

### Qualitative research
The [grounded theory method](https://en.wikipedia.org/wiki/Grounded_theory){:target="_blank"} is a research method that operates almost in a reverse fashion from traditional social science research. You start with a view, theory or expectation before you start. However as you gather more data when testing, your theory/expectation becomes more ‘grounded’ upon the information you uncover or discover. Basically as you experience and gather more and more data you change your perspective and viewpoint. This is what social scientist do when they go and live with social groups. They have something they want to find out – an assumption or otherwise – and find out if it is right or not by taking part (compare missions in Exploratory testing).

In qualitative research done by anthropologists for example the context of the research is very important. Here they accept and deal with ambiguity, situational specific results and partial answers. Qualitative data deals with meanings. Use it when you want to understand the underlying thoughts and intentions.

### Observation
Testers should not observe from the side-line. We should act like anthropologists do: become part of the group you are observing. Let me give you an example from my own experience.

A couple of years ago I worked as a test coordinator for a Media Company selling newspapers and magazines. We were implementing a new CRM system and my assignment was to organize the user acceptance testing. For some days I worked with the people selling the newspapers to learn how they were selling subscriptions and while doing that I learned what was important to them. First I was observing, but after a day I was selling newspapers myself and really learned how the users were working and what it took to make the department successful. We had requirements and designs, but the stuff I found out on processes and user sentiments was also very valuable to do testing. There were important steps not documented. I saw the people use the software in ways I didn’t expect and that wasn’t written down anywhere. I asked them what they did and why and they answered me “that is normally how we do this”. I learned that these people took short cuts to do their work. The team who were designing and building the software had no idea what I was talking about when I told them about my observations.

Humans will always take the shortest quickest route and the one that requires the least amount of thinking. This made clear how important it is to find out what people are thinking. And more important: the reasoning why they do the things they do. The product is a solution. If the problem isn’t solved, the product doesn’t work (5th basic principle of [context-driven testing](https://context-driven-testing.com/){:target="_blank"}).

Now I know it is called qualitative research and I think every team developing software should do something similar. Try to really understand the users and the environment in which the product will be used. IT is often way to focussed on technical stuff. Testers go out there and meet the people who are using the product. Be part of their world for a while and start asking those critical questions.

### Humans
Software is build by humans for humans. Social science is about people. Software should solve problems and help humans. To really solve a problem, we need to know more about how the users work, what they think, how they feel, their emptions, their desires. Too often I hear development teams say things like: “The user should not do that”. Or the all time classic: “[no real user would ever do that!](https://developsense.com/blog/2007/07/no-user-would-ever-do-that){:target="_blank"}”. IT is way too technical focussed.

Read John’s blog titled “[The Human Element}(https://steveo1967.blogspot.com/2010/12/human-element.html){:target="_blank"}”. It is an awesome story about his wife, a nurse, who explains why the human element is very important in her work. You see the parallel with our work?

### Now it is your turn!?
Use the reading list to learn more about what social sciences, biases and other relevant topics. I am curious and I want to learn from you too. So please share your thoughts and experiences with social science.

“Great software is not produced or tested in factories, but in studios
and rehearsal halls.” (Michael Bolton)
I owe John Stevenson and Michael Bolton many thanks for their inspiration, great discussions and reviewing these blogs.

### Reading List

- [Thinking fast & slow](https://www.amazon.com/Thinking-Fast-Slow-Daniel-Kahneman/dp/0374275637){:target="_blank"} – Daniel Kahneman
- [You’re not so smart](https://www.amazon.com/You-Are-Not-So-Smart/dp/1592407366){:target="_blank"} – David McRaney
- [The invisible Gorilla](https://www.amazon.com/Invisible-Gorilla-How-Intuitions-Deceive/dp/0307459667){:target="_blank"} – Christopher Chabris & Daniel Simons
- [Qualitative Data Analysis: a user-friendly guide for social scientists](https://www.amazon.com/Qualitative-Data-Analysis-Friendly-Scientists/dp/041505852X){:target="_blank"} – Ian Dey
- [Critical Thinking: a user’s manual](https://www.amazon.com/Critical-Thinking-Manual-Debra-Jackson/dp/0495814075){:target="_blank"} – Debra Jackson & Paul Newberry
- [Thinking in systems: a primer](https://www.amazon.com/Thinking-Systems-Donella-H-Meadows/dp/1603580557){:target="_blank"} – Donella Meadows
- [Are testers ethnographic researchers?](https://steveo1967.blogspot.com/2011/01/are-testers-ethnographic-researchers.html){:target="_blank"} – John Stevenson
- [What You Believe Might Not Be True (Part 1)](https://steveo1967.blogspot.com/2011/01/what-you-believe-might-not-be-true-part.html){:target="_blank"} – John Stevenson
- [Danger: confirmation bias](https://steveo1967.blogspot.com/2010/07/danger-confirmation-bias.html){:target="_blank"} – John Stevenson
- [Combining Qualitative & Quantitative Research](https://www.usersknow.com/blog/2013/02/combining-qualitative-quantitative.html){:target="_blank"} – Laura Klein
- [Software Testing a Social Science](https://www.kaner.com/pdfs/KanerSocialScienceSTEP.pdf){:target="_blank"} – Cem Kaner
- [Testing Through The Qualitative Lens](https://www.developsense.com/presentations/2012-04-STAREast-EvaluatingTestingTheQualitativeWay.pdf){:target="_blank"} – Michael Bolton
- [Curing Our Binary Disease](https://www.thetesteye.com/presentations/REdgren_CuringOurBinaryDisease.pdf){:target="_blank"} – Rikard Edgren
- [But how many test cases?](https://clarotesting.wordpress.com/2010/07/21/but-how-many-test-cases/){:target="_blank"} – James Christie
- [Reponse to How many test cases by James Christie](https://steveo1967.blogspot.com/2010/07/reponse-to-how-many-test-cases-by-james.html){:target="_blank"} – John Stevenson
- [The human element](https://steveo1967.blogspot.com/2010/12/human-element.html){:target="_blank"} – John Stevenson
- [What we can learn from Russel L. Ackhoff](https://flowoftesting.wordpress.com/2012/07/06/what-we-can-learn-from-russell-l-ackoff/){:target="_blank"} – Aleksis Tulonen
- [Predictably Irrational: The Hidden Forces that Shape Our Decisions](https://www.amazon.co.uk/Predictably-Irrational-Hidden-Forces-Decisions/dp/0007256531){:target="_blank"} – Dan Ariel
- [The Upside of Irrationality: The Unexpected Benefits of Defying Logic at Work and at Home](https://www.amazon.co.uk/The-Upside-Irrationality-Unexpected-Benefits/dp/0007354789/){:target="_blank"} – Dan Ariel


