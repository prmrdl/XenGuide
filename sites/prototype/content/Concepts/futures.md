+++
title = "Contract Horizon"
chapter = false
weight = 3
draft = false
+++

At its core, the Xeneta platform helps you understand the trends in the freight market. It does so by providing three views of the market:

1. The historical rate trends
2. The current day's rate
3. The trends of rates that run into the future or begin in the future

In the third case, Xeneta offers a short view of the future by showing contracted freight rates that extend past the current day. We refer to this as the **Contract Horizon**, and it is particularly useful for understanding the developing trends in the freight market as it moves into the future.

To understand the Contract Horizon, let's first walk through how Xeneta visualizes rates and how rates are filtered based on their age.

## Visualizing Rates

We can visualize Xeneta's rate data by viewing it as a collection of lines: the length of each line representing the duration of a contracted rate and its vertical position representing the price that the rate was negotiated at.

Xeneta creates a <a href="https://support.xeneta.com/hc/en-us/articles/115001532114-Market-Benchmarks" target="_blank">benchmark value</a> by combining all valid rates for a single day into one number. 

{{< fig src="../futures-1.png" text="Figure 1 — Freight market visualization." >}}

In the example above, the average benchmark price provided by Xeneta for today can be calculated by taking the arithmetic average of the 5 rates on our graph that pass through the blue dashed line. In this case, the market benchmark will be $300.

This is the most basic scenario of how Xeneta presents rates from across the market as a single value that is used for benchmarking. 

## Contracted Within

By default, Xeneta combines all contracts available in a single day into one price.

This includes contracts that were created in the past as well as those created recently. This means that long-term contracts from several months ago will influence the benchmark price provided by Xeneta. 

If you are interested in the most current freight rates available on the market, you can choose to exclude older contracts by using the <a href="https://support.xeneta.com/hc/en-us/articles/115001994874-Contracted-Within" target="_blank">Contracted Within</a> filter. This allows you to see only those rates that were recently contracted. This should give you a clear picture of the prices most-recently agreed upon by market participants.

{{< fig src="../futures-2.png" text="Figure 2 — A set of rates contracted within 3 months." >}}

In our example, if we calculate the market average for only those contracts that start within the scope of the Contracted Within filter for 3 months — the contracts that start within the pink region — we find that the market average value is $350.

This suggests that, by looking only at newer contracts, the market is moving towards a higher average price.

## Contract Horizon

Finally, Xeneta is able to look at contracts that run past the current day or are contracted to begin some time in the future.

These contracts — located at what Xeneta refers to as the Contract Horizon — contain additional information about the state of the freight market for the coming 3 months.

Consider that any contract set to begin in the future has to be negotiated near the present day. Because such contracts begin in the future, they will not be visible as part of the historical rate or the current day's rate.

{{< fig src="../futures-3.png" text="Figure 3 — Freight rates with the contract horizon." >}}

Nonetheless, these contracts set the basis for the market rates in the coming months. 
By looking at the Contract Horizon, you can see where market participants have decided to position their freight rates in the near future, and how long-running contracts overlap with them.

## Contracted Within and Contract Horizon

Finally, you can combine the Contracted Within filter with the Contract Horizon to see only the most recent contracts that extend into the future.

We'll look at two examples: a view of rates half way into the Contract Horizon and a view of the same rates at the very end of the Contract Horizon.

### Example 1

In this example, we'll set the scope of the Contracted Within filter to 3 months and will look at the middle of the Contract Horizon — one and a half months into the future.

{{< fig src="../futures-5.png" text="Example 1 — Freight rates in the middle of the contract horizon contracted within 3 months." >}}

We can see that only contracts 2, 3, and 7 will be valid for the given period. The older contracts — 1, 4, and 5 — will be excluded based on their age. Lastly, contract 6 will be excluded because it will only be valid in the future. If we calculate the market average using our valid rates, we'll find that its value will be $250.

### Example 2

In our second example, we'll look at the very last day of the Contract Horizon with the Contracted Within filter of 3 months applied. This means that at the end of the Contract Horizon, 3 months past the current day, the oldest contract could only begin from today's date. This means that you see the most current view of the market — a view that is least affected by older long-term rates.

{{< fig src="../futures-4.png" text="Example 2 — Freight rates at the end of the contract horizon contracted within 3 months." >}}

This view of the freight market shows us the absolutely newest contracts that have been negotiated, and the ones least affected by older long-term contracts.

In this example, only two contracted rates begin in the future, and their market average value is $100. By looking at the market in this way, we can get a sense of where the price of future contracts is trending.

### Why is the Contract Horizon limited to 3 months?

Due to the nature of the freight market, market participants simply do not negotiate contracts to start very far into the future.

Xeneta cannot show freight data past the Contract Horizon because such data simply does not exist.

Additionally, the further you look into the future, the fewer rates are available since older long-term rates begin to expire and fewer new long-term rates are contracted ahead of time. If you look too far into the future, there will simply be no data for Xeneta to show.

## Further Reading

- [Guides — Market Rates Beyond Today]({{< ref "guide3.md" >}})