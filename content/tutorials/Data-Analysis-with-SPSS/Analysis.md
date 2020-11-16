---
title: Analysis
#linktitle: Analysis
toc: true
type: docs
date: "2019-05-05T00:00:00Z"
draft: false
menu:
  Data-Analysis-with-SPSS:
    parent: Overview
    weight: 2

# Prev/next pager order (if `docs_section_pager` enabled in `params.toml`)
weight: 2
---

## *Before Analysis*
Before we jump into analysis, it is wise to have a look on the key terms often used in analyzing the data.\
The users must build a sound understanding of statistical concepts such as hypothesis formulation and testing, distribution, and some widely known parameters(mean, median, mode , standard deviation, standard error).
## **Doing analysis**
This tutorial will follow an analytical approach based on the data measurement types. Lets begin with analyzing the nominal/categorical data.
The descriptive statistics is the best suitable option for such categories of data. Frequency and test of independence are most widely used analysis for nominal variables. 
### *Descriptives for Nominal/categorical data*
To perform this analysis, we can go Analyze->Descriptive statistics->Crosstab. The sample output image below shows independence test between gender and attending a meeting.{{< figure library="true" src="Independence test.jpg" >}}
We should focus on these two things-- expected cell count message below the table and significance level. Usually, if more than 20% cells have expected cell count less than 5, we should NOT rely the test results. In this outcome, we see the significance level is 0.016 for the Pearson chi-square and 0% cells have expected count less than 5. Hence, we conclude that null hypthesis is rejected. And, there exists an association between gender and attendance in open meetings. In other words, individual gender can be an important factor in deciding the attendance of an open meeting. If the expected cell counts are less than 5 in more than 20% of the cells, researchers use Fisher's exact test to test the independence, but it is commonly acceptable for the 2x2 tables.
Selecting the chart option from the crosstab menu will result the percentage wise distribution of the variables. This way, we can get graph and statistical result of nominal variables. Usually, 2*2 and 3*3 tables are commonly reported. Though one can use more dimensions in the table, yet to avoid complexity, it is better to keep the analysis and interpretation simple with two-three columns and/or rows.

### Correlation
If the variables are ordinal, coorelation scores can be used by selecting Crosstab->statistics->correlation. We should report Spearman's correlation score from the table for the ordinal variables as they are calculated using rank order. If the variable is scale, use Pearson's correlation score and related significance level from the output table.

#### **Other Statistical Options**

The above scores are the widely used and primary reported values to test hypothesis. Based on the variable type (nominal/ordinal/scale) and your own understanding of statistical terms, other scores can be reported from the options given in the statistics tab. 