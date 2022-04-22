# GEOG458 Lab2
# Kristina Hsu


## 1. introduce your comparison of two places or two time periods. Why do you want to make this comparison? Make sure this narrative will be stored in a readme.md. (POINT 15)

I choose to compare the United States and India. Originally, I wanted to eliminate the time zone factors so I tried scraping for Canada and Brazil so that I can compare them with the United States. However, despite being in the same time zone there are only 3 tweets scraped from Brazil, and there are more tweets in the states than in Canada when I box the area using the coordinates search from [here](https://gist.github.com/graydon/11198540). I then tried with China too, but potentially due to government control, even in the morning, there aren't many tweets. In addition, the boxing of China also includes more tweets from India instead. Therefore I decided to compare India and the United States at the same time. And I think the comparison between the two countries can represent Western vs. Eastern thinking. 

## 2. export the two maps to the repository and then insert them to the readme.md. Please compare them and briefly discuss why they represent different geospatial patterns on the map. (POINT 15)

![India Map](/img/india_map.png) 
![USA Map](/img/usa_map.png) 

The spatial distribution of the 2 countries is slightly different. In the map of the states, there is a clearer clustering in major metropolitan areas like New York City and San Francisco. The India map is more evenly distributed, which may indicate a shorter distance between cities. However, while we scrape with the same parameters there seem to be more activities in the United States, despite it being late at night. This may be because the stakes to accessing the internet and mobile devices are much lower in the United States. 

## 3. export the two word clouds to the repository and then insert them to the readme.md. Please compare them and briefly discuss why they represent different context. (POINT 15)

![India Word Could](/img/wordcloud_india.png) 
![USA Word Could](/img/wordcloud_usa.png) 

For the word clouds, I eliminated all words that only have 1 or 2 occurrences, and those that aren't words, which may be produced due to the emojis that aren't viewable. Overall the two word clouds contain dominantly positive words. Oddly despite the time difference, there isn't a significant trend that is the difference between the two. And the glaring difference would be the location names in which Indians type more India, while Americas specify the location by states more like PDX and Portland.