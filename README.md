# Mischief_Detection_LUPI
Applying the learning under the privleged (LUPI) frameword to RNN for the task of questionable content detection in youtube videos 

## yt_meta_data_extraction
The code to extract metadata from youtube. 
the metadata is contained in the json files, training_metadata.json and test_metadata.json and is formatted {video_id: {metadata}}

## binary_text_classifier 
a small text classifier trained on the subtitle representation ("word_indexes") and the caption representation ("cap_indexes")
It gives a binary output that determines whether an input contains comic mischief. 
