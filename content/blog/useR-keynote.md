---
title: "Keynote at the useR! conference"
author: Julie Lowndes
date: '2019-08-21'
slug: keynote-useR
categories:
  - community
tags:
  - impact
banner: img/blog/keynote/user-keynote-titleslide.png
---

*In July 2019 I gave the opening keynote at the useR! Conference, the R language's international gathering that has happened annually throughout the world [since 2004](http://user2019.r-project.org/past/). It was, needless to say, an incredibly huge honor. This community  Here are a few highlights from my talk, and links to resources and conversations.*

*Quick links:* 

- *[keynote video](https://www.youtube.com/watch?v=Z8PqwFPqn6Y&feature=youtu.be) (starts at 46:30)*
- *[keynote slides](https://jules32.github.io/useR-2019-keynote/#1) (press `p` to see presenter notes)*
- *[artwork by Allison Horst](https://github.com/allisonhorst/stats-illustrations/tree/master/openscapes#dr-julia-lowndes-keynote-illustrations) (available for download and reuse)*
- *[useR website](http://user2019.r-project.org/program_overview/)*
- *[#user2019 on Twitter](https://twitter.com/search?q=%23user2019&src=typed_query)*
- *[blog by Mozilla](https://medium.com/read-write-participate/open-science-and-star-wars-2577b8081e8f)*

---

## R for better science in less time

<br>

<center>
  <a><img src="/img/blog/keynote/user-keynote-titleslide.png" width="500px"></a>
  <figcaption>by [@allison_horst](https://twitter.com/allison_horst)</figcaption>
</center>

<br>

My keynote talk was called "R for better science in less time" and is about how open software and teamwork can supercharge environmental science. And specifically, how R as a language and as a community have been so impactful on my science and on my life, so that now I am focused on passing forward what I've learned. While the message is relevant to many different fields, I focus on environmental science because that is where my expertise lies as a marine-scientist-turned-marine-data-scientist.

In my keynote I shared a lot about Openscapes and what motivates the [Champions mentorship program](https://www.openscapes.org/blog/2019/06/12/wins-cohort1/). That motivation comes from my own experience struggling with data (both alone and with collaborators) and getting through it with mentorship and teamwork, centered around open data science. My three big takehomes were that open data science is a mindset, that teamwork starts with openness, and that to be most effective we should harness the power of welcome. I won't build out those lessons learned here, but I will highlight some of what motivates my work — see options above to read and watch the whole story (or check out [@fmic_'s live-tweets!](https://twitter.com/fmic_/status/1148863951029067776)). 

But first I wanted to say thank you again to everyone that helped me prepare for the talk. In particular, thank you Allison Horst, who coached me weekly and designed beautiful, original artwork to help convey my ideas. I made the slides in R using Yihui Xie's `xaringan`, and published them on GitHub gh-pages. #opendatascience and #teamwork.

<br>

## Environmental open data science

<br>

<center>
  <a><img src="/img/blog/keynote/horst-eco-r4ds.png" width="800px"></a>
  <figcaption>by [@allison_horst](https://twitter.com/allison_horst)</figcaption>
</center>

<br>

This is the vision I see for environmental science. Where the elements that environmental scientsts are great at — like theory, and experimental design, and data collection — is streamlined using open data science to help us uncover and communicate environmental solutions faster. The center of this illustration (the import > tidy > transform/visualize/model > communicate cycle that accompanies [Wickham & Grolemund's definition of data science](https://r4ds.had.co.nz/introduction.html)) here is ringed by communities and support that my team has found so [critical to our success](https://www.nature.com/articles/s41559-017-0160). 

This complete picture is so important for the amazing scientists studying climate changes' affects on the environment (including food security and disease transmission) — but currently this is not the norm.

<br>

<center>
  <a><img src="/img/blog/keynote/horst-eco-r4ds-env-comm-only.png" width="700px"></a>
  <figcaption>by [@allison_horst](https://twitter.com/allison_horst)</figcaption>
</center>

<br>

Currently, environmental science looks like this. We are rarely taught how to work responsibly with data or have formal training with coding or computing. This means scientists learn on their own or in pockets of opportunity but are largely unsupported at broader institutional levels. And often they are not supported even at level of the research group, which is already poised to work like a team.

Helping complete this picture drives my work now. I want to figure out how to best introduce open data science and teamwork to this picture. 

## Open data science — teamwork feedback loop

<br>

<center>
  <a><img src="/img/blog/keynote/horst-lowndes-loop.png" width="500px"></a>
  <figcaption>by [@allison_horst](https://twitter.com/allison_horst)</figcaption>
</center>

<br>


Open data science and teamwork are so powerful together, and I've been thinking about them together as a beautiful feedback loop. Learning and using similar open software promotes and streamlines teammwork. And also working as a team better equips you to learn open practices data science.

For example, using shared conventions like the tidyverse in R can reduce friction when it comes to running each other's code, which can open up time for more thoughtful suggestions and collaboration. The relationships and trust built within the team from these experiences can prime them to improve upon their workflows — they might be more willing to introduce GitHub to their team as a way to reduce the friction that comes from from filesharing. 

This is a loop that feeds back on itself, which each fueling the other. I think that this is really what is doing on in the central portion of the environmental open data science illustration above: those communities ringing the open data science workflow. It's this feedback and this fueling that is so powerful, and it is not limited to the traditional definitions of teams and creates whole communities that innovate together.

And my work with Openscapes is harness the power of welcome to ... welcome more environmental scientists into this feedback loop. Our Ocean Health Index team has found this to be so powerful for our science but when you are outside of it, what are entry points to engage? With Openscapes, we approached it kind of like a spiral. We started with building trust as a team (cohort), but framed around open data science tools and practices. And each week we would build more trust, and dig into open data science a bit more. I'm excited to revisit and improve upon the Champions program to help this cycle get fueled as effectively as possible!


## Q&A

One of the questions I was asked after the talk was about whether "open data science" is needed as a distinction from "open science"; it's it a part of open science as a whole? I don't think I answered that question completely in the moment (I was pretty nervous the whole time) so I thought I'd try to articulate my response a bit here, as well as respond to a few of the other questions submitted on Sli.do after my talk. 

#### Do we need to talk about "open data science" instead of just "open science"

To me, this is more about bringing "open" to the topic of "data science" rather than distinguishing "data" in "open science". I think the concepts of openness are really critical when we think about data science and coding, but maybe since my coding experience began with propriatary software and difficulty sharing (for both technical and mindset reasons), I think it's important that we talk about openness and code together. This can help daylight "black box" algorithms as well as reuse and remix code that we can run on our own machines because the language is open source and we share it openly. 


#### With every PhD student generation, do you feel that it becomes easier to convince them to engage in Open Science? Or is there recurring resistance?

Yes, I think it is getting easier. I think that the new (now?) generation of scientists are much more willing to engage in open science. They have grown up sharing (Instagram, Twitter, GoogleDocs), and they help bring the idea of sharing openly to the scientific community. And I'm excited to see this because there is great opportunity for open practices to not only accelerate and amplify collaboration and scientific discoveries, but be valued, rewarded, and help favor team science. Because no one can do it all, and we need to break down the expectation that they should be able to.


#### How did u convince ur boss to have believe in something he didn't have knowledge about?

Convincing our boss that open data science was worth our time to learn required a combination of trust, demonstrating its value in ways that he cared about, and absolute necessity. 

In terms of trust, he already gave us independence in our tasks, valued our judgment, and welcomed feedback. This had been established within the team for months to years, so it was a collaborative environment before we even began talking about open data science. We were able to demonstrate value in ways that he cared about: we showed him that R and GitHub would save time. And it would not be immediate; it might take us 2 days to do something that we could produce in Excel in a half a day — but it will take just an hour next week and the week after that. We demonstrated how nimble we were to rerun analyses with small changes to parameters or subsets of data, and that these skills would be valuable not only for the current project but for projects to come. And visualizations helped a lot too, as well as interactive graphics and gifs (great for demonstrating change over time). 

This argument was helped because of absolute necessity. We had deadlines approaching and we were spending time retracing our steps instead of taking the next steps forward. We needed a better way to work: it was not sustainable to have to waste so much time doing forensics in our emails and files to try to figure out what we had done and why in order to advance our analyses. For a dramatic analogy, it was like accepting that candles were not enough anymore and that we needed to wire our house for electricity. It meant overcoming inertia and the time it takes for changing this infrastructure, but it means that we can be more efficient in the long run. 

#### how can you keep the balance between sharing and open data and protecting the data while working in a private company?

The advice that comes to mind is to "be as open as possible, and as closed as necessary". There are ways you can share code but not data, or summarize or anonymize data before sharing.

But I think that part of sharing and openness is being aware and engaged with what is possible on the software side so that current, individual skillsets don't limit your imagination. 

To go back to the Star Wars analogy I used in my keynote, when Luke was weighing his options of how to get his plane out of the Dagobah swamp, he *never* would have considered the Force unless he saw what Yoda was able to do. And that develops a mindset where even if you have not seen exactly everything that is possible, you start to *expect* that it is possible. 

On the science side, I think sometimes our uneasiness about sharing is because we do not know what's possible, and it seems like a lot of extra work. If your experience with sharing (smallish) data has been limited to email, the idea of sharing broadly and keeping things up to date seems like a huge task. But when you not only see but have a touch of experience with how a GitHub account and a bit of Markdown gives you a whole new communication platform, it can really spark a change in mindset. And while there is time involved in sharing information, the time-saving benefits and power in the near and long term are worth the investment (just like they were for Luke).

#### How to use twitter effectively to improve our skills and share our experience?



#### As a marine scientist how do we get involved in openscapes?

Great question :) :)





