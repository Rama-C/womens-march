# womens-march

This is my volunteer project for Data for Democracy. Data for Democracy is an inclusive community for data scientists and technologists. It is a space for like-minded people to organize, to transform, to collaborate, and to support each other's projects. We help each other track down datasets, refine models, improve visualizations, team up on apps, debug code, promote work, and connect with communities who need our analysis.

**Slack:** [#womens-march](https://datafordemocracy.slack.com/messages/womens-march/)

**Project Description:** The purpose of this project is to understand geographic, messaging, and sentiment patterns around the Women's March as well as ongoing resistance to Trump as he opposes supporting certain issues.

The Women's March was the largest protest there has been in US History and occurred during a time when technology facilitates the movement of information and people more quickly and cheaply. Because of this, understanding the march through digital data and understanding key issues around the event can help to shed light on how people are responding to the current political climate in a more technology-driven environment. We hope to explore Twitter data that has been pulled, crowd estimates, spatial data, as well as other types of data that we can collect like survey, news, or other social media data, with goals of making insights gained from analysis known to the public. Questions we've started to ask are

* In what cities did people march?
* How many people marched in each city?
* What are the top ranking topics/issues in tweets related to #womens-march?
* Do topics tweeted about differ by city?
* What are other hashtags that people used with #womens-march?
* From where were people tweeting about #womens-march?
* How do these topical and geographic trends relate to data from the Status of Women and issues that affect women?

In conducting this research, we hope to gain new insights and understand the Women's March through data and data visualizations rather than just through news, pictures, stories, and signs.

# Analysis report

The Women's March tweets data has 3100 entries with 5 columns. There are no missing values in 4 columns whereas the column named "place" has 308 known values(or 2792 missing values).

All the entries have the same id. Also, the id looks unusual. 51 different sources were used to post the tweets. Most people used "Twitter for iphone" as their source, followed by "Twitter for Android" and "Twitter webclient".

The tweets were created in different countries having different timezones and in different languages. Surprisingly, all the tweets were created between the time 23:56 and 23:59 on January 21, 2017.

The Women's March happened in various countries. The tweets include both abbreviated and full name of the US states.

The column named "place" holds the location from where the tweets are published. It has 308 known values(or 2792 missing values). The analysis was carried out with the known values.It was split into "city" and "State" to facilitate the analysis.
The dataframe was processed in detail to represent all the US states in an abbreviated form in the column named "State" and USA as their country in the column named "country". The Non-USA locations are unchanged.

The tweets came from 30 different countries. From the known location tweets, it is found that the major tweets came from USA.
There were tweets from 41 US states. The state CA(California) has the major tweets, followed by DC(The District of Columbia) and NY(Newyork). 

There were 3100 tweets in the data. The tweets include hashtags, text messages, links, tags and emojis or some symbols. The tweets were in different languages.
Analysis by Tags was carried out to find the most used tags. 399 rows were found. The most tweets doesn't have a tag. Some rows have more than one tags. The tags in each row are split and counted separately. There were 532 different tags found.
Analysis by links was carried out to find the most tweeted links. 1789 rows were found. 1295 tweets did not include any links. There were 1201 hashtags found. The hashtag #WomensMarch was the most used one.

The hashtag #WomensMarch, was widely used across various countries. USA has the most hashtags. California has the most hashtags within USA.






