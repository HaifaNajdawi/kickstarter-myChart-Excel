# Kickstarter Crowdfund service data analysis

### Given the provided data, what are three conclusions we can draw about Kickstarter campaigns?
1.	Based on first pivot table `state to category` we can figure out that the most successful projects category was about `Music, theater, film & videos`. In the other hand, the most failed ones were about `Journalism, Food, technology and Publishing`.

2.	By looking deeper on the most successful categories, we can see that the `rock` and `indie rock` music have a better chance to succeed comparing to other music types. In the `theater` category, it is obvious that `documentary` was the most successful.
If we look at the least successful categories such as `technology`, we can conclude that the `web` and `wearable` sub-categories were the most failed or canceled projects. Also, we can see that `Food trucks` projects had the lowest success rate on the food category.

3.	We can observe that campaigns started at the `first half of the year` had almost `7% higher success rate` than the ones started on the second half. 

### What are some limitations of this dataset?
Projects that exceeded initial goal, what was the time needed to reach the initial goal. This would be helpful on estimating the total time required for the campaign.

### What are some other possible tables and/or graphs that we could create?
1.	A pivot table that shows the relation between campaign period and state.
2.	A pivot table that shows the relation between project country and the successful rate.



### Use your data to determine whether the mean or the median summarizes the data more meaningfully?
By drawing histogram chart, you could tell that the data distribution is skewed. Based on that, `Median` will be preferable to summarize data.

### Use your data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?
There is more variability in `successful` campaigns. I think this does make sense, because of the following:
1.	Unsuccessful campaigns usually get very few backers. This will reduce the variability, as total number will fall in the range [0, 40]. In rare cases, you could see a campaign exceeds this range.
2.	Successful campaigns had wider range of backers, specially there are many projects exceed the initial goal.
