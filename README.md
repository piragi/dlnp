# exercise3_rnn

Your homework is to build a next word predictor using an RNN. You can use the code provided and the dataset.json file which is split in the first part of the sentence and the last word which you will need to predict.
- You will have to split the training data into train/test/val.
- Optional: Do k-fold cross validation.
- Try different number of layers and measure change in performance.
- You can modify the dataset to predict inner words but it will make building the model more difficult.

Goals: 
Evaluate how well the model predicts the next word on the testing dataset

Build a sentence_generator which can generate arbitrarily long sentences. 

Try to prevent the output from repeating the same word over and over (I wrote a poem poem poem poem poem poem poem poem poem poem poem).
Can your model generate plausible sentences? Bring your examples!
