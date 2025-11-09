---
title: Misconceptions about testing
date: 2013-03-31 00:00:00 +0100
categories: [Excellence]
tags: skills agile excellence learning mindset serious peerconference # TAG names should always be lowercase
image:
    path: /assets/img/misconceptions.png
---

A tweet by [Shmuel Gershon](https://www.linkedin.com/in/sgershon/){:target="_blank"} pointed me to an article on the scrum alliance website called "Agile Methodology Is Not All About Exploratory Testing" by [Dele Oluwole](https://www.scrumalliance.org/members/158191){:target="_blank"}. Unfortunately the article is no longer available. I share [Sigge Birgissons](https://www.linkedin.com/in/siggeb/){:target="_blank"} concerns: “the post clearly shows what I mean when having deep concerns about the knowledge of testing in agile community”.

### Understanding testing
I think Dele doesn’t fully understand what testing is or at least he uses a different definition than I do. And certainly he doesn’t understand exploratory testing. [Rikard Edgren](https://www.linkedin.com/in/rikard-edgren-6bb4612/){:target="_blank"} wrote [an open letter](https://thetesteye.com/blog/2013/03/open-letter-to-eurostar-organizers-testing-introduction/){:target="_blank"} to explain what testing is. Please read his high level summary of software testing to understand what testing means to me.

<blockquote class="prompt-info">"It is imperative to state in clear terms why Agile testing cannot be all about exploratory testing"</blockquote>
(The text in the blue frames are quotes form the article by Dele)

I wrote a blog post some weeks ago about agile testing titled ["what makes agile testing different"](/posts/what-makes-agile-testing-different){:target="_blank"}. I think agile testing isn’t that much different from “other” testing. Why do some people think agile is so different? To me there is no such thing as agile testing. There is testing in an agile context. And every agile context is probably different. So saying that agile testing cannot be about exploratory testing makes no sense to me.

### Estimating testing
<blockquote class="prompt-info">It is unequivocally the case that: you cannot estimate your time for exploratory testing, i.e., assign points realistically</blockquote>
Estimating testing is an interesting topic. This blogpost ["Why your estimates don't matter"](https://morgsterious.wordpress.com/2013/02/15/why-your-estimates-dont-matter/){:target="_blank"} by Morgan Ahlström nicely emphasizes that estimates are guesses. Martin Jansson of [the Test Eye](https://thetesteye.com/blog/){:target="_blank"} writes about “utopic estimations” [here](https://thetesteye.com/blog/2010/05/utopic-estimations-in-testing/){:target="_blank"}. Michael Bolton wrote a lot about estimation:
- [Test Estimation Is Really Negotiation](https://developsense.com/blog/2009/08/test-estimation-is-really-negotiation){:target="_blank"}
- [Why Is Testing Taking So Long? (Part 1)](https://developsense.com/blog/2009/11/why-is-testing-taking-so-long-part-1){:target="_blank"}
- [Project Estimation and Black Swans (Part 1)](https://developsense.com/blog/2010/10/project-estimation-and-black-swans){:target="_blank"}

He explains that testing is an open-ended task which depends on the quality of the products under test. The decision to ship the product (which includes a decision to stop testing) is a business decision, not a technical one.

Especially [the fifth part of the black swan series](https://developsense.com/blog/2010/10/project-estimation-and-black-swans-part-5-test-estimation){:target="_blank"} is interesting in this discussion because Michael writes about the fallacies surrounding “development” and “testing” phases. He also explains why estimating the duration of a “testing project” by counting “test cases” or “test steps” is not a smart thing to do.

### Expected results
<blockquote class="prompt-info">"You cannot plan for exploratory testing, as you do not have defined expected results."</blockquote>
Why are some people so obsessed by expected results? And why is there a need to have expected results to be able to plan testing? Expected results can be very helpful, but there is much more to quality then doing some tests with an expected result. A definition that I like is by Jerry Weinberg: “Quality is value to some person”. To understand this, you might want to read this blogpost called ["Quality: Not Merely The Absence Of Bugs"](https://developsense.com/blog/2009/02/quality-not-merely-absence-of-bugs){:target="_blank"} to understand that there is more to quality than the absence of bugs. Also have a look at the excellent free ebook [“The Little Black Book on Test Design”](https://www.thetesteye.com/papers/TheLittleBlackBookOnTestDesign.pdf) by Rikard Edgren. On page 2-6 he uses the [“testing potato”](https://thetesteye.com/blog/2009/12/in-search-of-the-potato/){:target="_blank"} to explain that there are more important aspects to the system than the requirements only.

<blockquote class="prompt-info">"There is no defined scope for exploratory testing."</blockquote>
In the exploratory testing I do in my projects there is a “scope”. I do targeted and focused testing using charters, sessions and planning my testing using a dashboard that resembles a scrum board. Have a look at the slides of my presentation [“Boosting the testing power with exploration“](/assets/files/Exploratory-testing-Huib-Schoots-DutchTestingDay.pdf){:target="_blank"}.

![ET in control](/assets/img/et_rabo.png){: width="300" .left}

Using a coverage outline in a mind map or a simple spreadsheet, I keep track of what I have tested. My charters (a one to three sentence mission for a testing session) help me focus, my wrap-up and/or debriefings help me determine how good my testing was. My [notes and the sessions sheets](https://www.developsense.com/presentations/etnotebook.pdf){:target="_blank"} keep track of what I have done in my testing. Like in scrum, I use “standup” meetings to plan my testing. In these meetings we discuss progress, risks, priorities and charters to be executed. This helps us to make sure we do the best testing we can do continuously.


### Being in control
<blockquote class="prompt-info">"The tester, product owner, and Scrum team are not in control."</blockquote>
I am not sure if I understand what you are trying to point out here. Are you saying that the team is not in control when doing exploratory testing? My model above shows that you can be in control when doing exploratory testing when done right. Exploratory testing is NOT ad hoc or unstructured when done right. If you do it right you will have control!

<blockquote class="prompt-info">"There is no measure of progress, as testers cannot determine when testing is enough."</blockquote>
How do we determine how much testing is enough? [Stopping heuristics](https://www.developsense.com/articles/2008-02-HowMuchIsEnough.pdf){:target="_blank"} might help here. No matter how simple the system is we are building, there are simply to many variables to test everything. So testing is about making choices what to test and what not to test. Even with a huge amount of automated checks, we can not check/test everything (to understand the difference between testing and checking read this blog post called ["Testing and checking refined"](https://www.satisfice.com/blog/archives/856){:target="_blank"}). Testing is not about doing X test cases and when they all pass, you are done. Testing is providing information for managers to make good decisions. And when do managers have enough information to inform their decisions?

### Agile testing quadrants

<blockquote class="prompt-info">"Still, not many agile projects will require just two phases, like integration and regression. But it's definitely not only exploratory testing that's needed, as is erroneously believed in some quarters."</blockquote>
I am not sure what you mean by two phases. What do you mean by testing in phases? I like to use the [agile testing quadrants](https://lisacrispin.com/2011/11/08/using-the-agile-testing-quadrants/){:target="_blank"} when I talk to others about how I think of testing in an agile context. It is not a tool or template, it's a heuristic to help think about what kind of testing can be done.

![agile testing quadrants](/assets/img/Agile-Testing-Quadrants.png){: width="400" .normal}

A team is developing software and the programmers do testing before checking the software in and making it available to the team. How do we call that sort of testing? Unit testing? But is that /only/ testing done by the programmer? I argue that the programmer might do all kinds of testing before checking his code in, even functional and acceptance tests. They probably will create a lot of automated checks and maybe even do some exploratory testing to see if the software meets their expectations: quickly testing some usability and performance aspects. So before the software is checked in, the programmer has covered testing in all 4 quadrants. This does not mean testing is done. More testing can be done, it depends on the context. What does the product owner wants to know? What are the risks involved? How much time do we have left? When discussing a test strategy I try not to speak about phases, I like to discuss what gets covered and why. What information is needed by the team and it’s stakeholders? When talking about coverage I do not mean code coverage but test coverage: the extent to which we have traveled over some map (model) of the system. An interesting source to learn about coverage is this talk by Michael Bolton: ["Finding Bugs Versus Coverage"](https://www.developsense.com/presentations/FindingBugsVersusCoverage.pdf){:target="_blank"} 

So I don’t think you can say “only exploratory testing is needed or not”.

Dele concludes his article with this statement:

<blockquote class="prompt-info">"It is the responsibility of the tester (and the Agile/Scrum team) to ensure that acceptance testing is in line with the expectation of the product owner. If we agree that there is an expectation, we therefore have to design test cases (even if minimal) that will verify the specified acceptance criteria."</blockquote>

Dear Dele please read about testing and exploratory testing. Some good starting points can be found in [this lists of resources](/posts/great-resources){:target="_blank"} on this blog or [another list of resources](https://developsense.com/resources){:target="_blank"} made by Michael Bolton. I am happy to point you to more good sources of information if you are interested. Just let me know.


---

### Comments from the original Wordpress blog:

> <code style="color : lightskyblue">Brian Osman - April 8, 2013 at 1:19 am</code><br>

> Good article Huib – interestingly enough i tweeted last year that i don’t believe in the label Agile testing (or Agile tester – note the caps). Rather i believe that testing is shaped by the context. Hence Agile testing to me is testing in an Agile context and of course that may vary project to project. The *testing* hasn’t/doesn’t/shouldn’t change but the bubble around the testing (i.e. the project/org dynamics) would.

> Unfortunately, too many people make ill conceived comments about good exploratory testing. Thanks for sharing.

> <code style="color : lightskyblue">Johan Jonasson - April 3, 2013 at 9:10 am</code><br>

> Good work Huib. Looking forward to your reply to Dele’s second post as well. 😉

>>  <code style="color : lightskyblue">Huib Schoots (Post author) - April 7, 2013 at 9:54 pm</code><br>

>> I am not sure I will write a comprehensive reply. Not sure it is worth the effort. I have a feeling Dele doesn’t want to understand. If I am wrong about this, I am happy to continue the discussion.

>> James replied with this tweet:[https://twitter.com/jamesmarcusbach/status/319763237732249600](https://twitter.com/jamesmarcusbach/status/319763237732249600){:target="_blank"}. I join James in offering my help. Dele recommends me to read books I already own and have read. This weekend I re-read pages 308-320. I hope he reads the stuff I recommended him.

>> I think my post wasn’t clear enough about the things we agree upon. I added a comment on his rejoinder blog to make clear that I do not think exploratory testing is the /only/ way people should test in agile contexts. I do value test automation. The claims Dele makes on exploratory testing are wrong and Dele will benefit from learning more about exploratory testing.

>>> <code style="color : lightskyblue">Johan Jonasson - April 8, 2013 at 9:24 am</code><br>

>>> Yeah, I agree. I felt I wanted to reply to his second post and point out to him that nobody’s saying “agile testing is all about ET”, but that if you are going to talk about why it isn’t, then at least one should make an effort to understand ET first (which I thought your post tried to help him with very generously).

>>> But, I found I didn’t have the energy to get into that sort of discussion. So I tried to trick you into doing it instead. 😉

> <code style="color : lightskyblue">XU Yi - April 3, 2013 at 7:24 am</code><br>

> Well, I started to define “Agile Testing” as “Doing testing in Agile way within an Agile environment under the guidance of Agile thinking.” I separated two things, 1st is how we test (verb) the object under test; 2nd is how we organize the testing (noun) activities as a whole, both in terms of many testers and many testing activities (e.g. design, execution…).

> And, if we agree that ET is more an approach to do test, does it make sense to say “It’s All About doing Things in One Approach!”?

> <code style="color : lightskyblue">Huib Schoots (Post author) - April 2, 2013 at 2:52 pm</code><br>

> Dele wrote a new blog: [Response to Magnifiant: exploring software testing – Huib Schoots](https://www.scrumhint.com/index.php/blog/256-response-to-magnifiant-exploring-software-testing-huib-schoots){:target="_blank"}.

> <code style="color : lightskyblue">Peter Varhol - April 1, 2013 at 12:21 pm</code><br>

> Best article I’ve read so far this year. It makes me realize how little I really know about testing.

> <code style="color : lightskyblue">Geir Gulbrandsen - April 1, 2013 at 2:30 am</code><br>

> That is one awesome collection of personal and referenced wisdom Huib! I will need to read through this a few more times just to digest what /you/ are saying, before digging further into the links you provide (although some are familiar)… and then connect it all together. Thanks for yet another great post.

> Geir

> <code style="color : lightskyblue">Wayne Peacock - March 31, 2013 at 8:09 pm</code><br>

> Great article Huib! You’ve brought together so many useful references here. You’ve also made some very good points yourself. I have read this on my mobile but have forwarded it to my work email address to read it again. I shall also share it with the testers where I work and beyond. Thank you.

> <code style="color : lightskyblue">Tony Bruce - March 31, 2013 at 7:49 pm</code><br>

> Fantastic feedback Huib, hopefully your post will make it to Dele.

> I’m not understanding where he is coming from either.
