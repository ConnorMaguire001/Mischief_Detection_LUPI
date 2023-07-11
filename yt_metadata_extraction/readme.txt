We use the video ids from the test and training features Json files to generate YT video links. 
We then use the links to scrape for the metadata and create dictionaries {Video_id : Metadata}
Finally we convert the dictionaries to Json files for later use.


Categories of Metadata:  
id, title, thumbnails, views, publishdate, category, channel_name, subscriber, keywords

there are 9 categories for each video: 
'Comedy', None, 'Entertainment', 'Film \\u0026 Animation',  'People \\u0026 Blogs', 'Pets \\u0026 Animals','News \\u0026 Politics', 'Education', 'Gaming' 
