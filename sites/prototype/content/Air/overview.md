+++
title = "Overview"
weight = 1
+++

{{% header %}} <a href="https://app.xeneta.com/air/dashboard" target="_blank">Xeneta for Air Freight</a> is an analytics and benchmark platform for understanding the prices of the air freight market. {{% /header %}}

## The Dashboard

Like the Ocean dashboard, the Air freight dashboard contains a port-to-port search bar and a summary of your price coverage and price benchmarks.

{{< fig src="../air-dashboard.png" text="Dashboard — Xeneta for Air Freight" >}}

## The Port-to-port Search

The port-to-port search on the dashboard is used to find spot rates for air freight.

{{< fig src="../air-search.png" text="Port-to-port search bar." >}}

Simply enter an origin port, a destination port, select your preferred <a href="https://support.xeneta.com/hc/en-us/articles/360012268533-Weight-Breaks-in-Air-Rate-Search" target="_blank">weight break</a>, and click **Search**.

## Search Results

After running the search, Xeneta will return results in the unit of **price per kilogram**. The results themselves can take one of two forms:

### Contracted Rates

A contracted rate is an aggregated rate that meets Xeneta’s data quality rule of at least 5 sources being available across 2 providers. It is the most accurate rate that Xeneta can provide.

{{< fig src="../air-search-contracted.png" text="A contracted rate." >}}

### Regional Rates

A regional rate is an aggregated rate that did not meet exact port-to-port search specifications because of a lack of rate data between the two ports.

{{< fig src="../air-search-regional.png" text="A regional rate." >}}

Regional rates are displayed with additional information that detail how the rate was constructed. This can be viewed by clicking the {{< inlineimg src="../exclamation-icon.png" >}} icon beside the name of the trade lane.

{{< fig src="../air-search-regional-dialog.png" text="Regional rate explanation for the Shanghai–Bremen trade lane." >}}

## Next Steps

Next, let's take a look at the My Prices page.

{{% linkbutton title="My Prices" %}} {{< ref "Air/myprices.md" >}} {{% /linkbutton %}}
