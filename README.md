# NLPCSS-20
The repository of the NLPCSS 2020 paper. It contains the dataset used in the paper "Analyzing Political Bias and Unfairness in News Articles at Different Levels of Granularity."

The news articles are storaged in json format, one news each line.
For each news, there are following fields:

 - title: the title of the news
 - content: the content of the news
 - source: the news portal 
 - allsides_bias: the bias indicated in the allsides.com (left, center, or right)
 - misc: other information, such as author, date, and topics
 - adfontes_fair: the labels from adfontesmedia.com, whehter the article is fair or not (bias, neutral, or unknown)
 - adfontes_political: the labels from adfontesmedia.com, whehter the article is political bias or not (bias, neutral, or unknown)
 - event_id: the event id. Articles with the same event have the same id
