---
title: "Week 11"
linktitle: "Week 11"
date: "2021-03-30"
start_date: "2021-03-30"
end_date: "2021-04-05"
menu:
  content:
    parent: Course content
    weight: 11
type: docs
toc: true
slides: "11-slides"
draft: false
---




## Required content

*Finish this material before class on April 6th*

- <i class="fab fa-youtube"></i> Lecture and exercises: R Markdown: The Basics ([see below](#lecture-r-markdown-the-basics))
- <i class="fab fa-youtube"></i> Project 3: Presentations in R Markdown ([see below](#project-3-presentations-in-r-markdown)). **Note: this project is not due until April 13**.
- <i class="fas fa-book"></i> [R Markdown: xaringan Presentations](https://bookdown.org/yihui/rmarkdown/xaringan.html)
- <i class="fab fa-youtube"></i> [renv: Project Environments for R (talk)](https://rstudio.com/resources/rstudioconf-2020/renv-project-environments-for-r/)
- <i class="fas fa-book"></i> [renv: Project Environments for R (blog post)](https://blog.rstudio.com/2019/11/06/renv-project-environments-for-r/)

## What's due this week

- Nothing!

## Bonus material
- <i class="fas fa-external-link-square-alt"></i> [R for Data Science: R Markdown](https://r4ds.had.co.nz/r-markdown.html)
- <i class="fas fa-external-link-square-alt"></i> [R Markdown for Scientists](https://rmd4sci.njtierney.com/)
- <i class="fas fa-external-link-square-alt"></i> [Fundamentals of Data Visualization: Telling a Story and Making a Point](https://clauswilke.com/dataviz/telling-a-story.html)

## Lecture: R Markdown: The Basics

### Exercises

*Work through these videos and exercises on your own prior to class on **April 6th***

<i class="fas fa-desktop"></i> **Option 1**: Download the material locally


```r
au.rcourse::use_module("11-rmarkdown_basics")
```

<i class="fas fa-cloud"></i> **Option 2**: Complete the exercises at RStudio Cloud: https://rstudio.cloud/project/2318426

**Reminder**: You need to save a permanent copy or download the project to keep your exercises

### Videos

Videos for each section of the lecture are [available at this YouTube playlist](https://www.youtube.com/playlist?list=PLYCuG6HXKxjQKJTN65LBuvjR92Gnv7Dbs).

- [01 - R Markdown: The Basics](https://www.youtube.com/watch?v=wleSfTnh150&list=PLYCuG6HXKxjQKJTN65LBuvjR92Gnv7Dbs)
- [02 - R Markdown: The Basics](https://www.youtube.com/watch?v=i5A7ZX2-7D8&list=PLYCuG6HXKxjQKJTN65LBuvjR92Gnv7Dbs)
- [03 - R Markdown: The Basics](https://www.youtube.com/watch?v=a0NFaa0HUSo&list=PLYCuG6HXKxjQKJTN65LBuvjR92Gnv7Dbs)
- [04 - R Markdown: The Basics](https://www.youtube.com/watch?v=1GqOHCGe17Q&list=PLYCuG6HXKxjQKJTN65LBuvjR92Gnv7Dbs)
- [05 - R Markdown: The Basics](https://www.youtube.com/watch?v=k4Rz9PDQxmw&list=PLYCuG6HXKxjQKJTN65LBuvjR92Gnv7Dbs)
- [06 - R Markdown: The Basics](https://www.youtube.com/watch?v=xUB9pEKnWoc&list=PLYCuG6HXKxjQKJTN65LBuvjR92Gnv7Dbs)
- [07 - R Markdown: The Basics](https://www.youtube.com/watch?v=sCb5JgQhpdM&list=PLYCuG6HXKxjQKJTN65LBuvjR92Gnv7Dbs)
- [08 - R Markdown: The Basics](https://www.youtube.com/watch?v=5L4SL7Mlxl8&list=PLYCuG6HXKxjQKJTN65LBuvjR92Gnv7Dbs)

You can also watch the playlist (and skip around to different sections) here:

<div class="embed-responsive embed-responsive-16by9">
<iframe class="embed-responsive-item" src="https://www.youtube.com/embed/videoseries?list=PLYCuG6HXKxjQKJTN65LBuvjR92Gnv7Dbs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

## Project 3: Presentations in R Markdown

### Project materials

Project 3 is due on **Apr 13**, and you will have time to work on it in class on Apr 6. You may work in groups or individually. Turn in a zip file with your project along with your name (and any group members, if applicable). You will also need to record a 5-7 minute presentation for this assignment. 

In this project, you'll take the results that you found in Project 2 and turn them into a presentation using R Markdown. My favorite R Markdown presentation tool is [xaringan](https://bookdown.org/yihui/rmarkdown/xaringan.html), but you can use any format you which, such as PowerPoint, as long as it was created in R Markdown. See the [presentations](https://bookdown.org/yihui/rmarkdown/presentations.html) and [reveal](https://bookdown.org/yihui/rmarkdown/revealjs.html) chapters of the R Markdown book for other options.

In addition to creating slides, you'll record a 5-7 presentation of your results for the Tidy Tuesday dataset you chose. Keep it simple: tell us about the dataset, show the figures you produced, and tell us what you learned about the data.

A low-tech way to record your video is via Zoom: start a meeting by yourself, share your slides, and record your session locally, which will record an .mp4 file. You may instead use any other video recording tool you're familiar with. 

If you are working with a group, it's up to you to decide how to divide the work for the presentation.

If your video recording is large, you may want to upload the file to Google Drive, YouTube (as an unlisted video), or some other service, rather than Blackboard. Just let me know where to find it!

*To reiterate, for this project, you need to submit*:
1. A project that contains your R Markdown presentation
2. A video recording of your presentation

In addition to completing the tasks in the assignment, this project must run on my machine. [Use a blank slate](https://rstats.wtf/save-source.html#always-start-r-with-a-blank-slate) and restart your R session regularly, running all of the code to make sure it works correctly. Regularly checking your code with a blank slate will make sure things work as you intend.

You must also use the [Tidyverse code style](https://style.tidyverse.org/). Feel free to use [styler](https://styler.r-lib.org/) to automate this process.
