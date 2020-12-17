# kickstarter-analysis

Kickstarter Campaign Analysis	

The first conclusion to draw from this dataset is that more successful Kickstarter campaigns are started in the spring than any other portion of the year. Specifically, 58% of campaigns started in April, May, and June were successful, easily outpacing the next closest quarter, which came in at 53% for January, February, and March. This is also evident in the graph of campaign success by start date where there is a clear spike in successful cases in May and a noticeable drop off towards the winter months.

Second, Kickstarter campaigns in journalism appear to be a bad idea. All 24 journalism campaigns in this data set were cancelled. Similarly, 80% of food campaigns either failed or were cancelled, falling far short of the complete dataset’s success rate. The most successful category by percentage appears to be music, where only 20% of campaigns had failed or been cancelled at the time the data was collected.

Finally, the number of successful theater campaigns outnumbered the total campaigns of any other category by a significant margin, though it also has many failed campaigns. This brings up one key limitation of the analysis so far in that we have not addressed the average goal amount for successful versus failed campaigns. It may be that theater campaigns on average have a lower goal amount and therefore are more likely to be successful. It would be worth comparing the average goal amount for each category before comparing their success rates.

A second limitation of this dataset is the lack of information about the campaigns that were unsuccessful, whether through cancellation or failure. We do not know how successful the cancelled campaigns would have been, especially since the cancelled campaigns had raised an average of $7,286.34 when they were cancelled. Similarly, campaigns could fail for reasons other than a poor idea. Lack of awareness or advertising for a campaign would make it more difficult to raise enough support by the deadline. 

A third limitation is the staff pick and spotlight columns. A quick analysis shows that 88% of staff pick campaigns and 100% of spotlight campaigns were successful. That should be valuable information but there is the problem of directionality. Why were those campaigns selected as staff picks or for spotlights? Would they have been successful without this added support and attention? There are factors outside the dataset which impact the roughly 2500 campaigns that fall into these categories.

With the data we do have, the goal amount for a campaign varies greatly across categories so comparing the raw numbers of successes and failures is less beneficial than comparing the success rate percentages within a category. Tables comparing goal amount and start date with success rate within a category would provide more useful information for those looking to start a Kickstarter campaign than data including all categories.


Additional Analysis

The mean number of backers summarizes the data more meaningfully than the median. We can see that successful campaigns averaged over 194 backers compared to only 18 for unsuccessful campaigns. These numbers will be slightly skewed by unsuccessful campaigns that never got rolling and ended with 0 backers, as well as successful campaigns that had a lot of backers but smaller average donation size. With either measure, there is too much unknown information about the financial side of the campaign to look at backer data alone. Neither provides much insight into the campaign itself.

It is clear from both standard deviation and variance that there is much more variability in successful cases because they have no cap, in a sense. Campaigns that failed already fell short of their goal amount so are limited to a much smaller range of backers. In other words, it would be difficult for a failed campaign to have a large number of backers without becoming a successful campaign. This is absolutely the expected result.