---
title: What testing can learn from social science – Part 4
date: 2013-04-11 00:00:00 +0100
categories: [socialscience]
tags: context-driven exploratorytesting rapidtesting socialscience # TAG names should always be lowercase
image:
    path: /assets/img/socialscience4.png
---

### Social science: three presentations
Social science is about society, human nature and human interaction. It is an umbrella term to refer to sciences like anthropology, economics, education, linguistics, communication studies, sociology and psychology.

Anthropology teaches us about how people life, interact and something about culture. Education and didactic helps acquire new or modifying existing knowledge, behaviours, skills, values, or preferences. It helps us understand how we learn and how we can teach others. Sociology teaches us empirical investigation and critical analysis and gives insight in human social activity. Psychology is the study of the mind and behaviour and helps testers understand individuals and groups. Now how is this useful in testing? I’ll try to answer that question later. Let me first tell you about three awesome presentations on the subject of social science and testing.

### Software Testing as a social science
![Cem Kaner](/assets/img/KanerSocialScienceSTEP.jpg){: width="200" .right}
Cem Kaner did a talk titled “[Software Testing as a social science"](https://www.kaner.com/pdfs/KanerSocialScienceSTEP.pdf){:target="_blank"} first time in 2006 (slides are here). I haven’t had the pleasure to see the talk myself but the slides drew my interest. Cem made me aware that to test effectively, our theories of error have to be theories about the mistakes people make and when and why they make them. We design and run tests in order to gain useful information about the product’s quality.

Testing is always a search for information. Cem talks about measurement and metrics and the dangers of using metrics wrongly to measure test completeness (new updated article on this can be found [here](https://kaner.com/pdfs/PracticalApproachToSoftwareMetrics.pdf){:target="_blank"}). He argues that bad models are counter productive. Cem also touched the topic of inattentional blindness in which humans often don’t see what they don’t pay attention to. He reminded us that programs never see what they haven’t been told to pay attention to. This is especially valuable when thinking about test automation. When testing we can’t pay attention to all the conditions. The systems under test are simply to complex and there are to many factors that are variable (and uncontrollable). He concludes that thinking in terms of human issues leads us into interesting questions:

- What tests we are running and why?
- What risks are we anticipating and how?
- Why are these risks important?
- What we can do to help our clients gather the information they need?

At EuroStar 2012 in Amsterdam I track chaired two excellent talks, which inspired me to study the subject of social science and qualitative research more.

### Curing Our Binary Disease
![Rikard Edgren](/assets/img/CuringOurBinaryDisease.jpg){: width="200" .left}
Rikard Edgren talked about the getting cured from the Binary Disease (slides are [here](https://www.thetesteye.com/presentations/REdgren_CuringOurBinaryDisease.pdf){:target="_blank"}, video is [here](https://vimeo.com/41977011){:target="_blank"}). The binary disease is when testers don’t provide useful information, because they aren’t allowed by (project) managers. They demand counting passes & fails and insist everything must be verifiable. The binary disease limits our thinking. Testers are addicted to counting passes and fails and don‘t communicate what is most important. When addicted there is no attention to serendipity moments. A model can help testers find important things, but a percentage number might not include things that are important. Therefore a coverage model is useful to get ideas but is not useful as a metric of completion. In his talk he introduces the testing potato to show that there are more things important besides written requirements. More about the potato can be found in his fabulous must read free eBook “[The Little Black Book on Test Design](https://www.thetesteye.com/papers/TheLittleBlackBookOnTestDesign.pdf){:target="_blank"}”.

### Testing Through The Qualitative Lens
![Michael Bolton](/assets/img/TestingThroughtheQualitiveLens.jpg){: width="200" .right}
Michael Bolton’s (slides of the StarEast version are [here](https://www.developsense.com/presentations/2012-04-STAREast-EvaluatingTestingTheQualitativeWay.pdf){:target="_blank"}) talk elaborated differences between physical and social sciences. In physics, humans are ideally irrelevant and mostly get in the way of the experiment. Use quantitative and qualitative research methods and accept high tolerance for ambiguity, context-specific results and be aware of biases while doing research. We should value “partial answers that might be useful”. You do qualitative research when you want to understand something. You do quantitative research to inform that understanding. Quantitative research put human values first; use participant observation and practice storytelling and narration. Software testing is the investigation of systems composed of people, computer programs, products, and the relationships between them. Excellent testing is more like anthropology: interdisciplinary, systems-focused, investigative, and uses storytelling.

---

## Comments from the original Wordpress blog:

<code style="color : lightskyblue">Michael Bolton - April 15, 2013 at 9:03 am</code>
> Hi, Huib…
> Thank you for the citation. I’d be remiss if I didn’t mention that the expression “partial answers that might be useful” comes directly from Cem Kaner’s 2006 talk, but it wasn’t in the slides; it was in his oratory. I thought that this was a hugely powerful way of expressing the value and the uncertainty that we must deliver as we test. As he uttered those words, I immediately reached for my Moleskine notebook. As I did so I turned around, and a few rows behind me I observed Adam White doing exactly the same thing.

> I think Cem may have finally incorporated it in written form somewhere, but I’m not sure where. In any case, the phrase is due to him. We would do well to incorporate it into our explanations of testing, as you have done here.

>—Michael B.