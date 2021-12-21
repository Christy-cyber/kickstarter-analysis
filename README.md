# Kickstarting with Excel

## Overview of Project

An initial analysis of data showed that productions in film and video, music, and theater (especially "plays") had the highest outcomes for all categories considered.  Based on these findings and due to the fundraising success of our client's play, *Fever*, in such a short time, our client, Louise, requested more information regarding campaign outcomes based on launch date and funding goals.

### Purpose

The purpose of these analyses were to uncover trends to address:
1) Theater campaign outcomes based on launch date
2) Campaign outcomes of plays based on funding goals

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

A pivot table was created in MS Excel in order to plot "Theater" outcomes against "Launch Date," thereby showing the number of successful, failed, and canceled campaigns based on the month in which the campaign launched across multiple years.  All countries were considred in the analysis.  The following figure shows that the most successful theater campaigns were launched in May (111 campaigns) and June (100 campaigns).  Beginning in May, the number of successful campaigns declines until December when the number of successful campaigns (37) approximates the number of failed campaigns (35).  The  number of failed campaigns tends to remain constant throughout the year, ranging from 31 to 50 in any given month.  However, the percentage of failed theater campaigns was less in the summer months compared to those that began in the fall (September through December), even though percentages were not calculated or shown in the figure.  The number of canceled theater campaigns remained constant across all months and ranged from 1 to 7 (mode = 3).

#### Challenges and Difficulties

While there were no particular challenges or difficulties with this data set, one should recognize that all types of theater production were included in the analyses.  When producing the figure,

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95387273/146973628-b7027bc4-b502-485e-b18b-9599c3eac25a.png)


### Analysis of Outcomes Based on Goals

A table was created in MS Excel using the COUNTIFS() function in order to investigate the number of successful, failed, and canceled plays based on 12 fundraising goal ranges.  Based on these findings, the percentage of successful, failed, and canceled plays was determined.  The number of "live" plays was not included in the data set.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95387273/146973890-387b7de8-f9f2-47a5-a81f-799135405017.png)


#### Challenges and Difficulties Encountered

## Results

### Conclusions regarding Outcomes based on Launch Date

### Conclusions regarding Outcomes based on Goals

### Limitations of this dataset

### Suggestions for additional tables and/or graphs

I recommend plotting the percentage of successful, failed, and canceled theater campaigns against month.  Additionally, it would  be helpful to further investigate the outcomes of the number and percentage of plays (as a subcategory of "Theater") and how this subcategory performs based on launch date.  Comparisons can be made between the sub-category, "Plays," and its category, "Theater."

Data were sorted by categories, subcategories, and launch date by country.  Descriptive statistics focusing on the mean and median for amounts pledged and goal amounts of successful and failed kickstarters in the US were performed.  A box and whisker plot shows the differences in mean and median values between successful and failed musicals in Great Britain.

Theater productions, music, and film & video were shown to do well across all countries, yet theater productions also showed a higher number of failed campaigns.  Additionally, theater productions (plays) were the most successful in Great Britain, even considering the smaller number of 604 starter campaigns for plays.  The average campaign goal for musicals was 4,000 GBP, with the upper quartile approximating 6,000 GBP and the median at 2,000 GBP.  Considering that the average pledge approximated 1,700 GBP, a campaign goal of 4,000 GBP or less would be recommended.

![Parent Category Outcomes--Module 1--Excel](https://user-images.githubusercontent.com/95387273/146690514-be59b1af-0ee3-4e6e-b5d2-f2214b3a36ba.png)

![Sub-Category Outcomes--Module 1--Excel](https://user-images.githubusercontent.com/95387273/146690529-eaf65945-5f66-4123-9b71-d21da18f980b.png)

![GB Musicals--Successful and Failed](https://user-images.githubusercontent.com/95387273/146690724-3004374b-2189-414b-93eb-3101d7fe00cf.png)


With respect to outcomes based on launch date, it was found that May, especially, and June were the best months to launch a kickstarter campaign.

![Launch Date Outcomes--Module 1--Excel](https://user-images.githubusercontent.com/95387273/146690544-424b2860-d0e3-45bc-97fb-fb26bcb4052a.png)


Descriptive statistics showed that mean goal and mean pledged for both successful and failed US kickstarters were much higher (around the upper quartile) than the median values for both. Median values approximated twice that of the lower quartile.  Standard deviation values were also higher than the mean for goal amounts and amounts pledged for successful and failed US kickstarters, indicating that a few large values, or outliers in both categories, were skewing the distributions for both.

![image](https://user-images.githubusercontent.com/95387273/146691595-45514b44-1dbe-4711-b288-77c55ce66b2d.png)


In summary, focus on theater productions, music, and film & video across all countries, and technology should also remain a consideration.  In Great Britain, theater (plays) campaigns do especially well with the target fundraising goal for musicals at 4,000 GBP or less.  Starting a campaign in May or June would produce the best outcomes.  A few outliers are skewing distributions for mean goal and mean pledged amounts for successful and failed campaigns in the US. Instead, focus on median values and note that failed campaigns have higher fundraising goals (median = $5,000.00) than successful ones (median = $3,000).
