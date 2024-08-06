# Mercado 'Search Traffic vs Stock Price' Trend Analysis 
![project logo](/images/logo.gif)
## Table of Contents 
#### [Project Overview](https://github.com/ncmoliver/prophet-challenge?tab=readme-ov-file#project-overview)    
#### [Installation Instructions](https://github.com/ncmoliver/prophet-challenge?tab=readme-ov-file#installation-instructions)    
#### [Analysis Steps](https://github.com/ncmoliver/prophet-challenge?tab=readme-ov-file#analysis-steps)    
#### [Screenshots](https://github.com/ncmoliver/prophet-challenge?tab=readme-ov-file#screenshots)    
#### [References](https://github.com/ncmoliver/prophet-challenge?tab=readme-ov-file#references)
## Project Overview
This project is for the top e-commerce site in Latin America, Mercado Libre. In this program, the goal is to find any unusual trends in the hourly Google search traffic and compare them to the stock price patterns. 
## Installation Instructions
### Google Colab - Github (strongly suggested)
1. Login to Google Colab
2. File --> Upload Notebook --> Github
- Enter Github user: ncmoliver    
- Repository: prophet-challenge    
- Branch: main    
- Upload & Run program
4. Enjoy your analysis & visualizations 
---
### Google Colab - Save Locally
1. Clone repository `git clone https://github.com/ncmoliver/prophet-challenge.git`
2. Login to Google Colab
3. File --> Upload Notebook --> Upload
4. Open repository & Run program
5. Enjoy your analysis & visualizations
---
## Analysis Steps
| Step | Description | 
| ----------- | ----------- | 
| **Step 1 -- Find Unusual Patterns In Hourly Google Search Traffic** | **1.** Using Google search trends on the company, the first step involved reading the data into a dataframe and slicing out the month the company released its quarterly financial results, which was in May 2020. --- **2.** Calculate May's total search traffic and compare it to the monthly median across all months and combine the search traffic trends and the stock data into one dataframe. (screenshot #1)  |
| **Step 2 -- Mine the Search Traffic Data for Seasonality** | This step resulted in three line graphs showing the hourly search data by time of day (24 hours), day of week (Monday to Sunday), and by the week of the year (Week 1 to Week 52). (Screenshot 2 - 4) |
| **Step 3 -- Relate Search Traffic to Stock Price Patterns** | **1.** In this step we first investigated the stock data and determined there as a shock in the beginning of year followed by increased revenues. **2.** Added new columns to the joint dataframe. |
| **Step 3a -- Lagged Search Trends** | Displays a one hour lag in the search trends,  |
| **Step 3b -- Stock Volatility** | Displays the variation of the company's closing trading stock prices |
| **Step 3 -- Hourly Stock Return** | Shows how much the stock has gone up or down in one hour. |
| **Step 4 -- Review & Analyze Correlation**| Created a time series model and plotted forecast.  This step involved setting up the data for a Prophet forcasting model, using the model to make predictions, and plotting the forecast. (screenshot ) |
---
## Results / Outcomes
| **Step 3 -- Hourly Stock Return** | Shows how much the stock has gone up or down in one hour. |

## Screenshots
#### Step 1 -- May's Total Search Traffic vs 2020 Monthly Median (all months)
<img src="/images/screenshot1.png" width="600" height="300">

#### Step 2 -- Hourly Search Data by Hour in Day
<img src="/images/screenshot2.png" width="600" height="300">

#### Step 2 -- Hourly Search Data by Day in Week
<img src="/images/screenshot3.png" width="600" height="300">

#### Step 2 -- Hourly Search Data by Week in Year
<img src="/images/screenshot4.png" width="600" height="300">

#### Step 3 -- This visualization shows the combined dataframes over the first half of the year
<img src="/images/combined.png" width="600" height="300">

#### Step 3 -- Relate Search Traffic to Stock Price Patterns
<img src="/images/screenshot6.png" width="600" height="300">

#### Step 4 -- Yhat (predictive values for each day) -- Upper/Lower (predictive range for each day)
<img src="/images/screenshot7.png" width="600" height="300">

#### Step 4 -- Relate Search Traffic to Stock Price Patterns
<img src="/images/screenshot8.png" width="600" height="300">

#### Step 5 -- 
## References
[Xpert Learning Assistant](https://bootcampspot.instructure.com/courses/6028/external_tools/313)    
[UNC Bootcamp Spot - Activities](https://git.bootcampcontent.com/UNC-Chapel-Hill/UNC-VIRT-AI-PT-06-2024-U-LOLC)    
[Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)

