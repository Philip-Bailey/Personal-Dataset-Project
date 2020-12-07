# Personal-Dataset-Project

## Motivation
I chose to analyze NFL data for my Personal Data Project because I enjoy watching the sport every year. There's something about seeing humans at their peak athlethisim competing against each other that is so satifying. For example DK Metcalf an absolute unit of a man standing in at 6'4" and weighing 229lbs. He is currently leading the NFL in recieving yards with over 1,000 yards at this point in the season and this is only his second season. Anyways I decided to look at all the stats from every NFL team over the past 30 years to see if there was a pattern in the data that could reveal how well a team is going to perform.


## Data Source
For the data about the NFL teams I got that from Sports Reference which is a site that has data on almost every sport. Their football data is updated weekly to keep up with the new season. That means things like SRS, OSRS and DSRS get updated which isn't horriably important when you're talking about one season out of 30 years. The website provides all kinds of information for a NFL teams season things like point differntial, offensive rank, points scored, strength of schedule and many more.


## Data Process
To startout I went through and downloaded every NFL Teams data from sports-reference. Then I had to decide a year to cut off some of the data because some teams in the NFL have been around since its forming and others have join in the past 30 years. I decided to cut off all data before 1991 because at that point in time there were 28 teams already in the league and the next four would follow after. The next step that I had to do was to fix the headings that the website put on the data. The website put two heading on every set the first one stated what category the data was. For example Points allowed, Points Scored and Point differential all fell under the heading Points and so on. This issue with this is now I was unable to pick a specific category that I wanted to compare like points allowed vs wins because Python only saw the point category. So I went through and removed the top heading as well as making the second group of headings easy to call back to if I needed to graph them. My final step for processing the data was to combine all of the data sets into one large set.


## Visualization
To begin the process I started out by comparing two teams to see if I could find any trends that I might want to explore with the large data set.
![l vs off pt rk](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/L%20vs%20Off%20Pt%20Rk.png)
![w vs pt dif rk](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/W%20vs%20Pt%20Dif%20Rk.png)

After looking over some of the patterns in the data I decided I wanted to explore the trend between point differential and wins.

![W vs Pt Dif](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/W%20vs%20Pt%20Dif%20NFL.png)
![W vs Pt Dif](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/W%20vs%20Pt%20Dif.png)

![W vs Pt S](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/W%20vs%20Pts%20S.png)
![L vs SRS](https://github.com/Philip-Bailey/Personal-Dataset-Project/blob/master/L%20vs%20SRS.png)


## Analysis

