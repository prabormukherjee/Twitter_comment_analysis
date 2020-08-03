# Twitter_comments

Here I implimented a classifier using NLP to predict whether a comment is positive or negative. The datset I used is from kaggel. A problem with this dataset is it has a class balence problem. Where one class has significantly large data than other one. You can improve it by SMOTE (Synthetic Minority Oversampling Technique) or use XgBoost or also can try K-fold cross validation to retrain and make the model robust.
<br>
After data cleaning I filted the data with NLTK , for removing the stopwords. Then performed count vectorization. And finally trained using Naive based classifier.
<br>
The dataset is added. Instruction and dependencies are also provided in the notebook. The algorithm is also explained in the notebook.If you like to check some other NLP problem on sentiment analysis then here is some other project by me.
<br>
<ol>
  <a href='https://github.com/Prabor1/Hotel_comment'>Hotel Comment</a>
  <a herf='https://github.com/Prabor1/Movie_comment'>Movie Comment</a>
</ol>
