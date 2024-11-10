# CDC-US-Cardiovascular-Death-Rate-Trend-Analysis-in-R

The CDC has published excess and cardiovascular disease death data for all to use:
https://data.cdc.gov/Heart-Disease-Stroke-Prevention/Cardiovascular-Disease-Death-Rates-Trends-and-Exce/rsk5-566a/about_data

We can use R to determine how trends are changing, what parts of the country are getting better and worse, as well as model the data for visual aid.

An overall summary: across the US, it seems death rates have remained mostly unchanged in 10 years. However, it is worth noting that some areas of the south (Texas,Florida) have gotten 
significantly worse. Other areas all across the country have made improvements as well. The general spread of the data can make it tricky to determine a nationwide trend. 

I have processed the CDC's whole csv file and focused in on latitude, longitude and percent change in death rate across 10 years. That preprocessed csv is available in this repository.

Feel free to use my R code and add on to the project in any way you see fit! All you need to do is copy the text from the txt script file into your R console and you'll get the models
and code to run.

<img width="635" alt="excess death trendmap " src="https://github.com/user-attachments/assets/5889c8d6-3d1a-47f0-84ec-0e133f46d93f">
<img width="675" alt="trend density excess deaths" src="https://github.com/user-attachments/assets/78157f0b-f284-4f1f-b2fc-7c9518ff4cdc">
<img width="929" alt="distribution graph" src="https://github.com/user-attachments/assets/cb92549c-339e-49ad-99b8-cf381c63829a">
<img width="953" alt="death trend boxplot" src="https://github.com/user-attachments/assets/da67416f-cf31-4e98-acbc-07c0c9bdd1b6">
<img width="950" alt="normalityqqplottrends" src="https://github.com/user-attachments/assets/2ef93ea7-4901-4c97-970e-d6f38dcddb4e">
<img width="388" alt="anova results statevstate" src="https://github.com/user-attachments/assets/531ffc1a-f0de-4b6f-9bd3-fbd70ff26727">

