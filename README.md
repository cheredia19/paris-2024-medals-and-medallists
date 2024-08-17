---
title: All the medals of the Paris 2024 Summer Olympic Games
description: ...
created: 2024-08-16
updated: 2024-08-17
---

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

 <LineChart
  data={{
    url: 'birth_dates.csv'
  }}
  title=""
  xAxis="birth_date"
  yAxis="number"
/>

 <PlotlyBarChart
  data={{
    url: 'every_medallists.csv'
  }}
  title=""
  xAxis="birth_date"
  yAxis="birth_date"
/>
