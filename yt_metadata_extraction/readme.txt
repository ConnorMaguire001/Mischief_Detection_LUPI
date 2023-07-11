We use the video ids from the test and training features Json files to generate YT video links. 
We then use the links to scrape for the metadata and create dictionaries {Video_id : Metadata}
Finally we convert the dictionaries to Json files for later use.


Categories of Metadata:  
id, title, thumbnails, views, publishdate, category, channel_name, subscriber, keywords

there are 9 categories for each video
Category: number of items

Comedy : 281
None : 237
Entertainment : 338
Film \u0026 Animation : 85
People \u0026 Blogs : 36
Pets \u0026 Animals : 12
News \u0026 Politics : 2
Education : 13
Gaming : 3
