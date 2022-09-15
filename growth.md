---
layout: page
title: Growth
sidebar_title: Growth
order: 4
---

Personal growth is one of the reasons I am a lecturer: if you have to explain something to someone, then you need to truly understand it. Teaching forces you to think about the big picture of a field, break it down into simpler parts, and deal with (often) difficult questions from students.

### Developing my teaching philosophy and teaching practices

#### (Long) before COVID

The first class I taught was AMB124 in 2013 (before I did my PhD). I made the mistake of thinking that because I am good at giving research talks, I would be good at giving lectures. In my very first (simple) lecture, I tried to do everything on the board, but as I started, I realized that I don't know how to write on the board! And this was in front of 200 eager students. The lecture was a disaster. After this, for the first few weeks of the course, I would go into an empty classroom every evening and give the whole lecture, on the board, to an empty room. I learned that for me it is essential to prepare very well: I need to know beforehand exactly what I will write on the board, when I will show what on a slide, and when I will flip to a demo.

During my PhD, I tutored students at the University of Edinburgh. A crucial lesson I learned here was the importance of meeting students where they were at. The natural language processing course I tutored involved a combination of machine learning and linguistics, and was taught to students coming from either computer science or the humanities. In answering questions, it was essential to know which background a student came from.

After my postdoc in Chicago, I returned to Stellenbosch. The first course I taught was CP143. CP143 has four lecturers and relies on a common set of slides. I realized early on that just flipping through slides is a guaranteed way of getting students to fall asleep. After watching [lectures from Stanford](https://www.youtube.com/watch?v=KkMDCCdjyW8), I decided to rather work predominantly on the blackboard. Having to write things out forces students to engage and learn actively. I still use slides, but only selectively. Slides and writing on the blackboard would be interleaved with me writing computer programs on the fly to solve example problems. This combination of technologies provides a multimodal form of learning but also forces students to look at their own handwriting afterwards and make the content their own.

Taking the above together, one of my students succinctly captured the core of my in-classroom teaching strategy in a feedback form:

> *Enthusiasm, class participation/engagement, combination of slides+blackboard, music/demos in Python.* --- Aspects of the lecturer that should be maintained, SS414 feedback, 2018.

#### During COVID

This strategy of working on the board, interleaved with selected slides, and live programming/demos is a model I continued to use for lectures. I had to adapt this strategy when we moved to online teaching in DatA414. With practice, it was relatively easy to use a partially populated slide and fill in the rest of the content in writing on a tablet [as a video progresses](https://youtu.be/L5-lxSGO9bM?t=275). Incorporating demos was much harder for me, but I think this is important, and so I have been doing this in my more [recent lecture videos](https://youtu.be/PPmNYwVbcts?t=40). ([This blog post](https://www.weaklysupervised.com/2021/01/15/why-lecture-videos/) describes in detail how I make my videos.)

![]({{site.url}}/fig/dtw_video.png)
*On the left, I am explaining (in writing) the underlying concepts of the code shown on the right. [Full video](https://youtu.be/X6phfLqN5pY?t=90).*

> *The handwritten notes that supplemented the text content made the slides much easier to follow and
"friendlier". Also the graphs and figures are a nice touch and tie the content together well. The student
can visually follow the progression in the lecture videos, which is super effective. I'll also mention that
the content was not presented monotonously, with lots of examples and demonstrations. This made it a
lot easier to stay focused and engaged in the lecture videos. Lastly, the length of the lecture videos was
amazing. They hit the sweet-spot of profundity vs. attention-span.* --- DatA414 course feedback, 2021.

I attended PREDAC in 2021. This gave me a way to talk about and improve things that I have been intuitively doing. In 2019 I had to develop and write the Form-Bs for the registration of two new courses: DatA414 (which I then also taught for the first time in 2020) and Foundations of Deep Learning 344. Going back to these forms, I see now that I tried to structure these courses around threshold concepts (see [Knowledge]({{site.url}}/knowledge/)), despite not being aware of what this idea was called at the time. When I had to develop the new NLP817 course for the [Structured MSc in Machine Learning and AI](https://mlai.sun.ac.za/),[^1] I immediately started building the curriculum around the threshold concepts.

I also relied heavily on another tool that I learned during PREDAC. This tool, which I learned from Karin Wolff, is the *semantic plane* (Wolff et al., 2022). I myself learn best by starting with the big picture and then moving down to the more abstract fundamental concepts---and I think many students learn best in this way as well. The mistake I used to make is starting at the high level and then moving to the abstract fundamental principle, but then I won't return and tie back the principle to the bigger picture! This is called a semantic escalator (Maton, 2013). What I am increasingly doing now is moving towards a semantic wave profile: tying the abstract back to the concrete as you proceed through a lecture. I recently redesigned the first DatA414 lecture to deliberately move over the semantic plane, as illustrated below.

![]({{site.url}}/fig/semantic_plane.png)
*The semantic plane moves from simple to complex on the x-axis, and from concrete to abstract on the y-axis. The figure illustrates how I use the plane to navigate through a lecture on simple linear regression. I start and end in the complex-concrete quadrant, moving roughly clockwise through the quadrants, but still referring back to previous quadrants as I move around.*

#### After COVID

At the beginning of 2022 I had to develop the new NLP817 course. This was also the first time that I would teach "post-COVID", with a return to face-to-face lectures. Building on both pre- and post-COVID teaching experiences, I wanted to figure out an in-class-room teaching strategy that I could use going forward in the longer term. What I did was to go way back: I wrote out how each of my favourite lecturers in under- and postgraduate courses taught. There were ten lecturers. Only one made exclusive use of slides. Two made exclusive use of the blackboard. The remaining seven all used a hybrid approach, with one variant that I particularly liked: using partially completed notes and then filling them out during the lecture. This is exactly what I did during COVID, but I didn't realize that I could do the same in in-person lectures (until doing this analysis). The value is that you can populate notes sparsely so that you don't have to write out everything (saving time in class) but then you still require students to fill in blanked-out portions (making the notes their own). This was the model I settled on for NLP817, and you can have a look at an example of an in-person recording [here](https://youtu.be/BSSoEtv5jvQ?t=510). I still think I am relying too much on the notes and can blank out even more content, but I think this is a good start, and plan to use this method going forward.

### ML4Ed: Machine learning for education

My own research is in the area of machine learning. One area where I aim to grow further is how to apply machine learning in education. I describe two recent efforts.

**E-learning for improving human arithmetic.** In a conference paper (Hall and Kamper, 2020), we did initial work towards the bigger goal of utilising machine learning to assist learners with developing their basic mathematics skills. The idea is to identify the types of problems a user struggles with and then present them with targeted questions to improve in these areas. In the paper, we only focussed on the prediction part of the  system: given a set of arithmetic questions and corresponding answers, can we predict which future questions a user will answer incorrectly? Our best model achieves an accuracy of 69% on real data.

**Automatic machine translation of English engineering assessments into Afrikaans.** The Language Policy of Stellenbosch University (2021) aims to promote multilingualism. In practice, this means that "[q]uestion papers in undergraduate modules are available in Afrikaans and English." While this is noble given the benefits of mother tongue education (Kioko et al., 2014), this places a major burden on already overloaded lecturers. In engineering, many lectures therefore turn to Google Translate to provide a first-pass translation. But these automatic translations often lack the required vocabulary to cover engineering concepts. This project has the broader goal of building a machine translation system specifically for the engineering education domain. In a pilot study, I collected a small corpus of roughly 800 parallel English-Afrikaans sentences from previous assessments in E&E. We are currently building and evaluating initial machine translation systems on this data (Kamper, 2022).

### References

T. Hall and H. Kamper, "Towards improving human arithmetic learning using machine learning," *PRASA*, 2020.

H. Kamper, "Automatic machine translation of engineering assessments: Data collection for a pilot study," *SoTL (in submission)*, 2022.

A. N. Kioko, R. W. Ndung’u, M. C. Njoroge, and J. Mutiga, "Mother tongue and education in Africa: Publicising the reality," *Multilingual Education*, 2014.

K. Maton, "Making semantic waves: A key to cumulative knowledge-building," *Linguistics and Education*, 2013.

Stellenbosch University, "Revision of language policy," [*Online*](http://www.sun.ac.za/english/Pages/Language.aspx), 2021.

K. Wolff, K. Kruger, R. Pott, and N. de Koker, "The conceptual nuances of technology-supported learning in engineering," *European Journal of Engineering Education*, 2022.

* * *

[^1]: I teach this additional course for the Faculty of Science using my extra engineering contract hours.