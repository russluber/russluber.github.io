---
layout: page
title: Project Scrapyard
description: Estimating the Striking Accuracy of UFC Fighters
img: assets/img/latent_acc_dist.png
importance: 2
category: work
related_publications: false
---

In this project, I analyzed UFC fight data to estimate how accurate each fighter is on average across their respective careers. 

To do this, I built a Bayesian multi-level logistic regression model, accounting for different sources of uncertainty about fighters' striking accuracy like gender, weight class, and fight-to-fight randomness.

Here's some of the plots I made for this project:

![Latent striking accuracy distribution]({{'/assets/img/latent_acc_dist.png' | relative_url}}){: .center width="720"}

![Top 10 Credible Interval]({{'/assets/img/top10_ci_plot.png' | relative_url}}){: .center width="720"}

You can find the GitHub repo [here](https://github.com/russluber/project-scrapyard).

<hr>