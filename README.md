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

## Top athletes by sport

Besides Marchand and Biles, the three golds clinched by Dutch [Harrie Lavreysen](https://olympics.com/en/athletes/harrie-lavreysen) made him the most winning cyclist. South Korean archers [Woojin Kim](https://olympics.com/en/athletes/woojin-kim) and [Sihyeon Lim](https://olympics.com/en/athletes/sihyeon-lim) and sprint canoeist [Lisa Carrington](https://olympics.com/en/athletes/lisa-carrington) were the top performers in their respective disciplines (three gold medals each). American [Gabrielle Thomas](https://olympics.com/en/athletes/gabrielle-thomas) was the queen of **athletics** with her three gold medals.

**Table tennis** player [Yingsha Sun](https://olympics.com/en/athletes/yingsha-sun) clinched two gold medals and a silver, while Chinese [Yiwen Chen](https://olympics.com/en/athletes/yiwen-chen) and [Hongchan Quan](https://olympics.com/en/athletes/hongchan-quan), with two golds each, topped **diving**.

German jockey [Jessica von Bredow-Werndl](https://olympics.com/en/athletes/jessica-von-bredow-werndl), fencers [Lee Kiefer](https://olympics.com/en/athletes/lee-kiefer) (USA) and [Sanguk Oh](https://olympics.com/en/athletes/sanguk-oh) (South Korea), and French judoka [Teddy Riner](https://olympics.com/en/athletes/teddy-riner) earned two golds each.

## Top athletes by country

More than half of the 51 most decorated athletes at the Paris 2024 Olympic Games come from the United States or China. 27.5% of the total represented the U.S. and 23.5% China. The best performers by the countries on the list were:

- United States: Torri Huske (swimming, 3G, 2S).
- China: [Zhanle Pan](https://olympics.com/en/athletes/zhanle-pan) (swimming, 2G, 1S).
- Australia: Mollie O'Callaghan (swimming, 3G, 1S, 1B)
- South Korea: Kim Woojin and Lim Sihyeon (archery, 3G each)
- New Zealand: Lisa Carrington (canoe sprint, 3G)
- Germany: [Jacob Schopf](https://olympics.com/en/athletes/jacob-schopf), [Max Lemke](https://olympics.com/en/athletes/max-lemke) (canoe sprint), and Jessica von Bredow-Werndl (equestrian) (2G each)
- France: Leon Marchand (swimming, 4G, 1B)
- Sweden: [Sarah Sjoestroem](https://olympics.com/en/athletes/sarah-sjoestroem) (swimming, 2G)
Philippines: [Carlos Edriel Yulo] (artistic gymnastics, 2G)
Netherlands: Harrie Lavreysen (cycling track, 3G)
Kenya: Beatrice Chebet (athletics, 2G)
Japan: Shunnosuke Oka (artistic gymnastics, 3G, 1B)
Canada: Summer McIntosh (swimming, 3G, 1S)
Brazil: Rebeca Andrade (artistic gymnastics, 1G, 2S, 1B)
Belgium: Remco Evenepoel (cycling road, 2G)

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
