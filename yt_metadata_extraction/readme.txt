We use the video ids from the test and training features Json files to generate YT video links. 
We then use the links to scrape for the metadata and create dictionaries {Video_id : Metadata}
Finally we convert the dictionaries to Json files for later use.


Categories of Metadata:  
id, title, thumbnails, views, publishdate, category, channel_name, subscriber, keywords
