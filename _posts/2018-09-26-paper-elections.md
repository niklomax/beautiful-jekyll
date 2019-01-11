---
layout: post
title: New Paper in the Journal of Information Technology and Politics
subtitle: Estimating the outcome of UKs referendum on EU membership using e-petition data and machine learning algorithms
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [new paper, brexit, estimates]
---

In our [paper](https://www.tandfonline.com/doi/full/10.1080/19331681.2018.1491926) *Estimating the outcome of UKs referendum on EU membership using e-petition data and machine learning algorithms* recently published in the Journal of Information Technology and Politics, we use novel e-petition data and machine learning algorithms to estimate the Brexit leave vote percentage for UK parliamentary constituencies.

On 23 June 2016, 52 per cent of the UK population voted in favour of leaving the EU (turnout 72 per cent of registered voters). Results were published for 382 ‘Counting Areas’ (generally the same as local authorities), but not for the 632 Westminster Parliamentary Constituencies, the geography at which elected members of Parliament are held to account by their constituents. In this paper, we argue that having an accurate view of the result for Constituencies is hugely important, given that they are the democratic geography of the UK.

Using a diverse range of eight machine learning algorithms, implemented via the R package carat, we used the known result for aggregations of Constituencies and Counting areas to ‘learn’ what the referendum result might be, using information from the UK government’s [e-petition](https://petition.parliament.uk/) website. Anyone can set up an e-petition, relating to any topic they choose, and the petition can be signed online by members of the public. The government will respond to any e-petition that receives over 10,000 signatories, while those that receive over 100,000 signatories are additionally considered for debate in Parliament. We argue that the themes of petitions signed by constituents gives a great deal of insight in to the political sentiment of that area.

We then used these learned results to predict a sample of known outcomes. We found that our best performing Cubist algorithm correlated at the 97% level with the known results. Using the method to predict the referendum outcome for all Constituencies in the UK, we compared our results with two other studies which have attempted to do the same thing (using different methods) and found that our results compared favourably to both: a correlation of 97% with the estimates produced by Chris [Hanretty](https://www.tandfonline.com/doi/full/10.1080/17457289.2017.1287081) and 96% when compared with estimates produced by Nigel [Marriott](https://marriott-stats.com/nigels-blog/brexit-why-leave-won/).

This is not the only work we have done with these e-petitions data. In a [paper](https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-017-0113-9) published in EPJ Data Sciencelast year, we mapped voter sentiment by creating a classification of Westminster Parliamentary Constituencies. We find there are four distinct clusters: Domestic Liberals; International Liberals; Nostalgic Brits and those with Rural Concerns. By focusing on the topics of the petitions signed within each Constituency, we provide insight in to the views which shape political debate, for example the two liberal clusters were generally more anti-Brexit while the Nostalgic Brits and Rural Concerns were far more conservative in their views.

From our work to date, we conclude that e-petition data is an informative and versatile source of information that allows us to gauge political sentiment in a given location. We argue that machine learning algorithms offer scope for researchers to gain confirmatory or alternative insight in to a range of problems. 

Read the full paper [here](https://www.tandfonline.com/doi/full/10.1080/19331681.2018.1491926) and you can see the slides from a presentation I gave BSPS in Winchester [here](https://speakerdeck.com/niklomax/estimation-of-eu-referendum-results-for-westminster-parliamentary-constituencies).
