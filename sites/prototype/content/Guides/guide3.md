+++
title = "Market Rates Beyond Today"
weight = 3
draft = false
+++

{{% header %}} In this guide, we'll look at the Contract Horizon feature to examine where the freight market is trending past the present day. {{% /header %}}

## Introduction

The Xeneta platform provides market trends and benchmarks based on current and historical freight rates. Of course, in the cycle of freight procurement and contract negotiation, new shipping contracts are always being established. 

In these cases, the contracts negotiated near the present day may be contracted to start a few weeks or months in the future — but they are still signed today and reflect today's market. In other cases, long-term contracts that extend past the present day also reflect the near-present market because they tend to be stable compared to the prices of short-term contracts.

Using the Market Horizon feature, you can extend your view of the Benchmarks and Trends graphs by three months.

## Viewing the Contract Horizon

To enable the Contract Horizon, start by clicking on the right-side of the date range picker on the graphs page.

{{< fig src="../g3-1.png" text="Step 1" >}}

Next, click **Show Futures** from the dialog that opens.

{{< fig src="../g3-2.png" text="Step 2" >}}

Finally, the graph will update to show an additional three months of data, indicated by a gray background on the graph.

{{< fig src="../g3-3.png" text="The Benchmarks graph with the Contract Horizon." >}}

## Understanding the Contract Horizon

The Contract Horizon is simply additional data about the state of the freight market. Having access to the Market Horizon is most useful in scenarios where having as many details as possible about the market is vital to your logistics strategy. 

If there is a contracted price for shipping freight that is valid for one year and began three months ago, it would be considered part of the Contract Horizon because it extends for nine months into the future. Similarly, if there is a recently formed contract that is set to become valid within a month, then this too would be part of the Contract Horizon because it is set to happen past the current day.

Anything on the Contract Horizon, with time, will eventually become part of regular historical data. It can be thought of as a window into the very first contracts being formed for future dates.

## Setting the Scope

Like the regular Benchmarks and Trends graphs, the Contract Horizon is also affected by the [Contracted Within](https://support.xeneta.com/hc/en-us/articles/115001994874-Contracted-Within) filter. As such, your view of the Market Horizon will vary based on how you choose to filter contracts based on their age.

### Three Views of the Future

In this example, we'll consider a four month period where three of the months are part of the Contract Horizon. We'll explore three different Contracted Within filter settings:

- All long-term contracts
- Long-term contracts created within the last 6 months
- Long-term contracts created within the last 3 months

#### All Long-term Contracts

By including all long-term contracts as part of the Contract Horizon, we can see that the price of shipping from Shanghai to Hamburg remains steady for contracts running beyond the current day.

{{< fig src="../g3-5.png" text="The Contract Horizon with all available long-term contracts." >}}

This view does not reveal very much because older long-term contracts tend to outnumber newer and younger contracts, such that the state of the market reflects the aged majority of contracts.

#### Long-term Contracts No Older Than 6 Months

If we apply the Contracted Within filter to exclude all contracts older than 6 months, we get the following view of the market:

{{< fig src="../g3-6.png" text="The Contract Horizon with contracts created within past 6 months." >}}

The average freight rate seen on the market begins to move slightly from month to month, showing less stability than the previous case.

#### Long-term Contracts No Older Than 3 Months

Finally, by looking at only contracts that were created within the past 3 months, we get the "freshest" view of the freight market. 

{{< fig src="../g3-7.png" text="The Contract Horizon with contracts created within past 3 months." >}}

Unlike the other two views, this view suggests that the prices for the newest contracts on the market will in fact be higher when entering August before dropping a bit in September. 

You'll notice that the line depicting the market average disappears when entering October. This is because there do not exist enough contracts that are at most three months old and run into the future for the platform to display in aggregate.

The conclusion we can draw here is that the market participants that are entering freight contracts near to the present day appear to be paying higher prices for shipments scheduled in the coming months.

## Further Reading

{{% linkarrow text="Concepts — Contract Horizon" %}} {{< ref "/Concepts/futures" >}} {{% /linkarrow %}}
