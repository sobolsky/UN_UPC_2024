---
layout: default
title: Anatomy of Solidarity
description: Anatomy of Solidarity in United Nations Voting
show_downloads: false
google_analytics:
permalink: /un/upc
---

# 1. Ukraine Political Conditions (2022–2023) - Research Highlights

## Intro
This is the first article in a series dedicated to the study of the nature of political solidarity in the voting of the United Nations General Assembly (UNGA) on six resolutions within the theme 'UKRAINE - POLITICAL CONDITIONS' for the years 2022–2023. At the time of publication of this article, the UNGA voting in 2024 on this topic had not taken place.

List of resolutions examined in this study:

* [A/RES/ES-11/6](https://digitallibrary.un.org/record/4003921) Principles of the Charter of the United Nations underlying a comprehensive, just and lasting peace in Ukraine / 2023–02–23
* [A/RES/ES-11/5](https://digitallibrary.un.org/record/3994052) Furtherance of remedy and reparation for aggression against Ukraine / 2022–11–14
* [A/RES/ES-11/4](https://digitallibrary.un.org/record/3990400) Territorial integrity of Ukraine : defending the principles of the Charter of the United Nations / 2022–10–12
* [A/RES/ES-11/3](https://digitallibrary.un.org/record/3967778) Suspension of the rights of membership of the Russian Federation in the Human Rights Council / 2022–04–07
* [A/RES/ES-11/2](https://digitallibrary.un.org/record/3965954) Humanitarian consequences of the aggression against Ukraine / 2022–03–24
* [A/RES/ES-11/1](https://digitallibrary.un.org/record/3959039) Aggression against Ukraine / 2022–03–02

In the General Assembly of the United Nations, a total of 193 countries can participate in the voting on resolutions. Each country has one vote. For more information about the participating countries in the UN General Assembly, please refer to the official UN website.

The aim of this study is to identify international political multipolarity within the context of UN General Assembly (UNGA) voting. To achieve this, a voting network was constructed to identify clusters, or `Solidarity Groups` (for more details about `Solidarity Groups`, please see below in this article.) This voting network was built based on the voting outcomes of these six resolutions. Henceforth, this network will be referred to as the `Solidarity Network`.

The main content of this study involves morphological and quantitative analyses of `Solidarity Groups` within the `Solidarity Network`. Morphological analysis entails examining the composition of `Solidarity Groups` within the `Solidarity Network` and the degree of interconnectedness among them.

Quantitative analysis of `Solidarity Groups` is based on three indicators for each of the 193 countries:

* **Population mid-year estimates** (millions), 2022. This indicator represents an estimate of the population size of each country in the middle of 2022, measured in millions of people. In tables and bar plots, this indicator will be denoted as **Population, M**.

* **Primary energy production** (PJ), 2020. Primary energy refers to energy derived directly from natural sources such as oil, gas, coal, nuclear fuel, hydro, wind, solar energy, etc. This indicator allows assessing the degree of a country's self-sufficiency in energy production and the sources of energy it utilizes. It is measured in petajoules (PJ), which is a unit of energy equal to 10¹⁵ joules. In tables and bar plots, this indicator will be denoted as **Energy, PJ**.

* **GDP in current prices** (millions of US dollars), for the year 2021. This represents an estimate of the gross domestic product (GDP) of each country at current prices as of the end of 2021, measured in millions of US dollars. In tables and bar plots, this indicator will be denoted as **GDP, M$**.

> [!NOTE]
> These data were obtained from the [Statistical Yearbook 66th issue (2023)](https://unstats.un.org/UNSDWebsite/Publications/StatisticalYearbook/).

Below in **Fig. 1** is the `Complete Solidarity Network`. This network is the key outcome of the study on voting regarding the theme of *Ukraine Political Conditions (2022–2023) in the UN*. Subsequently, in this article, the principles of constructing this network will be discussed, along with some research findings based on it.

![MacDown Screenshot](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/usg_full_pre.jpg)

**Fig. 1** Anatomy of Solidarity in UN Voting: Ukraine Political Conditions (2022–2023). `Complete Solidarity Network` (Population). Node sizes correspond to population density. [Click to enlarge the full network image](https://raw.githubusercontent.com/alexbukreev/UN_USG_2023/main/usg_full.jpg)

> [!NOTE]
> Download the `Complete Solidarity Network (Population)` in JPEG format [usg_full.jpg](https://raw.githubusercontent.com/alexbukreev/UN_USG_2023/main/usg_full.jpg).

> [!NOTE]
> Download the `Solidarity Network` in GEXF format ([UN_UKRAINE - POLITICAL_CONDITIONS_full_network.gexf](https://github.com/alexbukreev/UN_USG_2024/blob/main/UN_UKRAINE--POLITICAL_CONDITIONS_full_network.gexf))

## The content of this article
### 1. Voting Profiles
### 2. Solidarity Groups
- 2.1 Complete Solidarity Groups
- 2.2 Incomplete Solidarity Groups

### 3. Solidarity Network. Construction Principle
### 4. Complete Solidarity Groups
* 4.1. Group –1–1–1–1–1–1
* 2.2. Group00–10–10
* 2.3. Group00–1000
* 2.4. Group 000000
* 2.5. Group100101
* 2.6. Group110001
* 2.7. Group110101
* 2.8. Group110111
* 2.9. Group111101
* 2.10. Group111111

### 5. Conclusion

## 1. Voting Profiles
Each country can vote on each resolution in four different ways: for, against, abstain, and not participate in the vote. Let’s denote these possibilities as follows:

> [!NOTE]
> **-1** — the country votes against the resolution,
> 
> **0** — the country abstains from voting,
> 
> **1** — the country votes for the resolution,
> 
> **n** — the country did not participate in the vote.

The `Voting Profile` for each country will be called a simple sequence, consisting of **-1**,** 0**, **1**, and **n**, reflecting the country’s position on each vote. The length of such a sequence for each country is the same and equals the number of resolutions on the voting topic. In our case, it’s six.

In the `Voting Profile`, these symbols are arranged in chronological order, starting with the result of the earlier resolution and ending with the result of the later one.

Thus, the first symbol in the `Voting Profile` of a participating country represents its position on resolution [A/RES/ES-11/1](https://digitallibrary.un.org/record/3959039), the second symbol represents the position on resolution [A/RES/ES-11/2](https://digitallibrary.un.org/record/3965954), and so on, up to the sixth symbol, which corresponds to the vote on resolution [A/RES/ES-11/6](https://digitallibrary.un.org/record/4003921).

For example, Russia voted “against” all resolutions, so its voting profile looks like this: -1–1–1–1–1–1. The United States voted “for” all resolutions, so its profile looks like this: 111111. The profile of Algeria, for instance, looks like this: 00–1000, and Afghanistan’s profile looks like this: 11n111. The first three profiles in the example are `Complete Voting Profiles`, as the countries with these profiles participated in all six votes on the resolutions.

A profile similar to Afghanistan’s voting profile in this study will be referred to as an Incomplete Voting Profile because countries with such `Voting Profiles` have missed at least one vote on any resolution.

An `Incomplete Voting Profile` can include skips in different numbers of votes, from one, as in the case of Afghanistan, to all six votes, as in the case of Azerbaijan (its `Voting Profile`: nnnnnn).

Thus, `Voting Profiles` can not only be categorized into complete and incomplete, but also ranked based on the `Voting Participation Degree`. The `Voting Participation Degree` is a number from 0 to 1, where 0 corresponds to the Voting Profile of a country that did not participate in any of the votes, and 1 corresponds to the profile of a country with a `Complete Voting Profile`.

The `Voting Participation Degree` is calculated as the ratio of the actual number of votes to the maximum possible (in our case, 6). For example, the Voting Profile for Afghanistan (11n111) would be 5/6 or ~0.8. The `Voting Participation Degree` indicates the involvement of a particular country in the voting process on the entire topic.

Below, in **Table 1.1.1**, a list of all participating countries in the UNGA is provided, along with their `Voting Profiles` on the topic, arranged in order of increasing `Voting Participation Degree`. Additionally, for each country in the table, a demographic indicator is provided — population estimates for 2022 according to UN data in millions of people (Population, M).

<script src="https://gist.github.com/alexbukreev/91b6f101e46509511aabfdf64562b845.js"></script>

**Table 1.1.1.** List of all 193 participating countries in the UNGA and their `Voting Profiles` on the topic, arranged in order of increasing `Voting Participation Degree`.

Thus, all 193 participating countries formed 46 `Voting Profiles`. **Table 1.1.2** provides key country-specific and demographic indicators for all 46 Voting Profiles for each `Voting Group`: Country Count; Population, M; Country Share, % (calculated as the ratio of the number of countries with the same Voting Profile to the total number of participating countries) and Relative Population, % (calculated as the ratio of the total population of countries with the same `Voting Profile` to the total population of all participating countries).

|    | Votes Profile   |   Сountries Сount |   Population, M |   Country Share, % |   Relative Population, % |
|---:|:----------------|------------------:|----------------:|-------------------:|-------------------------:|
|  1 | nnnnnn          |                 4 |           67.80 |               2.10 |                     0.90 |
|  2 | nn0nnn          |                 1 |           27.90 |               0.50 |                     0.40 |
|  3 | nnn1n1          |                 1 |           37.50 |               0.50 |                     0.50 |
|  4 | 00nn0n          |                 1 |            1.70 |               0.50 |                     0.00 |
|  5 | 11nnn1          |                 1 |            0.20 |               0.50 |                     0.00 |
|  6 | 1n11nn          |                 1 |            0.10 |               0.50 |                     0.00 |
|  7 | nnn000          |                 1 |           13.90 |               0.50 |                     0.20 |
|  8 | 0000nn          |                 1 |           65.50 |               0.50 |                     0.80 |
|  9 | 0101nn          |                 1 |           17.30 |               0.50 |                     0.20 |
| 10 | 11n10n          |                 1 |            5.50 |               0.50 |                     0.10 |
| 11 | 11nn11          |                 1 |            1.10 |               0.50 |                     0.00 |
| 12 | 1nn111          |                 1 |           17.60 |               0.50 |                     0.20 |
| 13 | n0000n          |                 1 |            1.20 |               0.50 |                     0.00 |
| 14 | n0010n          |                 1 |            2.10 |               0.50 |                     0.00 |
| 15 | 00-1n-10        |                 1 |           88.60 |               0.50 |                     1.10 |
| 16 | 000n00          |                 1 |            6.30 |               0.50 |                     0.10 |
| 17 | 00n000          |                 1 |            2.80 |               0.50 |                     0.00 |
| 18 | 11110n          |                 1 |            0.10 |               0.50 |                     0.00 |
| 19 | 1111n1          |                 2 |           99.10 |               1.00 |                     1.30 |
| 20 | 11n101          |                 2 |           18.50 |               1.00 |                     0.20 |
| 21 | 11n111          |                 4 |           75.20 |               2.10 |                     0.90 |
| 22 | 1n1111          |                 1 |            0.80 |               0.50 |                     0.00 |
| 23 | n0-10-10        |                 1 |          123.40 |               0.50 |                     1.60 |
| 24 | n0-1000         |                 1 |           34.60 |               0.50 |                     0.40 |
| 25 | n00010          |                 1 |            8.80 |               0.50 |                     0.10 |
| 26 | -1-1-1-1-1-1    |                 4 |          202.40 |               2.10 |                     2.60 |
| 27 | -1-1-10-1-1     |                 1 |            3.70 |               0.50 |                     0.00 |
| 28 | 00-1-1-1-1      |                 1 |            7.00 |               0.50 |                     0.10 |
| 29 | 00-10-1-1       |                 1 |           22.60 |               0.50 |                     0.30 |
| 30 | 00-10-10        |                 4 |         1459.00 |               2.10 |                    18.40 |
| 31 | 00-1000         |                 9 |          217.70 |               4.70 |                     2.70 |
| 32 | 000000          |                 9 |         1867.80 |               4.70 |                    23.60 |
| 33 | 000100          |                 1 |           35.60 |               0.50 |                     0.40 |
| 34 | 000101          |                 1 |           29.60 |               0.50 |                     0.40 |
| 35 | 010001          |                 1 |           10.90 |               0.50 |                     0.10 |
| 36 | 010100          |                 1 |          171.20 |               0.50 |                     2.20 |
| 37 | 010101          |                 1 |           44.50 |               0.50 |                     0.60 |
| 38 | 100101          |                 2 |            3.00 |               1.00 |                     0.00 |
| 39 | 11-1100         |                 1 |            2.40 |               0.50 |                     0.00 |
| 40 | 110001          |                 2 |           74.00 |               1.00 |                     0.90 |
| 41 | 110101          |                23 |         1018.10 |              11.90 |                    12.80 |
| 42 | 110111          |                10 |          255.60 |               5.20 |                     3.20 |
| 43 | 111001          |                 1 |           10.40 |               0.50 |                     0.10 |
| 44 | 1111-11         |                 1 |            0.40 |               0.50 |                     0.00 |
| 45 | 111101          |                10 |           48.90 |               5.20 |                     0.60 |
| 46 | 111111          |                76 |         1724.70 |              39.40 |                    21.80 |

**Table 1.1.2.** Country and demographic indicators for all 46 `Voting Profiles` (aggregated by `Voting Profile`)

For clarity, below is a bar plot (**Fig. 1.1.1**) constructed based on the values of relative country-specific and demographic indicators from **Table 1.1.2**.

![MacDown Screenshot](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/votes_profiles_reports/vp_plot_usg_2024_pre.png)

**Fig. 1.1.1** Relative country-specific and demographic Indicators for All 46 `Voting Profiles` (aggregated by `Votes profile`). [Click to enlarge the image](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/votes_profiles_reports/vp_plot_usg_2024.png)

Similarly to **Table 1.1.2**, **Table 1.1.3** has been constructed, where the Voting Participation Degree is used instead of the `Voting Profile` as the basis.

|    |   Voting Participation Degree |   Сountries Сount |   Population, M |   Country Share, % |   Relative Population, % |
|---:|------------------------------:|------------------:|----------------:|-------------------:|-------------------------:|
|  1 |                          0.00 |              4.00 |           67.80 |               2.10 |                     0.90 |
|  2 |                          0.20 |              1.00 |           27.90 |               0.50 |                     0.40 |
|  3 |                          0.30 |              1.00 |           37.50 |               0.50 |                     0.50 |
|  4 |                          0.50 |              4.00 |           15.90 |               2.10 |                     0.20 |
|  5 |                          0.70 |              7.00 |          110.30 |               3.60 |                     1.40 |
|  6 |                          0.80 |             16.00 |          458.20 |               8.30 |                     5.80 |
|  7 |                          1.00 |            160.00 |         7209.50 |              82.90 |                    90.90 |


**Table 1.1.3** Country and demographic indicators for different values of the `Voting Participation Degree` (aggregated by `Voting Participation Degree`)

For clarity, below is a bar plot (**Fig. 1.1.2**) constructed based on the values of Country Share, %, and Relative Population, % from **Table 1.1.3**.
![MacDown Screenshot](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/votes_profiles_reports/vpr_plot_usg_2024_pre.png)

**Fig. 1.1.3** Relative country-specific and demographic indicators for all values of the `Voting Participation Degree`. [Click to enlarge the image](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/votes_profiles_reports/vpr_plot_usg_2024.png)

Similarly to the previous two tables, **Table 1.1.4** has been constructed to compare countries with complete and incomplete `Voting Profiles`. The values in this table can indicate the degree of involvement in the voting process for countries with these types of `Voting Profiles`. That is, the majority of countries (160 out of 193, 83%) are fully engaged in the voting topic, as they have a `Complete Voting Profile`.

|    | Votes Profile Type   |   Сountries Сount |   Population, M |   Country Share, % |   Relative Population, % |
|---:|:---------------------|------------------:|----------------:|-------------------:|-------------------------:|
|  1 | Complete Profile     |               160 |         7209.50 |              82.90 |                    90.90 |
|  2 | Incomplete Profile   |                33 |          717.60 |              17.10 |                     9.20 |

**Table 1.1.4.** Country-specific and demographic indicators for two types of countries — those with complete and incomplete `Voting Profiles`.

Below is a bar plot (**Fig. 1.1.3**) constructed based on the values of Country Share, %, and Relative Population, % from **Table 1.1.4**.

![MacDown Screenshot](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/votes_profiles_reports/vpt_plot_usg_2024_pre.png)

**Fig. 1.1.4** Country-specific and demographic indicators for two types of countries — those with complete and incomplete `Voting Profiles`. [Click to enlarge the image](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/votes_profiles_reports/vpt_plot_usg_2024.png)

Below, in **Fig. 1.1.5** and **Fig. 1.1.6**, two maps are provided, showing countries with complete and incomplete `Voting Profiles` respectively. The size of the circles corresponds to the values of `Relative Population`, % of these countries.

![MacDown Screenshot](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/votes_profiles_reports/full_prof_world_map_2024_pre.png)

**Fig. 1.1.5** Countries with `Complete Voting Profiles` and their Relative Population, %. [Click to enlarge the image](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/votes_profiles_reports/full_prof_world_map_2024.png)

![MacDown Screenshot](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/votes_profiles_reports/full_prof_world_map_2024_pre.png)

**Fig. 1.1.6** Countries with `Incomplete Voting Profiles` and their Relative Population, %. [Click to enlarge the image](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/votes_profiles_reports/full_prof_world_map_2024.png)

> **The main conclusion** that can be drawn from the analysis of `Voting Profiles` is that countries with the most active participation in voting (with `Complete Voting Profiles`) have significant weight both in terms of the number of countries (82% of all participating countries) and in terms of population (90% of the total population of participating countries).

## 2. Solidarity Groups

These is group of countries that have at least one identical voting position.

### 2.1 Complete Solidarity Groups
If two or more countries have the same `Complete Voting Profile`, these countries form groups, which will be referred to as `Complete Solidarity Groups` here. `Complete Solidarity` Group consists of countries with identical `Complete Voting Profiles`. Countries within the same `Complete Solidarity Group` always vote the same way on all resolutions (here, each country participates in six votes).

Let’s agree that `Complete Solidarity Groups` cannot consist of countries with `Incomplete Voting Profiles`. That is, groups where the voting profile includes one or more “n” values are excluded from `Complete Solidarity Groups`. This is because the focus is on solidarity in UN General Assembly voting, not on “non-attendance solidarity.” Overall, the reasons why a particular country did not attend the vote can be diverse and depend on the specific situation and political context of each country.

In total, there are 21 `Complete Voting Profiles` for this voting theme: -1–1–1–1–1–1, -1–1–10–1–1, 00–1–1–1–1, 00–10–1–1, 00–10–10, 00–1000, 000000, 000100, 000101, 010001, 010100, 010101, 100101, 11–1100, 110001, 110101, 110111, 111001, 1111–11, 111101, 111111. Among them, groups with two or more countries form 10 profiles. Thus, for the “UKRAINE — POLITICAL CONDITIONS” theme for 2022–2023, 10 `Complete Solidarity Groups` have formed. These profiles, along with their country-specific and demographic indicators, are provided below in **Table 1.2.1**.

|    | Complete Solidarity Group   |   Сountries Count |   Population, M |   Country Share, % |   Relative Population, % |
|---:|:----------------------------|------------------:|----------------:|-------------------:|-------------------------:|
|  1 | -1-1-1-1-1-1                |                 4 |          202.40 |               2.10 |                     2.60 |
|  2 | 00-10-10                    |                 4 |         1459.00 |               2.10 |                    18.40 |
|  3 | 00-1000                     |                 9 |          217.70 |               4.70 |                     2.70 |
|  4 | 000000                      |                 9 |         1867.80 |               4.70 |                    23.60 |
|  5 | 100101                      |                 2 |            3.10 |               1.00 |                     0.00 |
|  6 | 110001                      |                 2 |           74.00 |               1.00 |                     0.90 |
|  7 | 110101                      |                23 |         1018.10 |              11.90 |                    12.80 |
|  8 | 110111                      |                10 |          255.60 |               5.20 |                     3.20 |
|  9 | 111101                      |                10 |           49.00 |               5.20 |                     0.60 |
| 10 | 111111                      |                76 |         1725.20 |              39.40 |                    21.80 |

**Table 1.2.1** `Complete Solidarity Groups` with country-specific and demographic Indicators.

Below, based on the relative country-specific and demographic indicators from **Table 1.2.1**, a bar plot **Fig. 1.2.1** is constructed.

![MacDown Screenshot](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/sol_groups_reports/csg_plot_usg_2024_pre.png)

**Fig. 1.2.1** `Complete Solidarity Groups` with country-specific and demographic Indicators. [Click to enlarge the image](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/sol_groups_reports/csg_plot_usg_2024.png)

Below, **Table 1.2.2** compares these indicators for countries forming `Complete Solidarity Groups` and other `Voting Profile` countries in the voting (“Other Countries Groups” in the table).

![MacDown Screenshot](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/sol_groups_reports/tsg_plot_usg_2024_pre.png)

**Fig. 1.2.2** Country-specific and demographic indicators for Complete Solidarity Group countries and Other Countries Groups in the voting. [Click to enlarge the image](https://raw.githubusercontent.com/alexbukreev/UN_USG_2024/main/sol_groups_reports/tsg_plot_usg_2024.png)

> **The main conclusion** drawn from comparing `Complete Solidarity Group` countries with other participating countries in the voting is that the countries forming `Complete Solidarity Groups` hold significant weight both in terms of the number of countries (77% of all participating countries) and the population size (86% of the total population of participating countries). In the `Solidarity Network`, these form the main core clusters of the network.

### 2.2 Partial Solidarity Groups

In `Complete Solidarity Groups`, solidarity between countries is maximum and equals 6 (6 out of 6 possible matches in voting). The `Partial Solidarity Group` consists of countries with identical values in their Solidarity Profiles at corresponding positions, but not ‘n’.

Countries that do not have full solidarity among them can form groups with varying Solidarity Degree. The `Solidarity Degree` of a `Solidarity Group` is calculated as the ratio of the number of identical values in the `Voting Profiles` to the total number of votes, expressed both as a percentage and numerically (whole numbers from 1 to the total number of votes).

For example, a country with aVoting Profile of 111111 and a country with a `Voting Profile` of 111011 are in solidarity in their voting in 5 out of 6 cases, meaning their `Solidarity Degree` is 83% (their voting outcomes align on all resolutions except the 4th).

Another example is a country with a `Voting Profile` of 00–1n-10 and a country with a `Voting Profile` of 0000nn, which are in solidarity in 2 out of 6 cases, resulting in a `Solidarity Degree` of 33% (their voting outcomes match only on the first two resolutions).

Groups of countries with a `Solidarity Degree` less than 100% will be referred to as Partial `Solidarity Groups`.

For example, for the group of countries with a `Voting Profile` of 111111, there are groups of countries with `Voting Profiles` whose Solidarity Degree is 5/6 or 83%. Here are six profiles of these groups: 110111, 111101, 1111–11, 1111n1, 11n111, 1n1111. In other words, countries with these seven Voting Profiles form a `Partial Solidarity Group` with a `Solidarity Degree` of 83%. Furthermore, as the `Solidarity Degree` decreases, groups with `Solidarity Degrees` of 4/6 (67%), 3/6 (50%), 2/6 (33%), 1/6 (17%) will be formed.

## 3. Solidarity Network. Construction Principle


