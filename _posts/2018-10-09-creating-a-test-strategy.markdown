---
title: Creating a Test Strategy
date: 2018-10-9 00:00:00 +0100
categories: [test strategy]
tags: rapidtesting productanalysis strategy riskanalysis reporting    # TAG names should always be lowercase
<!-- pin: true -->
image:
  path: /assets/img/sherlock.png
---

![title slide](/assets/img/The-Magic-of-Sherlock-Holmes-1024x562.png){: width="400" .right .shadow}

At EuroStar 2017 I did a experiential workshop with Pekka Marjamaki and Carsten Feilberg called “The Magic of Sherlock Holmes – Test Strategy in a blink of an eye”. The goal of this full day workshop was to teach to create a Test Strategy rapidly so you can start testing as soon as possible. This blog post describes the summary of what we taught and publishes the example I made for the participants.

### What is a Test Strategy?

In the workshop we defined Test Strategy as a solution to a complex problem: how do we meet the information needs of the testers & stakeholders in the most efficient way possible. In Rapid Software Testing we define Test Strategy as “the set of ideas that guide your test design or choice of tests to be performed”. We also talk about logistics and test plan. Logistics is the set of ideas that guide your application of resources to fulfilling the test strategy and test plan is the set of ideas that guide your test project. A Test Plan is the sum of logistics and the strategy. 

Rikard Edgren did an [excellent workshop on Test Strategy at EuroStar 2014](https://thetesteye.com/presentations/Edgren_Tutorial_TestStrategyNextLevel.pdf){:target="_blank"}. In his workshop he says: Test strategy contains the ideas that guide your testing effort; and deals with what to test, and how to do it. Some people mean test plan or test process, which is unfortunate…. It is in the combination of WHAT and HOW you find the real strategy. If you separate the WHAT and the HOW, it becomes general and quite useless.

### What influences the Test Strategy?

Your Test Strategy is influenced by many factors.

- **Context**: your testing is influenced by the details of the specific situation like information available, the tester(s) doing the testing, what has been tested before, what tools and environments are available, how much time you have, etc.
- **Missions**: what do your stakeholders need to know about the product? 
- **Risks**: testing is mostly motivated by problems that might happen (risks). We want to find the important problems in the product. 
- **Product**: products have many dimensions. By modelling the product we find important and unique aspects of the product.
- **Quality Criteria**: various criteria or requirements that define what the product should be for the stakeholders.
= **Testing**: your testing changes the Strategy constantly. Each experiment learns you more about the product and the risks involved.

### How to create a Test Strategy?

![title slidehtsm slide](/assets/img/The-Magic-of-Sherlock-Holmes-ES-2017-Huib-Schoots-and-Pekka-Marjamaki-Featuring-Carsten-Feilberg--1024x532.png){: width="400" .right .shadow}

To create a Test Strategy, you have to examine the factors mentioned above. This can be done in several activities (which do not need to be done specifically in this order). Most likely you will do this in a iterative way, building your Test Strategy as you go.

1. Missions for your testing
2. Product analysis
3. Oracles & information sources
4. Quality characteristics
5. Context: project environment
6. Test strategies

I like to use to Heuristic Test Strategy Model (HTSM). It reminds me what to think about when if am creating my Test Strategy and tests.

The HTSM is a model which consists of several sets of heuristics (more about heuristics [here](https://www.satisfice.com/blog/archives/462){:target="_blank"} and [here](https://www.developsense.com/blog/2012/04/heuristics-for-understanding-heuristics/){:target="_blank"}).  The full model can be found [here](https://www.satisfice.com/tools/htsm.pdf){:target="_blank"}.

- Project Environment helps to understand our context and missons: MIDTESTD (mission, information, developer relations, test team, equipment & tools, schedule, test items, deliverables).
- Product Elements helps to identify dimensions and factors of the product that could be examined in a test: SFDIPOT (structure, function, data, interfaces, platform, operations, time).
- Quality Criteria helps to identify value and threats to various criteria of the product: CRISP DUCCS (capability, reliability, installability, security, performance, development, usability, charisma, compatibility, scalability). In this case you could also use the [software quality characteristics](https://thetesteye.com/posters/TheTestEye_SoftwareQualityCharacteristics.pdf){:target="_blank"} by the Test Eye.
- Risk analysis reveals potential problem. Risks motivate your testing. But the testing itself is risk analysis in itself: after analysing potential risks your testing informs you about the actual problems and learn new aspects of the product which helps you identify new risks. Each test has its own strategy: FDSFSCURA​ (function testing, domain testing, stress testing, flow testing, scenario testing, claims testing, user testing, risk testing, automatic checking​). To come up with good Test Ideas is an important skill. Erik Brickarp has an excellent blog post called [How to come up with test ideas](https://erik.brickarp.se/2016/08/how-to-come-up-with-test-ideas.html){:target="_blank"}.
- Identifying [Oracles](https://www.developsense.com/resources/Oracles.pdf){:target="_blank"} and Information sources helps learning about the product and identify potential problems. To design a good test strategy we need to know what’s important.

### Examples of Test Strategy

Before giving you my example, I like to link to two great example of how to create a thorough Test Strategy by Rikard Edgren.

- WorkRave Test Strategy
- Screen Pluck Test Analysis

The exercise in the workshop was defined as follows:

![Assignment slide 1](/assets/img/1.png){: width="600" .shadow}

Product we used in the workshop is here: [tinyurl.com/SherlockES](https://tinyurl.com/SherlockES){:target="_blank"}

![Assignment slide 1](/assets/img/2.png){: width="600" .shadow}

![Assignment slide 1](/assets/img/3.png){: width="600" .shadow}


### Approach used to create my Test Strategy

1. Look at mission and things we know (from the class) [1 min]
2. Explore wix platform website [1 min]
3. Explore wix casies website and create SFDIPOT mindmap while learning about the product [5-10 min]
4. Risk analysis [5-10 min]
5. Think of test ideas / approaches to deal with risks [5-10 min]
6. Wrap-up. Create testing story about what I know already. List next steps [5 min]
7. Tidy document and add some comments to make it readable for students

Total time used: 50-60 min

### 1. What do we know (and what important questions do I still have):

- No developers available –> No access to code
- Target customers? Who are they?
- (Considering the short time period, I choose not to do a thorough context analysis using MIDTESTD, if I had more time, I would do so).

**Mission**:
Casies is web shop build with the Wix platform where customers can buy a case for their mobile phone. Your mission is to find problems we want to fix before release. The owner of the website needs information to decide if this web shop can be released.

**Most important quality criteria**:
- Usability & charisma
- Reliability and security of the purchase process
- Functionality
  - Find, sort & filter
  - Purchase, cart, payment
  - Bestsellers
  - Contact
- Performance

### 2. Look at Wix platform site

(url: [https://www.wix.com/features/main](https://www.wix.com/features/main){:target="_blank"})

Product exploration: look at website about Wix platform

Claims about the product:
- Easy Drag and Drop
- Free & Reliable Hosting
- App market –> what else is there?
- Mobile Friendly
- loads of templates
- SEO

### 3. Explore Wix casies

Start using the product: Product exploration: play with casies website using SFDIPOT

![product coverage outline Wix](/assets/img/Wix-2018-10-09-00-45-54.png){: width="600" .normal .shadow}

Download [Xmind mind map](https://www.dropbox.com/s/qidmlaph8jysnhp/Wix.xmind?dl=0){:target="_blank"} above. It is created in [Xmind](https://xmind.com/){:target="_blank"}.

### 4. Risks

The risk mentioned here are probably too vague in some cases. Since risk analysis is a continuous process I will update risks later, making them more concrete and actionable. Also I will add more risks while testing.

- Web shop not available
- Web shop not easy to use
- Target customers do not like the web shop
- Web shop is not secure: customer data accessible by 3rd party
- Customer cannot add items to cart
- Customer cannot buy items in cart
- Customer cannot find the items wanted
- Web shop is not easy to find

### 5. Risks – Testing Tasks

**Test ideas**
Used document Software Quality Characteristics by Testeye

![product coverage outline Wix](/assets/img/Test-Strategy-Casies-Huib-Schoots-Google-Docs-2018-10-09-00-39-39.png){: width="600" .normal .shadow}

(More info on session based testing: [here](/posts/great-resources#session-based-test-management){:target="_blank"})

### 6. Testing Story & Next Steps

Looking at the website I found that the web shop doesn’t look complete to me: there is no possibility to check out and pay. Is this okay? To be able to do thorough testing to fulfil the mission “Your mission is to find problems we want to fix before release. The owner of the website needs information to decide if this web shop can be released” the website needs to be completed and payment functionality needs to be added. I am also interested in the maintenance model: how can I add cases? This would be very handy to create more test data and play with parameters in there to see how that comes out in the shop. Does this need to be part of my testing?

The results of my short initial exploration are captured in the [SFDIPOT](https://www.sharonob.com/blog/sfdipot){:target="_blank"} mind map I made while playing & interacting with the product. After that I made an initial risk analysis. I haven’t gone deep on anything yet.

Next steps will be talking to the product owner with my initial test strategy. If the payment module isn’t available soon, I will start with testing the first three charters, although I will not be able to fully do the purchase process charter, so I have to split this charter and focus on the cart part only.

- Purchase process: cart & payment including investigation of fields
(using the Test heuristic cheat sheet: [original](https://github.com/mlukjanska/testing-cheatsheet/blob/master/Heuristics/testheuristicscheatsheetv1.pdf){:target="_blank"} or [v2 by MoT](https://www.ministryoftesting.com/articles/test-heuristics-cheat-sheet){:target="_blank"})
- Finding cases – sorting & filtering cases
- GUI tour: check all links and info

### Used heuristics

Below an abstract of the “[Software Quality Characteristics](https://thetesteye.com/posters/TheTestEye_SoftwareQualityCharacteristics.pdf){:target="_blank"}” by Testeye used as heuristics for creating this Test Strategy

# Usability

- Affordance: product invites to discover possibilities of the product.
- Intuitiveness: it is easy to understand and explain what the product can do.
- Minimalism: there is nothing redundant about the product’s content or appearance.
- Learnability: it is fast and easy to learn how to use the product.
- Memorability: once you have learnt how to do something you don’t forget it.
- Discoverability: the product’s information and capabilities can be discovered by exploration of the user interface.
- Operability: an experienced user can perform common actions very fast.
- Interactivity: the product has easy-to-understand states and possibilities of interacting with the application (via GUI or API).
- Control: the user should feel in control over the proceedings of the software.
- Clarity: is everything stated explicitly and in detail, with a language that can be understood, leaving no room for doubt?
- Errors: there are informative error messages, difficult to make mistakes and easy to repair after making them.
- Consistency: behavior is the same throughout the product, and there is one look & feel.
- Tailorability: default settings and behavior can be specified for flexibility.
- Accessibility: the product is possible to use for as many people as possible, and meets applicable accessibility standards.
- Documentation: there is a Help that helps, and matches the functionality.

# Charisma

- Uniqueness: the product is distinguishable and has something no one else has.
- Satisfaction: how do you feel after using the product?
- Professionalism: does the product have the appropriate flair of professionalism and feel fit for purpose?
- Attractiveness: are all types of aspects of the product appealing to eyes and other senses?
- Curiosity: will users get interested and try out what they can do with the product?
- Entrancement: do users get hooked, have fun, in a flow, and fully engaged when using the product?
- Hype: should the product use the latest and greatest technologies/ideas?
- Expectancy: the product exceeds expectations and meets the needs you didn’t know you had.
- Attitude: do the product and its information have the right attitude and speak to you with the right language and style?
- Directness: are (first) impressions impressive?
- Story: are there compelling stories about the product’s inception, construction or usage?

# Reliability

- Stability: the product shouldn’t cause crashes, unhandled exceptions or script errors.
- Robustness: the product handles foreseen and unforeseen errors gracefully.
- Stress handling: how does the system cope when exceeding various limits?
- Recoverability: it is possible to recover and continue using the product after a fatal error.
- Data Integrity: all types of data remain intact throughout the product.
- Safety: the product will not be part of damaging people or possessions.
- Disaster Recovery: what if something really, really bad happens?
- Trustworthiness: is the product’s behavior consistent, predictable, and trustworthy?

# Security

- Authentication: the product’s identifications of the users.
- Authorization: the product’s handling of what an authenticated user can see and do.
- Privacy: ability to not disclose data that is protected to unauthorized users.
- Security holes: product should not invite to social engineering vulnerabilities.
- Secrecy: the product should under no circumstances disclose information about the underlying systems.
- Invulnerability: ability to withstand penetration attempts.
- Virus-free: product will not transport virus, or appear as one.
- Piracy Resistance: no possibility to illegally copy and distribute the software or code.
- Compliance: security standards the product adheres to.

# Performance

- Capacity: the many limits of the product, for different circumstances (e.g. slow network.)
- Resource Utilization: appropriate usage of memory, storage and other resources.
- Responsiveness: the speed of which an action is (perceived as) performed.
- Availability: the system is available for use when it should be.
- Throughput: the products ability to process many, many things.
- Endurance: can the product handle load for a long time?
- Feedback: is the feedback from the system on user actions app
- Scalability: how well does the product scale up, out or down?

### Final thoughts

As my example shows: you can create a Test Strategy in an hour. Of course this Test Strategy is not complete. But after the first tests (3 sessions) we learn and discover more about the product, so we can identify new risks, which inform new missions and will help us come up with new Test Ideas. Our Test Strategy will grow over time!

### Extra info

The slides are here:
<iframe src="/assets/files/magic-of-sherlock-holmes.pdf" width="400" height="250">
</iframe>

The pictures and flipcharts from the workshop are [here](https://www.dropbox.com/s/24lwo37orcvdori/The%20Magic%20of%20Sherlock%20Holmes%20-%20Flips%20and%20Pics%20-%20High%20Res.pdf?dl=0){:target="_blank"}.

### References

- [Rapid Software Testing](https://rapid-software-testing.com/){:target="_blank"} by James Bach and Michael Bolton
- [Thinking Strategically About Testing](https://youtu.be/O4d0Hbtd68s){:target="_blank"} – EuroSTAR by Fiona Charles
- [EuroStar tutorial “Test Strategy – Next Level”](https://thetesteye.com/presentations/Edgren_Tutorial_TestStrategyNextLevel.pdf){:target="_blank"} by Rikard Edgren
- [Heuristic Test Strategy Model](https://www.satisfice.com/tools/htsm.pdf){:target="_blank"} by James Bach
- [Test Strategy Checklist](https://thetesteye.com/posters/TestStrategyChecklist.pdf){:target="_blank"} by the Test Eye
- [What is a good test strategy](https://thetesteye.com/blog/2013/09/what-is-a-good-test-strategy){:target="_blank"} by Rikard Edgren
- [Heuristic Risk-Based Testing](https://www.satisfice.com/articles/hrbt.pdf){:target="_blank"} by James Bach
- [The Little Black Book on Test Design](https://www.thetesteye.com/papers/TheLittleBlackBookOnTestDesign.pdf){:target="_blank"} by Rikard Edgren
- [Context-free questions for testers](https://www.developsense.com/blog/2010/11/context-free-questions-for-testing/){:target="_blank"} by Michael Bolton
- Book: Lessons Learned in Software Testing by Kaner, Bach & Pettichord
- [Basics Revisited: Test Strategy](https://www.quality-intelligence.com/articles/BasicsRevisited-TestStrategy.pdf){:target="_blank"} by Fiona Charles
- [Sharing testing with non-testers in an agile team](https://nordictestingdays.eu/files/files/katrina_clokie-sharing_testing_with_nontesters_in_an_agile_team.pdf){:target="_blank"} by Katrina Clokie
- [Test Strategy Retrospective](https://katrinatester.blogspot.co.nz/2014/04/test-strategy-retrospective.html){:target="_blank"} by Katrina Clokie
- [A Question About Test Strategy](https://www.satisfice.com/blog/archives/63){:target="_blank"} by James Bach
- [Session Based Test Management](https://www.satisfice.com/sbtm/){:target="_blank"} by James Bach
- [More links on test strategy](/posts/great-resources#test-strategy){:target="_blank"}

---

### Comments from the original Wordpress blog:

> **Andrei - October 9, 2018 at 8:21 am**
From all the test strategies definitions available out there, the one that I find the easiest to explain is: “The design activity in which you apply the testing values & principles (you believe it) to a specific context” …inspired from the book “Nelson Mandela – Conversations with myself”


