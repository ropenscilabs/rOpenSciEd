---
slug: educollab-resources
title: "rOpenSci Educators Collaborative: What Educational Resources Work and Why?"
date: 2018-05-22
preface: "At the [5th annual unconference](http://unconf18.ropensci.org) in May 2018, a group of scientists and educators shared their experiences, frustrations, failures, and successes teaching science and R. What came out of this discussion was a framework for rOpenSci Educators’ Collaborative- a community of practice for people interested and engaged in science education using R. This blog post is the first of a 3-post series about education and R, written by this group of unconf18 participants. Read the first post about common pedagogical challenges [here](), and the third post about fostering a community of practice around teaching science with R and how to get involved [here]()."
authors:
  - name: Laura Ación
    url: https://github.com/lauracion
  - name: Mara Averick 
    url: https://github.com/batpigandme
  - name: Leonardo Collado Torres
    url:
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

In the first post of this series, we sketched out some of the common challenges faced by educators who teach with R across scientific domains. In this post, we delve into what makes a "good" educational resource for teaching science with R.

For instructors teaching sciences with R, there are a number of open educational resources that they can reuse, tailor to their own teaching style, or use to inspire them in creating their own materials. Some examples are:

- [Data wrangling, exploration, and analysis with R (a.k.a. STAT545)](http://stat545.com/) originally developed by Jenny Bryan, 
- [ModernDive: An Introduction to Statistical and Data Sciences via R](http://moderndive.com) by Chester Ismay & Albert Y. Kim, 
- [RStudio's Data Science "Course in a Box"](https://github.com/rstudio-education/datascience-box) by Mine Çetinkaya-Rundel,
- [Statistics and R](http://rafalab.github.io/pages/harvardx.html) by Rafael Irizarry and Michael Love
- The lessons offered by [The Carpentries](https://carpentries.org/), including [Software Carpentry](https://software-carpentry.org/lessons/) which are domain agnostic, and [Data Carpentry](http://www.datacarpentry.org/lessons/) which are domain specific. 

What makes these kinds of teaching materials appealing for educators?

For starters, curricular material for teaching must be open to be available and discoverable by other educators. However, a common belief is that educational resources that are closed are better than any open material can ever be. Otherwise, why would someone pay for educational materials? While there are surely cases of closed educational resources that are excellent, openness is one of the most appealing characteristics of high quality teaching resources for teaching sciences with R. Open materials also have no cost for students, allow a community of educators and students to improve and update the materials, and make it possible to reuse and adapt resources. All this makes the whole teaching experience a lot more efficient for the education community at large. In the closed model, where educators do not share their materials openly, they are often working alone (or in small groups) without any feedback nor the contribution of a nurturing community. 

An important benefit of having open materials is that they can be updated easily. One of the things all of our resources listed above share in common is that all of them have the source materials hosted in public [GitHub](https://github.com) repositories. The source materials are typically written in a shareable, editable format like R markdown using tools like [R Markdown websites](https://rmarkdown.rstudio.com/rmarkdown_websites.htm), [blogdown](https://bookdown.org/yihui/blogdown/), or [bookdown](https://bookdown.org/yihui/bookdown/). Keeping educational materials up-to-date is no small task! Having access to these kinds of open-source materials helps alleviate one of the biggest challenges for educators who use R in the classroom: the rapid pace at which packages are introduced and improved. Being able to access cutting-edge teaching materials that are kept current by R community members is far easier than relying on printed textbooks that include stale code and outdated package recommendations. 

Another desirable characteristic of good curriculum material is that they are designed for how humans learn. Scholars have rigorous formal training in research, which is then peer reviewed. However, when it comes to teaching at the university level, they have little to no formal training in educational practices and research. Also, formal mechanisms for peer review are scarce to null. In contrast, there have been real innovations in how to teach programming skills like R (e.g., [Greg Wilson’s “How to Teach Programming (and Other Things)”](http://third-bit.com/teaching/)), and how to train instructors to teach others programming skills like R (e.g., see [The Carpentries Instructor Training](https://carpentries.github.io/instructor-training/)). In our example resources, many have been designed with modern pedagogical approaches in mind For example, [ModernDive](http://moderndive.netlify.com/index.html#sec:connect-contribute) was reviewed by a [cognitive psychologist who specializes in the science of learning](http://www.learningscientists.org/yana-weinstein/). All have been "battle-tested" in real classrooms first, and have been iterated on by the authors based on real student feedback.

Courses that are developed using examples based on real data from the domain of interest and that are meaningful to the learner tend to be more successful teaching contents. Particularly when focusing in the actual practice of the concepts taught rather on purely focusing on the theory. Practice initially using groups of three persons, then two persons and then finally working on the materials individually is also a good way to transmit contents that are initially challenging. A parallel scheme is to introduce the new concepts using a spiral technique that repeats the new concepts over the course using an increased level of difficulty. Platforms for course materials also contribute to their quality and maximize their openness and possibilities of reaching out to more interested parties. 

/* Stef suggested this para lost her, and I may second that- is it helpful or can we make it more helpful?*/
Another feature of good course materials is that they teach people to be independent. Courses that focus in step-by-step instructions toward a topic, usually fall short to be as helpful in real life as courses that teach concepts that generalize to uses outside the classroom. In real life it is more important to know what questions to ask, how to find good answers to those questions, and how to keep the knowledge acquired up to date than to follow step-by-step tutorials for a procedure that may age.

How these learning aims are met, either as apart of a formal term long course, or in a short burst, like a two day workshop, can impact what makes good course materials. For a term long course, lessons that can be woven into existing courses may be more useful, where as teaching a certain set of R skills in a short burst may benefit from a more formal set of lessons that have been tested in an intensive workshop experience. 

In the following and last post for this series, we summarize some priority needs and call for action to advance these priorities to further resources teaching sciences with R.
