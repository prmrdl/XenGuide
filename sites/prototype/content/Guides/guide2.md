+++
title = "Using Excel for Benchmarking"
weight = 2
draft = true
+++

{{% header %}} In this guide, we'll take a look at working with Excel to look at Xeneta's Benchmarking data by exploring a few basic examples. {{% /header %}}

## Introduction

Xeneta can export the data that composes the Benchmarks graph to an Excel report. 

To begin, we'll need to generate the Benchmarks graph for the trade lane or trade corridor whose data we wish to export. Use the dashboard search or your followed trade lanes to reach the Benchmarks graph.

## Selecting Filters

The report exported by Xeneta is affected by the filters you select for the Benchmarks graph. The filters that affect the data exported to the Excel report are as follows:

- Origin and destination
- Date range
- Container type
- Contract duration
- THC methodology

All other data related to the benchmarks — including market positions and rate quality —  will be included by default. All of your uploaded freight rates available for the selected date range will appear as separate sheets in the exported report, separated by supplier name.

{{< fig src="../g2-1.png" text="Supplier prices sorted into separate sheets." >}}

## Generating the Graph

Once you have selected the filters that capture the data you wish to export, click the {{< inlineimg src="../export-icon.png" >}} icon in the top-right corner of the page to generate the Excel report.

Depending on the size of your dataset, generating the report may take some time. Once it is ready, the report will automatically download to your computer.

## Understanding the Report Data

The exported data will map your supplier prices for the selected origin-destination pair to Xeneta's benchmark prices for every day included in the date range filter.

{{% tip %}} Refer to this [article](https://xeneta.zendesk.com/hc/en-us/articles/115001632653) for more information about the meaning of each column in the Excel report. {{% /tip %}}

{{< fig src="../g2-2.png" text="The output of the Excel report." >}}

{{< fig src="../g2-3.png" text="Additional output of the Excel report." >}}

## Working with Report Data

With the report available to you, you can use Excel features to transform and manipulate the data.

### Creating a Table

Creating a table will let you sort and filter your data in Excel. You can create a table in the following way:

1) Select all data columns in the **Raw Data** sheet.

{{< fig src="../g2-4.png" text="Step 1" >}}

2) From the Excel Ribbon display, select **Insert** > **Table**.

{{< fig src="../g2-5.png" text="Step 2" >}}

3) Check the **My table has headers** option and click **OK**.

{{< fig src="../g2-6.png" text="Step 3" >}}

Your data will now be structured as a typical Excel table, which can be used to filter and sort your data to your preference.

{{< fig src="../g2-7.png" text="Data in table form." >}}

### Creating Charts

If you wish to see alternate visualizations of freight benchmark data, you can use Excel to create charts from the exported dataset. In this example, we'll focus on creating a basic line chart with a trend line that captures the general movement of the market average freight rate.

1) Select the Day, My Price, Market Average, Market Low, and Market High columns in the Excel report.

{{< fig src="../g2-8.png" text="Selected market prices in Excel spreadsheet." >}}

2) Navigate to **Insert** and select the **2-D Line Graph** chart option.

{{< fig src="../g2-9.png" text="Line graph chart type." >}}

3) A line graph will be generated based on the benchmark data and the date will automatically be used as the x-axis.

{{< fig src="../g2-10.png" text="Line graph showing My Prices and three market positions." >}}

4) Click on the chart and then on the green cross in the top-right corner of the chart to open the Chart Elements menu.

{{< fig src="../g2-11.png" text="Chart elements menu." >}}

5) Select the **Trendline** option and then **Market Average** and click **OK**.

6) A dotted trendline for the Market Average benchmark will be added to your graph.

{{< fig src="../g2-12.png" text="A line chart with a Market Average trend line." >}}

## Summary

Exported reports provide an additional layer of analysis on top of the Xeneta platform. Using Xeneta's data with Excel can be useful for exploring benchmarking data and understanding the market.