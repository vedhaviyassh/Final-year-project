# Final-year-project
Learning to Summarize YouTube Videos With Transformers: A Multi- Task  Approach 

Abstract: The wide-range availability of online 
video content has made people consume more time 
to keep up with the amount of information 
available. In this paper, we present a system for 
summarizing YouTube videos that use NLP and 
machine learning techniques to retain the 
important details without any data loss. There are 
a few techniques for summarization on YouTube, 
the first approach is YouTube API which has been 
a popular method used for video summarization. 
However, it has certain limitations, such as limited 
accuracy, language barriers, and inability to 
summarize caption-less videos. To overcome these 
limitations, a new approach using transformers has 
been proposed. The proposed approach involves 
downloading the video' audio, converting it to 
WAV format, performing speech-to-text 
conversion using the Hugging Face Automatic 
Speech Recognition model, and then using 
transformers and pipeline for summarization. For 
evaluation we have used Rogue (Recall-oriented 
understudy for Gisting evaluation) which is a
popular metric used for summarization tasks with 
an f1 score of 0.6. The approach has been tested on 
multiple videos with different video lengths and has 
shown good results in terms of accuracy and 
efficiency. The proposed approach can be used for 
a wide range of applications, including online 
education, video marketing, and false thumbnail 
videos
