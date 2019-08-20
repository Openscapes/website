---
title: "Keynote at the useR! conference — followup Q&A"
author: Julie Lowndes
date: '2019-08-20'
slug: keynote-useR
categories:
  - community
tags:
  - impact
banner: img/blog/keynote/user-keynote-titleslide.png
---

*Last month I gave the opening keynote at the useR! Conference. *

*For more details on Openscapes see [blog by Mozilla](https://medium.com/read-write-participate/open-science-and-star-wars-2577b8081e8f)*.

Quicklinks: 

- [video](https://www.youtube.com/watch?v=Z8PqwFPqn6Y&feature=youtu.be) (starts at 46:30)
- [slides](https://jules32.github.io/useR-2019-keynote/#1) (press `p` to see presenter notes)
- [artwork by Allison Horst](https://github.com/allisonhorst/stats-illustrations/tree/master/openscapes#dr-julia-lowndes-keynote-illustrations) (available for download and reuse)

---

"Last month, R users from across the world gathered in Toulouse, France to discuss new developments at the useR! conference, the language’s premier international gathering." - Dan Kopf https://qz.com/1661487/hadley-wickham-on-the-future-of-r-python-and-the-tidyverse/

useR! is an annual international conference for innovators around the R programming language, which are called useRs. The conference in Toulouse was the ... Learn more about it here. 


My talk was about xyz. I like to talk about this with parallels to Star Wars, and art

This is a condensed summary of my talk, with [full slides available](), along with a [video]() of the presentation live in Toulouse. 


---

<br>

<center>
  <a><img src="/img/blog/keynote/user-keynote-titleslide.png" width="500px"></a>
  <figcaption>art: [@allison_horst](https://twitter.com/allison_horst)</figcaption>
</center>

<br>

## R for better science in less time

The talk is called "R for better science in less time" and is about how open software and teamwork can supercharge environmental science. And specifically, how R as a language and as a community have been so impactful on my science and on my life, so that now I am focused on passing forward what I've learned through mentorship and training. While the message is relevant to many different fields, I focus on environmental science because that is where my expertise lies as a marine-scientist-turned-marine-data-scientist.

In my talk I shared a lot about Openscapes and what motivates the [Champions mentorship program](https://www.openscapes.org/blog/2019/06/12/wins-cohort1/). That motivation comes from my own experience struggling with data and getting through it with mentorship and teamwork, centered around open data science.

One of the questions I was asked after the talk was about whether "open data science" is needed as a distinction from "open science"; it's it a part of open science as a whole? I don't think I answered that question completely in the moment (I was pretty nervous the whole time) so I thought I'd try to articulate my response a bit here, as well as respond to a few of the other questions submitted on Sli.do after my talk. 

But first, I wanted to say thank you again to everyone that helped me prepare for the talk, particularly Allison Horst, who coached me weekly and designed beautiful, original artwork to help convey my ideas. I made the slides in R using Yihui Xie's `xaringan`, and published them on GitHub gh-pages. 

- [video](https://www.youtube.com/watch?v=Z8PqwFPqn6Y&feature=youtu.be) (starts at 46:30)
- [slides](https://jules32.github.io/useR-2019-keynote/#1) (press `p` to see presenter notes; I intentionally limited text on slides for the keynote and unapologetically read my notes because I was nervous!)
- [artwork by Allison Horst](https://github.com/allisonhorst/stats-illustrations/tree/master/openscapes#dr-julia-lowndes-keynote-illustrations) (available for download and reuse)




## Do we need to talk about "open data science" instead of just "open science"

To me, this is more about bringing "open" to the topic of "data science" rather than distinguishing "data" in "open science". I think the concepts of openness are really critical when we think about data science and coding, but maybe since my coding experience began with propriatary software and difficulty sharing (for both technical and mindset reasons), I think it's important that we talk about openness and code together. This can help daylight "black box" algorithms as well as reuse and remix code that we can run on our own machines because the language is open source and we share it openly. 


#### With every PhD student generation, do you feel that it becomes easier to convince them to engage in Open Science? Or is there recurring resistance?

Yes, I think it is getting easier. I think that the new (now?) generation of scientists are much more willing to engage in open science. They have grown up sharing (Instagram, Twitter, GoogleDocs), and they help bring the idea of sharing openly to the scientific community. 

<!---Sharing is important to accelerate ideas and analysis in science, but I think that it's also important for sharing the workload. And this is important because individual scientists cannot do it all (research, publications, mentorship, teaching, travel, committees, communication, grant writing, etc., and now open data science?), nor should they be expected to. There is great opportunity for open practices to not only accelerate and amplify collaboration and scientific discoveries, but be valued, rewarded, and help favor team science. And moving forward, the workload and credit should be more distributed. If we had a culture where open data science was valued, collaboration was fueled by the open web, credit was transparent, and researchers worked on projects as a team – as we do with the Ocean Health Index –  then we could find environmental solutions we have yet to imagine – and elevate everyone in the process.
--->



#### How did u convince ur boss to have believe in something he didn't have knowledge about?

Convincing our boss that open data science was worth our time to learn required a combination of trust, demonstrating its value in ways that he cared about, and absolute necessity. 

In terms of trust, he already gave us independence in our tasks, valued our judgment, and welcomed feedback. This had been established within the team for months to years, so it was a collaborative environment before we even began talking about open data science. We were able to demonstrate value in ways that he cared about: we showed him that R and GitHub would save time. And it would not be immediate; it might take us 2 days to do something that we could produce in Excel in a half a day — but it will take just an hour next week and the week after that. We demonstrated how nimble we were to rerun analyses with small changes to parameters or subsets of data, and that these skills would be valuable not only for the current project but for projects to come. And visualizations helped a lot too, as well as interactive graphics and gifs (great for demonstrating change over time). 

This argument was helped because of absolute necessity. We had deadlines approaching and we were spending time retracing our steps instead of taking the next steps forward. We needed a better way to work: it was not sustainable to have to waste so much time doing forensics in our emails and files to try to figure out what we had done and why in order to advance our analyses. For a dramatic analogy, it was like accepting that candles were not enough anymore and that we needed to wire our house for electricity. It meant overcoming inertia and the time it takes for changing this infrastructure, but it means that we can be more efficient in the long run. 


#### how can you keep the balance between sharing and open data and protecting the data while working in a private company?

The advice that comes to mind is to "be as open as possible, and as closed as necessary". But I think that part of this is being aware and engaged with what is possible on the software side so that current, individual skillsets don't limit your imagination. 

To go back to the Star Wars analogy I used in my keynote, when Luke was weighing his options of how to get his plane out of the Dagobah swamp, he *never* would have considered the Force unless he saw what Yoda was able to do. And that develops a mindset where even if you have not seen exactly everything that is possible, you start to *expect* that it is possible. 

So on the science side, I think sometimes our uneasiness about sharing is because we do not know what's possible, and it seems like a lot of extra work. If your experience with collaborative and publishing software has been limited to email, the idea of sharing broadly and keeping things up to date seems like a huge task. But when you not only see but have a touch of experience with how a GitHub account and a bit of Markdown gives you a whole new communication platform, it can really spark a change in mindset. And while there is time involved in sharing information, the time-saving benefits and power in the near and long term are worth the investment (just like they were for Luke).

#### How to use twitter effectively to improve our skills and share our experience?



#### As a marine scientist how do we get involved in openscapes?

Great question :)



