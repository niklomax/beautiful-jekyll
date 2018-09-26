---
layout: post
title: New Paper in the Journal of Information Technology and Politics
subtitle: Estimating the outcome of UKs referendum on EU membership using e-petition data and machine learning algorithms
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [new paper, brexit, estimates]
---

In this paper published in the Journal of Information Technology and Politics, we use novel e-petition data and machine learning algorithms to estimate the Brexit leave vote percentage for UK parlimentary constituencies.

On 23 June 2016, 52 per cent of the UK population voted in favour of leaving the EU (turnout 72 per cent of registered voters). Results were published for 382 ‘Counting Areas’ (generally the same as local authorities), but not for the 632 Westminster Parliamentary Constituencies (WPCs), the geography at which elected members of Parliament are held to account by their constituents. We argue that having an accurate view of the result for WPCs is hugely important, given that WPCs are the democratic geography of the UK.

Using 8 machine learning algorithms, implemented in the r package carat, we used the known result for aggregations of WPCs to 'learn' what the refferendum result might be, using information from the UK government's e-petition website. We argue that the themes of petitions signed by constituents gives a great deal of insight in to the political sentiment of that area. We then used this to predict a sample of known outcomes. We found that our best performing Cubuist algorythm predicted 97 per cent of the result accurately. Using the method to predict the refferendum outcome for all WPCs in the UK, we compared our results with two other studies which have attempted to do the same thing (using different methods) and found that our results compared favourably to both: a correlation of 0.97 with the estimates produced by [Hanretty](https://www.tandfonline.com/doi/full/10.1080/17457289.2017.1287081) and 0.96 when compared with  estimates produced by [Marriott](https://marriott-stats.com/nigels-blog/brexit-why-leave-won/).

We conclude that e-petition data is an informative and versatile source of information that gauges the political sentiment in a location and argue that machine learning algorithms offer scope for political scientists to gain confirmatory or alternative insight in to a range of problems.

Read the full paper [here](https://www.tandfonline.com/doi/full/10.1080/19331681.2018.1491926) and you can see the slidees from a presentation I gave in Cork [here](https://speakerdeck.com/niklomax/estimation-of-eu-referendum-results-for-westminster-parliamentary-constituencies).
