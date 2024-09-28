Coded a Spam Classification model for both SMS and Mail
<br>
Removed unwanted columns and removed duplicated values from the dataset. Used LabelEncoder so that it is possible for Algorithms to Comprehend the data. Then used NLTK Library for Word Tokenizing and Sentence Tokenizing.
<br> 
The Graphs plotted are to see the difference in sentences, words and characters in Ham Messages and Spam Messages. Applied Preprocessing on the data for Stemming and removing Punctuation. Used the WordCloud to see the Top used words in both Ham Messages and Spam Messages and also ploted a graph to see the number of times the particular words were used.
<br>
Used TFidf Vectorizerizer then used GaussianNB, MultinomialNB, BernoulliNB these Algorithms to test which Algorithm gives better Accuracy Score and Precision Score for the Model
