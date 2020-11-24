This is the link I follow to do the train.
https://medium.com/swlh/a-simple-guide-on-using-bert-for-text-classification-bbf041ac8d04

I tried the data by combining the data of all TOPS, or using the data with each row contains one tops. However, the loss is high about 0.6*
The result is not good.

The prepareData.ipynb. used to do some clean work and generate the data for bert to use.
TrainBert.ipynb is used to train the train data
BERT_eval.ipynb is used to eval the model.

There are things like TaskName you may need to change for your train data each time to use the right data.