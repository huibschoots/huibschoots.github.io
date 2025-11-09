---
title: How should we test this? Part 1 - Learning
description: Part 1 in "How should we test this?" on learning, heuristics and models
date: 2025-09-11 11:00:00 +0100
categories: [Test Strategy]
tags: strategy risk reporting models # TAG names should always be lowercase
image:
    path: /assets/img/learning.png
---

<blockquote class="prompt-info">This blog series explores a central question in software testing: “How should we test this?” (HSWTT?) We'll start with some foundational concepts that shape how we approach testing: learning, modelling, and heuristics. From there, the series dives into practical thinking tools: how to learn about the product (Product Analysis), how to identify important potential problems (Risk Analysis) and how to search for those problems effectively (Test Strategy). Finally, we’ll look at how to communicate what we’ve found in a meaningful way (Reporting).</blockquote>

How should we test this: [Introduction](/posts/how-should-we-test-this-introduction/){:target="_blank"}

## Part 1: Learning, heuristics, and models

## Learning

Agile is incremental and iterative. And that's for a good reason. Software is complex, many problems can no longer be
solved by one person or within one discipline. Collaboration, critical and creative thinking, communication, being able
to see relationships, all these aspects are therefore becoming increasingly important in software development.

Chopping learning in smaller pieces makes things easier to understand. Iterative work is a natural process. We call this
[evolutionary design](https://modernagile.org/){:target="_blank"}: "A strategy to add value quickly by growing
something over time from a primitive but complete entity to a higher level of sophistication".

This is how people learn: we must accept that deep learning is a confusing process at first, but it gets better quickly.
By letting go of the work for a while (defocus) we give our brain a chance to process the information learned and
integrate it with the models we have in our head. Learning happens in "loops." So, as in agile, feedback is important:
do something, check or discuss the result, move forward based on the result. The shorter and more focused the feedback
loop, the faster you get feedback on whether you are doing a good job. The less waste we produce.

## Bootstrapping

In RST we teach the bootstrap approach: this means that we need to accept that any deep learning or real innovation is a
confusing process at first, but it gets rapidly better.

<blockquote class="prompt-info">Booting is the process of starting a computer, specifically with regard to starting its software. The process involves a chain of stages, in which at each stage, a smaller, simpler program loads and then executes the larger, more complicated program of the next stage. It is in this sense that the computer "pulls itself up by its bootstraps"; i.e., it improves itself by its own efforts.<br>
</blockquote>
Source: [https://en.wikipedia.org/wiki/Bootstrapping#Computing](https://en.wikipedia.org/wiki/Bootstrapping#Computing){:target="_blank"}

This is very similar in how we learn: we start with understanding small parts and while we progress these small parts of
knowledge or expertise helps us understand larger, more complicated knowledge. Step by step we learn the complex things
we need to learn.

In practice this means that you should digest information in (small) parts, take time to learn and accept that you will
experience some confusion when learning a product. This confusion is necessary, temporary, and healthy.

Some other interesting facts about learning:

-   Learning needs time, your brain needs time to process
-   New ideas, understanding often comes when you are NOT working (defocus)
-   Build upon ideas from others in your team is an effective way to learn (and innovate) fast

Applied to an agile way of working this means that refining your stories should be done in several steps. So called
learning in chunks. Where many teams refine a story only once, I recommend rather spend 3 times 10 minutes on refining a
(complex or complicated) story than 1 time 60 minutes. Your brain needs time to process all the information shared. The
same can be said about Risk Analysis or Test Strategy. It needs time to unfold and be developed.

Another tip on learning is asking questions. Asking questions is I will write a blogpost on asking good questions later.

## Heuristics

Another aspect of learning and understanding better are heuristics. In RST we say: “heuristics are fallible methods for
solving problems”. They are like guidelines or rules of thumb. Some examples: “Pull on the handle, push on the plate”,
“Don’t drink and drive”, “If it rains, take an umbrella” and “If you are having difficulty understanding a problem, try
drawing a picture”. Heuristics are mental shortcuts that help you solve problems or makes decisions fast and with
minimal mental effort.

<blockquote class="prompt-info">"The engineering method is the use of heuristics to cause the best change in a poorly understood situation within the available resources.”<br>
<br>
A heuristic has four definite signatures that make it easy to recognize:<br>
1. A heuristic does not guarantee a solution<br>
2. It may contradict other heuristics<br>
3. It reduces the search time for solving a problem<br>
4. Its acceptance depends on the immediate context instead of on an absolute standard <br>
   <code class="language-plaintext highlighter-rouge">Source: Billy Vaughan Koen in Discussion of the
   Method</code></blockquote>

The most important set of heuristics I use is the
[Heuristic Test Strategy Model](https://www.satisfice.com/download/heuristic-test-strategy-model){:target="_blank"}
(HTSM). This model is full of guideword heuristics: words or labels that help you access the full spectrum of your
knowledge and experience as you analyze something. The HTSM is a model which consists of four sets of heuristics:

1. Project Environment help to understand our context and mission(s)
2. Product Elements help to identify dimensions and factors of the product that could be examined in a test
3. Quality Criteria help to identify value and threats to various criteria of the product
4. General test techniques help to design tests

These heuristics help me think of important aspects when thinking of risks and test strategy.

Heuristics are not followed, they’re applied as means of solving problems in uncertain conditions with uncertain,
imperfect, or incomplete information. They can substitute for complete and rigorous analysis when that kind of analysis
would be very expensive or impossible.

## More on heuristics

-   [The Essence of Heuristics](https://www.satisfice.com/blog/archives/462){:target="_blank"}
-   [Heuristics for understanding heuristics](https://www.developsense.com/blog/2012/04/heuristics-for-understanding-heuristics/){:target="_blank"}
-   [A collection of Testing Mnemonics made by Del Dewar](https://findingdeefex.files.wordpress.com/2015/05/testingmnemonics1.jpg){:target="_blank"}

## Models

The last important aspect of learning and understanding better are models. Your mental models of the product control
your testing of it. Better (mental) models mean better thinking. Better thinking means better testing.

A model is a representation of an idea, activity, or object such as something complex that you need to work with or
study. It helps you understand or manipulate the thing that it represents. For example: a map helps navigate and
atmospheric models help predict the weather in your town. Models help you understand by visualizing something that is
difficult to see or understand. Mental models help you think better. A mental model is simply a representation of how
something works in your head. We cannot keep all details of a product in our brains, so we use models to simplify the
complex into understandable and organizable chunks.

Mental models helps understand life. Mental models about testing help you do better testing. For instance, the
[RST framework](https://www.satisfice.com/download/a-rapid-software-testing-framework){:target="_blank"} is a model of
how testing works.
[Elements of excellent testing](https://www.satisfice.com/download/elements-of-excellent-testing){:target="_blank"} is
a model of what testing is, what it involves and what a tester does. The
[heuristic test strategy model](https://www.satisfice.com/download/heuristic-test-strategy-model){:target="_blank"}
helps you think better about test strategy.

Visual models help you think and talk about your testing. There are many, many models you can use to visualize important
things in your work: (whiteboard) sketches, a bunch of stickies on the wall, UML, data flow diagrams, data models,
activity diagrams, state diagrams, process flow diagrams, architecture diagrams, context diagrams, use cases,
wireframes, swim lanes, mind maps,
[product ecology](https://ruudcox.wordpress.com/2013/10/25/an-example-of-a-product-ecology-for-testers/){:target="_blank"},
product coverage outline, and many more. I use drawings all the time. I cannot explain stuff without drawing or pointing
to a visual model of some kind. I like to use all kinds of models in refinements and risk analysis sessions. The models
help understanding because we can point to something while talking.

## Modeling a hospital

When working in a hospital several years ago, we had to test the 32 most important applications (medical record, drug
administration, surgical planning, etc) when they moved from three different locations into a single new building. All
department codes had changed and we had to do regression testing to see in these 32 applications still would work. We
had 6 months and we did not have a lot of experience with these applications. The models (see picture below) we used
saved our lives and gave us a quick insight in how things work. Every time we spoke to people we put them in front of
our wall of models to quickly understand what they were talking about.

![Visuals at a hospital](/assets/img/hospital.png){: width="600}

## More on models

-   [Mental Models. The Best Way to Make Intelligent Decisions](https://fs.blog/mental-models/#building_a_latticework_of_mental_models){:target="_blank"}
-   [Many models - better test ideas by Rikard Edgren](https://thetesteye.com/blog/2012/02/many-models-better-test-ideas/){:target="_blank"}

---
