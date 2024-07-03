# cognitive-distortions
This project focused on analyzing the online expressions related to the mental health of Singaporean students and North American teenagers. Leveraging a vast dataset from Reddit comprising over 31 million posts and comments, we employed techniques such as time series analysis and natural language processing in Python programming language to identify text patterns in sequences of 1 to 5 grams (n-grams). These text patterns are expressions of cognitive distortions with links to mental health as described in Bollen et al. (2021) paper in the Proceedings of the National Academy of the United States of America. Our findings have yielded interesting results, revealing an unexpected trend in distortions post-COVID-19 that are region-specific. I have further analyzed the data in more detail including using large language models (RoBERTa and Sentence BERT). RoBERTa was used in the main detection algorithm, giving us the score of the positive, neutral, and negative probability of a sentence (basically a kind of sentimental analysis). I used SentenceBERT for topic modeling to give further insights into which distortions are more common. </br>
Code can be run seperately on each dataset (I divided the dataset into five parts and calculated for each part separately, which were later merged).
