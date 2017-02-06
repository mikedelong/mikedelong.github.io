# A second cut

We've cleaned up the data somewhat by removing punctuation and small tokens. This gets rid of a lot of the garbage. Next we've used colors to distinguish different kinds of tokens: red for stopwords, cyan for partial tokens, yellow for junk, green for tokens that start with capital letters, and black for everything else.

![aef9f](/pentagon-papers/aef9f.png)

We're displaying another hundred tokens, and we're running 7000001 iterations, about 70x more than for the initial run. The results here are substantially better, with some of the transcription differences for the same token showing up near each other, and with dates clustering fairly near each other in a couple of clusters.

This could do with more work; it would probably be better to have a dynamic view of the data rather than a static view, and it might be worth running a lot more iterations to see how much more the results can converge.

