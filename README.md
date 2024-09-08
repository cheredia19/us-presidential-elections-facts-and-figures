---
title: Facts and figures of the U.S. presidential elections
description: 
---

If **Donald Trump** becomes the new president of the United States next November, he will overtake incumbent **Joe Biden** as **the oldest US-elected president ever**.

The current GOP candidate would be **the second head of state in history with two non-consecutive periods** if he wins. The first one was **Grover Cleveland** (1885-1889) and (1893-1897).

Cleveland was 47 when he took office for the first time. 

Only six men became president of the United States at a younger age. **Theodore Roosevelt** was 42 years old when he had to assume office due to the assassination of William McKinley in 1901. It made him the youngest chief of state in the country's history.

<PlotlyBarChart
  data={{
    url: 'age_elected_pres.csv'
  }}
  title="How old were the presidents at the time of their election?"
  xAxis="president_year"
  yAxis="age"
/>
###### *(a) John Tyler (51) assumed the presidency on April 4, 1841 due to the death of WIlliam Henry Harrison, thirty-two days after Harrison began his term in office.*
###### *(b) Millard Fillmore (50) assumed the presidency on July 9, 1850 due to the death of Zachary Taylor, who passed away of natural causes after just over a year in office.*
###### *(c) Andrew Johnson (56) assumed the presidency on April 15, 1865 due to the assassination of Abraham Lincoln.*
###### *(d) Chester Arthur (51) assumed the presidency on September 20, 1881 due to the assassination of James Garfield.*
###### *(e) Theodore Roosevelt (42) assumed the presidency on September 14, 1801 due to the assassination of William McKinley.*
###### *(f) Calvin Coolidge (51) assumed office on August 2, 1923 due to the myocardial infarction of Warren Harding that led to his death.*
###### *(g) Harry Truman (60) assumed office on April 12, 1945 due to the brain hemorrhage of Franklin Roosevelt that led to his death.*
###### *(h) Lyndon Johnson (55) assumed office on November 22, 1963 due to the assassination of John F. Kennedy.*
###### *(i) Gerald Ford (61) assumed office on August 9, 1974 after Richard Nixon's resignation due to the Watergate scandal.*

Biden was 77 when [he was declared the winner of the 2020 election](https://apnews.com/article/joe-biden-wins-white-house-ap-fd58df73aa677acb74fce2a69adb71f9). Thirteen days later, the incumbent turned 78.

## Popular votes by party and winners (1856-2020)

The former vice president is the only candidate to surpass the 80 million popular-vote barrier (81,283,501) in a presidential election. It's fair to say that he and Trump (74,223,975) are the only ones to have surpassed 70 million votes, both in the 2020 race.

Since the first Republican nominating convention in 1856, in which ex-senator John Charles Frémont got the nomination, Democrats and Republicans have been pitted against each other every four years, taking center stage in every election.

The following two line charts show the popular vote performance of Democratic and Republican candidates from that year to the last election in 2020.

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

Twenty-four GOP candidates have been elected as the United States president. The first one was **Abraham Lincoln** in 1860. Since then, the Republicans achieved **six consecutive times** the U.S. presidency until Democratic aspirant **Grover Cleveland** defeated former Secretary of State James G. Blaine in the 1884 election.

From James Buchanan (1856) to Joseph R. Biden, eighteen Democratic candidates have been elected as U.S. president.

The Democrats won five consecutive times beginning in 1932. **Franklin D. Roosevelt** started the streak. He also triumphed in '36, '40 and '44. 

Roosevelt is the only president in history to occupy the presidential spot for over two consecutive terms. However, he did not finish the last of his terms, as he died on April 12, 1945, days before the end of World War II. **Harry S. Truman took office immediately. Three years and a half later, he defeated Thomas Dewey and States' Rights candidate **Strom Thurmond** in the election of 1948.

<FlatUiTable data={{ url: 'votes_dem_rep.csv' }} />
###### *NOTE: The 2016 elections are, along with those of 1824, 1876, 1888 and 2000 the only ones in which the winning candidate lost the popular vote.*

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
