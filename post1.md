
---
slug: educollab-challenges
title: "rOpenSci Educators Collaborative: What Are The Challenges For Teaching Science With R?"
date: 2018-05-22
preface: "At the [5th annual rOpenSci unconference](http://unconf18.ropensci.org) in May 2018, a group of scientists and educators shared their experiences, frustrations, failures, and successes teaching science with R. What came out of this discussion was a framework for rOpenSci Educators’ Collaborative - a community of practice for people interested and engaged in science education using R. This blog post is the first of a 3-post series about education and R, written by this group of unconf18 participants. Read the second post about what makes a "good" open educational resource [here](), and the third post about fostering a community of practice around teaching science with R and how to get involved [here]()."
authors:
  - name: Laura Ación
    url: https://github.com/lauracion
  - name: Mara Averick 
    url: https://github.com/batpigandme
  - name: Leonardo Collado Torres
    url: https://lcolladotor.github.io
  - name: Auriel Fournier 
    url: https://github.com/aurielfournier
  - name: Alison Hill
    url: https://alison.rbind.io
  - name: Sean Kross
    url: https://github.com/seankross
  - name: Lincoln Mullen
    url: https://github.com/lmullen
categories: blog
topicid: 
tags:
- R
- community
- meetings
- unconf
- unconf18
---


Educators who teach science using R tend to face common pedagogical problems, regardless of their scientific domain. Yet instructors who teach with R often feel isolated at their institutions. They may be the only ones in their departments to teach using R; even if there are others, unlike the rich culture of collaboration around research, the culture of collaboration around teaching materials is rare. In this three-part series of blog posts, participants at the rOpenSci 2018 unconf briefly surveyed the state of teaching science with R. This first post aims to summarize the main challenges that educators face, as a tool to help them think through the decisions they make about their course materials. The second post explains what makes for a good educational resource which can address these shared challenges. The final post sketches out the main things that educators can do in the future to create and share teaching materials and — even more important — to foster a community of practice around teaching science with R.

The primary challenge instructors face is how to keep the focus on their subject matter and not on R. In most courses that use R, some subject like ecology, statistics, or history is the main discipline to be taught, and teaching R is only a means to that end. In other words, we are not teaching courses about R programming or programming in general, as one might in computer science. Rather, we are teaching R so that we can teach specific skills, such as modeling, manipulating, or visualizing data. And we teach those skills so that we can teach students how to think as ecologists, psychologists, statisticians, or historians. Yet much of the day to day work of teaching and learning is necessarily focused on R, since in these domains R is not just a programming language but actually a language of thought and expression within one’s discipline. Educators therefore must balance teaching R with teaching their subject.

This challenge leads into the fundamental question of course design: scoping and sequencing. What things should be taught, and in what order? In a course that teaches a discipline with R, questions of scoping necessarily involve which parts of R should be taught. Will the course be primarily focused on the tidyverse, or will it mostly use base R? If the tidyverse is taught, at what point are base R conventions taught so that students have access to the whole R ecosystem? Much of this decision depends on the characteristic data structures for the field of study. For example, can tabular data structures (i.e., data frames) be used? Or must students also be taught how to deal with matrices, lists, or some other data structure less amenable to the tidyverse? 

In R-based courses, much of students’ time is spent getting up to speed with R: setting up a development environment, learning the syntax, understanding basic computing concepts (file paths are a perpetual problem), and inevitably dealing with bugs in their code. New students can be easily discouraged by seemingly impenetrable error messages, which can derail their progress in learning the scientific concepts that the course is actually intended to teach. Instructors have to decide how best to spend their limited time in and out of class dealing with such issues. A particular challenge for educators is developing materials and techniques for helping students get past the noise of technical problems to the actual signal of the subject at hand.

Educators must think about assessment: evaluating student work in progress during the semester, evaluating the overall ability to apply the course material by the end of the semester, and evaluating the overall effectiveness of the course so that it can be revised for future iterations. Evaluating code can be difficult, and often requires a substantial infrastructure to make sure that instructors can run and comment on student’s code.

Finally, educators must find a way to get students from basic skills (e.g., data manipulation and visualization) to conceptual problems (e.g. statistical modeling, social science thinking). But even more educators must find a way to get students from the controlled environment of the classroom to independent application of materials. In the classroom, students often are given defined data, instructed which methods to use, and given required outcomes. The format of many tutorials inclines students to following steps rather than understanding concepts. These classroom recipes may fall short in real life where students have real (and often messy) datasets, choose the correct methods to analyze the data, and define their own outcomes. The ultimate aim of our courses, the most pressing problem of our pedagogy, is teaching students how to flexibly and independently apply the concepts taught in our courses.

In the next post we will present some examples of open educational materials that are successful at addressing these common challenges, and distill the desirable characteristics of those materials we find particularly useful and inspirational for teaching science with R.
