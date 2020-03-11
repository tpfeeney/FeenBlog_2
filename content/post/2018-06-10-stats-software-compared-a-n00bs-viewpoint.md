---
title: 'Stats software compared: A n00bs Viewpoint'
author: TF
date: '2018-06-10'
slug: stats-software-compared-a-n00bs-viewpoint
categories: []
tags: ["r", "sas", "stata", "software"]
header:
  caption: ''
  image: ''
---


While in my MPH training I had the opportunity to use (in class) both Stata and SAS. They were both great, but it became apparent during that time that serious stat were done with R. Further, visualizations that I saw from R packages like ggplot were just so much prettier than anything I saw in SAS or Stata. 

There were no specific classes to learn R during my MPH, but I was able to teach myself by taking free online class, googling answer, and just experimenting with my data and comparing it to other software I already knew. It wasnt easy, but it has been worth it. 

Through this time I have developed a very strong position on the different stats packages and I thought I would go through my thoughts on them now. In short, R is the best, Stata is OK, and SAS should just be avoided.

Stata: this was the first stats program I was exposed to, and it was used to help me learn basic biostatistics. It is a good package. It is really easy to learn, particularly for someone without any programming background (like myself). The interface is instuitive, running tests and regressions are strightforward and tend to use natural language syntax instead of more complex syntax of SAS and R. Oh, and it allows for additional pakcages to be added on. I have use these packages for things like multiple testing adjustments and graphing quantile regression output. In essence Stata offers simple straightforward analysis that is advanced, easy to get going in, and with at least some upgradability.

SAS. Oh SAS. How I hate thee. I understand that there was a time when SAS was THE SOFTWARE to use to analyze data. R wasnt nearly as developed, Stata didnt exist, and doing things by hand wasnt really an option. So, I understand why previous generations used it, and since they have all this experience with it they continue to hold on. BUT, times have changed, and for a newcomer SAS is terrible. First, its hard as hell to get a hold of. You can get a free education version, but that is severely limited. It isnt native to a unix environment, so those with linux and macs need to virtualize, and it is EXPENSIVE. Couple these "features" with its steep learning curve, and you have a conflagration of awful. I remember how hard it was to learn SAS AND learn regression--it was atrocious. The learning curve is just too high for minimal payoff above Stata. If you are going to sacrifice ease of use you might as well just use R.

R is an open source (read: free) software package built for data analysis. It is by no means easy to use; far from it in fact. The learning curve is steep, which is similar to SAS. BUT, R is infinitely expandable and VERY powerful. Not to mention it comes with a huge community of users that are helpful, great visualization packages, and tha ability to actually program your own additional functions. Moreover, it can be used for more than just data analysis. I am writing this blog using R and it is a wonderful experience. Last, a feature of R that is often overlooked is that it FORCES you to know what you are doing. In stata, things happen behind the scenes and outputs are given to you without much user thought. For instance, after running a regression you can use the postestimation command: lroc, and voila' you get a ROC with a calculated AUROC. It's nice and convenient, but in R you have to do a bit more. You have to run the regression, and then understand that you need to predict the output for each individual and then compare that to the actual outcome in the individual to get and ROC. In that way R teaches while you perform functions, because there is more to success than a simple command.

In the end, getting away from SAS will be benefitial for everyone. Start and stick with Stata, and learn R if you want to do more and be even better, but dont even bother with SAS since the cost effectivness of what you can do given time to learn is just not worth it. I have made a little table below to summarize my opinions.



Feature   |   Stata   |   SAS   |   R
----------|-----------|---------|---------
Expense|high|high| FREE
Learning Curve|low|high|very high
Expandibility|moderate  |low  |very high
Power|moderate|high|very high

