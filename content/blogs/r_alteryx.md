---
categories:
- ""
- ""
date: "2017-10-31T22:42:51-05:00"
description: ""
draft: false
image: r_alteryx.png
keywords: ""
slug: r_alteryx
title: R or Alteryx?
---

Having worked for about 4 year with Alteryx to do Data Science tasks, exploring R definitely took me out of my comfort zone. And by doing that, it is inevitable that some comparisons were made.

First and foremost, Alteryx is much more intuitive than R. A drag and dropping, no-code/low-code platform is much more user-friendly than raw coding in R-Studio, no matter how intimidating you think coding is. However, R is more flexible in what you can do, even though all functionalities we used during the class can be replicated in Alteryx. Actually, many of Alteryx's tools are programmed in R in the background, so the way you work with the data is similar in many ways. For example, the Summarize tool in Alteryx relies on the same syntax as the summarize function in R, using group by, means, standard deviations, so on and so forth.

One dimension that R definitely stands out is data visualization. Alteryx weakness is data visualization, it is not meant to that (besides geospatial reporting). R ggplot is versatile, easy to use and offers a nice looking. Alteryx reports are ugly and inflexible. 

Alteryx's workflows are very use to replicate and adapt, and the same can be done with pieces of R code. Alteryx allows you to build macros, that work similarly to R functions, i.e., you can call them in other workflows/codes.

Machine learning tools in Alteryx come pre built-in, and are very easy to use. R requires many steps between defining the model, creating a recipe and running it. Even though R offers more flexibility if you dominate the modeling process, Alteryx offers a fair amount of hyperparameters and tunning options.

To conclude, Alteryx has a native tool that allows you to insert a piece of R code into it, and it become another block in your workflow that you can connect up and downstream. So why not use both combined to extract what each of them has to offer as their best?
