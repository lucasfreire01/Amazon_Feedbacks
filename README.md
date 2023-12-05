# Amazon_Feedbacks
Hello, guys, I'm here to tell you a little about this project, the goal is to predict if the client will like the Amazon Echo variation. This dataset has 5 columns:<br>

Rating: The column has values from 1 to 5 this is the evaluation of the variation.<br>
Date: The date this relative extraction data<br>
Variation: The variation of Amazon Echo<br>
Verified_reviews: The reviews of clients<br>
feedback: The goal column <br>

This data got a little preprocessing encoding some columns<br>
The variation column: each value has a column with binary values<br>
Verified_reviews: creating vectors and using stop_words to clear these specific dates<br>

Model<br>
The model was built with 1 input layer, 1 hidden layer, and 1 output layer. The model chosen was Sequential with  relu activation in the input and hidden layers and sigmoid in the output layer. Next, the result is reset in the 0 or 1 because the goal column is a binary value<br>
![Model train score]((https://drive.google.com/drive/u/1/my-drive)https://drive.google.com/drive/u/1/my-drive)
