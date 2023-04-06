---
title: "Designing automated workflows, a chat  with Dr. Sean Kross"
author: Sean Kross, Julie Lowndes, Stefanie Butland
date: '2023-04-06'
slug: sean-kross-Kyber
categories:
  - community
tags:
  - community-call
banner: img/blog/IMAGE.png
---

## **How the Kyber R package connects Google Sheets, RMarkdown, GitHub, and Agenda docs for open education**

*Quicklinks*

-   [*Video recording*](https://youtu.be/K99uqIlhI9s)
-   [*Collaborative Notes*](https://docs.google.com/document/d/1Ok-_axfN9wpmhbmGNkAcrJTCN2b3KuERLp1NrjNOxnc/)
-   [*Slides*](https://docs.google.com/presentation/d/1GrUu4n8M4xsYKmRet3jkfjNapmmwUJAnxzYHJxFCZrM/)

*Our 8th Openscapes Community Call featured a "celebrity interview" with [Dr. Sean Kross](https://seankross.com/). Sean is a Data Staff Scientist at the [Fred Hutch Data Science Lab](https://hutchdatascience.org/). His work includes understanding [data science as a practice](https://courses.csail.mit.edu/18.337/2015/docs/50YearsDataScience.pdf), and approach combines computational, statistical, ethnographic, and design-driven methods. Sean earned his PhD in Human-Computer Interaction at UC San Diego where he was advised by [Philip Guo](https://pg.ucsd.edu/), and interned at Microsoft Research. Before grad school Sean was the Chief Technology Officer at the [Johns Hopkins Data Science Lab](https://jhudatascience.org/). He is a frequent consultant for data analysis and software development projects, and a maintainer of several open source software projects. Sean was interviewed by Stefanie Butland, MSc, Openscapes Team member.*

------------------------------------------------------------------------

Sean joined us from his office-with-a-great-view at Fred Hutch Cancer Center in the South Lake Union area of Seattle.

## **What is Kyber?**

[Kyber](https://github.com/openscapes/kyber) is an R package that contains tools for setting up learning cohorts on GitHub, purpose-built for the [Openscapes Champions Program](https://www.openscapes.org/champions/). Kyber reads in data from Google Sheets and from that creates RMarkdown documents which are then exported to Google Docs. It also sets up repositories and files and organizes people on GitHub. Kyber replaces manual steps with R functions while maintaining the ability to edit outputs so we're not constrained by the automation. How cool and practical is that?!

<br> <center> <a><img src="/img/blog/kyber-design.png" width="700px" alt="image of kyber flow design from left to right with Google Sheets icon, horizontal arrow, hexagonal logo of kyber with blue diamond on green background, diagonal arrow pointing up to GitHub and another diagonal arrow pointing down from kyber to hexagonal RMarkdown logo then horizontal arrow pointing to Google Docs icon"></a> </center> <br><figcaption>Kyber design</figcaption><br>

Watch the [video (starting at 44:30)](https://youtu.be/K99uqIlhI9s?t=2670) of Julie screensharing Openscapes' call metadata and RMarkdown components that are the ingredients from which Kyber makes an agenda sandwich 🥪.

## **What was the motivation for Kyber?**

<br> <center> <a><img src="/img/blog/airbnb-work.jpg" width="700px" alt="6 smiling people sit at a round table with their laptops open. Window in background"></a> </center> <br><figcaption>Sean Kross joined the Openscapes summit</figcaption><br>

Sean Kross assisted our 2019 Inaugural Openscapes Champions Cohort, learning from and supporting 7 academic marine science research teams. Photo from our [summit](https://www.openscapes.org/blog/2019/04/25/summit-reflections2/).

Sean was deeply involved with the [inaugural](https://www.openscapes.org/blog/2019/06/12/wins-cohort1/) Champions Cohort at Openscapes in 2019 and was privy to the manual creation of the infrastructure to make it happen. Sharing that curriculum with more groups would require repetition so:

1.  Openscapes already makes heavy use of Google Drive and GitHub, how can we use R to bring both together?

2.  How could we push RMarkdown's parameterized reporting features?

3.  How much automation can we drive with minimal programming for the end-user?

In Fall 2022, Openscapes ran 4 Cohorts, each with a separate [GitHub repo](https://github.com/nmfs-openscapes/2022-noaa-nwfsc-fall) with 40 team members and 40 uniquely-named Markdown files, plus 5 detailed Google Doc lesson agendas listing different start and end dates and times, discussion prompts, and links to slides. Using Kyber was a huge win for saving time and reducing manually-produced errors.

<br> <center> <a><img src="/img/blog/kyber-example-agenda.png" width="700px" alt="image titled Automating processes with kyber. screenshots of Google sheet, plus sign in middle, R code to call kyber, below that is arrow pointing to screenshot of a Google doc agenda produced by those inputs"></a> </center> <br><figcaption>An example use of kyber for creating Openscapes Cohort Call agendas</figcaption><br>

Beyond the nuts and bolts of tool development, we got into some more philosophical discussions. Discussions with our audiences are the best!

## **How do you manage your time?**

As an early career professional with a full time job, consulting, being involved in data science communities, and keeping up with ever-evolving data science tools, how do you manage all of that? Sean feels that working in the open a lot - on GitHub, YouTube, websites - has magnified the perception of the work he does, based on others reusing and resharing. [Philip Guo](https://pg.ucsd.edu/), Sean's PhD advisor embraces the concept of "[fire and motion](https://www.joelonsoftware.com/2002/01/06/fire-and-motion/)": it's better to be moving forward, even if you're just moving forward a little bit. If you have 20 minutes to write 3 sentences for that blog post that you've been wanting to write, do it, even if you don't know if it will ever be published. After trying lots of tools, Sean uses [Notion](https://www.notion.so/) to write ideas and snippets of text that he can come back to later.

Watch the [recording](https://youtu.be/K99uqIlhI9s) and browse the [collaborative notes](https://docs.google.com/document/d/1Ok-_axfN9wpmhbmGNkAcrJTCN2b3KuERLp1NrjNOxnc/) for Sean's thoughts on his motivations for engaging in this kind of tool-development project, adapting the design and some of the functions in Kyber to automate other workflows, why use R for this application rather than using the coding capacity within Google products themselves, and how others can get into this kind of work.

## **Resources**

-   Subscribe to Monday Morning Data Science: [fhdata.substack.com](https://fhdata.substack.com/). Your weekly dose of data news from The Fred Hutch Data Science Lab
-   R Package development (context: how can others get into this)
    -   [Package Development: the Mechanics](https://rpkgdev-mechanics.netlify.app/) and the sequel, [rOpenSci: Package Development: Not Rocket Science](https://rpkgdev-rocket.netlify.app/) by Maëlle Salmon for rOpenSci.

    -   [Forwards Package Development Modules](https://github.com/forwards/workshops/tree/master/package-dev-modules)

    -   [R-Packages](https://r-pkgs.org/) book - Hadley Wickham

    -   [bookdown: Authoring Books and Technical Documents with R Markdown](https://bookdown.org/yihui/bookdown/) - Yihui Xie
-   [quartificate](https://github.com/ropenscilabs/quartificate) R package to transform Google Docs into Quarto Books, by Maëlle Salmon for rOpenSci
-   Recent [interview with Abby Cabunoc Mayes about open source philosophy](https://podcasters.spotify.com/pod/show/mechanical-ink/episodes/Open-Source-at-GitHub-with-Abigail-Cabunoc-Mayes-and-Naytri-Sramek---Episode002-e1s5i6t): Abby's now at GitHub and previously at Mozilla. She created Moz Open Leaders
-   Jeff Leek has "[the most forked GitHub repo](https://github.com/jtleek/datasharing)" \> 243,000 forks of How to share data with a statistician
