---
title: All the medals of the Paris 2024 Summer Olympic Games
description: ...
created: 2024-08-16
updated: 2024-08-17
---

## All the individual and team medal winners

<FlatUiTable
  data={{
    url: 'each_medal.csv'
  }}
 />

 ## All the medallists (individual and team members)

 <FlatUiTable
  data={{
    url: 'all_medallists.csv'
  }}
 />

 <PlotlyLineChart
  data={{
    url: 'birth_dates.csv'
  }}
  title=""
  xAxis="birth_date"
  yAxis="number"
/>

 <PlotlyBarChart
  data={{
    url: 'all_birth_dates.csv'
  }}
  title=""
  xAxis="birth_date"
  yAxis="number"
/>
