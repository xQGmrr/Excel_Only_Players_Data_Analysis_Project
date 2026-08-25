# European Football Player Analytics 2025/26

## Introduction

Football produces a huge amount of performance data, but raw player
statistics can be difficult to interpret without a structured analytical
approach. This project uses Excel to explore player performance across
five major European leagues during the 2025/26 season.

The goal is to turn player-level statistics into clear insights about
goals, assists, goal contributions, positions, leagues, nationalities,
age groups, and playing time.

![Football_Dashboard](https://github.com/xQGmrr/Excel_Only_Players_Data_Analysis_Project/blob/main/0_Resourses/images/Football_Dashboard.gif)

### Questions to Analyze

To understand player performance across Europe's top leagues, I asked
the following:

1.  **Who are the top players by goals and assists?**
2.  **Which leagues produce the most goals?**
3.  **How are players distributed across different positions?**
4.  **Which positions contribute the most goals?**
5.  **Which countries contribute the most players?**
6.  **How does age relate to matches played?**
7.  **Which players have the highest goal and assist production?**
8.  **How does goal contribution vary across different age groups?**

### Excel Skills Used

The following Excel skills were utilized for analysis:

-   **📊 Pivot Tables**
-   **📈 Pivot Charts**
-   **🧮 DAX (Data Analysis Expressions)**
-   **🔍 Power Query**
-   **💪 Power Pivot**
-   **🔎 XLOOKUP**
-   **📉 Data Visualization**
-   **📌 Data Modeling**

## Football Players Dataset

The dataset contains player-level statistics from the 2025/26 season
across five major European leagues:

-   🇩🇪 Bundesliga
-   🏴 Premier League
-   🇪🇸 La Liga
-   🇫🇷 Ligue 1
-   🇮🇹 Serie A

The workbook contains information used to analyze:

-   **⚽ Goals**
-   **🎯 Assists**
-   **🔥 Goals + Assists**
-   **🏟️ Matches Played**
-   **👤 Player Position**
-   **🌍 Nationality**
-   **🎂 Age**
-   **🏆 League**
-   **🏢 Club**

The dashboard summarizes **2,490 players**, **4,534 goals**, **3,182
assists**, **96 clubs**, and **113 countries** represented in the
analysis.

------------------------------------------------------------------------

## 1️⃣ Who are the top players by goals and assists?

### 📊 Analysis

I used Pivot Tables and Pivot Charts to rank players according to their
total Goals and total Assists.

![Football_Dashboard](https://github.com/xQGmrr/Excel_Only_Players_Data_Analysis_Project/blob/main/0_Resourses/images/Top_Scorer.png)


The top of the ranking includes:

-   **Harry Kane** --- 36 goals
-   **Erling Haaland** --- 27 goals 
-   **Kilyan Mbappe** --- 25 goals 
-   **Vedat Muriqi** --- 23 goals 
-   **Igor Thiago** --- 22 goals 
-   **Deniz Undav** --- 19 goals 
-   **Serhou Guirassy** --- 17 goals 

### 💡 Insights

-   ⚽ **Harry Kane** leads the overall goals + assists ranking with
    **36 goal contributions**.
-   🔥 **Erling Haaland** follows with **27**, highlighting his elite
    attacking production.
-   🌟 **Kilyan Mbappe** ranks third with **25**, showing a strong
    contribution across goals.
-   📈 The leading players combine high attacking output with
    substantial match involvement.


![Football_Dashboard](https://github.com/xQGmrr/Excel_Only_Players_Data_Analysis_Project/blob/main/0_Resourses/images/Top_Assists.png)


### 🤔 So What?

Identifying players with the highest goal contributions provides a quick
way to compare attacking impact rather than looking at goals alone. This
can be useful for scouting, player comparison, and evaluating offensive
efficiency.

------------------------------------------------------------------------

## 2️⃣ Which leagues produce the most goals?

### 📊 Skill: Pivot Tables & Pivot Charts

I created a league-level analysis to compare total goals across the five
competitions.

The total goals recorded by league are:

 ![Football Dashboard](https://github.com/xQGmrr/Excel_Only_Players_Data_Analysis_Project/blob/main/0_Resourses/images/Goals_By_League.png)

### 💡 Insights

-   🇪🇸 **La Liga** has the highest total with **973 goals**.
-   🏴 **Premier League** is extremely close with **971 goals**.
-   🇩🇪 **Bundesliga** follows with **954 goals**.
-   🇫🇷 **Ligue 1** has the lowest total among the five leagues with
    **782 goals**.
-   ⚽ Across all five leagues, the dataset records **4,534 goals**.

### 🤔 So What?

Comparing total goals by league provides a high-level view of attacking
production across competitions. It also creates a useful foundation for
deeper analysis of scoring rates, player efficiency, and differences
between leagues.

------------------------------------------------------------------------

## 3️⃣ How are players distributed across positions?

### 💪 Power Pivot & Pivot Tables

I used the Data Model and Pivot Tables to analyze player positions and
their contribution to the overall player population.

The dashboard shows the following position groups:

 ![Football Dashboard](https://github.com/xQGmrr/Excel_Only_Players_Data_Analysis_Project/blob/main/0_Resourses/images/Player_Pos.png)


### 💡 Insights

-   🧠 **Midfielders (MF)** represent the largest group in the analysis.
-   🛡️ **Defenders (DF)** are the second-largest group.
-   ⚡ **Forwards (FW)** are fewer in number but naturally account for a
    much larger share of goals.
-   📊 Position-based analysis helps separate player volume from
    attacking production.

### 🤔 So What?

The number of players in a position does not necessarily indicate its
attacking importance. Combining player counts with goals and assists
gives a more meaningful picture of positional contribution.

------------------------------------------------------------------------

## 4️⃣ Which positions contribute the most goals?

### 📊 Analysis

I compared the number of players in each position with their total
goals.

The analysis records:

![Football_Dashboard](https://github.com/xQGmrr/Excel_Only_Players_Data_Analysis_Project/blob/main/0_Resourses/images/table_1.png)

### 💡 Insights

-   ⚽ **Midfielders** have the highest total number of goals with
    **2,767**.
-   🔥 **Forwards** score **2,490 goals** despite being a smaller player
    group.
-   🛡️ **Defenders** contribute **666 goals**, considerably lower than
    midfielders and forwards.
-   📈 This demonstrates why player count and attacking output should be
    analyzed together.

### 🤔 So What?

A positional analysis helps identify where attacking production comes
from. While midfielders contribute the highest total number of goals in
this dataset, forwards show a particularly strong attacking impact
relative to their smaller population.

------------------------------------------------------------------------

## 5️⃣ Which countries contribute the most players?

### 🔎 Skill: XLOOKUP & Data Analysis

I used country-level player counts and XLOOKUP to support the
nationality analysis and prepare the data for visualization.

Some of the largest nationality groups include:

-   🇧🇷 **Brazil** --- 81 players
-   🇦🇷 **Argentina** --- 66 players
-   🇵🇹 **Portugal** --- 55 players
-   🇧🇪 **Belgium** --- 49 players
-   🇸🇳 **Senegal** --- 49 players
-   🇪🇸 **Spain** --- 376 players

### 💡 Insights

-   🇪🇸 **Spain** has by far the largest player representation in the
    dataset with **376 players**.
-   🇧🇷 Brazil and 🇦🇷 Argentina are among the largest international
    groups.
-   🌍 The players represent **113 countries**, highlighting the
    international nature of Europe's top leagues.

### 🤔 So What?

Nationality analysis demonstrates how international European football
has become. Although the competitions are based in Europe, players from
a wide range of countries contribute to them.

------------------------------------------------------------------------

## 6️⃣ How does age relate to matches played?

### 📊 Analysis

I grouped players into four age categories and compared their average
age with average matches played.

![Football_Dashboard](https://github.com/xQGmrr/Excel_Only_Players_Data_Analysis_Project/blob/main/0_Resourses/images/table_2.png)

![Football_Dashboard](https://github.com/xQGmrr/Excel_Only_Players_Data_Analysis_Project/blob/main/0_Resourses/images/AverageMP.png)
### 💡 Insights

-   👶 Players under 21 average only **11.18 matches**, the lowest of
    all groups.
-   📈 The **24--29** group has the highest average number of matches at
    approximately **22.69**.
-   🧓 Players aged 30+ average approximately **21.98 matches**,
    slightly below the 24--29 group.
-   ⚽ The results suggest that established players generally receive
    more playing time than younger players.

### 🤔 So What?

Age can be an important factor when evaluating player development and
experience. Younger players may have fewer opportunities for regular
first-team appearances, while players in their prime tend to have
greater involvement.

------------------------------------------------------------------------

## 7️⃣ Which players have the highest goal and assist production?

### ⚽ Goals

The analysis of goal production identifies several standout performers.

Among the highest goal scorers are:

-   **Harry Kane** --- 36 goals
-   **Erling Haaland** --- 27 goals
-   **Kylian Mbappé** --- 25 goals
-   **Vedat Muriqi** --- 23 goals
-   **Igor Thiago** --- 22 goals

### 🎯 Assists

The assist analysis also highlights several high-performing players:

-   **Bruno Fernandes** --- 21 assists
-   **Michael Olise** --- 19 assists
-   **Luis Díaz** --- 14 assists
-   **Julian Ryerson** --- 15 assists
-   **Lamine Yamal** --- 11 assists
-   **Rayan Cherki** --- 12 assists

### 💡 Insights

-   ⚽ Goal scoring is concentrated among elite attacking players.
-   🎯 Assist production highlights the importance of creative players,
    not only traditional goal scorers.
-   🔥 Combining goals and assists provides a more complete measure of
    attacking contribution.

### 🤔 So What?

Looking at goals and assists separately can reveal different player
profiles. A player may have a lower goal total but still have a major
impact through chance creation and assists.

------------------------------------------------------------------------

## 8️⃣ How does goal contribution vary across age groups?

### 📊 Analysis

I compared total goals + assists across four age groups.

![Football_Dashboard](https://github.com/xQGmrr/Excel_Only_Players_Data_Analysis_Project/blob/main/0_Resourses/images/GoalbyAge.png)

### 💡 Insights

-   🔥 Players aged **24--29** account for the largest share of goal
    contributions with **3,880**.
-   📈 Players aged 21--23 contribute **1,746** goal contributions.
-   🧓 Players aged 30+ contribute **1,308**.
-   🌱 Players under 21 account for **782**, reflecting their lower
    average playing time.

### 🤔 So What?

The 24--29 age range appears to represent the strongest combination of
experience, playing time, and attacking production in this dataset. This
makes the age group particularly relevant when evaluating players at
their performance peak.

------------------------------------------------------------------------

## Conclusion

This Excel project analyzes European football player performance across
the 2025/26 season using Pivot Tables, Pivot Charts, DAX, Power Query,
Power Pivot, XLOOKUP, and data visualization.

The analysis shows several important patterns:

-   ⚽ **4,534 goals** and **3,182 assists** are recorded across the
    analyzed dataset.
-   🏆 **La Liga** has the highest total goals with **973**, closely
    followed by the Premier League with **971**.
-   🔥 **Harry Kane** leads the goals + assists ranking with **41 goal
    contributions**.
-   🧠 **Midfielders** form the largest positional group and record the
    highest total goals.
-   🌍 Players from **113 countries** are represented, demonstrating the
    international nature of European football.
-   📈 Players aged **24--29** have the highest average match
    involvement and the largest total goal contribution.
-   🎯 Combining goals, assists, age, position, league, and playing time
    provides a more complete view of player performance.

Overall, this project demonstrates how Excel can transform football
statistics into an interactive analytical dashboard and provide useful
insights for player evaluation, scouting, performance analysis, and
football decision-making.
