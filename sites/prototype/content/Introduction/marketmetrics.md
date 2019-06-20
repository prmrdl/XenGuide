+++
title = "Market Metrics"
chapter = false
weight = 5
+++

{{% aside %}} For an in-depth look at Market Metrics, read our <a href="https://support.xeneta.com/hc/en-us/articles/360000925173-Market-Metrics" target="_blank">article</a> in the help center. {{% /aside %}}

Market metrics are a set of options that control how freight rate data is displayed in Xeneta. You can think of them as a global-level filters for rate information.

 They appear in the top-right corner of on any pages capable of showing freight data — including Air and Ocean dashboards. 

{{< fig src="../market-metrics-ocean.png" text="Market metrics for ocean freight." >}}

Currently, Xeneta uses 3 types of market metrics across both Ocean and Air freight products:

* Contract duration (Ocean)
* Market position (Air and Ocean)
* Service levels (Air)	

## Understanding Your Metrics — Ocean

It is important to select the right market metrics when viewing data in Xeneta because market metrics determine the data you will be shown.

Xeneta separates data between short-term contracts and long-term contracts, which means that you need to use market metrics to select the type of contracts you would prefer to see. Additionally, long-term contracts can be filtered by their age using the [Contracted Within](https://support.xeneta.com/hc/en-us/articles/115001994874-Contracted-Within) option.

Xeneta also allows you to focus on different parts of the market, including the average freight rates, as well as the low and high segments of the market. You can read more about how Xeneta divides prices into different segments of the freight market [here](https://support.xeneta.com/hc/en-us/articles/115001532114-Market-Benchmarks).

With this in mind, let's take a look at the following freight rate search results and see how they are affected by market metrics:

### Short-term Contracts and Market Average Position

In this case, Xeneta returns the market average price across all short term contracts available on the Shanghai–Hamburg trade lane.

{{% fig src="../mm-1.png" text="Rate from Shanghai to Hamburg with short-term rates and a market average position." %}}

### Short-term Contracts and Market High Position

Here we can see the same short term contracts but the market position is now focused on the **market high**, or, in other words, the highest prices paid on the market to ship freight on this trade lane.

{{% fig src="../mm-2.png" text="Rate from Shanghai to Hamburg with short-term rates and a market high position." %}}

### Long-term Contracts and Market Low Position

Finally, we can see long-term contracts with the market low position — that is, the lowest prices paid by market participants. 

{{% fig src="../mm-3.png" text="Rate from Shanghai to Hamburg with long-term rates and a market low position." %}}

### Summary

The market metrics determine the parts of the freight rate market that Xeneta will show. In the examples above, the freight rate can vary drastically under different market metrics. The price of long-term contracts will differ from the short-term, and the market average value can be significantly different between the highest and lowest prices paid on the market.

## Understanding Your Metrics — Air

Market metrics in Xeneta for Air Freight differ from Ocean freight in the following ways:

* Air freight uses only long-term contracts
* Air freight has a market metric tied to the service level of the cargo

{{% fig src="../mm-4.png" text="Market metrics for Air freight." %}}

Like Ocean freight, Xeneta uses three different market positions to show freight rates for the market average, low, and high segments.

However, unlike Ocean freight, air freight is categorized by Xeneta into [service levels](https://support.xeneta.com/hc/en-us/articles/360012088593). This is done to ensure that air cargo, which lacks the standardization of ocean freight, can be made comparable to other air cargo.

In general, the way Xeneta creates benchmarks for air freight differs from the way it is done for ocean freight. You can read more about our benchmarking methodology [here](https://support.xeneta.com/hc/en-us/articles/360012921174-Air-Benchmarking-Methodology).

Let's examine how the service level market metric affects the prices seen within the air freight search:

### Mid-Tier Service Level and Market Average

Here we can see the prices for air freight from Shanghai to Frankfurt at the market average. 

{{% fig src="../mm-5.png" text="Mid-tier service level and a market average position." %}}

### Mid-Tier Service Level and Market Low

Contrast the price above with the same service tier but focused on the lowest price on the market. We can see that the spread between the market average and the market low is not very large.

{{% fig src="../mm-6.png" text="Mid-tier service level and a market low position." %}}

### Low-Tier Service Level and Market Average

Finally, we can look at the low-tier service level at the market average for the same trade lane.

{{% fig src="../mm-7.png" text="Low-tier service level and a market average position." %}}

The difference between the low-tier and mid-tier air freight viewed at the market average provides a good insight into the value of service level offered by carriers. For instance, if you're particularly price-sensitive, it would make sense to forgo some service level benefits — like shipping speed — for a lower price.