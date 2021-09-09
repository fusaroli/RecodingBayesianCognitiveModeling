# Recoding  of *Bayesian Cognitive Modeling* by Lee & Wagenmakers in Stan, cmdstanr and BRMS

version 0.1.0
Riccardo Fusaroli

2021-08-02

Michael Lee and EJ Wagenmakers' *Bayesian Cognitive Modeling*  text, (https://bayesmodels.com/), is a common entry to computational cognitive modeling, also thanks to the summer school Lee and Wagenmakers regularly hold in Amsterdam. The book presents code in WinBUG and JAGS. This project is an effort to contextualize the models presented in the book in a more up-to-date Bayesian Workflow relying on Stan. 

The Bayesian Workflow is developed in Michael Betancourt's work - e.g. https://betanalpha.github.io/assets/case_studies/principled_bayesian_workflow.html - as well as in this long paper - https://arxiv.org/abs/2011.01808 - by Andrew Gelman, Aki Vehtari, Daniel Simpson, Charles C. Margossian, Bob Carpenter, Yuling Yao, Lauren Kennedy, Jonah Gabry, Paul-Christian Bürkner, and Martin Modrák. Compared to the Bayesian Cognitive Modeling handbook, the Bayesian workflow insists on more extensive testing of the assumptions implied in the priors and likelihood used, on assessing predictions and whether the models can recover the parameters from simulated data.

Stan is a fast developing probabilistic programming language - https://mc-stan.org/ - with a variety of interfaces. Here I will focus on cmdstanr - https://mc-stan.org/cmdstanr/ - and separately Bürkner’s [**brms**](https://github.com/paul-buerkner/brms).

The project is mostly to allow me to go deeper in my modeling skills with Stan, but it might have some more general usefulness, so here the book with my journey.

## Acknowledgments
This project is largely inspired by Solomon Kurz's generous recoding of statistical books in brms and tidyverse: https://solomonkurz.netlify.app/bookdown/.
My Stan code often relies on  an earlier Stan recoding of the book by Martin Smira. The code is a bit outdated and keeps closer to the original winBUG code, but I've abundantly relied on it to get unstuck.

This repository contains the code and text behind the [Recoding *Bayesian Cognitive Modeling*](FUTURE LINK) book. It was all stitched together using Yihui Xie's [**bookdown** package](https://github.com/rstudio/bookdown). Enjoy.

-`bookdown::render_book("index.Rmd")`


