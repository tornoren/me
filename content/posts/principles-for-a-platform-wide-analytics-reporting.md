+++
draft = false
date = 2022-04-25T05:08:21+01:00
title = "Principles for a platform-wide analytics reporting"
slug = "principles-for-a-platform-wide-analytics-reporting"
aliases = ["/blogg/principles-for-a-platform-wide-analytics-reporting"]
tags = []
categories = []
+++
A platform in this context refers to a group of sites that share important characteristics. 

Important questions include: 

* Who are the users? 
* What do they need? 

If we have several user groups, we should prioritize and make choices. Which one is more important? And can we help all of them?  

We should also take note of their needs today as well as make projections for the future.   

Drawing on the [previous post](/posts/three-ground-rules-for-your-analytics) I put forward that our data should tell us our state, our direction and provide us with the ability to extract sense from vast quantity of data. 

From the vantage point of the biggest user group, the reporting should provide a quick overview of the most important metrics today as well as indicate the trends to let us assess the direction we are going. 

Easy.

From the platform perspective the reporting should let us quickly navigate from the whole via the subgroup to the relevant site. We should combine numbers and present and aggregated view or views - if we have several subgroups of sites. 

The setup should also allow for quickly imlementing more advanced measurements, i.e. *events*, that can be pushed to the entire collection of sites, a subgroup or just one of them. 

Moreover, reporting should be easily pushed to production platform-wide.

Not everyone finds beauty in numbers. To help people understand that these metrics do in fact represent *a user* in the aggregate, and that we can infer intentions and behavior from these numbers, several avenues are worth exploring. 

Firstly, we should provide context for the data. A short text describing the what the numbers refer to may suffice. 

Secondly, we should present the information in bite-sized pieces where the most important metrics take precedence. 

Thirdly, we should let interested users dig through their data by drilling down into their reports. And in the case the reports available cannot reveal what the user desires from them, we should let people make simple feature requests – in that context. 


