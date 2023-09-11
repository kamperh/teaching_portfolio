---
layout: page
title: "Knowledge: Developing students' knowledge and skills"
sidebar_title: Knowledge
order: 3
---

I briefly unpack some of the details around my teaching philosophy and teaching practice in order to show how I think about developing students' knowledge and skills.


### Threshold concepts

The undergraduate courses I teach involve a combination of applied mathematics and programming. These courses have threshold concepts (Meyer and Land, 2003) that students need to grasp. These are more than just "key" or "important" concepts: a threshold concept really changes the way a student thinks about a field, it allows a student to tie together concepts in new ways, and it helps students to identify the boundaries of a conceptual area within a course. These concepts are also often troublesome for students to acquire. But they are also hard to unlearn: once grasped, they stick (Flanagan, 2020).

In programming courses (e.g. CP143), it is often amazing to see what happens when a threshold concept "clicks in". A good example is the concept of pointers. I quote from (Boustedt et al., 2007), where a student says the following during an interview:

> ... once you've realized that a pointer is just pointing to a place in memory, it's just pointing to a location, that's all it is. Then I think everything will flow from that. ... I didn't think about memory nearly so much.

I think  it is essential to identify and construct a curriculum around these concepts, which often serve as building blocks for a field. How does a lecturer identify these concepts? A primary way is for the lecturer to be a practitioner themselves (see [below](#giving-the-bigger-picture)). Another way is through assessments.

While assessing the 2020 DatA414 projects, used as a formative assessment during the term, I realised that most students didn't grasp the threshold concept of one-hot feature representations: many students thought you could use it exactly the same way whether it was used to represent the input or the output of a machine learning model. One reason why this happened was that the concept popped up at very different points in the course: I spoke about input and output representations in disjoint lectures. To address this, I simply reordered my lectures in 2021 to make it possible to have [one lecture](https://youtu.be/AoZdxBqw9n0&list=PLmZlBIcArwhNSvaKyVSoIEq0ewNX9KTC4) where I unpack one-hot representations specifically, highlighting it as a threshold concept. This also shows the importance of giving and pointing students to good resources ([Teaching Philosophy]({{site.url}}/philosophy/), goal 3).

![]({{site.url}}/fig/20220518_075838.jpg)
*Building the NLP817 course around threshold concepts in 2022. I write out the threshold concepts on post-it notes and then arrange them to get the overall structure of the course (or lecture) before starting to create the content.*


### Giving the bigger picture

For students to be motivated to learn threshold concepts, it is also important that they connect with the broader engineering discipline---something that is difficult for a single lecturer to do in a single course. I therefore co-founded the [Maties Machine Learning (MML)](https://mml.sun.ac.za/) seminar series in 2017. Speakers are generally lecturers, postgraduate students or industry partners working on particular problems in machine learning. This gives students the opportunity to see how the concepts they learn are used in real-world applications and research. To date, we have hosted [more than 100 speakers](https://mml.sun.ac.za/talks) at MML. This also plays a major role in helping students see how what they are learning fit into the broader field ([Teaching Philosophy]({{site.url}}/philosophy/), goal 2).

To teach within engineering, I think it is important to be a practising engineer: I need to engage with the content. I do this by being an active research engineer: solving real problems at the edge of what we currently understand requires a deep grasp of the threshold concepts and the broader discipline. I have grown [as a researcher](https://scholar.google.com/citations?user=F3dhs4kAAAAJ) in the last few years. I have also increasingly been involved in consultancy work, e.g. working with [Amira Learning](https://www.amiralearning.com), [Voxcroft](https://www.voxcroft.com/) and [Camb.ai](https://www.camb.ai/).

> *The content was interesting and the fact that it will be useful in industry was clear.* --- DatA414 course feedback, 2020.


### Postgraduate supervision: A Wand Dispenser

In postgraduate supervision, I really like to think of myself using an analogy from [Johan Fourie](https://www.johanfourie.com/teaching/): I am a Wand Dispenser. My goal is to provide upcoming wizards (research students) with the appropriate wands (skills, tools) in order to do magic of their own (research, exploring creation). Extending this analogy from the Harry Potter books a bit: different types of wands go with different students. In the same way, with each postgraduate student I try to find the unique approach that makes them tick.

A little more formally, in *The Structure of Scientific Revolutions*, Kuhn (1962, 2012) gives a philosophy of scientific research: he comes up with the idea that we are all working in a particular paradigm, and our goal as researchers in this paradigm is to solve meaningful puzzles (until a shift happens). Kuhn also gives a direct application to teaching: we should equip students to be able to solve puzzles. Badat (2009) states this as a core role of the university: "Our task is not simply the dissemination of knowledge to students but also the induction of our students into the making of knowledge."

![]({{site.url}}/fig/wands.jpeg)
*I see my role as a postgraduate supervisor as a Wand Dispenser.*

So how do I equip students (give wands) in order to solve puzzles (do magic)? My main strategy is to give postgraduate students enough freedom to learn, explore, and ask questions of their own, while at the same time nudging them so that they continue to make progress. I follow the three goals of my [Teaching Philosophy]({{site.url}}/philosophy/). One slight difference from undergraduate teaching is in goal 3. In undergraduate courses, I would curate and point students to resources directly. In postgraduate studies, I think the skill of figuring out where to find resources and whether it is worth working through them is essential in becoming a contributor to knowledge and a lifelong learner.


### University management and administration

I have served as our department's Postgraduate Programme Coordinator since the beginning of 2022. My main goal has been to make my colleagues more effective Wand Dispensers themselves. I have been doing this by simplifying the postgraduate research processes, e.g. by giving a [centralised webpage](https://eepostgrads.sun.ac.za/) where all relevant documentation can easily be accessed;[^1] by improving the system through which postgraduate students are tracked; and by improving transparency, e.g. by sending out a summary email to all supervisors after every departmental Management Committee meeting.


### References

S. Badat, "The role of higher education in society: Valuing higher education," *HERS-SA Academy*, 2009.

J. Boustedt, A. Eckerdal, R. McCartney, J. E. Moström, M. Ratcliffe, K. Sanders, and C. Zander, "Threshold concepts in computer science: do they exist and are they useful?," *ACM SIGCSE Bulletin*, 2007.

M. T. Flanagan, "Threshold concepts: Undergraduate teaching, postgraduate training, professional development and school education," [*Online*](https://www.ee.ucl.ac.uk/~mflanaga/thresholds.html), 2020.

T. S. Kuhn, *The Structure of Scientific Revolutions*, University of Chicago Press, 1962, 2012.

J. H. F. Meyer and R. Land, "Threshold concepts and troublesome knowledge: Linkages to ways of thinking and practising," *Improving Student Learning -- Theory and Practice Ten Years On*, 2003.

* * *

[^1]: After implementing this, our Undergraduate Programme Coordinator blatantly plagiarised [the idea](https://eeundergrads.sun.ac.za/).
