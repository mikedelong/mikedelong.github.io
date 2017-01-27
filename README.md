# January 27, 2017

Is yesterday's picture interesting? Yes, I suppose so. It is kind of noisy and cluttered. First let's clean it up by removing the markers and as much padding as we can.

![Pentagon Papers: a first attempt](/pentagon-papers/41dff.png)

# January 26, 2017

## Pentagon Papers skip-gram

A first cut at visualizing the Pentagon Papers using skip-gram. For this visualization we simply

1. downloaded the PDFs of the Pentagon Papers
2. Extracted the text using `textract`
3. Train a word2vec model using Tensorflow
4. Visualize the results using matplotlib as a scatter plot

![Pentagon Papers: a first attempt](/pentagon-papers/0628d.png)


