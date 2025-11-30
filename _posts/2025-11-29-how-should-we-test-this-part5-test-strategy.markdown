---
title: How should we test this? Part 5 - Test Strategy
description: Part 5 in "How should we test this?" on Test Strategy and making deliberate choices
date: 2025-11-29 14:00:00 +0100
categories: [Test Strategy]
tags: strategy risk reporting models heuristics learning # TAG names should always be lowercase
image:
    path: /assets/img/teststrategy.png
---

[Photo by energepic.com](https://www.pexels.com/photo/woman-sitting-in-front-of-macbook-313690/){:target="_blank"}

<blockquote class="prompt-info">This blog series explores a central question in software testing: “How should we test this?” (HSWTT?) We'll start with some foundational concepts that shape how we approach testing: learning, modelling, and heuristics. From there, the series dives into practical thinking tools: how to learn about the product (Product Analysis), how to identify important potential problems (Risk Analysis) and how to search for those problems effectively (Test Strategy). Finally, we’ll look at how to communicate what we’ve found in a meaningful way (Reporting).</blockquote>

How should we test this:
- [Part 1 - Introduction](/posts/how-should-we-test-this-part1-introduction/){:target="_blank"}
- [Part 2 - Learning](/posts/how-should-we-test-this-part2-learning-heuristics-models){:target="_blank"}
- [Part 3 - Product Analysis](/posts/how-should-we-test-this-part3-product-analysis){:target="_blank"}
- [Part 4 - Risk Analysis](/posts/how-should-we-test-this-part4-risk-analysis){:target="_blank"}

## Part 5: Test Strategy

Test Strategy is a solution to a complex problem: how do we meet the information needs of the team & stakeholders in the most efficient way possible? Test strategy contains the ideas that guide your testing effort and deals with WHAT to test and HOW to do it. Test Strategy is based on risks. We want to find the (potential) important problems in the product. Test Strategy is not a document but a mental model, an ongoing process to guide your testing. Documents and visuals help you understand and transfer your ideas. Test strategy is the set of ideas that guide your test design.

Test Strategy is influenced by many factors:
- Context: your testing is influenced by the details of the specific situation like information available, the tester(s) doing the testing, what has been tested before, what tools and environments are available, how much time you have, etc.
-   Missions: what do your stakeholders need to know about the product?
-   Risks: testing is mostly motivated by problems that might happen (risks). We want to find the important problems in the product.
-   Product: products have many dimensions. By modelling the product in a product coverage outline, we identify
    important and unique aspects of the product.
-   Quality Criteria: various criteria or requirements that define what the product should be for the stakeholders.
-   Testing: your testing changes the Strategy constantly. Each experiment learns you more about the product and the risks involved.

To create an effective Test Strategy, you must examine the factors described above. You can do this through several key activities:
- Defining the missions for testing
- Analyzing the context
- Understanding stakeholder needs and quality criteria
- Studying the product and its characteristics
- Performing risk analysis
- Identifying oracles and information sources[^1]
- Considering appropriate testing strategies

The activities above do not need to be done specifically in this order. Most likely you will do this in an iterative way, building Test Strategy as you go.

## Think strategically about Test Strategy
How do you determine what is important to test? All the activities we did so far is “just” the preparation. Here we answer the question “how should we test this?”.

James Bach shared a list of different perspectives on thinking strategically about testing in a private conversation a while ago:

1. What is IMPORTANT to do because it will find bugs that matter?
2. What is EASY to do, and yet might be worth doing?
3. What is EXPECTED for me to do, and so I might want to do even if it's not critical?
4. How can I make good use of TOOLS?
5. What ENABLING tasks must be done to get ready or to create testability?
6. What has already been tested?

In the [recently published book "Taking Testing Seriously"](https://www.amazon.com/-/en/Taking-Testing-Seriously-Software-Approach/dp/1394253192){:target="_blank"} there are even 12 considerations called "Twelve Test Strategy Entry Points".

1. What Are You Here For?
    What testing will fullfil your mission?
2. What Do You Need to Learn?
    Are you ready to create a test strategy or do you need to learn more?
3. What Is Happening Right Now?
    Are there things you can test right now? 
4. How Is Your Testing Constrained?
    Push for testability as soon as possible.
5. What Testing Has Been Done Already?
    Determine what testing was done before and reuse it only if you understand and trust it.
6. How Is the Product Being Built?
    Adapt you strategy to the risks left in your development process.
7. What Is the Product?
    whatever the product is, test it. Products have pieces. Test the pieces. oes it process data? Test with the data.
8. How Important Is Your Testing?
    Use Risk-based testing.
9. How Will People Most Likely Use the Product?
    Learn who the users are and why they would want to use the product.
10. What Testing Is Easy to Do?
    Some testing may provide limited value, but they can still be worthwhile if the cost is low.
11. What Do People Expect You to Do?
    Sometimes it’s easier to go along with what others want if it doesn’t take much time and can save a lot of trouble.
12. What’s Fun to Do?
    Start starting with something you feel like doing.

Another list which is worth mentioning here is the [FIBLOTS mnemonic](https://scott-barber.blogspot.com/2011/09/model-workloads-for-performance-testing.html){:target="_blank"}. Scott Barber created it years ago: it was created for use in performance testing, but it works in any form of testing.

- **Frequent**: Common application usage
- **Intensive**: i.e. Resource-heavy activities
- **Business Critical**: Even if these activities are both rare and not risky
- **Legal**: Stuff that will get you sued or not paid
- **Obvious**: Stuff that is likely to earn you bad press
- **Technically Risky**: New technologies, old technologies, places where it’s failed before, previously
    under-tested areas
- **Stakeholder Mandated**: Don’t argue with the boss (too much).

Both models help you think about Test Strategy better and faster.

## Documenting Test Strateg
A concise way of describing a Test Strategy is to use a table with 2 or 3 columns (an extra column if you want to add risk classification). This table relates risk areas to specific mitigation tasks. Any tasks listed in the second column which are not completed will increase the likelihood of customer dissatisfaction in the associated risk area on the left. A thrid column can be added to indicate in which "test type" the test ideas are covered. This supports team discussion about testing, planning and testability and prevents redundant testing or missing essential coverage. It supports in depth discussion with your team on what will be tested where and by whom. It also helps creating balanced automation in testing because the whole team is involved instead of only testers deciding what need automation. I think “what to automate?” it is an important aspect that should be part of your Test Strategy discussion with your team.

**Example Test Strategy Table: (incomplete)**<br>
Here is an example table. Obviously, it is incomplete, but it should give you an idea of what such a table can look like.

| Risk | Risk Class | Activity | Where |
|------|------------|-----------------|---------------------|
| Code is hard to read, test, and modify | Medium | - Code review<br>- Static code analysis | Development    |
| The web shop is not available | Critical | - Run load/stress/performance tests<br>- Application Performance Monitoring<br>-Infrastructure Reliability<br>- Monitoring | - Developement<br>- Operations |
| The customer cannot find the desired items | High | - Check Query Parsing, Search Algorithm, Ranking Logic and Empty & Null Handling<br>- Functionality, Accuracy, performance of search<br>- User testing (user panel) | - Unit test<br>- System test<br>- Acceptance test |
| The web shop is not easy to use / does not look good | High  | - UX design<br>- Expert usability testing<br>- User testing (user panel) | - Design<br>- System test<br>- Acceptance test |

NB: To see the last column in the table you sometimes need to scroll

James Bach introduced Risk-Task lists already years ago. Some examples can be found in the
[RSTE appendices](https://www.satisfice.com/download/rst-appendices){:target="_blank"}.

Notes:
-   Be as specific as possible. Also, add questions and name things you don't know in the PCO (mind map) or risk table.
-   Conduct exploratory testing that does not focus on specific risks to discover unrecognised risks. Remember that a big risk in complex environments is that we overlook risks!

## Test Strategy considerations
Things to keep in mind:
-   Working on Risk Analysis and Test Strategy Refinement in multiple sessions is necessary to think things through deep enough (see part 2)
-   Do not only focus on identified risks in your testing. We can’t predict or identify all risks upfront. There are unknown unknowns which only can be found by exploration.
-   How much detail you put in the PCO, risk analysis and strategy is person/team and even story dependent. Try to be as specific as possible. General statements do not help and are risky because they are ambiguous
-   Experiment and see what works and what doesn't. Adjust where necessary. Discuss your way of working and the
    artefacts you create with the team in retrospectives
-   Don’t overdo it and keep your documentation concise. It should fit on 1 max 2 A4 sheets depending on the complexity and size of the part you’re working on
-   Risk analysis and Test Strategy support faster & often less testing because we can make better choices
-   It also supports fast & structured learning by creating a PCO, a Risk Analysis and a Test Strategy. It doesn’t have to take a lot of time. Discussing stories in detail often does.
-   It is a great way to involve the team in testing during refinements
-   There is not one strategy, there are many:

![Test strategies](/assets/img/teststrategies.png){: width="600}

## Testability is extremely important

Testability is how easy it is to test a product. The easier it is to test a product, the faster it can be done. I have been in and seen many projects where testability made a huge difference. In one example testers were creating their test data by editing an enormous text file which took them about a week. When I asked a developer if he could help us, he created a simple tool in a couple of hours that did the job in 15 minutes.

Many factors influence testability: having a lot of technical and product knowledge, how easy it is to configure the product under test, having the right data, availability of oracles, how easy it is to see what is happening
(observability), etc.

Teams want to go faster, and testability can help them. So, we need to discuss testability with our team on a regular basis. Unfortunately, tester must ask for testability since it is often not considered. Testability is not a tester thing; it concerns the whole team. A great way to involve the whole team is to make testability part of the test strategy discussion in refinements.

Three great sources to learn more about testability:

-   [Heuristics of Software Testability by James Bach](https://www.satisfice.com/download/heuristics-of-software-testability){:target="_blank"}
-   [Team Guide to Software Testability by Ash Winter and Rob Meaney](https://leanpub.com/softwaretestability){:target="_blank"}
-   [Rethinking Testabilit series by Maria Kedemo](https://mkedemo.wordpress.com/2025/08/18/testability-is-about-people-not-just-code/){:target="_blank"}

## What if I do not have time to create a Test Strategy?

This is a question I hear often in training and consulting. Testers who claim that they do not have time to do risk analysis or create a Test Strategy because they must keep up with de developers. I think there is always time for strategising, and I even dare to claim that you always take time to strategise. You might not write a strategy document. You do the strategic thinking and you are struggling how to visualise it or write it down.

To be able to test deeply, you need to know WHAT you want to test deeply. To figure out what is important, you need a Test Strategy. How do you know what to test? What is important? What is risky? Many testers test too much and put too much effort in unimportant features. Doing risk analysis with your team and discussing your Test Strategy with your product owner reduces the change of testing the wrong stuff and will increase the value of your testing.

I think that creating a Test Strategy is essential to do excellent testing. Creating a test strategy document is not. Use concise and lean ways of capturing and transferring your Test Strategy: use mind maps, drawings on a white board, flip charts, and sticky notes. Stop putting Test Strategies in Word documents as a default. If you want to create a list, consider using notepad!

So how does this work in my team? Work on product & risk analysis and test strategy preferably in several “sessions”. Deep thinking and fully understanding takes time and that’s okay. Working on something multiple times it is better than one time. Better discuss stories 3 x 10 minutes than an hour at a time.

Refinements could go something like this:

- Session 1: PO gives a high-level overview of what they need. With this info the tester makes a first draft of a Risk Analysis. This initial list is discussed with team members and stakeholders in 1-on-1 sessions. The developers can start designing the solution and think of how to build and unit test it.
- Session 2: Team refines the story with input from the team, after the session further elaboration might take place if needed. There are many ways to do this: three amigos session, pairing with teammates, 1-on-1 discussions with developers, domain experts or your PO, etc. Tester asks questions based on the PCO and risk analysis made. A first draft of a Test Strategy is presented and discussed.
- Session 3: Discuss the Risk Analysis and Test Strategy during the refinement. Of course, the team also discusses technical approach and other things needed to be ready to estimate and pick up a story/feature in sprint. Teams estimates and takes the story into sprint.

In sprint you further detail the PCO and/or create tests. You can also use PCO to track progress.

## Final considerations

A Test Strategy is not a fixed thing. We learn new things all the time. So your Strategy changes too, it evolves, it grows while we learn & discover more about the product. Based on value and risks we decide what to test first. For those areas we have more details in the Test Strategy. We go from global to more details. Your Test Strategy is “complete” at the end of your testing. I can’t imagine a situation where we create the complete Strategy upfront and we stick to it until the end. A good Test Strategy20 is product specific so it will vary in different teams/organisations. If you can copy a Test Strategy from another team, sprint or even a story tested before, it is not specific enough.

I can’t emphasize enough: a Test Strategy is not a document! Whenever you test anything, you have a Strategy in your head. Most of your Strategy is in your head or in several heads spread over the team and will become clear when you discuss it. Writing things down, making mind maps or other visuals and models only helps you understand and communicate your Strategy better. The trick is to become aware of the Strategy in your head (mental model) and create insight and overview for yourself and your team and the stakeholders.

## More on Test Strategy

-   [Creating a Test Strategy](/posts/creating-a-test-strategy){:target="_blank"}
-   [Ask Me Anything: Test Strategies](https://club.ministryoftesting.com/t/ask-me-anything-test-strategies/36305){:target="_blank"}
-   [Test Strategy example by Rikard Edgren](https://thetesteye.com/examples/Example_WorkRaveTestStrategy.pdf){:target="_blank"}
-   [Test Analysis example (from which you can easily create a strategy) by Rikard Edgren](https://thetesteye.com/examples/ScreenPluck_TestAnalysis.pdf){:target="_blank"}

---

[^1]:
    An oracle is a heuristic principle or mechanism by which someone recognizes a problem. If we perceive a problem, it’s because an oracle is telling us that there’s a problem. The better oracles and information we have, the easier it becomes to test a product! More on oracles
    [here](https://developsense.com/blog/2012/04/all-oracles-are-heuristic){:target="_blank"} and
    [here](https://developsense.com/blog/2015/09/oracles-from-the-inside-out){:target="_blank"}
