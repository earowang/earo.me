+++
date = "2012-12-28T00:00:00"
draft = false
tags = ["book", "data"]
title = "Data Analysis, From Numbers To Insights"
summary = """
A couple of thoughts on "data analysis with open source tools".
"""
math = false
+++

For good or ill, we crossed the end of the world predicted by Mayans and were pushed back to a tough world. It's time to move forward.  

> Data analysis, as I understand it, is not a fixed set of techniques. It is a way of life, and it has a name: curiosity. There is always something else to find out and something more to learn.  

> Remember: The purpose of computing is insight, not pictures. (L.N.Trefethen)  

> Simple is better than complex.  
> Explicit is better than opaque.  
> Insight is more important than precision.  
> Understanding is more important than technique.  
> Think more, work less.  

All quotations above come from a book named ["Data analysis with open source tools"](http://www.amazon.com/Data-Analysis-Open-Source-Tools/dp/0596802358) by Philipp K. Janert, which is the first book on data analysis offering readers some general and valuable guidances whilst dealing with data. Strictly speaking, it's not going to be a book review but to develop my own wildest understanding of data analysis, I might add, from an amateur's point of view.  

**Big data** has been one of the most heated topics for recent years. I recalled the first time I've heard about big data was the year of 2011 when McKinsey published a [report](http://www.mckinsey.com/Insights/MGI/Research/Technology_and_Innovation/Big_data_The_next_frontier_for_innovation) to remind management either in public sector or in corporate domain of the coming era. Big data, by definition, refers to mountains of datasets with increasing capacity of servers and is getting bigger and bigger as a result of its potential value. According to McKinsey, the company that is able to take full advantage of data will succeed in pleasing customers and making tremendous profits. So there's a war on and curiosity is the best weapon we can bring into this invisible war, for data is mere appearance and the forces driving it do lure us. As if we were peeling onions, we ought to analyze data until it has nothing left. This is what we call it **"Curiosity"** as the first quotation mentioned. No one can stop us questioning except ourselves and the root reasons are the solitary goal. Keep in mind that the more curious we are, the further we go along this way.

## Assumption

Where there's self-interest, there's an incentive; where there's an incentive, there's an act; where there's an act, there's a trace; where there's a trace, there's a pattern. If there's a pattern, it can be predictive.

## Part 1: Preparation: tidying up data

Each of data analysts would appreciate if they were given perfect datasets excluding missing values and messy encoding. On the contrary, industries are filled with a variety of unbearably abnormal data. I often suspect if I'll be well capable of modeling in a company at the completion of my undergraduate degree. Because students have least concern about datasets that have been already sorted out and never hesitate to start modeling. I'm not complaining about our course structure but I'm quite aware of the fact we get one thing done at a time, since programming skill involves the preparation of data. Philipp suggests it's beneficial for analysts to master some scripting languages such as Python and Perl and even Linux commands at the appendix of the book and I think it's partly due to naughty data. Another book ["Bad data handbook"](http://www.amazon.com/Bad-Data-Handbook-Cleaning-Back/dp/1449321887) touches on modern wisdom of beating bad data shared by a dozen of experts from different realms for readers wanting detailed information.

## Part 2: Graphics: looking at data

The best way to grasp a general picture of data is visualizing it. It makes no sense to stare at individual numbers for long. Insights start with graphs which lead us to see how one variable responds to others, linear or non-linear, positively or negatively. Histogram, kernel density function and cumulative density function are most suited to a single variable, as shapes and distributions are of interest. As for bivariate analysis, scatter plot is the best choice to obtain the relationship and for multivariate analysis, multi-plots or false-color plots are to be selected. Ahead of modeling, graphs are meant to help us find a clue of where we start and which method we pick, like painters sketch in pencils before painting in brushes. In particular, outliers can be easily found out in a graph, which are about to get us into troubles. Intuition linked with scientific diagrams is more likely to convince people.

## Part 3: Analytics: modeling data

Modeling plays CPU role in concentrating on processing, if you think of preparation and graphics as inputs. We come to the most existing part full of roughly awakening moments. The reason for that is we keep doing trial and error before the model is best fitted to actual data. Graphs initiate some vague ideas but models related to statistics require accuracy and precision. In other words, assuming a case is known to follow Poisson distribution, the single parameter $\lambda$ still needs to be figured out. The essence behind modeling is we calculate probability based on datasets to get estimation and then derive statistics to forecast. From uncertainty to uncertainty. Through it, we have the closest look at correlations and develop insights into how the system works.

## Part 4: Applications: using data

The full circle of data analysis ends up with transformation. At a regular conference, we confidently present our work with clear interpretation and beautiful visualization to management. They may ask "So what's it for? We all know what happened in the past." at the end of presentation. We are not only historians but also fortune tellers. What a high standard! After all, decisions stemmed from the model are the only way to prove it right or wrong. Application is indeed the hardest part. Datasets generated from a specific field don't seem isolated from the business context, otherwise they are absolutely random. We should be trained with strong business knowledge relevant to the field where we're working so as not to get the model far away from the fact. I believe, this is also an indicator of professionalism. Although we master the mechanism, there are variations or even structural breaks beyond the observation. Insightful analysts live with luck.

**Happy New Year!**
