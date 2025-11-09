---
title: On the scale of Context-driven…
date: 2013-01-07 00:00:00 +0100
categories: [context-driven]
tags: contextdriven ideas thoughts visualization # TAG names should always be lowercase
image:
    path: /assets/img/cdtcont.png
---

In the last edition of Testkrant (in Dutch) I published an article on context-driven testing called [“I am a context-driven tester! Huh? Really? So?“](/assets/files/testkrant20122contextdriventesten.pdf){:target="_blank"}. In this article I (try to) explain what context-driven testing means and why I think I am context-driven. Jan Jaap Cannegieter reacted via email asking an interesting question which has crossed my mind several times already. The following quote is from his email but translated and slightly changed.

### Jan-Jaap

> “Isn’t everyone context-driven to some extend? And I mean that on a sliding scale. People who always use the same method and implements this method slightly different every time are maybe 2% driven context (I have combined context-driven and context-aware, sorry for simplification). The Jedi tester using dozens of test methods that he blends to a unique test approach to apply in a specific situation is perhaps 98% context-driven.”

### Jon Bach

![Jon Bach ET continium](/assets/img/etscale.png){: width="250" .left}
Jon Bach presented a “freedom” scale in his presentation [Telling Your Exploratory Story](https://youtu.be/uUdWm7ddgfU){:target="_blank"} at Agile 2010 Conference. Jon contrasts scripted testing and exploratory testing by plotting them in the freedom scale above.

Could such a scale also be applied to being a context-driven tester? Contrasting “Context-oblivious” with “Context-driven”? Maybe putting “context-aware” somewhere in the middle of the scale? Context-driven, context-oblivious and context-aware are explained on the website [www.context-driven-testing.com](https://context-driven-testing.com/){:target="_blank"}.

### CDT continium?

![My little drawing](/assets/img/cdt_scale.jpg){: .normal}
I am not totally happy with this model yet, but can’t put my finger on it how to improve it. There is more to being context-driven as only applying methods and techniques. I also ask myself what is the added value of such a scale? I think it helps testers understand the differences between context-oblivious, context-aware and context-driven better. It might also make it easier to bridge the gap between the extremes or even advocate that everybody is or can be context-driven in some extend?

What do you think?

---

### Comments from the original Wordpress blog:

> <code style="color : lightskyblue">Jari Laakso - February 23, 2013 at 11:46 am</code><br>
> Hi Huib, Thanks for the post and opening the discussion!

> Everyone is context-driven by some definition. Being context-driven is asking first and shooting after. 🙂 Seriously speaking, to me, being a part of the context-driven testing community means something more than being context-driven. But I’ll try to focus on the context-driven mentality in this comment. I’ll preserve the CDT community discussions until Let’s Test 2013. 😉

> Being context-driven means we will first try to understand the context as well as we can, so we can let it drive our actions. It’s not context-driven testing if one only takes into consideration contextual matters while testing. There is really no scale here. There maybe could be a scale how much one drills into the context, but that, well, depends on context. I don’t see a scale between context-driven and for example context-oblivious testing. (Even if I dislike most analogies about religions, here goes one.) Just like I don’t see a scale between being Buddhist and Jewish. The analogue is flaky, but it also points out an important (to me!) factor: context-driven testing is not something you can just toss out from the window when it doesn’t really work for you; it’s not a technique.

> You say about the picture: “it helps testers understand the differences between context-oblivious, context-aware and context-driven better.” In my opinion, it makes the separation more difficult. I think giving an example of context-aware, oblivious, specific, imperial and driven testing would clarify the differences much better. I’d love to talk more about this on Skype, for example, because clearly there is something I am not seeing like you do; and we both know you are over my thinking skills. Maybe I’m just too extremist at the moment.

> I was looking at the picture and I am not really sure what the triangles are representing. Jon Bach used freedom for scaling, but I don’t really understand what is the scale you are trying to visualise. Could you explain this a bit?

> As a side note, I saw Joep Shuurkes’s comment only after writing mine. He seems to have similar thoughts what I had. I was also thinking first that we could use a 2-dimensional (not to make too complex so that it works as a simplified model) illustration of the differences. However, I was not able to come up with a XY-scale that would really change anything. The best (from my point of view) idea I had was to use “context” as the x axis and “driven” as the y axis; only to notice none of the other options are driven by context at all.

> Have a funtastic weekend!

> Best regards, Jari

> <code style="color : lightskyblue">Jan Jaap Cannegieter - January 10, 2013 at 10:06 am</code><br>
> Wow, great discussion Huib started here after my email to him. Thanks a lot everybody!
Let me first tell you how I came to this idea. When I was first confronted with context driven testing, about a year ago, I started to study it and come to the conclusion I am pretty context driven because in every project I act differently. Let me give an example. In 2012 Q3 and Q4 I implemented requirements processes at a small insurance company and a big government organization. And you can’t compare the two implementations and implemented processes!
During the last year I visited quite some SYSQA-testers who use some kind of exploratory testing. And I noticed that none of them stick to any method. One tester adjusted a specific method depending on the context, the second combined two methods, the third took different things from different sources and sometimes added something to it him- of herself. For all of them the context led them in some degree.
That brings me to the added value of the continuum. I had a discussion with a tester about the usability of a specific test method in a certain project. I made the suggestion that maybe practices from another method could be very useful in this specific project. He agreed, started to study this method and actually started to use practices from this other method in his project. So he became more context driven, but definitely not totally! So by defining some stereotypes you can help testers becoming more context driven. For example: are you a tester who uses one method every project the same way, your first step should be to adjust this method for every project. Are you someone who adjusts a specific method for you project, the first step should be to learn more methods and combine these etc. So to give a reaction to Simon Morley (nice to meet you): I see becoming context driven as a evolution, not a revolution.
Some comments suggested an two axes model, very interesting thought. I don’t know yet how this would look like, but I will sure start to think about that. I hope to get back to this some day soon!

> <code style="color : lightskyblue">Joep Schuurkes - January 9, 2013 at 10:07 pm</code><br>
> The single axis scale for context-drivenness does not work for me. The freedom scale does: I can imagine what a test approach that’s 20% scripted and 80% exploratory, would look like. But what would 20% context-oblivious and 80% context-driven mean? We fail to see 20% of the context? In 20% of our activities we don’t take the context into account?

> To me saying that we are all context-driven to some degree is like saying that all water is ice to some degree – and water at 5 degrees centigrade more so than water at 25 degrees centigrade. In a way that’s not incorrect, but in the end as long as water is not below 0 degrees centigrade, it’s just water and not ice. (Ignoring all that cool physics stuff like the triple point here, of course.)

> As an alternative I would propose to haves two axes: primacy of context and adaptability.
Context-oblivious testers score zero on both.
Context-aware testers score 0.5 on both.
Context-driven testers score 1 on both.
Context-specific testers score 1 on primacy of context, but -1 on adaptability. (Negative adaptability because “s/he is not aware of the degree to which skilled testing will be different across contexts” and for the symmetry with context-imperial.)
Context-imperial testers score -1 on primacy of context and -1 on adaptability. (They try to substitute the present context with their own, hence both negative.)
Of course, in stead of single points on the axes, all groups would occupy an area in the plane defined by the axes. Since I’m terrible at drawing, I’ll leave that as an exercise for the reader. 😀

> <code style="color : lightskyblue">Mohinder Khosla - January 9, 2013 at 9:35 pm</code><br>
> I am not sure why you are using sliding scale for context. According to Wikipedia the word “context” stems from a study of human “text”; and the idea of “situated cognition,” that context changes the interpretation of text, is an idea that goes back many thousand years (http://en.wikipedia.org/wiki/Context_awareness#Qualities_of_context). Three important aspects of context are: (1) where you are; (2) who you are with; and (3) what resources are nearby. Anything driven by context has these attributes that occupy three dimensional space and not linear. Something that is obvious for one person may not be for other. Context awareness is learnt through experience. A working model for context-aware for mobile computing is described here (http://www.teco.edu/~albrecht/publication/draft_docs/context-is-more-than-location.pdf) that may help improve your slider. In most cases you use the tool what we call rule of thumb or gut feeling to explicitly examine the context. Fully understanding the context requires lot of effort and other analytical frameworks.

> <code style="color : lightskyblue">Simon Morley - January 8, 2013 at 2:01 am</code><br>
> If the context-driven approach is a paradigm shift – as Kuhn described – this would mean a revolution in approach. In which case, it is probably natural that context awareness is spreading after such a “revolution”.

> People latch onto the context more and more (both in testing, in the media, in more widespread reporting of scientific studies, etc) – and use context to inform their decisions and judgement. Being context-driven is a worldview (in the Kuhnian sense) – meaning that’s their whole drive and way of experiencing the world/situation. How that would look in practice – an exemplar – I don’t know. How to assess if they’re context-driven or just aware is a grey area.

> I like the idea of a map/diagram as a communication aid to help testers get a grasp of where they are in the world – as a means of learning and improvement. How it should look, I don’t know.

> Lots of don’t knows there! Thought-provoking and puzzling. I need to think some more…

> <code style="color : lightskyblue">Ilari Henrik Aegerter - January 7, 2013 at 10:35 pm</code><br>

> Where would you place context-imperial on your continuum?

> <code style="color : lightskyblue">Tim Western - January 7, 2013 at 9:33 pm</code><br>

> I rather like the idea of having some kind of map between the two, but I wonder if instead of being continuous along a single axis, it might look more like a range along two axis. One axis would be context awareness, and the other perhaps (a suggestion) could be the amount of impact that context actually has upon the tests that are run. If you did that you could have four quadrants emerge, and differing attributes of each maybe.

> I’m not sure what that would be, but that’s the thought that jumped out to me. Not sure if the second axis I suggest is the best thing to compare it too though.

> <code style="color : lightskyblue">Kristoffer Nordström (@kristoffer_nord) - January 9, 2013 at 1:23 pm</code><br>

> Tim, I like the idea of two axises, also not sure the impact one is the best.
But here’s a suggestion how we could use it to map out (stereotypical) tester personalities.

> What do you think Huib (hope it’s visible&accesible)?
[https://plus.google.com/u/0/118334178016897255443/posts/QpSonnN2jyw](https://plus.google.com/u/0/118334178016897255443/posts/QpSonnN2jyw){:target="_blank"}

> Upper left corner: “Test Savant”
Naturally does “the right” thing
Lower left corner: “ISTQB”, “9-5” tester
…
Lower right corner: “Test theorist”
Reads all about it, but doesn’t put it into practise
Upper right corner: “Professional context-driven tester” “RST Tester”