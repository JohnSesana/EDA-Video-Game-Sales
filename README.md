# Video Game Sales Analysis Project

## Table of Contents
- [Introduction](#introduction)
- [Data Description](#data-description)
- [Methodology](#methodology)
  - [1. Define the Problem and Goals](#1-define-the-problem-and-goals)
  - [2. Prepare and Process](#2-prepare-and-process)
  - [3. Analyze](#3-analyze)
  - [4. Share and Act](#4-share-and-act)
- [Conclusion](#conclusion)
- [Limitations](#limitations)
- [Disclaimer](#disclaimer)
- [References](#references)

## Introduction

The video game industry has grown rapidly over the years, and understanding the trends and patterns within it is crucial for game developers and investors. In this project, I analyzed video game sales data to identify the factors that contribute to a game's success or failure.

## Data Description

The dataset used for this analysis contains information on video game sales from 1980 to 2020. It includes details such as the name of the game, the platform it was released on, the year of release, the genre, and the sales figures in various regions. The dataset was obtained from Kaggle and provides a comprehensive view of the video game industry over the past four decades.

## Methodology

### 1. Define the Problem and Goals
The first step in this project was to define the problem I wanted to solve and the goals of my analysis. I asked questions such as:
* What are the current sales trends in the video game industry?
* What are the most popular platforms and genres?
* What are the top selling games?
* What are the top selling publishers?

By answering these questions, I aimed to gain insights into the video game industry and provide valuable information for game developers and investors.

### 2. Prepare and Process

To prepare the dataset for analysis, I first needed to understand it better and identify any cleaning duties that were necessary. Here are the steps I took:
1. Opened the dataset in Excel.
2. Analyzed the raw data to gain insights and identify potential issues.
3. Created pivot tables to identify any anomalies and inconsistencies in the data.

Next, I began the data cleaning process by performing the following tasks:

1. Corrected any typos in game names using the find and replace function ("PokÃ©mon" -> "Pokemon").
2. Standardized platform names to make them more easily understandable ("2600" -> "Atari 2600", "x360" -> "Xbox 360", "ws" -> "Wonderswan").
3. Used text splitting to isolate the platform developer company from the platform column, making it easier to perform platform-based analysis.

<div align="center">
<img src="https://user-images.githubusercontent.com/117879912/229331783-cb19de74-fb27-42c1-b9b0-b001d2bdaba6.png" alt="platform_before_after" width="700" height="900">
</div>


### 3. Analyze

In this phase, I analyzed the video game sales data to uncover insights and trends. I used Excel to create interactive graphs using pivot tables to display my findings. Some of the key insights I discovered include:

* The top-selling video game genre worldwide is Action, followed by Sports and Shooter.
* North America is the region with the highest total sales, followed by Europe and Japan.
* The most popular platform in terms of sales is the Playstation 2, followed by the Xbox 360 and Playstation 3.
* The highest-selling video game, accounting for all platforms, is Wii Sports , followed by Grand Theft Auto V and Super Mario Bros.

I also created several visualizations to help illustrate my findings, including bar charts, line charts, and pie charts. These visualizations allow us to easily compare different genres, platforms, and games.

<div align="center">

<img src="https://user-images.githubusercontent.com/117879912/231908243-137e0826-811b-4e41-93a4-777e27385040.png" alt="Excel Dashboard" width="900" height="900">
</div>

Overall, the analysis phase helped us gain a better understanding of the video game sales data and identify key trends and insights.

### 4. Share and Act


If this project was a real business task I would share my findings with colleagues to gather feedback and identify any areas for improvement. I would discuss potential areas for further analysis and visualizations that could help provide additional insights.

Moving forward, I would work on addressing any new issues or concerns that arise from my discussions with colleagues. This may involve cleaning the data further or creating additional visualizations to better showcase my findings.

Once any new issues have been addressed and I am satisfied with the quality of my analysis and visualizations, my final step would be to share my findings with stakeholders and use the insights to inform decisions and actions that can help drive business success.


## Conclusion

Through this project, I was able to analyze and visualize video game sales data using Excel to uncover key insights and trends. By cleaning and preparing the data and using Excel's built-in features such as pivot tables and charts, I was able to analyze the data for patterns and trends and create compelling visualizations that helped to showcase my findings.

Some of the key insights I uncovered include the fact that Action is the top-selling genre worldwide, North America is the region with the highest total sales, and the Playstation 2 is the top-selling platform.

Overall, this project was a great opportunity to work with real-world data and apply a range of analytical and visualization skills using Excel. I look forward to continuing to develop these skills and using them to uncover insights and drive business success in the future.

## Limitations

While this project provided valuable insights into video game sales data, there are some limitations that must be acknowledged:

* The video game sales dataset used in this project was obtained from Kaggle, and it was likely webscraped from various sources. As such, there may be some data quality issues that were not addressed in this project. Further analysis should be done to ensure the reliability and accuracy of the data.
* The sales data used in this project is not current and only goes up until 2016, meaning it does not account for the newest generation of consoles. Therefore, the insights gained from this analysis may not be entirely representative of the current state of the video game industry.
* Some year values in the dataset were missing, which could affect the accuracy of the insights gained from this project.
* The data used in this project only specifies sales data from North America, Japan, and Europe, and may not be representative of video game sales trends in other regions of the world.

These limitations should be taken into consideration when interpreting the insights gained from this analysis. Future studies using more current and comprehensive datasets may be necessary to gain a more accurate understanding of the video game industry.

## Disclaimer

This project was done solely for the purpose of practicing and showcasing my skills in data analytics using Excel. I do not own any of the data used in this project. The video game sales dataset was obtained from Kaggle and belongs to its respective owners. This project does not represent any official views or opinions of the dataset owners.

## References
Kaggle dataset: [Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)
