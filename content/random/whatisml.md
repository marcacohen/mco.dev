+++
images = []
banner = ""
menu = ""
description = ""
categories = []
tags = ["AI"]
title = "Machine Learning Explained in Three Easy Steps"
date = "2017-04-17"
+++

You've probably heard the term "machine learning" and how it's 
[changing everything](https://www.nytimes.com/2016/12/14/magazine/the-great-ai-awakening.html).
In this article, I'm going to explain the fundamental concept behind machine learning. <!--more-->

There will be no math or programming. There will be no scary diagrams. 
You won't need a background in 
computer science or engineering. All you need is the ability to read and think, which you 
obviously already have if you've made it this far. Well done on that reading and thinking! 
Onward...

### Foxes and Dogs

There's a nice sequence of words which is famous for containing every letter in the english language
in one short sentence. Have you seen it?

> The quick brown fox jumps over the lazy dog.

I'm going to slightly perturb this sentence and I'd like you to read it to yourself, out loud:

> The brown quick fox jumps over the lazy dog.

I'm sure you noticed the small change. If you're a native english speaker, chances are the part that I
altered sounded like fingernails on a blackboard. Do you know why "brown quick fox" sounds so wrong?

I recently presented this example to a room of 200 people and nearly everyone knew it sounded wrong
but only one person had any idea why. The reason you don't like the sound of that phrase is because
there are a very distinct set of rules governing the sequence of adjective types in English. 
To be more precise, adjectives must be arranged in the following order:

1. Quantity or number
1. Quality or opinion
1. Size
1. Age
1. Shape
1. Color
1. Proper adjective (often nationality, other place of origin, or material)
1. Purpose or qualifier
 
Since quick is a quality/opinion and brown is a color, "quick brown" is the proper order, not "brown quick".
To give an extreme example, this is fine: "one really big old antique American car" but perturb that sequence
of adjectives in any way you like and the results sound very wrong.

The amazing thing about this sequence is that nearly every native english speaker knows it, but **very few people
know they know it**. In my audience of 200 professional CS and IT people, not a single person could tell me
this sequence.

How did you come to know these things that you don't even know you know? You've been exposed
to so many examples of properly and improperly formulated English phrases that you've developed
a finely tuned adjective order detection engine in your brain.

**Observation one:** Thanks to repetition of examples, you know some things (actually lots of things) you didn't even know you know.

### My Friend Hal

I have a friend named Hal. Hal grew up in a non-English speaking household and, 
at the ripe old age of 30, begins studying English. Hal asks me about this phrase, why 
"quick brown fox" is fine but "brown quick fox" is incorrect. I do some research and
I share with Hal the adjective ordering list above. Hal studies the list exhaustively and 
whenever he's about to utter a phrase, he mentally checks his formulation against the list.

This works ok but there are several problems:

- It's tedious and time consuming to consciously check every sentence. Native english speakers do this automatically,
subconsciously, and effortlessly.
- Manual checking is highly error prone and subjective (e.g. is "amorphous" a quality or a shape?)
- After doing all this work, Hal is able to solve (badly) just one problem from an enormous set of challenges.

**Observation two:** You can compensate for the lack of an automatic detection mechanism by internalizing a set of rules (a computer scientist would call this an algorithm) but the rule-based engine is likely to be less efficient and less accurate than the experience-based engine.

### How Babies Learn

The difference between the two examples above is basically the difference between how a baby acquires language
and how an adult acquires language. A baby acquires language by listening to millions of examples, over
and over, for many years, most of which come from their very own personal language trainer (which is why
your native language is called your "mother tongue"). At some point, babies learn to make their own
sounds, begin to formulate their own sentences, and they receive feedback from their environment about
the correctness of such attempts. Without even thinking about it, they build an efficient neural network
in their brain that automatically recognizes correct linguistic constructs, like the proper order of
adjectives.

An adult learner, on the other hand, doesn't have the luxury of spending 18 years building a finely
tuned pattern matching engine. The adult may also not have a dedicated language tutor. So the best
way for an adult to quickly acquire language skills is to try to boil the language down to a set of
algorithmic rules they can apply through conscious thought, usually with less satisfying results.

This explains why, sadly, after studying French for a few years, I still don't speak nearly as well
as the average four year old in Paris. 

**Observation three:**  Experience based learning leads to entities that "know" things more deeply,
and more intutively than rule based learning.

### So, what is machine learning? 

Rather than trying to encode a definitive set of rules, which is the
method used by previous generations of artificial intelligence research (and which largely failed),
machine learning is the process of training a computer to learn something the same
way a child acquires language, by repeated exposure to examples and experience.

In so doing, we've enabled a new generation of software capable of doing some amazing things, like
automatic [language translation](https://research.googleblog.com/2016/09/a-neural-network-for-machine.html),
medical diagnosis (e.g. [diabetic retinopathy]
(https://blog.google/topics/machine-learning/detecting-diabetic-eye-disease-machine-learning/),
and [cancer detection]
(https://www.diagnosticimaging.com/pacs-and-informatics/machine-learning-algorithms-outperform-inexperienced-radiologists)),
and beating humans in [Chess](https://reallifemag.com/computer-moves/), 
[Jeopardy](https://www.techrepublic.com/article/ibm-watson-the-inside-story-of-how-the-jeopardy-winning-supercomputer-was-born-and-what-it-wants-to-do-next/), 
and [Go](https://www.wired.com/2016/03/two-moves-alphago-lee-sedol-redefined-future/).

That, in a nutshell is what machine learning is all about and why people are so excited about its potential.
In a future article, I'll work through a concrete example of a simple machine learning application, to help
you understand some of the mechanics behind applying this technology to a real world problem.
