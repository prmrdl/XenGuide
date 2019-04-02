+++
title = "Search"
weight = 2
+++

{{% header %}} The port-to-port search allows you to find today's rate for the majority of port-to-port combinations in the world across a variety of <a href="https://support.xeneta.com/hc/en-us/articles/115002624293-Container-Types" target="_blank">container types</a>. {{% /header %}}

## Overview

The port-to-port search bar can be found on the <a href="https://app.xeneta.com/ocean/dashboard" target="_blank">dashboard</a> and at the top of any <a href="{{< ref "/Ocean/graphs.md" >}}" >graphs</a> pages.

{{< fig src="../ocean-dashboard-search.png" text="The port-to-port search with a result." >}}

Simply enter an origin port and a destination port, select your preferred container type, and click **Search**.

## Search Results

The results of a port-to-port search will return a market rate based on the rate data available to Xeneta. Search results include the spot rate, the price change since a week ago, the applied THC methodology, and a link to the [Trends graph]({{< ref "/Ocean/graphs.md#trends-graph" >}}) associated with the ports in the search.

Xeneta can return a number of results based on the availability of rate data for a particular port-port pair. The results fall into the following categories:

### Contracted Rate

A contracted rate is an aggregated rate that meets Xeneta's data quality rule of at least 5 sources being available across 2 providers. It is the most accurate rate that Xeneta can provide.

{{< fig src="../search-contracted.png" text="A contracted rate." >}}

### Regional Rate

A regional rate is an aggregated rate that did not meet exact port-to-port search specifications because of a lack of rate data between the two ports. 

{{< fig src="../search-regional.png" text="A regional rate." >}}

To create a regional rate, Xeneta increases the scope of the search to include ports near to the selected ports. Once enough nearby ports are found, their data is aggregated together to form a rate that — while not as precise as a contracted rate — still informs you about the general rate of shipping goods in the region.

{{% tip %}} Regional rates vary in precision based on how much the data scope was increased to create the regional rate. See this <a href="https://support.xeneta.com/hc/en-us/articles/115003167489-Geo-Hierarchy-Methodology" target="_blank">article</a> for more information. {{% /tip %}}

### Estimated Rate

An estimated rates is a computed approximations of what a freight rate might be for a lane lacking contracted rate data. Estimated rates are not available for all trade lanes and are shown only when Xeneta has confidence that an estimated rate meets a certain level of accuracy.

{{< fig src="../search-estimated.png" text="An estimated rate." >}}

{{% tip %}} See <a href="https://support.xeneta.com/hc/en-us/articles/115003199553-Estimated-Rates" target="_blank">this article</a> for more information on estimated rates. {{% /tip %}}

## Followed Market Trends

You can follow any trade lane whose trends you wish to keep an eye on from the search results.

{{< fig src="../ocean-dashboard-follow.png" text="Dashboard — Following a Trade Lane" >}}

Followed lanes are added to the bottom of the dashboard and show their current price as well as changes in the price since the week before.

{{< fig src="../ocean-dashboard-followed-markets.png" text="Dashboard — Followed Market Trends" >}}

## Geo-Selector Tool

The geo-selector tool helps you visually navigate ports and their respective regions. It can be opened by clicking on the globe icon {{< inlineimg src="../globe-icon.png" >}} on the search bar.

{{< fig src="../ocean-dashboard-geo-selector.png" text="Search — Geo-Selector Tool" >}}

## Next Steps

Next we'll take a look at how Xeneta handles your prices.

{{% linkbutton title="My Prices" %}} {{< ref "Ocean/myprices.md" >}} {{% /linkbutton %}}
