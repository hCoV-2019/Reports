







# Lineages report for SHEF




This report gives summaries of UK specific lineages sequenced by SHEF for week 2020-07-03. 
There are time lags due to batching, curation and analysis, the most recently sampled sequence is 2020-06-24. The analysis (eg time since last sample) is therefore undertaken from this date.
<br/>
1566 sequences in the UK from the sequencing centre SHEF have been included in this analysis.


A few notes: the size of a lineage may be due to a low amount of transmission of this lineage, but it is likely also that it just hasn't been sampled as frequently, especially for newer lineages.
It's also important to realise that these lineages are *estimates* of how we think the virus is spreading in the UK after being introduced from abroad, as the low evolutionary rate of the virus makes it difficult to separate lineages with certainty.



The minimum number of introductions is 105 and the maximum is 488


Sequences which were replicates or too error-prone were removed from this analysis.



91 are lineages which only contained five sequences or fewer, and so have been left out of visualisation in the interests of clarity


Furthermore, those sequences which haven't been sampled in the last month are not shown.



Of the 7 that remain:
4 are pending extinction, ie last seen three weeks ago.
1 has gone quiet, ie hasn't been seen this week.
2 lineages have been continuously circulating.



The following table contains information about the ten largest lineages lineages and the number of sequences the dataset. Information about other lineages is found in the appendix, along with the raw data for all of the other figures.


Each entry is the count of sequences from each lineage in each country, with the percentage of the total sequences from that lineage that this count represents.

"Activity score" is calculated by taking the average gap between sampling for each lineage, and dividing it by the number of days since the lineage was last sampled. Therefore the higher the number, the more active the lineage is.
If the score is above 1, then it has been sampled *more* recently than expected given its average gap size. We might interpret this as an increase in activity.
If the score is below 1, it has been sampled *less* recently than expect given its average gap size, so we might interpret this as a decrease in activity.



The global lineages are correct as of the data release on 2020-05-19


It is written to "summary_files" as "lineage_summary.tsv" for further use, and the full list of lineages is available in the same directory as "all_lineages.csv"



| Lineage name   | England      | Date range     |   Total sequences | Global lineage          |   Time since last sample (days) | Activity score   |
|:---------------|:-------------|:---------------|------------------:|:------------------------|--------------------------------:|:-----------------|
| UK5            | 874 (100.0%) | Mar-02, Jun-24 |               874 | B.1.1.1, B.1.1.5, B.1.1 |                               0 | active today     |
| UK319          | 76 (100.0%)  | Mar-28, Jun-03 |                76 | B.1                     |                              21 | 0.0425           |
| UK107          | 66 (100.0%)  | Mar-05, May-03 |                66 | B.2.1                   |                              52 | 0.0175           |
| UK51           | 32 (100.0%)  | Mar-25, Jun-20 |                32 | B.1.36                  |                               4 | 0.7016           |
| UK42           | 30 (100.0%)  | Mar-20, Jun-03 |                30 | B.1                     |                              21 | 0.1232           |
| UK1177         | 25 (100.0%)  | Apr-22, Jun-09 |                25 | B.1.1                   |                              15 | 0.1333           |
| UK240          | 24 (100.0%)  | Mar-20, Apr-27 |                24 | B.2                     |                              58 | 0.0285           |
| UK2916         | 22 (100.0%)  | Mar-03, Apr-23 |                22 | B.1                     |                              62 | 0.0392           |
| UK24           | 19 (100.0%)  | Mar-21, Apr-10 |                19 | B.2.1                   |                              75 | 0.0148           |
| UK23           | 18 (100.0%)  | Mar-23, May-02 |                18 | B.9                     |                              53 | 0.0444           |


These data is represented in the figure one. Note that the number of sequences is likely to be due more to differing sampling efforts in different regions, rather than genuine differences in numbers of cases. 

The raw data for this bar chart are in the table above.


![Number of sequences sampled in a lineage by country](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/SHEF/figures/report_SHEF_stacked_bars_by_country_1.png){#stacked_bars_by_country }


Different sequencing centres have different delays in turn around from receipt of samples to submission of sequence data. 
This will affect all of the figures shown after this if lineages have geographical variation, as some regions have less up to date data.


```
The lag for this sequencing centre is 9 days
```



The relative growth and decline of the ten most sampled lineages in terms of number of counties they are present in is shown in figure three. 



![Lineages by number of adm2 regions present by epiweek](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/SHEF/figures/report_SHEF_geog_plot_1.png){#geog_plot }










These lineages are shown on the timeline. Each line represents the length of the cluster, from oldest to most recent sampling date.
The dots are sized by the number of sequences taken on that date, and again are colour coded by country.
The raw data has been written to a summary file.




![Timeline of lineages, sized by number of sequences from each country.](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/SHEF/figures/report_SHEF_make_timeline_1.png){#make_timeline }


The date of first sequence in the cluster is shown in figure five for every cluster with date information. 






![Lineage starts per week, split by singletons and non-singletons](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/SHEF/figures/report_SHEF_firsts_plot_1.png){#firsts_plot }

For comparison, here is a plot of the day that every sequence was taken, coloured by country. Note that sequences without dates were not included.


![Sequences taken on each day by country](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/SHEF/figures/report_SHEF_seqs_over_time_1.png){#seqs_over_time }


The map shows the number of sequences sampled in each admin2 region in the UK. The colour scale is the same for all four countries, but with different underlying base colours.





```
There are 4 sequences without enough geographical information to map
from this centre.
```

![Map showing the number of sequences sampled by adm2 region](/cephfs/covid/bham/raccoon-dog/2020-07-03/analysis/7/regional_reports/SHEF/figures/report_SHEF_map_1.png){#map }












Other results modules for UK lineage analysis can be added in here if required.

\pagebreak

## Appendix









Below are the raw data tables for each of the figures in the report.

**Table S1** Description of all lineages that have been circulating in the last month, and have more than 5 sequences.


| Lineage name   | England      | Date range     |   Total sequences | Global lineage          |   Time since last sample (days) | Activity score   |
|:---------------|:-------------|:---------------|------------------:|:------------------------|--------------------------------:|:-----------------|
| UK5            | 874 (100.0%) | Mar-02, Jun-24 |               874 | B.1.1.1, B.1.1.5, B.1.1 |                               0 | active today     |
| UK319          | 76 (100.0%)  | Mar-28, Jun-03 |                76 | B.1                     |                              21 | 0.0425           |
| UK107          | 66 (100.0%)  | Mar-05, May-03 |                66 | B.2.1                   |                              52 | 0.0175           |
| UK51           | 32 (100.0%)  | Mar-25, Jun-20 |                32 | B.1.36                  |                               4 | 0.7016           |
| UK42           | 30 (100.0%)  | Mar-20, Jun-03 |                30 | B.1                     |                              21 | 0.1232           |
| UK1177         | 25 (100.0%)  | Apr-22, Jun-09 |                25 | B.1.1                   |                              15 | 0.1333           |
| UK240          | 24 (100.0%)  | Mar-20, Apr-27 |                24 | B.2                     |                              58 | 0.0285           |
| UK2916         | 22 (100.0%)  | Mar-03, Apr-23 |                22 | B.1                     |                              62 | 0.0392           |
| UK24           | 19 (100.0%)  | Mar-21, Apr-10 |                19 | B.2.1                   |                              75 | 0.0148           |
| UK23           | 18 (100.0%)  | Mar-23, May-02 |                18 | B.9                     |                              53 | 0.0444           |
| UK384          | 18 (100.0%)  | Mar-15, Apr-02 |                18 | B.2.1                   |                              83 | 0.0128           |
| UK5741         | 18 (100.0%)  | Mar-24, May-13 |                18 | B.1                     |                              42 | 0.07             |
| UK6            | 17 (100.0%)  | Mar-22, Jun-16 |                17 | B.1                     |                               8 | 0.6719           |
| UK167          | 17 (100.0%)  | Mar-24, Apr-16 |                17 | B.1                     |                              69 | 0.0208           |
| UK501          | 15 (100.0%)  | Mar-23, Apr-29 |                15 | B.1                     |                              56 | 0.0472           |
| UK131          | 15 (100.0%)  | Mar-20, Apr-10 |                15 | B.15                    |                              75 | 0.02             |
| UK607          | 15 (100.0%)  | Mar-08, Apr-21 |                15 | B                       |                              64 | 0.0491           |
| UK339          | 13 (100.0%)  | Mar-18, Apr-09 |                13 | B.3                     |                              76 | 0.0241           |
| UK199          | 13 (100.0%)  | Mar-24, Apr-12 |                13 | B.1, B.1.5              |                              73 | 0.0217           |
| UK72           | 12 (100.0%)  | Mar-01, Apr-03 |                12 | B                       |                              82 | 0.0366           |
| UK5561         | 10 (100.0%)  | Mar-06, Apr-06 |                10 | B.2.2                   |                              79 | 0.0436           |
| UK601          | 10 (100.0%)  | Mar-22, Apr-29 |                10 | B.10                    |                              56 | 0.0754           |
| UK2735         | 10 (100.0%)  | Mar-24, Apr-21 |                10 | B.1.1                   |                              64 | 0.0486           |
| UK2464         | 9 (100.0%)   | Mar-28, Jun-06 |                 9 | B.1.p11                 |                              18 | 0.4861           |
| UK5676         | 8 (100.0%)   | Mar-21, Apr-18 |                 8 | B.2                     |                              67 | 0.0597           |
| UK12           | 8 (100.0%)   | Mar-26, Apr-22 |                 8 | B.1.p11                 |                              63 | 0.0612           |
| UK4            | 7 (100.0%)   | Mar-07, Apr-02 |                 7 | B                       |                              83 | 0.0522           |
| UK5084         | 6 (100.0%)   | Mar-29, Apr-16 |                 6 | B.1                     |                              69 | 0.0522           |
| UK173          | 6 (100.0%)   | Mar-22, Mar-30 |                 6 | B                       |                              86 | 0.0186           |
| UK15           | 6 (100.0%)   | Mar-02, Mar-31 |                 6 | B.1.1                   |                              85 | 0.0682           |
| UK116          | 6 (100.0%)   | Mar-24, Apr-02 |                 6 | B.1                     |                              83 | 0.0217           |
| UK109          | 6 (100.0%)   | Mar-27, May-10 |                 6 | B.1.5                   |                              45 | 0.1956           |

\pagebreak

**Table S2** Raw data for figure two showing lags between the most recent sequence and current date for each sequencing centre


|    | Centre   |   Lag in days |
|---:|:---------|--------------:|
|  0 | SHEF     |             9 |

\pagebreak

**Table S3** Raw data for figure three showing the number of admin2 regions a lineage is present in over time


| Week commencing   |   UK5 |   UK319 |   UK51 |   UK42 |   UK1177 |   UK6 |   UK2464 |
|:------------------|------:|--------:|-------:|-------:|---------:|------:|---------:|
| 2020-03-01        |     1 |       0 |      0 |      0 |        0 |     0 |        0 |
| 2020-03-08        |     1 |       0 |      0 |      0 |        0 |     0 |        0 |
| 2020-03-15        |     2 |       0 |      0 |      1 |        0 |     0 |        0 |
| 2020-03-22        |     2 |       1 |      1 |      2 |        0 |     1 |        1 |
| 2020-03-29        |     1 |       1 |      1 |      2 |        0 |     1 |        1 |
| 2020-04-05        |     2 |       1 |      1 |      1 |        0 |     1 |        0 |
| 2020-04-12        |     2 |       1 |      1 |      0 |        0 |     1 |        0 |
| 2020-04-19        |     1 |       1 |      1 |      1 |        1 |     1 |        1 |
| 2020-04-26        |     1 |       1 |      1 |      0 |        1 |     1 |        1 |
| 2020-05-03        |     1 |       1 |      1 |      0 |        0 |     0 |        0 |
| 2020-05-10        |     1 |       1 |      1 |      1 |        1 |     0 |        1 |
| 2020-05-17        |     1 |       0 |      0 |      0 |        1 |     0 |        1 |
| 2020-05-24        |     1 |       1 |      1 |      0 |        1 |     0 |        0 |
| 2020-05-31        |     1 |       1 |      1 |      1 |        0 |     0 |        1 |
| 2020-06-07        |     1 |       0 |      1 |      0 |        1 |     0 |        0 |
| 2020-06-14        |     1 |       0 |      1 |      0 |        0 |     1 |        0 |
| 2020-06-21        |     1 |       0 |      0 |      0 |        0 |     0 |        0 |

\pagebreak


Table S4 is not appropriate for this report and so has been omitted.




\pagebreak

**Table S5** Raw data for figure five showing when lineages started per day, divided by singletons and non-singletons


| Day        |   Number of singleton starts |   Number of non-singleton starts |   Total |
|:-----------|-----------------------------:|---------------------------------:|--------:|
| 2020-03-01 |                            0 |                                1 |       1 |
| 2020-03-02 |                            0 |                                3 |       3 |
| 2020-03-03 |                            0 |                                1 |       1 |
| 2020-03-05 |                            0 |                                1 |       1 |
| 2020-03-06 |                            0 |                                1 |       1 |
| 2020-03-07 |                            0 |                                1 |       1 |
| 2020-03-08 |                            1 |                                1 |       2 |
| 2020-03-15 |                            0 |                                1 |       1 |
| 2020-03-16 |                            1 |                                0 |       1 |
| 2020-03-17 |                            0 |                                1 |       1 |
| 2020-03-18 |                            0 |                                2 |       2 |
| 2020-03-19 |                            1 |                                1 |       2 |
| 2020-03-20 |                            1 |                                3 |       4 |
| 2020-03-21 |                            1 |                                4 |       5 |
| 2020-03-22 |                            2 |                                3 |       5 |
| 2020-03-23 |                            1 |                                4 |       5 |
| 2020-03-24 |                            4 |                                7 |      11 |
| 2020-03-25 |                            9 |                                6 |      15 |
| 2020-03-26 |                            4 |                                3 |       7 |
| 2020-03-27 |                            1 |                                3 |       4 |
| 2020-03-28 |                            1 |                                2 |       3 |
| 2020-03-29 |                            1 |                                2 |       3 |
| 2020-03-30 |                            1 |                                2 |       3 |
| 2020-03-31 |                            2 |                                0 |       2 |
| 2020-04-01 |                            3 |                                1 |       4 |
| 2020-04-02 |                            1 |                                1 |       2 |
| 2020-04-03 |                            4 |                                0 |       4 |
| 2020-04-04 |                            1 |                                0 |       1 |
| 2020-04-05 |                            4 |                                0 |       4 |
| 2020-04-09 |                            2 |                                0 |       2 |
| 2020-04-11 |                            1 |                                0 |       1 |
| 2020-04-13 |                            1 |                                0 |       1 |
| 2020-04-14 |                            1 |                                0 |       1 |
| 2020-04-15 |                            2 |                                0 |       2 |
| 2020-04-16 |                            1 |                                0 |       1 |
| 2020-04-19 |                            1 |                                1 |       2 |
| 2020-04-20 |                            1 |                                0 |       1 |
| 2020-04-21 |                            2 |                                0 |       2 |
| 2020-04-22 |                            0 |                                1 |       1 |
| 2020-04-23 |                            1 |                                1 |       2 |
| 2020-04-27 |                            0 |                                1 |       1 |
| 2020-04-28 |                            1 |                                0 |       1 |
| 2020-05-01 |                            1 |                                0 |       1 |
| 2020-05-05 |                            1 |                                0 |       1 |
| 2020-05-10 |                            1 |                                0 |       1 |
| 2020-05-14 |                            1 |                                0 |       1 |
| 2020-05-30 |                            0 |                                1 |       1 |
| 2020-06-08 |                            1 |                                0 |       1 |

\pagebreak

**Table S6** Raw data for figure six showing the number of sequences taken over time.


| Day        |   England |
|:-----------|----------:|
| 2020-03-01 |         1 |
| 2020-03-02 |         4 |
| 2020-03-03 |         2 |
| 2020-03-05 |         1 |
| 2020-03-06 |         1 |
| 2020-03-07 |         1 |
| 2020-03-08 |         2 |
| 2020-03-09 |         2 |
| 2020-03-12 |         3 |
| 2020-03-13 |         1 |
| 2020-03-15 |         3 |
| 2020-03-16 |         5 |
| 2020-03-17 |         4 |
| 2020-03-18 |        15 |
| 2020-03-19 |         9 |
| 2020-03-20 |        15 |
| 2020-03-21 |        26 |
| 2020-03-22 |        24 |
| 2020-03-23 |        31 |
| 2020-03-24 |        53 |
| 2020-03-25 |        74 |
| 2020-03-26 |        53 |
| 2020-03-27 |        36 |
| 2020-03-28 |        30 |
| 2020-03-29 |        30 |
| 2020-03-30 |        55 |
| 2020-03-31 |        30 |
| 2020-04-01 |        53 |
| 2020-04-02 |        70 |
| 2020-04-03 |        35 |
| 2020-04-04 |        19 |
| 2020-04-05 |        13 |
| 2020-04-06 |        18 |
| 2020-04-07 |        11 |
| 2020-04-08 |        22 |
| 2020-04-09 |        34 |
| 2020-04-10 |        39 |
| 2020-04-11 |        40 |
| 2020-04-12 |        23 |
| 2020-04-13 |        16 |
| 2020-04-14 |        26 |
| 2020-04-15 |        26 |
| 2020-04-16 |        24 |
| 2020-04-17 |        33 |
| 2020-04-18 |        34 |
| 2020-04-19 |        23 |
| 2020-04-20 |        16 |
| 2020-04-21 |        25 |
| 2020-04-22 |        34 |
| 2020-04-23 |        21 |
| 2020-04-24 |        11 |
| 2020-04-25 |         9 |
| 2020-04-26 |        11 |
| 2020-04-27 |        31 |
| 2020-04-28 |        17 |
| 2020-04-29 |        26 |
| 2020-04-30 |        12 |
| 2020-05-01 |        17 |
| 2020-05-02 |        15 |
| 2020-05-03 |         7 |
| 2020-05-04 |        11 |
| 2020-05-05 |         5 |
| 2020-05-06 |         5 |
| 2020-05-07 |         5 |
| 2020-05-08 |         9 |
| 2020-05-09 |         4 |
| 2020-05-10 |        17 |
| 2020-05-11 |        17 |
| 2020-05-12 |         7 |
| 2020-05-13 |        11 |
| 2020-05-14 |         6 |
| 2020-05-15 |        10 |
| 2020-05-16 |         7 |
| 2020-05-17 |         3 |
| 2020-05-18 |         6 |
| 2020-05-19 |         3 |
| 2020-05-20 |         4 |
| 2020-05-21 |         4 |
| 2020-05-22 |         7 |
| 2020-05-23 |         3 |
| 2020-05-24 |         3 |
| 2020-05-25 |         3 |
| 2020-05-26 |         5 |
| 2020-05-27 |         5 |
| 2020-05-28 |         5 |
| 2020-05-29 |         3 |
| 2020-05-30 |         1 |
| 2020-06-01 |         4 |
| 2020-06-02 |         4 |
| 2020-06-03 |         6 |
| 2020-06-04 |         3 |
| 2020-06-05 |         2 |
| 2020-06-06 |         2 |
| 2020-06-07 |         4 |
| 2020-06-08 |         4 |
| 2020-06-09 |         3 |
| 2020-06-10 |         4 |
| 2020-06-11 |         3 |
| 2020-06-12 |         4 |
| 2020-06-13 |         5 |
| 2020-06-14 |         6 |
| 2020-06-15 |         9 |
| 2020-06-16 |         3 |
| 2020-06-17 |         1 |
| 2020-06-18 |         3 |
| 2020-06-19 |         3 |
| 2020-06-20 |         1 |
| 2020-06-24 |         1 |

\pagebreak

**Table S7** Raw data for the figure seven with the number of sequences assigned to each admin2 region.


| Admin2                   | Country   |   Number of sequences | Sequence group   |
|:-------------------------|:----------|----------------------:|:-----------------|
| DERBYSHIRE               | England   |                    14 | 10-50            |
| EAST RIDING OF YORKSHIRE | England   |                     8 | 1-10             |
| SOUTH YORKSHIRE          | England   |                  1540 | >500             |

\pagebreak





