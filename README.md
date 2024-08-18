---
title: All the medals of the Paris 2024 Summer Olympic Games
description: ...
---

## Most decorated athletes

<PlotlyBarChart
  data={{
    url: 'country_number.csv'
  }}
  title=""
  xAxis="country"
  yAxis="number"
/>

<PlotlyBarChart
  data={{
    url: 'country_golds.csv'
  }}
  title=""
  xAxis="country"
  yAxis="gold_medals"
/>

<PlotlyBarChart
  data={{
    url: 'country_total.csv'
  }}
  title=""
  xAxis="country"
  yAxis="total_medals"
/>

<PlotlyBarChart
  data={{
    url: 'discipline_athletes.csv'
  }}
  title=""
  xAxis="discipline"
  yAxis="pct_athletes"
/>

<FlatUiTable
  data={{
    url: 'most_gsb_winning_athletes.csv'
  }}
 />

## All the individual and team medal winners

<FlatUiTable
  data={{
    url: 'every_medals.csv'
  }}
 />

 ## All the medallists (individual and team members)

 <FlatUiTable
  data={{
    url: 'every_medallists.csv'
  }}
 />

 <PlotlyLineChart
  data={{
    url: 'all_birth_dates.csv'
  }}
  title=""
  xAxis="birth_date"
  yAxis="number"
/>

 <PlotlyBarChart
  data={{
    url: 'birth_year.csv'
  }}
  title=""
  xAxis="birth_year"
  yAxis="number"
/>
