---
title: How should we test this? Part 4 - Risk Analysis
description: Part 4 in "How should we test this?" on Risk Analysis
date: 2025-11-22 22:00:00 +0100
categories: [Test Strategy]
tags: strategy risk reporting models heuristics learning # TAG names should always be lowercase
image:
    path: /assets/img/risk.png
---

<blockquote class="prompt-info">This blog series explores a central question in software testing: “How should we test this?” (HSWTT?) We'll start with some foundational concepts that shape how we approach testing: learning, modelling, and heuristics. From there, the series dives into practical thinking tools: how to learn about the product (Product Analysis), how to identify important potential problems (Risk Analysis) and how to search for those problems effectively (Test Strategy). Finally, we’ll look at how to communicate what we’ve found in a meaningful way (Reporting).</blockquote>

How should we test this:
- [Part 1 - Introduction](/posts/how-should-we-test-this-part1-introduction/){:target="_blank"}
- [Part 2 - Learning](/posts/how-should-we-test-this-part2-learning-heuristics-models){:target="_blank"}
- [Part 3 - Product Analysis](/posts/how-should-we-test-this-part3-product-analysis){:target="_blank"}

## Part 4: Risk analysis

Risk‐based testing means organizing test strategy around suspected product risks. This means testers perform risk
analysis before, during, and after tests are performed.

-   Before to guide the test process
-   During to adjust the strategy
-   After to inform our stakeholders about remaining risks

Even after the product is released we learn about risks that were missed in the original planning. Basically you do risk
analysis all the time, because testing is risk analysis!

Risk-based testing (which is arguably a pleonasm) is a powerful way to focus your testing effort, avoid overtesting, and
justify the time and energy needed to go deep where it truly matters. Many testers tell me they apply an implicit risk
analysis. In other words, they test with a sense of risk-awareness and let risk guide their decisions but they don't
talk about it, and they don’t make those risks explicit. If the feature under test is relatively simple, that approach
might be sufficient. But I prefer to make the risks I see explicit, so I can get feedback from my team and have
meaningful discussions with fellow testers.

Risk analysis means building awareness and understanding about the state of the product and process by thinking
critically and remaining skeptical about possible errors, activities, and situations that (may) jeopardise the value.
This mindset is important for the whole team: because not only testing mitigates risks, everything we do in a team
should be based on creating as much value as possible. We do this by introducing as few risks as possible and
eliminating as many as possible. In the end, there will always be some level of risk, but when we analyse them thorough,
the risks become visible and manageable. We can then make conscious decisions about which risks we accept as a team.

## Web shop: an example

A lot can go wrong in software, and the risks are both significant and varied. Imagine you're building a web shop. How
do you identify the risks? And how do you deal with them? The business might say “everything must work” or “It has to
meet the requirements.” But what does that actually mean? By getting specific about those expectations, the conversation
suddenly becomes much more concrete and something you can act on. Looking at the system from a different angle helps
uncover even more. Ask yourself: What could go wrong? A quick brainstorm might already reveal a list of possible risks:

-   The web shop is not available
-   The web shop is not easy to use
-   The web shop does not look good
-   The customer cannot find the articles he wants
-   The web shop is not safe
-   The customer cannot add items to the cart
-   The customer cannot buy articles in the cart
-   The web shop cannot be found

A good start, but not complete and not specific enough. Vague or general risks are a good start but are difficult to
convert into actions. Therefore, make risks as specific as possible. Give the list to a colleague or discuss it with
your team. I am sure that additional risks will quickly be added. The level of detail will also increase rapidly. It is
very easy to inspire each other working together in pairs or in a team. Having diverse people (i.e. different roles)
working together will help to identify as many risks as possible.

After the next "round", the risk analysis could look like this:

-   The web shop is not available because:
    -   The server is down
    -   The database is unavailable
    -   DNS problems
    -   The connection to the computer centre is lost
-   The web shop is not easy to use
    -   Sessions and time-outs not properly regulated
    -   Bad search function
    -   Unclear error messages
    -   Not clear where you are in the web shop
    -   Interface too complex
    -   Unreadable fonts
    -   Unclear texts
-   The shop doesn't look good
    -   Design is not attractive
    -   Web shop does not look professional
    -   Too much text
    -   Design is not intuitive
-   Customer cannot find desired items
    -   Search function incorrect
    -   Search function unclear
    -   Search function returns too many / too few possibilities
    -   Search function cannot be found on the page
    -   The search function is clumsy because there is no auto-suggest function
    -   Filtering is not possible, so there are too many results
-   Web shop is not safe
    -   SQL injection
    -   Man in the middle vulnerabilities
    -   Spoofing
    -   Storage of passwords/salting

Also think about other "departments". Give our list to a sales or marketing colleague and you will suddenly hear about
completely different risks. And if they are not available, you can also try to stand in their shoes.

-   The target group does not find the products in the shop interesting
-   Lost sales because products are missing
-   No actions possible to attract customers
-   Negative publicity due to bad reviews and/or major problems
-   Competition is better or cheaper

The finance department gives you other risks:

-   What happens if the payment is cut off?
-   Suppliers cannot pay
-   Customers do not pay
-   Legal liability for faulty products
-   Customer gets a product twice

A HRM person thinks about the staff:

-   Unqualified personnel
-   Theft by staff And this might make you think of other risks:
-   Fire in the warehouse so that nothing can be delivered
-   Delivery service delivers parcels too late or wrongly

The last risks are not directly IT-related, but they are important and may give you some insight into what is involved
in a web shop. Involve multiple people and perspectives in a risk analysis. Drink coffee with a developer to get their
technical perspective. Talk to a business analyst to understand the business perspective better. These conversations do
not need to take a lot of time. Creativity and learning does takes time: therefore, do not try to be complete at once.
Leave it for a few hours/days and then look at it again. Also ask yourself how serious the risks are. By discussing your
mind map or list, you get the team and the stakeholders thinking. So, it is also an idea generator.

Previously, risk analysis was mainly a matter for project managers and testers. Project managers were busy mitigating
project risks. Testers focused on the product risks by testing. This dates to the time when we mainly worked in siloes
and did testing when the product was already built. Nowadays, risk analysis is much more a team affair. For one thing
because we often no longer have project managers. But also, the way we work and technological developments are causing
changes. Agile/DevOps teams want to create as much value as possible in short iterations with fast feedback. The big
question we must answer as a team is: are there any potential problems that threaten the on time, successful completion
of the product? Of course, we do this together with our stakeholders.

## It starts with a simple list

You don't create a risk analysis all at once. We are dealing with complex products and to fully understand takes time.
Start with a simple list, made by someone in the team. Then discuss this list with someone else in the team or a
stakeholder. By discussing, you will get new ideas and the list will grow. Then discuss it in a refinement with the
team. Remember that these discussions help the team by going deeper and providing more insight that creates "common
understanding".

How do you perform risk analysis? The simple answer to this question is: by thinking of all the things that can go
wrong. Yet many teams have problems performing a proper risk analysis. I regularly see them looking for simple answers.
Calculation of “failure change x impact” is a commonly used method to quantify risk. But then we forget an important
factor: people! Risks are about people experiencing problems. In addition, uncertainty is often confused with risk.
Finally, many teams do not have a systematic method to carry out risk analysis and it is not part of the way of working.

Here are some suggestions to do risk analysis:

-   Brainstorm a list of risks and rank them in order of importance
-   Use a list of heuristics and/or a checklist
-   Consider creating and maintaining a product risk list and a project risk list, especially if no one else on the team
    is doing it
-   Use visualisations and models such as a product coverage outline, architectural overviews, flow diagrams or data
    models while discussing risks
-   Ask the questions listed below
-   Use the four-part risk story below to elaborate on the risks
-   Compare the risk list to coverage and quality criteria areas in the Heuristic Test Strategy Model, and/or your own
    taxonomies
-   Research known problems and patterns previously found in your team/department/organisation
-   Think about value too: what is important to the stakeholders? What is used often? What is critical to the system?

## Questions to ask while doing risk analysis

-   <span style="color:#7ca1dc">[pointing at a figure in a diagram]</span> What if this function doesn't work?
-   Can this function ever be invoked at the wrong time?
-   <span style="color:#7ca1dc">[pointing at any part of the diagram]</span> What error check are we doing here?
-   <span style="color:#7ca1dc">[pointing at an arrow]</span> What exactly does this arrow mean? What happens if it
    doesn't work?
-   <span style="color:#7ca1dc">[pointing at a data stream]</span> If the data going from here to there is somehow
    corrupted, how do we see it? What happens then?
-   What is the greatest load this process can handle?
-   On which external components, services, configurations does this process depend?
-   Can the sources or components drawn here be influenced by another process? How can I crash the process?
-   Is this the whole story? What did you leave out?
-   How do you test this while you are building it?
-   What are you most worried about? What do you think we need to test?

Tip: whenever you do a risk analysis, use a visual model to guide and enrich your discussion about the product.

## The four-part risk story

Risk is about people using or depending on software. So, the story of what goes wrong is about people with a problem. It
is not a "cold" analysis where we calculate failure chance x impact. Someone may be harmed because of something that
might go wrong, due to some vulnerability in the product that is exploited by some threat.

1. Victim: some person that experiences the impact of a problem. Ultimately no bug can be important unless a human cares
   about it.
2. Problem: something the product does that we wish it wouldn’t do.
3. Vulnerability: something about the product that causes or allows it to exhibit a problem, given some condition.
4. Threat: some condition, such as input to the product, that can trigger a problem in a vulnerable product.

Use the four-part risk story to elaborate on the risks and to identify new ones. An expanded view of the risk story is
shown in the image below.

![Risk Story ELements](/assets/img/riskstory.png){: width="600} _Slide from the Rapid Software Testing training -
Copyright © 1995-2025, Satisfice, Inc_

Remember: a simple bullet list is enough to get discussions started on the risks involved.

## When do you do risk analysis?

Risk analysis is not something you do once during a sprint. It is a continuous process. Some examples of risk related
activities during a sprint:

-   Make an initial risk list the first time an epic/feature/story is presented
-   Talk to experts/colleagues to extend your initial list as preparation for refinement
-   Discuss with your team during refinements: what are the risks involved? How do we mitigate them?
-   During testing: how do I test this risk? Identify new risks
-   During testing: explore to find unidentified risks (unknown unknowns)
-   Talk to your peers/team after test sessions (during debriefs): am I done with this part?
-   Talk to your team and Product Owner after testing. Discuss topics like: are we done? What risks are remaining?
-   And more…

## More on risk analysis

-   [Michael Bolton on Risk Analysis](https://www.youtube.com/watch?v=g97mMeC9EIE){:target="_blank"}
-   [Risk Heuristics](https://www.developsense.com/resources/RiskHeuristics.pdf){:target="_blank"}
-   [Software Quality Characteristics by the test eye](https://thetesteye.com/posters/TheTestEye_SoftwareQualityCharacteristics.pdf){:target="_blank"}[^1]
-   [Test Sphere & Risk Storming](https://www.ministryoftesting.com/testsphere/riskstorming){:target="_blank"}[^2]

---

[^1]:
    The main categories of this list resemble the Quality Criteria from the HTSM. The reason I often use the list by the
    Test Eye is that this list is more detailed and contains statements and questions which are useful doing Risk
    Analysis.

[^2]:
    Please be aware that Risk Storming is just a way to get risk analysis started. It cannot replace risk analysis in teams, but it can be a good way to get your team going. There is also an [online version](https://app.riskstormingonline.com/){:target="_blank"}
