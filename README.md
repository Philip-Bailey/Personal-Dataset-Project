# Personal-Dataset-Project

## Motivation
I chose to analyze NFL data for my Personal Data Project because I enjoy watching the sport every year. There's something about seeing humans at their peak athleticism competing against each other that is so satisfying. For example DK Metcalf an absolute unit of a man standing in at 6'4" and weighing 229lbs. He is currently leading the NFL in receiving yards with over 1,000 yards at this point in the season and this is only his second season. Anyway, I decided to look at all the stats from every NFL team over the past 30 years.  The goal was to see if there was a pattern in the data that could reveal how well a team is going to perform.


## Data Source
For the data about the NFL teams, I got that from Sports Reference which is a site that has data on almost every sport. Their football data is updated weekly to keep up with the new season. That means things like SRS, OSRS, and DSRS get updated which isn't important when you're talking about one season out of 30 years. The website provides all kinds of information for an NFL team's season things like point differential, offensive rank, points scored, the strength of schedule, and many more.


## Data Process
To start, I went through and downloaded every NFL Teams data from sports-reference. Then I had to decide a year to cut off some of the data. Some teams in the NFL have been around since its forming and others have joined in the past 30 years. I decided to cut off all data before 1991 because at that point there were 28 teams already in the league and the next four would follow after. The next step that I had to do was to fix the headings that the website put on the data. The website put two heading on every set the first one stated what category the data was. For example, Points allowed, Points Scored, and Point differential all fell under the heading Points and so on. This issue with this is now I was unable to pick a specific category that I wanted to compare like points allowed vs wins because Python only saw the point category. So I went through and removed the top heading as well as making the second group of headings easy to call back to if I needed to graph them. My final step for processing the data was to combine all of the data sets into one large set.


## Visualization
To begin the process I started by comparing two teams to see if I could find any trends. I compared things like strength of schedule to wins and losses and they show little to no correlation. Another comparison I made was wins against the team's OSRS and DSRS. OSRS is Offensive Simple Rating System which rates a team's offense compared to the average same with DSRS except it compares defense. It looked like there was some correlation but not it was still pretty spread. Another category that I looked at the wins against offensive yards rank with was very unhelpful.
![l vs off pt rk](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/L%20vs%20Off%20Pt%20Rk.png)
![w vs pt dif rk](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/W%20vs%20Pt%20Dif%20Rk.png)
![L vs SoS](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/L%20vs%20SoS.png)
![W vs DSRS](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/W%20vs%20DSRS.png)
![W vs OSRS](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/W%20vs%20OSRS.png)
![W vs Off Yds RK](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/W%20vs%20Off%20Yds%20Rk.png)


## Analysis
Eventually, after sifting through all of the visualizations I found some that had some potential for predicting a team's success or success. It seems like a team's point differential is a great indicator of how well their season is going and where it can lead. This is visible throughout the Wins vs Point Differential. A point differential for a team is how many points they score subtracted by how many they allow. It makes sense that if you're scoring more than you're allowing in over the long run that you would do better. Another piece of data that might provide great insight into a team is their Simple Rating System (SRS) Score. This is a calculation of Margin of Victory (MoV) plus Strength of Schedule (SoS). When you compare a team's losses to their SRS there is a strong trend that as your losses increase your SRS decreases. 

![W vs Pt Dif](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/W%20vs%20Pt%20Dif.png)

![L vs SRS](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/L%20vs%20SRS.png)


## Description of Code and Material 
All of the data that I got off of sports-reference has been included in the GitHub under their respective team names. The team that I processed and put all together is under the name NFL.csv. My notebook has also been included as Personal Dataset(1).ipynb.
