# Sentiment-Analysis-on-IMDB-tfds-

In this project ,using the 'imdb_reviews' of tfds(tensorflow datasets),I was able to perform sentiment analysi(whether the review was positive or negative).I create a deep learning model having an excellent accuracy and a validation accuracy of 83.24% at training time.After that,I downloaded the metadata (having actual words) and the vector file(vector direction of the words as words having positive meaning will point to a similar direction in the vector plane).

Using the Embedding Projector,the Word embeddings were viewed as follows:

![imdb_reviews_pic1](https://user-images.githubusercontent.com/58786895/87229403-4e6d9700-c3c5-11ea-8385-4fb47616e82b.png)


Checking for word 'boring',we get many words having similar meaning.

![imdb_reviews_pic2](https://user-images.githubusercontent.com/58786895/87229443-955b8c80-c3c5-11ea-9b12-2dc23f3c017a.png)

Just those words similar to the word 'boring',having a negative feedback:


![imdb_reviews_Pic3](https://user-images.githubusercontent.com/58786895/87229466-c6d45800-c3c5-11ea-8759-13c2064b796a.png)
