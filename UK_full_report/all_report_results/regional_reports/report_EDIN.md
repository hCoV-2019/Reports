







# Lineages report for EDIN




This report gives summaries of UK specific lineages sequenced by EDIN for week 2020-07-03. 
There are time lags due to batching, curation and analysis, the most recently sampled sequence is 2020-06-22. The analysis (eg time since last sample) is therefore undertaken from this date.
<br/>
1388 sequences in the UK from the sequencing centre EDIN have been included in this analysis.


A few notes: the size of a lineage may be due to a low amount of transmission of this lineage, but it is likely also that it just hasn't been sampled as frequently, especially for newer lineages.
It's also important to realise that these lineages are *estimates* of how we think the virus is spreading in the UK after being introduced from abroad, as the low evolutionary rate of the virus makes it difficult to separate lineages with certainty.



The minimum number of introductions is 107 and the maximum is 493


Sequences which were replicates or too error-prone were removed from this analysis.



95 are lineages which only contained five sequences or fewer, and so have been left out of visualisation in the interests of clarity


Furthermore, those sequences which haven't been sampled in the last month are not shown.



Of the 5 that remain:
2 are pending extinction, ie last seen three weeks ago.
1 has gone quiet, ie hasn't been seen this week.
2 lineages have been continuously circulating.



The following table contains information about the ten largest lineages lineages and the number of sequences the dataset. Information about other lineages is found in the appendix, along with the raw data for all of the other figures.


Each entry is the count of sequences from each lineage in each country, with the percentage of the total sequences from that lineage that this count represents.

"Activity score" is calculated by taking the average gap between sampling for each lineage, and dividing it by the number of days since the lineage was last sampled. Therefore the higher the number, the more active the lineage is.
If the score is above 1, then it has been sampled *more* recently than expected given its average gap size. We might interpret this as an increase in activity.
If the score is below 1, it has been sampled *less* recently than expect given its average gap size, so we might interpret this as a decrease in activity.



The global lineages are correct as of the data release on 2020-05-19


It is written to "summary_files" as "lineage_summary.tsv" for further use, and the full list of lineages is available in the same directory as "all_lineages.csv"



| Lineage name   | Scotland     | Date range     |   Total sequences | Global lineage                     |   Time since last sample (days) | Activity score   |
|:---------------|:-------------|:---------------|------------------:|:-----------------------------------|--------------------------------:|:-----------------|
| UK109          | 240 (100.0%) | Mar-21, Jun-12 |               240 | B.1.5, B.1.5.5                     |                              10 | 0.0347           |
| UK36           | 182 (100.0%) | Mar-21, May-22 |               182 | B.1                                |                              31 | 0.011            |
| UK5            | 157 (100.0%) | Mar-06, Jun-17 |               157 | B.1.1.1, B.1.1.4, B.1.1.p12, B.1.1 |                               5 | 0.1321           |
| UK199          | 137 (100.0%) | Mar-20, Jun-22 |               137 | B.1.5                              |                               0 | active today     |
| UK42           | 125 (100.0%) | Mar-04, May-21 |               125 | B.1.71, B.1                        |                              32 | 0.0197           |
| UK2464         | 54 (100.0%)  | Mar-20, Jun-06 |                54 | B.1.p11                            |                              16 | 0.092            |
| UK304          | 36 (100.0%)  | Apr-16, Jun-02 |                36 | B.1.1.14                           |                              20 | 0.0671           |
| UK72           | 32 (100.0%)  | Mar-11, Apr-25 |                32 | B                                  |                              58 | 0.025            |
| UK2913         | 31 (100.0%)  | Mar-28, May-13 |                31 | B.1.p11                            |                              40 | 0.0383           |
| UK4493         | 26 (100.0%)  | Apr-23, May-19 |                26 | B.1                                |                              34 | 0.0306           |


These data is represented in the figure one. Note that the number of sequences is likely to be due more to differing sampling efforts in different regions, rather than genuine differences in numbers of cases. 

The raw data for this bar chart are in the table above.


![Number of sequences sampled in a lineage by country](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/EDIN/figures/report_EDIN_stacked_bars_by_country_1.png){#stacked_bars_by_country }


Different sequencing centres have different delays in turn around from receipt of samples to submission of sequence data. 
This will affect all of the figures shown after this if lineages have geographical variation, as some regions have less up to date data.


```
The lag for this sequencing centre is 11 days
```



The relative growth and decline of the ten most sampled lineages in terms of number of counties they are present in is shown in figure three. 



![Lineages by number of adm2 regions present by epiweek](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/EDIN/figures/report_EDIN_geog_plot_1.png){#geog_plot }










These lineages are shown on the timeline. Each line represents the length of the cluster, from oldest to most recent sampling date.
The dots are sized by the number of sequences taken on that date, and again are colour coded by country.
The raw data has been written to a summary file.




![Timeline of lineages, sized by number of sequences from each country.](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/EDIN/figures/report_EDIN_make_timeline_1.png){#make_timeline }


The date of first sequence in the cluster is shown in figure five for every cluster with date information. 






![Lineage starts per week, split by singletons and non-singletons](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/EDIN/figures/report_EDIN_firsts_plot_1.png){#firsts_plot }

For comparison, here is a plot of the day that every sequence was taken, coloured by country. Note that sequences without dates were not included.


![Sequences taken on each day by country](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/EDIN/figures/report_EDIN_seqs_over_time_1.png){#seqs_over_time }


The map shows the number of sequences sampled in each admin2 region in the UK. The colour scale is the same for all four countries, but with different underlying base colours.





```
There are 147 sequences without enough geographical information to map
from this centre.
```

![Map showing the number of sequences sampled by adm2 region](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/EDIN/figures/report_EDIN_map_1.png){#map }












Other results modules for UK lineage analysis can be added in here if required.

\pagebreak

## Appendix









Below are the raw data tables for each of the figures in the report.

**Table S1** Description of all lineages that have been circulating in the last month, and have more than 5 sequences.


| Lineage name   | Scotland     | Date range     |   Total sequences | Global lineage                     |   Time since last sample (days) | Activity score   |
|:---------------|:-------------|:---------------|------------------:|:-----------------------------------|--------------------------------:|:-----------------|
| UK109          | 240 (100.0%) | Mar-21, Jun-12 |               240 | B.1.5, B.1.5.5                     |                              10 | 0.0347           |
| UK36           | 182 (100.0%) | Mar-21, May-22 |               182 | B.1                                |                              31 | 0.011            |
| UK5            | 157 (100.0%) | Mar-06, Jun-17 |               157 | B.1.1.1, B.1.1.4, B.1.1.p12, B.1.1 |                               5 | 0.1321           |
| UK199          | 137 (100.0%) | Mar-20, Jun-22 |               137 | B.1.5                              |                               0 | active today     |
| UK42           | 125 (100.0%) | Mar-04, May-21 |               125 | B.1.71, B.1                        |                              32 | 0.0197           |
| UK2464         | 54 (100.0%)  | Mar-20, Jun-06 |                54 | B.1.p11                            |                              16 | 0.092            |
| UK304          | 36 (100.0%)  | Apr-16, Jun-02 |                36 | B.1.1.14                           |                              20 | 0.0671           |
| UK72           | 32 (100.0%)  | Mar-11, Apr-25 |                32 | B                                  |                              58 | 0.025            |
| UK2913         | 31 (100.0%)  | Mar-28, May-13 |                31 | B.1.p11                            |                              40 | 0.0383           |
| UK4493         | 26 (100.0%)  | Apr-23, May-19 |                26 | B.1                                |                              34 | 0.0306           |
| UK21           | 26 (100.0%)  | Mar-18, May-23 |                26 | B.1.40                             |                              30 | 0.088            |
| UK1667         | 25 (100.0%)  | Mar-31, May-18 |                25 | B.1.p9                             |                              35 | 0.0571           |
| UK5676         | 24 (100.0%)  | Mar-17, Apr-27 |                24 | B.2                                |                              56 | 0.0318           |
| UK2735         | 19 (100.0%)  | Mar-18, May-02 |                19 | B.1.1                              |                              51 | 0.049            |
| UK107          | 16 (100.0%)  | Mar-21, Apr-24 |                16 | B.2.1                              |                              59 | 0.0384           |
| UK2200         | 15 (100.0%)  | Mar-25, May-05 |                15 | B.1.5, B.1.5.6                     |                              48 | 0.061            |
| UK66           | 14 (100.0%)  | Mar-28, May-20 |                14 | B.1.1.8                            |                              33 | 0.1235           |
| UK43           | 13 (100.0%)  | Mar-26, Apr-18 |                13 | A.5                                |                              65 | 0.0295           |
| UK44           | 13 (100.0%)  | Mar-25, Apr-19 |                13 | B                                  |                              64 | 0.0326           |
| UK436          | 12 (100.0%)  | Apr-13, May-14 |                12 | B.1.5                              |                              39 | 0.0723           |
| UK14           | 10 (100.0%)  | Mar-21, May-21 |                10 | B                                  |                              32 | 0.2118           |
| UK167          | 9 (100.0%)   | Mar-22, May-15 |                 9 | B.1                                |                              38 | 0.1776           |
| UK5498         | 9 (100.0%)   | Mar-12, Apr-27 |                 9 | B.2, B                             |                              56 | 0.1027           |
| UK594          | 8 (100.0%)   | Apr-20, May-01 |                 8 | B                                  |                              52 | 0.0302           |
| UK2916         | 7 (100.0%)   | Mar-04, May-18 |                 7 | B.1                                |                              35 | 0.3571           |
| UK133          | 6 (100.0%)   | Mar-22, Apr-25 |                 6 | B.1                                |                              58 | 0.1172           |

\pagebreak

**Table S2** Raw data for figure two showing lags between the most recent sequence and current date for each sequencing centre


|    | Centre   |   Lag in days |
|---:|:---------|--------------:|
|  0 | EDIN     |            11 |

\pagebreak

**Table S3** Raw data for figure three showing the number of admin2 regions a lineage is present in over time


| Week commencing   |   UK109 |   UK5 |   UK199 |   UK2464 |   UK304 |
|:------------------|--------:|------:|--------:|---------:|--------:|
| 2020-03-01        |       0 |     1 |       0 |        0 |       0 |
| 2020-03-08        |       0 |     4 |       0 |        0 |       0 |
| 2020-03-15        |       1 |     2 |       2 |        2 |       0 |
| 2020-03-22        |       1 |     4 |       1 |        4 |       0 |
| 2020-03-29        |       3 |     4 |       2 |        5 |       0 |
| 2020-04-05        |       4 |     7 |       3 |        4 |       0 |
| 2020-04-12        |       5 |     4 |       4 |        3 |       1 |
| 2020-04-19        |       5 |     5 |       5 |        2 |       1 |
| 2020-04-26        |       5 |     3 |       3 |        2 |       1 |
| 2020-05-03        |       5 |     4 |       4 |        3 |       2 |
| 2020-05-10        |       6 |     2 |       4 |        2 |       2 |
| 2020-05-17        |       4 |     4 |       3 |        0 |       1 |
| 2020-05-24        |       3 |     1 |       2 |        0 |       1 |
| 2020-05-31        |       3 |     0 |       2 |        1 |       2 |
| 2020-06-07        |       2 |     2 |       1 |        0 |       0 |
| 2020-06-14        |       0 |     1 |       0 |        0 |       0 |
| 2020-06-21        |       0 |     0 |       1 |        0 |       0 |

\pagebreak


Table S4 is not appropriate for this report and so has been omitted.




\pagebreak

**Table S5** Raw data for figure five showing when lineages started per day, divided by singletons and non-singletons


| Day        |   Number of singleton starts |   Number of non-singleton starts |   Total |
|:-----------|-----------------------------:|---------------------------------:|--------:|
| 2020-03-04 |                            0 |                                2 |       2 |
| 2020-03-05 |                            0 |                                1 |       1 |
| 2020-03-06 |                            0 |                                2 |       2 |
| 2020-03-07 |                            0 |                                1 |       1 |
| 2020-03-08 |                            0 |                                1 |       1 |
| 2020-03-09 |                            2 |                                2 |       4 |
| 2020-03-11 |                            2 |                                2 |       4 |
| 2020-03-12 |                            3 |                                3 |       6 |
| 2020-03-13 |                            1 |                                0 |       1 |
| 2020-03-17 |                            0 |                                1 |       1 |
| 2020-03-18 |                            0 |                                2 |       2 |
| 2020-03-20 |                            2 |                                3 |       5 |
| 2020-03-21 |                            1 |                                5 |       6 |
| 2020-03-22 |                            1 |                                2 |       3 |
| 2020-03-23 |                            2 |                                2 |       4 |
| 2020-03-24 |                            3 |                                0 |       3 |
| 2020-03-25 |                            0 |                                3 |       3 |
| 2020-03-26 |                            1 |                                1 |       2 |
| 2020-03-27 |                            3 |                                0 |       3 |
| 2020-03-28 |                            1 |                                2 |       3 |
| 2020-03-29 |                            1 |                                1 |       2 |
| 2020-03-30 |                            5 |                                4 |       9 |
| 2020-03-31 |                            5 |                                1 |       6 |
| 2020-04-01 |                            4 |                                1 |       5 |
| 2020-04-02 |                            2 |                                1 |       3 |
| 2020-04-03 |                            2 |                                1 |       3 |
| 2020-04-04 |                            0 |                                1 |       1 |
| 2020-04-06 |                            0 |                                1 |       1 |
| 2020-04-07 |                            3 |                                0 |       3 |
| 2020-04-08 |                            4 |                                0 |       4 |
| 2020-04-10 |                            0 |                                1 |       1 |
| 2020-04-11 |                            1 |                                0 |       1 |
| 2020-04-12 |                            2 |                                1 |       3 |
| 2020-04-13 |                            3 |                                1 |       4 |
| 2020-04-16 |                            1 |                                1 |       2 |
| 2020-04-20 |                            1 |                                1 |       2 |
| 2020-04-21 |                            1 |                                0 |       1 |
| 2020-04-22 |                            2 |                                0 |       2 |
| 2020-04-23 |                            1 |                                1 |       2 |
| 2020-04-24 |                            2 |                                0 |       2 |
| 2020-04-25 |                            0 |                                1 |       1 |
| 2020-05-05 |                            0 |                                1 |       1 |
| 2020-05-08 |                            0 |                                1 |       1 |
| 2020-05-11 |                            1 |                                0 |       1 |
| 2020-05-15 |                            1 |                                0 |       1 |
| 2020-05-19 |                            1 |                                0 |       1 |
| 2020-06-15 |                            1 |                                0 |       1 |

\pagebreak

**Table S6** Raw data for figure six showing the number of sequences taken over time.


| Day        |   Scotland |
|:-----------|-----------:|
| 2020-03-04 |          2 |
| 2020-03-05 |          1 |
| 2020-03-06 |          2 |
| 2020-03-07 |          2 |
| 2020-03-08 |          1 |
| 2020-03-09 |          4 |
| 2020-03-10 |          1 |
| 2020-03-11 |          9 |
| 2020-03-12 |         10 |
| 2020-03-13 |          5 |
| 2020-03-14 |          3 |
| 2020-03-15 |          3 |
| 2020-03-17 |          5 |
| 2020-03-18 |          7 |
| 2020-03-19 |          3 |
| 2020-03-20 |         11 |
| 2020-03-21 |         14 |
| 2020-03-22 |         16 |
| 2020-03-23 |         16 |
| 2020-03-24 |         12 |
| 2020-03-25 |          8 |
| 2020-03-26 |         18 |
| 2020-03-27 |         20 |
| 2020-03-28 |         13 |
| 2020-03-29 |         11 |
| 2020-03-30 |         37 |
| 2020-03-31 |         30 |
| 2020-04-01 |         26 |
| 2020-04-02 |         24 |
| 2020-04-03 |         23 |
| 2020-04-04 |         27 |
| 2020-04-05 |         20 |
| 2020-04-06 |         28 |
| 2020-04-07 |         23 |
| 2020-04-08 |         20 |
| 2020-04-09 |         10 |
| 2020-04-10 |          9 |
| 2020-04-11 |         18 |
| 2020-04-12 |         31 |
| 2020-04-13 |         31 |
| 2020-04-14 |         32 |
| 2020-04-15 |         29 |
| 2020-04-16 |         27 |
| 2020-04-17 |         13 |
| 2020-04-18 |         22 |
| 2020-04-19 |         25 |
| 2020-04-20 |         32 |
| 2020-04-21 |         28 |
| 2020-04-22 |         28 |
| 2020-04-23 |         23 |
| 2020-04-24 |         35 |
| 2020-04-25 |         32 |
| 2020-04-26 |         21 |
| 2020-04-27 |         39 |
| 2020-04-28 |         19 |
| 2020-04-29 |         22 |
| 2020-04-30 |         21 |
| 2020-05-01 |         19 |
| 2020-05-02 |          4 |
| 2020-05-03 |         14 |
| 2020-05-04 |          6 |
| 2020-05-05 |         15 |
| 2020-05-06 |         19 |
| 2020-05-07 |          9 |
| 2020-05-08 |         26 |
| 2020-05-09 |         11 |
| 2020-05-10 |         14 |
| 2020-05-11 |         16 |
| 2020-05-12 |         33 |
| 2020-05-13 |         24 |
| 2020-05-14 |         36 |
| 2020-05-15 |         12 |
| 2020-05-16 |          6 |
| 2020-05-17 |          9 |
| 2020-05-18 |         14 |
| 2020-05-19 |         17 |
| 2020-05-20 |         10 |
| 2020-05-21 |         12 |
| 2020-05-22 |          3 |
| 2020-05-23 |          4 |
| 2020-05-24 |          3 |
| 2020-05-25 |          2 |
| 2020-05-26 |          1 |
| 2020-05-27 |          2 |
| 2020-05-28 |          4 |
| 2020-05-29 |          1 |
| 2020-05-31 |          1 |
| 2020-06-01 |          3 |
| 2020-06-02 |         11 |
| 2020-06-03 |          2 |
| 2020-06-04 |          7 |
| 2020-06-05 |          1 |
| 2020-06-06 |          2 |
| 2020-06-07 |          1 |
| 2020-06-08 |          1 |
| 2020-06-11 |          2 |
| 2020-06-12 |          2 |
| 2020-06-13 |          1 |
| 2020-06-15 |          2 |
| 2020-06-17 |          1 |
| 2020-06-22 |          3 |

\pagebreak

**Table S7** Raw data for the figure seven with the number of sequences assigned to each admin2 region.


| Admin2                 | Country   |   Number of sequences | Sequence group   |
|:-----------------------|:----------|----------------------:|:-----------------|
| ABERDEEN               | Scotland  |                     1 | 1-10             |
| ABERDEENSHIRE          | Scotland  |                     6 | 1-10             |
| ANGUS                  | Scotland  |                    46 | 10-50            |
| CLACKMANNANSHIRE       | Scotland  |                     2 | 1-10             |
| DUMFRIES AND GALLOWAY  | Scotland  |                     2 | 1-10             |
| DUNDEE                 | Scotland  |                   154 | 150-200          |
| EAST LOTHIAN           | Scotland  |                    57 | 50-100           |
| EDINBURGH              | Scotland  |                   456 | 400-500          |
| FALKIRK                | Scotland  |                     4 | 1-10             |
| FIFE                   | Scotland  |                    47 | 10-50            |
| GLASGOW                | Scotland  |                     1 | 1-10             |
| MIDLOTHIAN             | Scotland  |                   146 | 100-150          |
| MORAY                  | Scotland  |                    10 | 10-50            |
| NORTHUMBERLAND         | England   |                     3 | 1-10             |
| PERTHSHIRE AND KINROSS | Scotland  |                    29 | 10-50            |
| SCOTTISH BORDERS       | Scotland  |                   142 | 100-150          |
| SOUTH LANARKSHIRE      | Scotland  |                     4 | 1-10             |
| WEST LOTHIAN           | Scotland  |                   130 | 100-150          |

\pagebreak





