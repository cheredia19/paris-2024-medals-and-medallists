---
title: All the medals of the Paris 2024 Summer Olympic Games
description: ...
---

The six medals won by Chinese swimmer [Yufei Zhang](https://olympics.com/en/athletes/yufei-zhang) at the Paris 2024 Summer Olympic Games made her the most decorated athlete in the competition. However, **Zhang wasn't even in the top 50 of the athlete's medal table** because none of those medals were gold.

The top performer in Paris 2024 was [Leon Marchand](https://olympics.com/en/athletes/leon-marchand). The French swimmer clinched **four golds and a bronze medal**.

American [Torri Huske](https://olympics.com/en/athletes/torri-huske) and Australian [Mollie O'Callaghan](https://olympics.com/en/athletes/mollie-o-callaghan), swimmers, won three gold medals each. Huske added two silvers, while O'Callaghan clinched a silver and a bronze medal. 

One-third of the most decorated athletes in Paris 2024 were **swimmers**. Far behind were artistic gymnasts (9.8%), track and field athletes, sprint canoeists, and table tennis players among the athletes who won the most medals at the last Olympic Games.

<PlotlyBarChart
  data={{
    url: 'discipline_athletes.csv'
  }}
  title="Disciplines in which the top medalists performed (%)"
  xAxis="discipline"
  yAxis="pct_athletes"
/>

Gymnast legend [Simone Biles](https://olympics.com/en/athletes/simone-biles) won three golds and a silver. Biles was **the best non-swimmer performer at the Games**. Her 11 Olympic medals confirm her as [the most decorated gymnast in history](https://www.washingtonpost.com/sports/olympics/2024/08/01/simone-biles-olympic-medals-count/).

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
