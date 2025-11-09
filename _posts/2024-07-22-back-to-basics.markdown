---
title: Back to basics
date: 2024-07-22 00:00:00 +0100
categories: [Test Basics]
tags: skills excellence learning testbasics serious # TAG names should always be lowercase
image:
    path: /assets/img/basics.png
---

How do testers determine what to test? And how do they know if they have tested enough? These are the most difficult questions testers face. Organizations are often concerned that testing is not sufficiently focused on finding the problems that really matter. Thinking about risk and test strategy is often skipped because sprints are too short.

This worries me! Testers cannot explain how they work, nor can they explain how they decide what to test or when to stop. Some claim to use their “common sense” to guide their testing, but when I ask what that means, they can’t explain. Most testing is done on gut feeling and that’s a shame. How can anybody take a tester seriously who cannot explain what he is doing all day? To be really valuable, testers need to learn to talk about their testing in a way others understand and find valuable.

I recently spoke to a lecturer at a university of applied sciences who is doing research for his PhD. He wants to make it easier to teach testing in higher education and at universities. Amongst other things he is interviewing testers about how they think and how they decide what to test… His first results match what I see in the industry: most testers cannot explain how they work. And this is a big problem! Testers are naturally inclined to over-test. So we need to help them creating insight in what is important to test and when to stop…  The solution is simple: back to basics!

### What does back to basics mean?

Back to basics is to consider all necessary activities to do excellent testing! Before we dive into what I mean with excellent testing, let’s look at how testing often works.

This is how testing often works in daily practice:

1. Read/discuss the user story
2. ![Magic](/assets/img/magic-happens.png){: width="220" .normal}
3. Write test cases
4. Execute test cases
5. All test cases passed (or worse: all test cases are executed)
6. Story = done!

If your testing looks like this, you are in trouble! There is much more to excellent testing than just writing test cases and executing them. Let me name a few:

All testing depends on the context, so we need to take context into consideration at all times.
We do not test to check user stories; we test the product!
Testing is about making choices on what to test and what not to test?
Testers do not decide if a product is “good enough”; product owners and managers do.
For me excellent testing should look like this:

1. Model the test space: Context and Product
2. Identify risks
3. Consider coverage (or non-testing activities)
4. Consider oracles
5. Determine test procedures
6. Test the system
7. Evaluate the test results
8. Report test results


- Context analysis helps us consider the context
- Product analysis helps us consider the whole product instead of user stories
- Risks help us decide what to test and what not to test
- Test strategy helps us discuss test coverage in an early stage 
- Reporting helps product owners and managers to make informed decisions

### Risk-based testing

Risk-based testing means organizing the quality or testing strategy around suspected product risks. This means testers perform risk analysis before, during and after testing. They perform risk analysis before testing to set up testing strategies or to guide the testing process. While they test to adjust the strategy and after testing is done to inform our stakeholders about remaining risks. Risk-based testing is a powerful way of focusing testing, not over-testing, and justifying the time and energy it takes to test deeply where necessary. Risk-based testing is important because testers tend to over-test. Testers are risk-averse and like to build in as much certainty as possible. By testing as much as possible, they think they can achieve that. But we don’t test to minimize risk, we need to test “just enough” because we test to inform stakeholders so they can make informed decisions. By conducting a risk analysis and using it to guide our testing, we avoid testing too much or the wrong things.

Many testers report that they test with an implicit risk analysis. In other words, they test risk-aware and use implicit risk to determine what to test, but they don’t talk about it or make it explicit. If the function you are testing is not too complex, this can be a good way. The products we work with are often very complex, so feedback and inputs from others are needed to ensure that as many risks as possible are identified. To be able to discuss and get regular feedback from the team, testers need to make the risks explicit.

### Reporting

Reporting is an important concept for keeping track of where you stand. Creating insight into the important question ‘are there any issues that threaten the timely, successful completion of the product’ is an important task that testers often perform. By reporting, I don’t necessarily mean a written report. Reporting can be done verbally or even in your head if you defocus for a moment and think about what you have done, where you are and what the next step might be.

Many testers don’t report, and the organization assumes that if the checkmarks are green, testing is done and the product is okay… Stakeholders want insight into the status of the work, the status of the product and the remaining risks. It is therefore important to report on this (verbally or otherwise). A report is often a story about the product and its quality on 3 levels:

1. Product story: a story about the status of the product: it informs about the quality of the product: what works and what does not (yet).
2. Test story: a story about how you tested it: The test story is about the coverage we obtained and how we gathered the information about the product.
3. Quality and risk story: a story about the value of testing. It provides insight into the quality of our testing, what risks have been mitigated and what risks we still face.
How do testers determine what to test? And how do they know if they have tested enough? By going back to basics—product (and context) analysis, risk analysis, quality/test strategy, and reporting! As mentioned before, testing is way more than ticking off user stories
