# A first cut

We're going to look at these documents using code derived from the Tensorflow `word2vec` demo code available [here](https://github.com/tensorflow/tensorflow/blob/master/tensorflow/examples/tutorials/word2vec/word2vec_basic.py), where the author analyzes the text8 corpus.

We train the model in 100001 steps and plot 500 words. We plot the results using `matplotlib` but for clarity we remove the axes and scatterplot points. 

![41dff](/pentagon-papers/41dff.png)

This has some of the results we would like to see: the names of the US Presidents are close together near the top center, some of the bullet point markers (e.g. "(3", "(2", "(4") cluster near top center, and some of the variant pairs ("63316" and "63316.", "War" and "War,", "Volume" and "Volun:e") are near each other, and some of the years are relatively close, some not.

[A second cut](/pentagon-papers/second-cut.html)
