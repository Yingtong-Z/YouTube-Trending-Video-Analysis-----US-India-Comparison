# YouTube-Trending-Video-Analysis---US-India-Comparison
## Introduction
As a globally popular video platform, YouTube takes up most of the time in our daily life, no matter where we live in, what language we speak and what culture background we have. However, people from different countries do have different inclinations to choose a video. In this report, we are going to discuss the differences of video preferences in the US and India
## Objective
**Our main objective of this analysis is to find out the characteristics of trending YouTube videos in the US and India? And What are the differences between them? How will it affect the decision of setting up a new channel in each of the two countries?**

To compare trending videos in the US and India, we will divide the analysis into 6 sub-tasks and examine the differences in detail
* Sub-Task 1:
  * What is the distribution of trending video categories and channels in the US? What are the top 5 categories and top 10 channels?
  
* Sub-Task 2:
  * What is the distribution of trending video categories and channels in India? What are the top 5 categories and top 10 channels? How are they different from those in the US?
* Sub-task 3:
  * Among trending videos in the US, what are the distributions and characteristics of top 30 most viewed videos? How are the likes and comment counts distributed? What are the response rate of those videos?
* Sub-Task 4:
  * Compared to trending videos in the US, what are the characteristics of top 30 most viewed videos in India? How are the likes and comment counts distributed? What are the response rate of those videos?
* Sub-Task 5:
  * What are the most common words in trending videos’ tags in 2021 in the US and India respectively?
* Sub-Task 6:
  * If we want to create a new channel, how should we design it to boost popularity on YouTube. How we will do it differently in the US and India?
## Dataset
The data used in this analysis was retrieved from Kaggle dataset of [YouTube trending video dataset](https://www.kaggle.com/rsrishav/youtube-trending-video-dataset?select=US_youtube_trending_data.csv) (updated daily) , which was collected using the YouTube API. As noted, we focused our analysis in 2021. The time period of dataset available to retrieve was from 2021/01/01 to 2021/12/03 (trending date) when we started this analysis in the December of 2021. So, we will refer our analysis on 2021 trending videos comparison of US and India with the 11-month data.
## Highlighted Analysis
### Distribution of Video Categories and Channels in US
Among 15 categories, the top 5 categories based on the number of videos are **Gaming, Entertainment, Music, Sports and People & Blogs.** Together top 5 categories cover 76.71% of all the trending videos.

![a](/Graphs/US 2021 Distribution of Trending Video Categories.png)

According to the most popular channels, Americans are more interested in sports, computer games, and talk shows. We found that the number of channels in these categories are very different. There are 800 channels for Gaming, 769 for Entertainment and 732 for Music, but only 294 channels in Sports. The channels in Entertainment or Music are much more than those in Sports. **This means that if someone is interested in Sports, he/she will only have a few choices of channels to watch the videos, while trending videos of Gaming, Entertainment or Music are widely distributed in many channels,** so for each single channel, it may not contain as many trending videos as channels in category of Sports.
[image]

### Distribution of Video Categories and Channels in India
Trending channels in India look much more enjoyable than those in the US. According to the dataset, the most popular channels in India are TV shows, comedy or story related. 
[image]

Unlike the channel features in US, the rank of number of trending channels in these categories exactly matches the rank of categories themselves. This means there is no disproportionate relationship between categories and channels within them.
[image]

### US top 30 trending videos by view counts
Below is the table of US top 30 trending videos by view counts. The response rate is calculated as the sum of likes, dislikes and comment count divided by view count, a metric reflecting to what extent audience interact with the video. The yellow highlighted videos are short videos while the pink ones are Korean music videos.
[image]
Among the top 30 most viewed videos, music accounts for nearly 50% of the total videos. Taking a closer look at the music videos in detail, those on the top of most viewed lists are videos of official videos of songs for new albums by popular singers such as Adele, Justin Bibber and some Korean singers and bands like BTS and Lisa. Interestingly, those top most view music videos from Korean bands enjoy some characteristics: firstly, they typically last for 8-10 trending days; secondly, the response rate for those videos are on average higher than other trending videos, with an average number of around 10%. Based on the numbers, it is safe to assume that **one reason why those Korean bands’ music videos are on the trending list is that fans actively help boost popularity for their idols’ new songs.**

### Frequent tags in trending videos between US and India
The word clouds below show us the most common 500 words (excluding None) in the US (background color in blue) and India (background color in yellow). It is obvious that words like funny, comedy and Minecraft gaming were more typical key words of the trending videos in the US. While comedy, Hindi shows and big boss are more common than other words in trending videos in India. In short, comedy videos are most popular across US and India. However, in 2021, gaming such as Minecraft related videos have been a trend in the US, a difference from that in India
[image]
[image]

## Conclusion

Throughout our analysis, we started from finding patterns of 2021 trending videos by exploring and visualizing the dataset and then compared difference in trending videos between US and India. **We will summarize our insights derived from our analysis from 5 angles: video types, video channels, video numeric metrics, video tags and recommendation to create a potential  popular channel on YouTube.**
 
- **Video types**

Top 5 categories of trending videos in the US and India were similar in 2021. **Gaming, entertainment, music, sports and people & blogs are top 5 categories in the US while entertainment, people & blogs, music, comedy and gaming are top 5 ones in India**. However, entertainment consisted of nearly half (44%) of total trending videos in India, while video categories spread evenly in the US.

- **Video channels**

**Distributions of video channels of 2021 trending videos are contrasting between US and India.** In India, top trending channels mirror the top categories of videos. I.E, the higher the percentage of certain category of video, the more channels of that category. Things are interestingly different in the US. Top channels distribution is not corresponding to top categories distribution. Sports channels dominate the top 10 channels but it only ranks the fifth in top categories list. This means that sport channels center in a few mainstream channels while the other top categories like entertainment, music and etc. are more diffuse in channels

- **Video numeric metrics**

Music contributes to nearly 50% of top 30 most viewed trending videos both in the US and India. Short videos are prevailing in both countries as well, filling the majority of top 30 most viewed lists. It is an interesting insight to see that, both in the US and India, Korean music videos stands in the top viewed list because fans help boost popularity for their idols’ albums. Usually the popularity boosting leaves the video trending for an average of 10 days and responsive rate of 10%, an above average number compared to other top viewed trending videos. **Overall, 2021 top viewed videos in the US and India enjoy a great deal of commons.**

- **Video tags**

Depicted by word cloud graphs, the top 3 most common words of 2021 trending videos in the US are funny, comedy and Minecraft gaming and those in the India are comedy, Hindi shows and big boss. It is a similar vibe with slight difference for trending videos in these two countries.**The audience profile is more of people who are game and fun oriented while it is more of comedy and opera oriented in India.**

- **Recommendation to create a popular channel on YouTube**

In the last task, we came up with some clues on creating a popular channel on YouTube by combining categories, contents and title names analysis.

To increase the chance of become a popular channel in the US, creating a gaming or entertainment channel with funny and gamed related videos with video titles of around 50 characters in short videos or vlogs format would be the ideal choice. 

As for creating a popular channel in India, an entertainment channel with comedy oriented videos with long video titles of 70 characters should be an promising popular try.


