# RStudio Table Contest 2020 Submission

## [The Big Mac Index Table](https://rpubs.com/acalatroni/682678)

Our goal for the [2020 RStudio Table Contest](https://blog.rstudio.com/2020/09/15/announcing-the-2020-rstudio-table-contest/) was to learn and practice with the [gt package](https://gt.rstudio.com/). To do so we decided to focus on the following aspects: 
-	Include interactive figures within the table. For this, we chose the [echarts4r package](https://echarts4r.john-coene.com/) to create interactive graphics with Echarts Javascripts, albeit other packages would have also worked (ie. Plotly, highcharter, etc.)
-	Include images, either through a [GitHub](https://github.com/HatScripts/circle-flags) repo (flags) or Wikimedia commons scraping (maps)
-	Include as many HTML tricks as necessary to improve the overall readability of the table (for example HTML color of headers, icons, spanners, hyperlinks, currency symbols, etc.)
-	Include footnotes, in particular a footnote color legend for the color column, an HTML details tab to display in an inconspicuous way the R session information, and font awesome icons for github and twitter hyperlinks).  
- Include CSS with the [new feature](https://github.com/rstudio/gt/releases/tag/v0.2.2) `opt_css` to improve the tables aesthetics, especially in light of the interactive graphics tweaking.

In short the Big Mac Index is published by [The Economist]( https://www.economist.com/) as an informal way of measuring the purchasing power parity (PPP) between two currencies and provides a test of the extent to which market exchange rates result in goods costing the same in different countries. It seeks to make exchange-rate theory a bit more digestible. The magazine's latest version (July 2020) of the [The Big Mac index interactive currency comparison tool](https://www.economist.com/news/2020/07/15/the-big-mac-index). Furthermore, you can also download the data or read the methodology behind the Big Mac index [here]( https://github.com/TheEconomist/big-mac-data)
