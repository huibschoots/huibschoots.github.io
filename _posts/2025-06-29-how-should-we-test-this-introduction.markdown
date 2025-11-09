---
title: How should we test this? - Introduction
description: Introduction to a series of blog posts on the question "How should we test this?"
date: 2025-10-21 10:00:00 +0100
categories: [Test Strategy]
tags: strategy risk reporting models # TAG names should always be lowercase
image:
    path: /assets/img/hswtt.png
---

<blockquote class="prompt-info">This blog series explores a central question in software testing: “How should we test this?” (HSWTT?) We'll start with some foundational concepts that shape how we approach testing: learning, modelling, and heuristics. From there, the series dives into practical thinking tools: how to learn about the product (Product Analysis), how to identify important potential problems (Risk Analysis) and how to search for those problems effectively (Test Strategy). Finally, we’ll look at how to communicate what we’ve found in a meaningful way (Reporting).</blockquote>

## Introduction

All the ideas in this series are heavily been influenced by Rapid Software Testing.[^1]

“How should we test this?” is one of the toughest questions a practicing tester can encounter. We are often concerned
that our testing is not oriented on finding the problems that really matter. We skip thinking about risks
and test strategy because sprints are too short. Most testing is done on gut feeling and that is a pity, because it can
be done much better, easily. Testers are naturally inclined to over-test. Using risk analysis and test strategy and
discussing them on a regular basis with the team and product owner can help preventing testing too much.

## Humans like certainty

Humans are addicted to knowing. Knowing for sure preferably. Certainty is what we want. People get stressed by
uncertainty, but in the world out there where we do our work, especially software development, nothing is certain. We
must deal with that!

The “structured test methodologies” like ISTQB try to teach a standardized way of working. Especially in the 90’s and
00’s almost every test methodology was teaching a structured, document heavy way of testing. They called it structured
testing. To me it sounded funny because of what they mean with it is that you have to follow a specific structure and
your testing process in the systematic way they prescribe. Nowadays I think structured testing is a pleonasm (like white
snow or green grass). Using an exploratory approach in testing is also structured, but it is structured in a different
way.

I also see people who like to make problem solving and testing systematic (also called mechanic or algorithmic),
oversimplifying it so it becomes easier. Like calculating risk by multiplying probability and impact. Or by always using
a standard way of working, without considering context. Humans like to make things easy. Our brain is built that way: 85
to 90% of what we do is done automatically, without thinking. We have to put our brain in an active mode to use System 2
(as Kahneman1 called it). In my experience I see many people preferring an algorithmic way of working in their testing.

## Thinking paradigms

Only recently via [Professor Dr. Tanja Vos](https://www.linkedin.com/in/tanja-e-j-vos-4812ba/){:target="_blank"} did I discover two distinct paradigms for understanding knowledge:
[Rationalism and Empiricism](https://www.sciencedirect.com/science/article/pii/S0167642318300030){:target="_blank"}.
Empiricism emphasizes learning through experience, observation, and iterative experimentation. It values direct
interaction with software, user behavior, and continuous feedback loops. In contrast, Rationalism is rooted in logic,
reasoning, and formal methods. It relies on systematic processes and abstract theories to design and prove software
“correctly.” While Rationalism prioritizes structure, standardization, and formal rigor, I found already early in my
career that this approach didn’t resonate with me. The highly methodical, logic-heavy mindset felt restrictive. Instead,
I was drawn to the empirical spirit of agile, context-driven testing, and Rapid Software Testing—approaches that embrace
uncertainty, learn by doing, and adapt based on real-world outcomes.

## Research and development

Making software is a continuous process of research and development. Business and IT work together to find suitable
solutions, solve problems and prevent them. It is a challenging puzzle to make the translation between what people want
and what machines can do. To cope with complexity, interim changes, and new insights. In the end, it's all about what
works and what doesn't.

Software is everywhere, it powers our daily lives, making things easier, faster, more efficient, and often more
enjoyable. It's so deeply embedded in what we do that living without it has become nearly impossible. It shapes not just
how we live, but what we're able to do.But do you know that nervous feeling when new software goes live? That moment of
uncertainty? You're not entirely reassured. What if something goes wrong? What if your car won’t start tomorrow because
of a system glitch? Or your phone needs a reinstall, and all your photos vanish? What if, suddenly, you can’t work at
all?

The quality of software is crucial. It takes a lot to make good software work. Not only the software itself must be
good, but also the processes around it, the machines and networks it runs on, the people who work on it and with it.
Many different aspects have an influence. Collaboration, communication and teamwork are decisive. This forms the basis
for successful departments, projects, and teams. You see this all around you: where professional people work well
together, successes are achieved and the life of the user becomes easier, richer, and more exciting.

## Quality

Now we mentioned Quality, let's talk about what it actually means. In RST we define Quality as "value to some person who
matters". We see Quality as a dynamic relationship. Quality is an opinion, not a fact. Decisions about quality start
with decisions about whose values matter, what they value, and how that value might be threatened. Quality
Characteristics help stakeholders model value. But keep in mind that this is a simplified story about quality! The
product is the experience that the user receives. Specifications only partly correspond to the needs of the customer,
and it also partly corresponds to the product that is ultimately built. There is no way specifications are ever
complete. Different people can look at the same things and see different quality.

## Dealing with complexity and uncertainty

Software development is complex. It is really hard to fully and deeply understand what a system should do. Because there
are many requirements, but also because we deal with customers who don't know exactly what they want or can't explain it
well. IT teams don't always understand the business well. We also must deal with a
[VUCA](https://en.wikipedia.org/wiki/VUCA){:target="_blank"} world: complexity, confusion, changes, new insights, and
half answers. As a result, we face considerable risk. Making software is a continuous process of research and
development. Business and IT work together to find suitable solutions, solve problems and prevent them. It is a
challenging puzzle to make the translation between what people want and what machines can do. Therefore software
development is about learning and dealing with risks.

Complexity is a serious and often undervalued problem in software development. Being aware of it, is the first step. We
need to reduce complexity continuously: by working agile we deal with complexity, but also by building our systems
modular using microservices helps. [Team Topologies](https://teamtopologies.com/){:target="_blank"} introduced the
concept of [cognitive load](https://itrevolution.com/articles/cognitive-load/){:target="_blank"} to me. It made me
realize that in many cases we expect our teams to deal with too much information and complexity and this is asking for
problems! Modeling and visualization is a great way to make complex things easier to understand.

In my career I developed being comfortable with uncertainty. As a fast thinker I used to deal with uncertainty in a very
different way. I got nervous and irritated if I didn’t understand things fully fast enough. Nowadays I know that deep
understanding takes time and effort and can be facilitated by creating your own models and visuals.

The remainder of this series is organized into five main parts:

1. Learning, heuristics and models
2. Product Analysis
3. Risk Analysis
4. Test Strategy
5. Reporting

The in next blog we will dive into learning.

---

[^1]:
    Rapid Software Testing (RST) is a responsible approach to software testing, centered around people who do testing
    and people who need it done. It is a methodology (in the sense of “a system of methods”) that embraces tools (aka
    “automation”) but emphasizes the role of skilled technical personnel who guide and drive the process. The essence of
    this methodology lies in its humanism (we foster responsibility and resilience by putting the methodology under the
    control of each practitioner), its ontology (how we organize and define the various priorities, ideas, activities,
    and other elements of testing), and its heuristics (fallible methods of solving a problem). In RST, we’re not afraid
    of learning, applying, and discussing words like “ontology” or “heuristics”. For us, words are important tools we
    use to help us develop our expertise and to describe and explain our work. Rather than being a set of templates and
    rules, RST is a mindset and a skill set. It is a way to understand testing; it is a set of things a tester knows how
    to do; and it includes approaches to effective leadership in testing.

    Source: [Rapid Software Testing Website](https://rapid-software-testing.com/){:target="_blank"}
