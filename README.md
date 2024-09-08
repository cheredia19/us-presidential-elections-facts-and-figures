---
title: Facts and figures of  the US presidential elections
description: 
---

If Donald Trump becomes the new president of the United States next November, he will overtake incumbent Joe Biden as **the oldest US-elected president ever**.

The current GOP candidate would be **the second head of state in history with two non-consecutive periods**. The first one was Grover Cleveland (1885-1889) and (1893-1897).

Cleveland was 47 when he took office for the first time. 

Only six men became president of the United States at a younger age. Theodore Roosevelt was 42 years old when he had to assume office due to the assassination of William McKinley in 1901. This made him the youngest chief of state in the country's history.

<PlotlyBarChart
  data={{
    url: 'age_elected_pres.csv'
  }}
  title="How old were the presidents at the time of their election?"
  xAxis="president_year"
  yAxis="age"
/>
######*(a) John Tyler (51) assumed the presidency on April 4, 1841 due to the death of WIlliam Henry Harrison, thirty-two days after Harrison began his term in office.<br />(b) Millard Fillmore (50) assumed the presidency on July 9, 1850 due to the death of Zachary Taylor, who passed away of natural causes after just over a year in office.<br />(c) Andrew Johnson (56) assumed the presidency on April 15, 1865 due to the assassination of Abraham Lincoln.<br />(d) Chester Arthur (51) assumed the presidency on September 20, 1881 due to the assassination of James Garfield.<br />(e) Theodore Roosevelt (42) assumed the presidency on September 14, 1801 due to the assassination of William McKinley.<br />(f) Calvin Coolidge (51) assumed office on August 2, 1923 due to the myocardial infarction of Warren Harding that led to his death.<br />(g) Harry Truman (60) assumed office on April 12, 1945 due to the brain hemorrhage of Franklin Roosevelt that led to his death.<br />(h) Lyndon Johnson (55) assumed office on November 22, 1963 due to the assassination of John F. Kennedy.<br />(i) Gerald Ford (61) assumed office on August 9, 1974 after Richard Nixon's resignation due to the Watergate scandal.*

Biden was 77 when [he was declared the winner of the 2020 election](https://apnews.com/article/joe-biden-wins-white-house-ap-fd58df73aa677acb74fce2a69adb71f9). Thirteen days later, the incumbent turned 78.

## Popular votes by party and winners (1856-2020)

<FlatUiTable data={{ url: 'votes_dem_rep.csv' }} />
**NOTE: The 2016 elections are, along with those of 1824, 1876, 1888 and 2000 the only ones in which the winning candidate lost the popular vote.*

<PlotlyLineChart
  data={{
    url: 'votes_dem_rep.csv'
  }}
  title="Evolution of the Democratic Party's popular votes since 1856"
  xAxis="year"
  yAxis="democratic"
/>

<PlotlyLineChart
  data={{
    url: 'votes_dem_rep.csv'
  }}
  title="Evolution of the Republican Party's popular votes since 1856"
  xAxis="year"
  yAxis="republican"
/>

## Electoral votes by party (1856-2020)

<FlatUiTable data={{ url: 'ev_dem_rep.csv' }} />

<PlotlyLineChart
  data={{
    url: 'ev_dem_rep.csv'
  }}
  title="Evolution of the Democratic Party's electoral votes since 1856"
  xAxis="year"
  yAxis="democratic"
/>

<PlotlyLineChart
  data={{
    url: 'ev_dem_rep.csv'
  }}
  title="Evolution of the Republican Party's electoral votes since 1856"
  xAxis="year"
  yAxis="republican"
/>
