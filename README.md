# Spark-Network-Anamoly
Using the dataset NETWORK ANAMOLY DETECTION from kaggle - https://www.kaggle.com/anushonkar/network-anamoly-detection/version/1?select=Train.txthttps%3A%2F%2Fwww.kaggle.com%2Fanushonkar%2Fnetwork-anamoly-detection%2Fversion%2F1%3Fselect%3DTrain.txt

The train.txt and test.txt files are streamed via a tcp connection using spark streaming using the stream.py file to the spark-client.py file whilst logging to a log.txt file keeping track of the currently streaming file.
The data is streamed in batches, each batch getting cleaned and pre-processed before being fitted to various classifiers and clustering algorothms taking advantage of incremental learning from the Sklearn Library.

This project is the final project of the course BIG DATA(UE19CS322).
