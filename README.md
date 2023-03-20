# get-betteR
"Life is growth. If we stop growing, technically and spiritually, we are as good as dead."  -Morihei Ueshiba

A curated list of links, references, web-books and conference slides for anything and everything around R and R Shiny. 

---

# Books

- R Programming for Data Science by Roger D. Peng (2022-05-31) {[book](https://bookdown.org/rdpeng/rprogdatascience/)}
- R (BGU course) by Jonathan D. Rosenblatt (2019-10-10) {[book](https://www.john-ros.com/Rcourse/)}


# Coding Standards

- A debugging manifesto by [Julia Evans](https://github.com/jvns) {[website](https://jvns.ca/blog/2022/12/08/a-debugging-manifesto/)}
- New zine: The Pocket Guide to Debugging by [Julia Evans](https://github.com/jvns) {[website](https://jvns.ca/blog/2022/12/21/new-zine--the-pocket-guide-to-debugging/)}


# Conference Slides

## ShinyConf 2023 by Appsilion

- How to Quickly Build a Production-Ready Real World Data Dashboard? by Kamil Wais {Roche} {[slides](https://drive.google.com/file/d/1K4gMi4jNhquR4qZM-CIOfzUGMUkFOcGS/view)}


# Links & Reference


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

# Misc Reference

- Markdown cheatsheet {[github](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#hr)}
