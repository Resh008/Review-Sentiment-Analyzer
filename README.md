# Review-Sentiment-Analyzer

In this study, I explored sentiment analysis on reviews of Kindle books. Our objective was to classify 
these reviews into positive, negative, or neutral categories. I employed a text classification 
approach, a technique that involves analyzing textual data and assigning it to predetermined 
classifications. To achieve this, we developed a sequential model utilizing Long Short-Term 
Memory (LSTM) networks. LSTMs are a type of recurrent neural network (RNN) adept at handling 
sequential data, such as text. The model incorporated an embedding layer, which numerically 
represents words, followed by batch normalization for enhanced stability. An LSTM layer was then 
employed to capture the relationships within the text data. Finally, a dropout layer was included 
to mitigate overfitting. This report researches into the model's performance and its efficacy in 
classifying unseen data.
