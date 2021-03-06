---
title: Resources
---

There are a lot of questions and answers on the internet. This page lists resources that I have found useful, so I thought you might find them useful too.

# Starting out with R

Step one: [download R](https://cran.r-project.org) to your appropriate system (Windows, Mac, and Linux).

Step two: [download RStudio](https://www.rstudio.com/products/rstudio/download2/). RStudio has invested a lot of time and money to make using R much, much easier. It's also free!

Step three: [Read R for Data Science](https://r4ds.had.co.nz/). This is a great guide written by Hadley Wickham and Garrett Grolemund It introduces the principles of the [`tidyverse`](https://tidyverse.org/) - a set of R packages that play really well together. They cover tools to data reading in/out, manipulate data, perform data visualisation, and tools for modelling, summarising models, and communiating results.

If you are having problems with getting R or RStudio, check out [this guide](https://github.com/fawda123/swmp_installR/blob/master/R_install_guide.pdf), from [this person (can't find their name on their website )](https://beckmw.wordpress.com/2014/09/28/back-to-square-one-r-and-rstudio-installation/). It covers installing R and RStudio in a little more detail.

# Learning and Troubleshooting with R

To learn R, you need to learn [how to get unstuck with R](https://stat545.com/help-general.html). This teaches you a really good process to iterate through when going through the process of getting unstuck.

To learn a new function or package, [Quick-R](https://www.statmethods.net), provides nice quick description of functions and other R-related things.

For all my other problems, I usually google the error message, or try my darndest to ask an reasonable question to google that describes my current dilemna, and then look read the appropriate blog post, or [StackOVerflow Answer](https://stackoverflow.com). [RSeek](https://rseek.org/) is also basically a google search that filters by R related content. 

A new community really worth checking out is [the RStudio community](https://community.rstudio.com/), which aims to provide a nice, friendly space to ask questions that don't necessarily fit into GitHub issues, bug reports, or Stack Overflow. You can read more about it here in [their announcement of the community](https://blog.rstudio.com/2017/09/14/rstudio-community/).

I would also recommend checking out RStudio's [list of resources for learning R](https://www.rstudio.com/resources/training/online-learning/#R), and [this blog post](https://www3.nd.edu/~mclark19/projects.html), which describes learning R from a social sciences background.

To stay up to date with what other people around the world are doing with R, I recommend checking up on [r-bloggers](r-bloggers.com) every other day, and checking out the [#rstats](https://twitter.com/search?q=%23rstats&src=tyah) hashtag on twitter. The R and statistics community on twitter is both excellent and friendly.
 
# Learning Advanced R

Got a basic handle on R and are hankering for more? I recommend these free, online books by [Hadley Wickham](https://hadley.nz/):

- [Advanced R Programming](https://adv-r.had.co.nz">Advanced R Programming)

- [R Packages](https://r-pkgs.had.co.nz"), and

There is also a book, [Ramarro](https://www.quantide.com/R/r-training/r-web-books/ramarro-r-for-developers), by quantide which seems similar(ish) to Hadley's books.

# Advanced R stuff: S3 Classes

R's S3 classes are this really awesome minimal class of functions that can be super handy in R. They are described nicely in Hadley's book, but I have also found these to be helpful:

- [This R Book](https://www.cyclismo.org/tutorial/R/s3Classes.html)

- [This blog post](https://abhishek-tiwari.com/hacking/class-and-objects-in-r-s3-style), which also has such a suave blog layout.

- [This video by Andrew Robinson](https://www.youtube.com/watch?v=VZkD7DXQ-fk&amp;feature=g-upl). Sides available [here](https://files.meetup.com/1685538/presentation.pdf). Thanks to [https://damjan.vukcevic.net/](Damjan Vukcevic) for this information.

I have also written a [blog post](https://www.njtierney.com/r/missing%20data/rbloggers/2016/11/06/simple-s3-methods/) about S3 methods, and have a [preprint on arxiv](https://arxiv.org/abs/1608.07161).

# Data Visualisation

`ggplot2`

If you are going to do a plot in R, it should be in ggplot. It takes about 5 minutes to get the hang of, and once you've got it down you can create plots that make sense, behave how you expect, and look fantastic.

ggplot follows a logical syntax adapted from the book "The Grammar of Graphics". It makes visualisation make sense. And there are lots of other packages that build upon it to make it more awesome, such as [GGally](https://ggobi.github.io/ggally/), [ggalt](https://github.com/hrbrmstr/ggalt), [ggExtra](https://cran.r-project.org/web/packages/ggExtra/index.html), [ggforce](https://cran.r-project.org/web/packages/ggforce/index.html), [gganimate](https://github.com/dgrtwo/gganimate), and [ggbeeswarm](https://cran.r-project.org/web/packages/ggbeeswarm/index.html), to name a few!

Here are some ggplot resources in order of usefulness

- The [RStudio ggplot cheatsheet](https://www.rstudio.com/wp-content/uploads/2015/05/ggplot2-cheatsheet.pdf) sits pinned up above my desk.
- [The official documentation](docs.ggplot2.org/current)
- [The R Graphics Cookbook](https://www.cookbook-r.com/Graphs/) usually has the answers for what I'm after.
- I also recently discovered the [ggplot2 wiki](https://github.com/hadley/ggplot2/wiki), which has some great case studies and examples.
- [This handout](https://www.ceb-institute.org/bbs/wp-content/uploads/2011/09/handout_ggplot2.pdf) provides an introduction to ggplot.

# plotly

Plotly for R, written and maintained by [Carson Sievert](https://cpsievert.github.io), is a very powerful and flexible interactive plotting engine in R. It has a fully fledged API for writing interactive graphics in R, as well as a fantastic function that gives the user a lot for free: `ggplotly`. You can read more about plotly for R in Carson's [free and online book](https://cpsievert.github.io/plotly_book/).

# ggvis

ggvis is another great package written by Hadley Wickham, which builds upon the structure of ggplot but it allows for more interactive, reactive, plot building. Examples can be found [here](https://ggvis.rstudio.com/0.1/quick-examples.html) [here](https://ggvis.rstudio.com/ggvis-basics.html), and [here](https://ggvis.rstudio.com/cookbook.html).

More serious development on ggvis will apparently begin in 2018, as Hadley and his team at RStudio will be spending 2017 to make the everything in the tidyverse work well together. For the moment I would recommend using plotly to do your interactive graphics, although ggvis is still great!

# Shiny

shiny is a really awesome way to enhance your R script, package, or method. Shiny turns these into 'apps', that people can interact with.

- [shiny](https://shiny.rstudio.com/tutorial) tutorial
- [shiny cheatsheet](https://shiny.rstudio.com/articles/cheatsheet.html)
- [super awesome example](https://shiny.rstudio.com/gallery) here


# Data Manipulation

- Use [dplyr](https://github.com/hadley/dplyr) to manipulate data in R. [Here is a helpful lesson](https://www.dataschool.io/dplyr-tutorial-for-faster-data-manipulation-in-r)
- Use [tidyr](https://github.com/hadley/tidyr) to change the data format; gathering data into long format, and spreading them into wide format, etc. It also has heaps of other little handy tools, like `tidyr::replace_na`.
- Use [broom](https://github.com/dgrtwo/broom#broom-lets-tidy-up-a-bit) to create **tidy dataframes** of statistical models. [Here is a helpful lesson](https://127.0.0.1:22465/session/Rvig.15c681ac18b1d.html)

# R Webinars

The [RStudio webinars](https://github.com/rstudio/webinars) page is in my opinion an untapped resource of the R community! 

# Reproducible Reporting

Probably the coolest thing ever. `knitr` is this amazing package that allows the user to combine their code and document text, making research easier to reproduce, and it does this while looking slick and classy. The idea is essentially to let the human do the writing, and the computer handle displaying the results, so that reports can be easily constructed, and most importantly, reproduced easily.

Check out some really nice guides [here](https://rmarkdown.rstudio.com/) and [here](https://rmarkdown.rstudio.com/html_document_format.html), and from the awesome dude who created knitr [here](https://yihui.name/knitr/).

You can also augment your rmarkdown documents with [templates](https://rmarkdown.rstudio.com/developer_document_templates.html). For example -  [rticles](https://github.com/rstudio/rticles) which is an r package that adds loads of rmarkdown templates. Currently, there are templates for the R Journal, the UseR Conference, Journal of Statistical Software, PLoS Computational Biology, and more!


# Learning Statistics Using R

If you want to learn statistics using R, check out [this website](https://www.dataschool.io/15-hours-of-expert-machine-learning-videos) containing 15 hours of an applied R statistics course from Stanford. They also have an [excellent (and free!) book](https://www-bcf.usc.edu/~gareth/ISL/).

# Decision Trees

I use decision trees a lot in R, and I even [wrote a little package](https://github.com/njtierney/treezy) that helps take care of some common tasks in interrogating decision trees. Here are a list of resources that I recommend using to learn about them:

- [This book from James et al](https://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf) - chapter 8 specifically refers to decision trees. They've also made the book free! Also [their videos](https://www.youtube.com/playlist?list=PL5-da3qGB5IB23TLuA8ZgVGC8hV8ZAdGh) on decision trees are very useful. You can find a comprehensive list of all their videos and material at [this website](https://www.dataschool.io/15-hours-of-expert-machine-learning-videos)	

- This [book chapter](https://mason.gmu.edu/~csutton/vt6.pdf) from the Handbook of Statistics is broad and general.

- This [page](https://architects.dzone.com/articles/regression-tree-using-gini%E2%80%99s) helps explain regression trees. Their [gif](https://f.hypotheses.org/wp-content/blogs.dir/253/files/2013/01/gini-x1x2-x1-b.gif) demonstrating how decision trees choose splitting values is also really helpful.

- [This video on](https://www.statsoft.com/Textbook/Boosting-Trees-Regression-Classification) introduction to boosting trees for regression and classification by statsoft.

# Using R for Spatial Data Wrangling, Analysis, and Visualisation.

Spatial data analysis can be really different to anything else that you've done in R. Well, it was for me. Fortunately, [recent awesome progress](https://www.r-consortium.org/blog/2017/01/03/simple-features-now-on-cran) has been made on the simple features R package, officially supported by the RConsortium, and authored by [Edzer Pebesma](https://github.com/edzer). The format of simple features is to adopt a standard dataframe format, where every row is a spatial feature, and the spatial features are described in a geometry list column. This is really fantastic, because it means that (for the most part), working with spatial data is very similar to working with regular dataframes, which is the bread and butter of analysis and data wrangling in R. 

In particular, simple features is designed to play nicely with [the tidyverse](https://tidyverse.org/), and accordingly plays well with ggplot2, dplyr, purrr, and so on. It's amazing. 

Here is a list of resources on using spatial data in R:

- The [R Spatial Blog](https://r-spatial.org/) is a great way to stay updated with the latest changes in simple features.

- [A blog post by Matt Strimas-Mackey](https://strimas.com/r/tidy-sf/) on how to use simple features with dplyr, tidyr, and ggplot2.

- [Mapping France at night](https://sharpsightlabs.com/blog/mapping-france-night/)

- [Spatial Pipelines](https://walkerke.github.io/2016/12/spatial-pipelines/)

- [Simple Features Vignettes](https://edzer.github.io/sfr/articles/)

- [Using simple features with ggraph](https://rpubs.com/cyclemumner/sf-ggraph)

- [A comparison of plotting in sp compared to sf](https://rpubs.com/cyclemumner/sf-plotting)

- [Geocomputation with R (a book)](https://geocompr.robinlovelace.net/)

- [The R Task View on Spatial Data](https://cran.r-project.org/web/views/Spatial.html)

- [Introduction to GIS with R](https://www.jessesadler.com/post/gis-with-r-intro/)

- [Steph de Silva-Stammel's blog post on resources for geospatial data and transport](https://www.stephdesilva.com/post/the-keys-to-the-kingdom/)

- [The `tmap` package provides a great rich way to build static and interactive spatial plots in a layered approach similar to ggplot2](https://github.com/mtennekes/tmap)

- [The `mapview` package provides functions to very quickly and conveniently create interactive visualisations of spatial data.](https://r-spatial.github.io/mapview/)

For more thoughts on R for spatial data analysis:

- [Michael Sumner's overview](https://mdsumner.github.io/2017/01/10/spatial-r-2017.html) of R's spatial capabilities for 2017.

For interactive visualisation of spatial data, I really like RStudio's [leaflet](https://rstudio.github.io/leaflet/), which is a port of the excellent [JavaScript leaflet library](https://leafletjs.com/) is my go to place. 

[ggmap](https://cran.r-project.org/web/packages/ggmap), is also great, as it produces static maps.

# git

If you write code or plain text (LaTeX, RMarkdown, Markdown, R, c++ or even .txt), you should really consider using git to help manage your workflow. It's like Dropbox on steriod.

To get started I would recommend 2 things to get started:

1. Read Jenny Bryan's awesome book, [Happy git with R](https://happygitwithr.com/).

2. [Download GitKraken](https://www.gitkraken.com/), it's the best free GUI for interacting with git.

Some other great resources include:

- [these slides](https://slides.com/michaelfreeman/git-collaboration#/1)
- [git - the simple guide](https://rogerdudler.github.io/git-guide/)
- [oh shit, git!](https://ohshitgit.com/)

I would also really recommend reading an article by [Karthik Ram](https://inundata.org/), ["Git can facilitate greater reproducibility and increased transparency in science"](https://scfbm.biomedcentral.com/track/pdf/10.1186/1751-0473-8-7?site=scfbm.biomedcentral.com).

# STATA Related Resources

STATA do a great job of explaining multilevel and hierarchical models on their blog. I found these two blogs and video really helpful:

- [Blog part 1](https://blog.stata.com/2013/02/04/multilevel-linear-models-in-stata-part-1-components-of-variance/)

- [Blog part 2](https://blog.stata.com/tag/multilevel-models/)

-  [Video](https://www.youtube.com/watch?v=rUWT_EWV6QI)

# Typography

Just as it is important to have strong data visualisation skills, it is important to understand what makes a good looking document, poster, business card, and whatnot. To this end, you should read [typography in ten minutes](https://practicaltypography.com/typography-in-ten-minutes.html), and the [summary of key rules of typography](https://practicaltypography.com/summary-of-key-rules.html). One day I will purchase some fonts to pay him back.

<!-- # Blogs I like 

Of course, there is [r-bloggers]()
 -->
