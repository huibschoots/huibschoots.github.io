---
title: Do we need testers?
date: 2020-05-17 00:10:00 +0100
categories: [DevOps]
tags: testing agile devops skills responsible # TAG names should always be lowercase
<!-- pin: false -->
image:
  path: /assets/img/testerpuzzle.png
---


Last week I did a talk at Agile, Testing & DevOps Showcase in Amsterdam. My topic was “Testing in modern times“.


### Testing in modern times

<iframe src="/assets/files/testing_in_modern_times.pdf" width="400" height="250">
</iframe>

In agile and especially DevOps approaches the motto is: automated everything! Companies like Facebook claim they do not have testers at all. Microsoft only has SDET (software development engineers in Test), other companies are T-shaping developers to do the testing. New kid on the block is AI and machine learning, that will definitely replace testing I hear people claim. What is really happening globally?

Do we no longer need testers? I am not sure anymore. Why? Because testers have a bad name. If you cannot automate nowadays, you are no longer valuable, people say. That makes me sad. I think skilled testing is super important! Testing informs decisions about value, quality and risk by learning about the product (and a serious professional tester also will give you insight in the status of the project or team they are working in). Modern technology and tooling is reducing the need for dedicated testers. Not by replacing testers, but by reducing certain types of risks we used to test. More and more people are getting obsessed by “automate everything”. Sadly even some testers I meet are obsessed by trying to automate everything they do…

### Valuable software
How can we make valuable software for our clients? I believe that personal leadership and collaboration ultimately makes the difference. The quality of software is crucial nowadays. Therefore I like to focus on an integrated quality approach. As a tester, a mentor and a coach, I help people and teams learn effectively and continuously develop with attention to sustainable adaptability that leads to improving (team) results and way of working. It enables teams to create more customer value by building quality solutions!

In IT we need insights in risks. Risks and value. For that we need to learn continuously. And I think we need smart people who do skilled testing, determined to find problems that matter. Teams need to create insight and overview in the risks we take by creating, releasing and using (IT) products. Often people with excellent testing skills excel in doing this… I hear new job titles as “Quality coach” and “Quality Engineer”. Is this the way to go? Well if that solves the problem of “automation obsession” and a lack of testing skills in teams? I am game. 

### We will always need testers
So far the original post on linkedin. Recent events make me doubt if we ever get to a point where we do not need dedicated testers.

Dan Ashby reacted on linkedin:
> "It's a really interesting question. My take: yes, we need testers... because we need skilled testing, and the Dev communities haven't kept up with what skilled testing is and how to do it. One thing too: Facebook use offshore testers (lots of them via a tester contracting company - I know people that work at FB and at the 3rd party testing company). Also MS have done a U-turn too, and they also employ testers again as well as SDETs. They also have test manager roles again too. Maybe lots of the big companies have hit that realisation that they needed good testing (and hence needed the testers who have those skills)? If so, hopefully the smaller companies that tend to imitate the big companies will soon follow suit. 😁"
I like what he says here: “we need testers… because we need skilled testing.” Although there are some developers who have really good testing skills, many are not interested in testing nor learning to do skilled testing. So I think he has a point there. But dedicated testers alone do not solve the problem. We need better testers and better thinking about testing too!

I see a huge fixation on “test automation” and this is causing us to lose connection with the human, social purposes of software development and testing. The essence of software development is that during development, we learn about what we need, what the customer really wants and how the product we are building actually works. This is research and development, learning along the way, and needing sense making and feedback to get it right.

This [Vision on the Future of Software Testing](/assets/files/ISTQB_The_Vision_on_the_Future_of_Software_Testing_Final.pdf){:target="_blank"} by ISTQB from 2019 has nothing to do with skilled testing. This shows that even an institute like ISTQB does not understand IT in general nor testing. That makes me so sad!

Test approaches like TMAP and ISTQB are neglecting the human aspects of testing. They try to approach testing with mechanistic thinking and are not dealing with the complexity and uncertainty that developing software and dealing with people brings. Leading test experts told me we cannot make testing too complicated or else testers will not understand.

Recently the new TMAP book was published called “Quality for DevOps teams”. Reading how TMap deals with risk analysis and test strategy gives me goosebumps. The risk analysis is just a list of quality attributes with a simple calculation (possible impact x chance of failure) and based on the number we assigned a “risk class” (high, medium, low). And based on the risk class we assign the test intensity in dots. See for yourself what it looks like here and here. Now let’s look at some quotes from the book that made my eyes roll.

## Chapter 47 “Experience-based testing”

>“Exploratory testing is an experience-based approach of testing, the most important approach of experience-based testing in our opinion. We distinguish coverage-based and experience-based testing. Others use terms like scripted testing and free-style testing, but we prefer the division in focus on either experience or coverage.”

All testing that you do uses experience, because there is no way you can shut it off. And doing any test will give you some coverage. I guess they just do not know how to talk about coverage in a way that makes sense.  Why make this strict distinction in only two categories? There are so many more ways to classify test techniques (note: what TMAP calls “approach” is called “technique” in BBST).  There is no strict distinction between test techniques. See slide 62 of [BBST Test Design](/assets/files/BBSTTestDesign2011pfinal.pdf){:target="_blank"} “Every test addresses all of these. A specific technique typically addresses 1 to 3 of them, leaving the rest to be designed into the individual test“. Personally I like the way BBST classifies techniques looking at the driving ideas behind the testing.

>“The main downside of applying error guessing is the lack of documentation. Therefore, tests are not reproducible. This may result in a developer not being able to investigate an anomaly, the tester not being able to retest a fix, and the test cannot be added to a regression test set.”

Why do tests need to be reproducible? If a tester is capable of telling or showing the developer what goes wrong, you do not need any documentation. I think with enough product knowledge, it is not that difficult to retest. So we are solving a problem in the wrong way, aren’t we?

## Chapter 48 “Is there any value in unstructured testing?”

>“Any testing lacking a plan containing what to do and what to expect of a system, or lacking preparation of the test, is unstructured. This is also called ad-hoc testing. Some people see a great advantage in unstructured testing because, as they say: “You can start testing right away.” That is, without “losing” any time on preparation.”

The only structure TMap knows is plans and test cases. Structure is “the arrangement of and relations between the parts or elements of something complex”. Michael Bolton wrote about this [here](https://www.developsense.com/resources.html){:target="_blank"}. Testing is about learning and learning involves mental models. TMap seems to have no attention at all about how people learn. Deep learning in the beginning is a confusing process, but it gets clearer along the way. By letting it rest (defocus), we give our brains the chance to process the learned information and integrate it with the models we have in our heads. So good (mental) models are important. These “mechanistic test approaches” forget the whole learning part.

>“When you have an IT system that is of good quality, the testers do their unstructured testing and don’t encounter any faults or failures. Can they now say the quality is good and that there are no significant risks? Did they really measure the quality and risks? No, the only thing they can truly say is they did “some” testing and didn’t find any problems. However, they cannot explain which requirements or quality risks have been covered. They are not even sure which parts of the system have been covered.”

This is an interesting approach taken by TMAP here which is called an “appeal to ignorance”. The testers cannot explain so the approach must be wrong! But is the approach the problem or are skills of the testers the problem here?

<blockquote class="prompt-info">The first version of this blog was published on [linkedin](https://www.linkedin.com/pulse/do-we-need-testers-skilled-testing-yes-huib-schoots/) on February 5, 2020 titled “Do we need testers? No! Do we need skilled testing? Yes!”. I added my new insights to this blogpost.</blockquote>{:target="_blank"}