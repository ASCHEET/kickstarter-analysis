#Kickstarting with Excel

## This project was requested by Louise after the success of her play 'Fever' came close to her fundraising goal within a short amount of time.

###  Louise requested analysis of other Kickstarter campaigns that will help her better understand trends within the Kickstarter data she can use to continue to have successful fundraisers.

## Analysis and Challenges

### Over 4,000 Kickstarter campaigns were analyzed based on category, requested goal, date initiated, and if the fundraising goal was met or not.
### The compiled data started as far back as 2009 up to 2017 and even included current 'live' crowd sourcing campaigns. However, the live campaigns were not overly helpful with analysis and for the most part were excluded.  Categories of Kickstarter campaigns included: film and video, food, games, journalism, music, photography, publishing, technology, and theater.

### The data was first refined to a Parent Category of 'Theater' and from those a subcategory exclusive of 'Plays' was analyzed to most accurately reflect crowdfunding Louise would find helpful.
### This resulting data was organized by Launch Date and plotted based on the overall outcome.  See below in Figure 1.
![Outcomes vs. Kickstarter Date](https://github.com/ASCHEET/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png?raw=true)
### As you can see in Figure 1 above, the best time to start a crowd sourcing campaign is late spring or early summer.  There was no real correlation to campaign start vs. failure to meet the funding goals.

### Analysis of Outcomes Based on Goals is shown below in Figure 2. 
![Figure 2 - Funding Outcomes Based on Monetary Goal](https://github.com/ASCHEET/kickstarter-analysis/blob/main/Outcomes_vs.Goals.png?raw=true)
### Figure 2 shows the probability of reaching the crowd funding goals based on the monetary amount requested.  As you can see, fundraising campaigns less than $5000, have a success rate of greater than 75%.  
### The trend is decreases as the funding amount increases generally.  There is a point where it goes up to 75% for campaigns requesting for money between $25,000 and $35,000 dollars, but we must understand it is a limited data set and the trend might not be truly representative.

### Challenges and difficulties to this data set is 1) the lack of clarity of failed Kickstarter campaigns 2) and the aged data set itself only going through 2017.  
## Results

### Conclusions you can draw about the Outcomes Based on Launch Date have and average success rate of 39% over failed campaigns during the course of the year.  
### However, there is a spike in success rates for the months of May, June, and July that are above average (44-51%) respectively.

### Conclusions about the Outcomes based on Goals show that keeping fundraisers below $5,000 has a significantly higher success rate than above $5,000.  Also, there is much more data (Kickstarter campaigns) that can be evaluated below $25,000.  

### Limitations of this dataset show charts can be misleading as there are very few campaigns (less than 40 total both failed and successful) that were over $25,000.
### Figure 3 below shows an Outcomes Based on Goals but has the Number of Campaigns plotted on a secondary axis to give an additional perspective of what might be expected.  
![Figure 3 - Outcomes Based on Goals with Number of Campaigns on Secondary Axis](https://github.com/ASCHEET/kickstarter-analysis/blob/main/Outcomes_vs.Goalswnumber_of_campaigns.png?raw=true)
### Additionally, how long to expect to have a fundraiser open may help to understand when to start or how much time is needed to collect for successful campaigns.  Below, in Figure 4, shows
### that most successful fundraisers that were given more than 50 days to collect donations were much more successful.  More than 50 days the success vs failure inverses after 60 days showing more 
### 'failed' campaigns than 'successful'.  
![Figure 4 - Outcomes Based on Funding Duration](https://github.com/ASCHEET/kickstarter-analysis/blob/main/Outcomes_based_on_funding_duration.png?raw=true)

