| [home page](https://cmustudent.github.io/tswd-portfolio-templates/) | [visualizing debt](visualizing-government-debt) | [critique by design](critique-by-design) | [final project I](final-project-part-one) | [final project II](final-project-part-two) | [final project III](final-project-part-three) |

# Visualizing Government Debt

## Part 1

<iframe src="https://data.oecd.org/chart/7b32" width="860" height="645" style="border: 0" mozallowfullscreen="true" webkitallowfullscreen="true" allowfullscreen="true"><a href="https://data.oecd.org/chart/7b32" target="_blank">OECD Chart: General government debt, Total, % of GDP, Annual, 2020</a></iframe>


## Part 2

<div class="flourish-embed flourish-chart" data-src="visualisation/14949439"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Part 3

<div class="flourish-embed flourish-sankey" data-src="visualisation/14928245"><script src="https://public.flourish.studio/resources/embed.js"></script></div>

## Discussion
The grid of lines chart is very effective for quickly scanning all countries to see how their debt to GDP ratio has changed over time.  Unfortunately, this plot falls short when comparing the values between the countries.  It is fairly easy to compare values for countries on the same row in the grid, but it is difficult to compare countries that are on different rows.  My goal was to create a visualization that makes comparisons across countries clear without losing the idea of trend.

I think the grid of lines chart is probably the best way to show all of this data at once, so when making my visualization based on comparisons, I decided to compare two countries: the USA and Canada.  It would be feasible to compare ~5 countries (I think) using my method, but any more than that would likely get confusing - and I would then recommend going back to the grid of lines.

My initial attempt was to make a single line chart, graying out the lines that do not correspond to the USA and Canada.  This worked fairly well, but I wanted to quickly visually query both the value (debt to GDP ratio) as well as see the relative ranks of the countries.  To support this, I created the modified Sankey diagram shown above.  In this chart, it is easy to see that Canada has the second highest value and the USA has the 6th.  The countries cross over around 2006, reversing their relative ranks.  The width of the bars corresponds to the value as well, showing how it shrinks and grows.  

I find the Sankey approach to be a bit cleaner than an alternative using lines because there is clear separation between the country labels using this approach - and the exact values are available on each label (and on-hover).  In practice, creating this plot required some fairly complicated data manipulation, so I would have to evaluate whether or not it is worth the effort in the future.




