+++
title = "Spend Analysis"
weight = 2
+++

## Overview

Spend Analysis uses your uploaded volume data to calculate estimated savings and theoretical market spend in dollars.

## Spend Comparison

The Spend Comparison — available on the Analytics dashboard — helps you compare the price you paid for your volume you have shipped against shipping the same volume at different market prices. The Spend Comparison panel compares your spend volume to the market low, average, and high spends.

{{% note %}}

**Example**: If you ship 100 TEU at $100 each, the value of My Covered Spend will be $10,000. If the price to ship at the market low is $80, then the value of Market Low Spend will be $8000 ($80 × 100).

{{% /note %}}

For example, in the image below, **My Covered Spend** is calculated by adding up all your shipped volumes and their associated prices across all your trade lanes. The three Market Spend values are calculated by taking the same volume and trade lanes but using Xeneta's market data for the price instead.

{{< fig src="/img/spend-comparison.png" >}}

In our example, we can see that the My Covered Spend values are actually below the Market Average Spend, which suggests that in total the prices we have paid to ship our cargo are reasonable. Nonetheless, they are still above the Market Low Spend, which expresses the lowest prices paid on the market. 

## Saving Potentials

The Saving Potential is a calculation of the savings possible for your shipped volume given that the prices for those volumes improve if they use market prices instead of the prices you supplied. It is available on the Analytics dashboard and as part of the Spend Overview.

{{< fig src="/img/saving-potentials.png" >}}

In other words, the Saving Potential reflects the possible savings that can be achieved if your worst-performing trade lanes are negotiated to rates matching the market.

## Spend Overview

The Spend Overview ties together your volume and prices with Xeneta's market data. As with any analytics page in Xeneta, the Spend Overview is affected by [market metrics]({{< ref "Concepts/marketmetrics.md" >}}).

{{< fig src="/img/spend-overview.png" >}}

The Saving Potential at the corridor level combines all possible savings from the trade lanes available within the corridor. It gives you a view into the corridors that would benefit the most from better prices. 

{{% note %}}

Not all of your spend may be covered by Xeneta. If you have rates for small and uncommon trade lanes, Xeneta may not have enough coverage to provide an analysis. 

The **My Covered Spend** column shows how much of your total spend is covered by Xeneta. This is also the value that is compared against the market benchmark to calculate a savings potential.

{{% /note %}}

{{< fig src="/img/spend-overview-port.png" >}}

Using the filters available on the page, you can drill down to the port level and find the exact prices you have paid to ship on your trade lanes. Here, too, you can see the Saving Potential available to you specific to each trade lane. 
