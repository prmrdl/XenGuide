+++
title = "Regions"
chapter = false
weight = 3
+++

To categorize and analyze the movement of freight, Xeneta organizes ports into regional and sub-regional groups. The mapping is done to give a better view into the way geography plays into freight prices. To reflect this, nearby ports with similar costs of shipping will be grouped together.


## Geographic Hierarchy

The availability of freight data fluctuates throughout the year and Xeneta may not always have optimal freight rate coverage to provide to the user. In cases like these, the Xeneta platform will automatically attempt to find the most relevant freight rates based on geographic proximity to the rates requested.

For example, if a user were to search for a freight rate between Hamburg (DEHAM) and Oslo (NOOSL), they might find that direct pricing information between those two ports is unavailable. However, to provide a useful price to the user, Xeneta will automatically look at the freight rates in the places closest to Hamburg and Oslo. 

The platform may expand the search area to include more ports with which to compare rates. In the the examples below, you can see how both Oslo and Hamburg are mapped out in Xeneta's geographic hierarchy.

{{% ratehierarchy city="Oslo" width="123px" %}} Oslo → Norway South East → Scandinavia → Northern Europe → Europe → World {{% /ratehierarchy %}}

{{% ratehierarchy city="Hamburg" width="158px" %}} Hamburg → North Europe Main → Northern Europe → Europe → World {{% /ratehierarchy %}}

Based on the availability of freight rates, Xeneta may compare **Norway South East** and **North Europe Main** instead of Hamburg and Oslo. The main goal of the geographic hierarchy is to provide the user with some level of confidence about freight rates between any two location.

{{% tip %}} You can read more about the Geographic Hierarchy methodology and how Xeneta uses regional aggregation to give the best insight into the freight market <a href="https://support.xeneta.com/hc/en-us/articles/115003167489-Geo-Hierarchy-Methodology" target="_blank">here</a>. {{% /tip %}}