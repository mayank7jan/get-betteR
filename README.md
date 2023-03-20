# get-betteR
"Life is growth. If we stop growing, technically and spiritually, we are as good as dead."  -Morihei Ueshiba

A curated list of links, references, web-books and conference slides for anything and everything around R and R Shiny. 

---

# Books

- *Advanced R* by [Hadley Wickham](https://hadley.nz/) {[book](https://adv-r.hadley.nz/)}  
  - *Advanced R Solutions* by Malte Grosser, Henning Bumann and Hadley Wickham {[solutions](https://advanced-r-solutions.rbind.io/)}
  - 1 version {[book](http://adv-r.had.co.nz/)} {[solutions](https://advanced-r-solutions-ed1.netlify.app/)}
- *R for Data Science* by [Hadley Wickham](https://hadley.nz/) and Garrett Grolemund {[book](https://https://r4ds.had.co.nz/)}  
  - 2e version (still in development) {[book](https://r4ds.hadley.nz/)}
- *R packages (2e)* by [Hadley Wickham](https://hadley.nz/) and [Jenny Bryan](http://jennybryan.org/) {[book](https://r-pkgs.org/)}  
- *R Programming for Data Science* by Roger D. Peng (2022-05-31) {[book](https://bookdown.org/rdpeng/rprogdatascience/)}
- *R (BGU course)* by Jonathan D. Rosenblatt (2019-10-10) {[book](https://www.john-ros.com/Rcourse/)}
- *Github actions with R* by Chris Brown, Murray Cadzow, Paula A Martinez, Rhydwyn McGuire, David Neuzerling, David Wilkinson, Saras Windecker (2021-04-09) {[book](https://orchid00.github.io/actions_sandbox/)}

# Coding Standards

- A debugging manifesto by [Julia Evans](https://github.com/jvns) {[website](https://jvns.ca/blog/2022/12/08/a-debugging-manifesto/)}
- New zine: The Pocket Guide to Debugging by [Julia Evans](https://github.com/jvns) {[website](https://jvns.ca/blog/2022/12/21/new-zine--the-pocket-guide-to-debugging/)}


# Conference Slides

## ShinyConf 2023 by Appsilion

- How to Quickly Build a Production-Ready Real World Data Dashboard? by Kamil Wais {Roche} {[slides](https://drive.google.com/file/d/1K4gMi4jNhquR4qZM-CIOfzUGMUkFOcGS/view)}
- Taking Flight with Shiny: A Modules-First Learning Approach by [Emily Riederer](https://github.com/emilyriederer) {[slides](https://docs.google.com/presentation/d/1mCnBpClhIV82z4PnfdsfDTii9g2O5uspXVI2R3hw6C8/edit#slide=id.g205314064bf_0_52)}
- Sharing app state between modules by [Marcin Dubel](https://github.com/mdubel) {[slides](https://docs.google.com/presentation/d/13___ZiOO1aEv0xiCj2TAm2JenEdy_Sfy6SEIWAltAYI/edit#slide=id.g216fe8fbc25_0_71)}
- How to build user-centric applications? by [Anna Skrzydlo](https://github.com/aniaskrzydlo) {[slides](https://docs.google.com/presentation/d/1rPYctMwhr99efkF_Nkgxzmb27O4v37C8M3sVQg1lmZ0/edit#slide=id.g214f1d58d84_0_0)}
- Finding #RStats resources with Shiny and **GitHub Actions** by [Nicola Rennie](https://github.com/nrennie) {[portfolio](https://nrennie.rbind.io/)} {[slides](https://nrennie.rbind.io/talks/appsilon-shinyconf-github-actions/slides.html#/title-slide)}
- Debugging Shiny Apps by [Tan Ho](https://tanho.ca/) {[slides](https://docs.google.com/presentation/d/1yuV8wkcsnclF_mQACuR1Fesd8E4A3RrQpmpOruPbzVA/edit#slide=id.p)} {[github repo](https://github.com/tanho63/shinyconf_debugging)}
- *Towards the next generation of Shiny UI* a.k.a. *How to make a dashboard with {bslib}* by [Carson Sievert](https://github.com/cpsievert) {[slides](https://talks.cpsievert.me/20230317/#/towards-the-next-generation-of-shiny-ui)}

# Data Science Hangout by RStudio (now Posit) {[website](https://posit.co/)}

Currently organized by [Rachael Dempsey](https://www.rstudio.com/authors/rachael-dempsey/) {2022-2023}

# R packages

## R Shiny

- `shinymeta` : Record and expose Shiny app logic using metaprogramming {[website](https://rstudio.github.io/shinymeta)} {[github](https://github.com/rstudio/shinymeta)}
- `histoslider` : histogram slider input for Shiny {[github](https://github.com/cpsievert/histoslider)}

## R Advanced - CI/CD, DevOps, MLOps

- `r-lib/actions` : GitHub Actions for the R community {[github](https://github.com/r-lib/actions)}
- `shinycoreci`: Application-level tools to perfrom manual and automated tests for Shiny apps {[website](https://rstudio.github.io/shinycoreci/)} {[github](https://github.com/rstudio/shinycoreci)}


## R development

- `tidyverse/reprex` : Render bits of R code for sharing, e.g., on GitHub or StackOverflow. {[website](https://reprex.tidyverse.org/)} {[github](https://github.com/tidyverse/reprex/)}



---

# Level Up

## Aynchronous programming

- Futureverse {[website](https://www.futureverse.org/)} - future {[github](https://github.com/HenrikBengtsson/future)} {[website](https://future.futureverse.org/)} and promises {[github](https://github.com/rstudio/promises/)} {[website](https://rstudio.github.io/promises/)}
  - A future is an abstraction for a value that may be available at some point in the future. The state of a future can either be unresolved or resolved
  - A future always returns a promise. It stores the state of a future to be evaluated later in the r shiny workflow.  
- callr {[github](https://github.com/r-lib/callr)} - Perform a computation in a separate R process, without affecting the current R process at all.
- Parallelization: 
  - parallelly: Enhancing the 'parallel' Package {[github](https://github.com/HenrikBengtsson/parallelly)}
  - ParallelLogger: Support for parallel computation with progress bar, and option to stop or proceed on errors {[github](https://github.com/OHDSI/ParallelLogger)}
  - Reference reads 
    - R Programming for Data Science - Parallel Computation {[book](https://bookdown.org/rdpeng/rprogdatascience/parallel-computation.html)}
    - R (BGU course) - Parallel Computing {[book](https://www.john-ros.com/Rcourse/parallel.html)}
    - Quick Intro to Parallel Computing in R by Matt Jones {[blog](https://nceas.github.io/oss-lessons/parallel-computing-in-r/parallel-computing-in-r.html)}
    - Parallelized loops with R {[blog](https://www.blasbenito.com/post/02_parallelizing_loops_with_r/)}
- coro {[github](https://github.com/r-lib/coro)} - Implements coroutines for R, i.e. functions that can be suspended and resumed later on


---

# Links & Reference


## R Shiny Applications

### R in Pharma 

- RISK ASSESSMENT APPLICATION - {[app](https://rinpharma.shinyapps.io/risk_assessment/)}


## Misc Reference

- Markdown cheatsheet {[github](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#hr)}
- Bootstrap : Powerful, extensible, and feature-packed frontend toolkit. Build and customize with Sass, utilize prebuilt grid system and components, and bring projects to life with powerful JavaScript plugins. {[website](https://getbootstrap.com/)}
- Bootswatch : free themes for Bootstrap {[website](https://bootswatch.com/)} {[github](https://github.com/thomaspark/bootswatch/)}
  - Lux {[website](https://bootswatch.com/lux/)}
- App wireframe
  - draw.io {[website](https://app.diagrams.net/)} {[alternate website](https://draw.io)}
  - Excalidraw {[website](https://excalidraw.com/)}

{[]()}
