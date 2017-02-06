# A second cut

This has some of the results we would like to see: the names of the US Presidents are close together near the top center, some of the bullet point markers (e.g. "(3", "(2", "(4") cluster near top center, and some of the variant pairs ("63316" and "63316.", "War" and "War,", "Volume" and "Volun:e") are near each other, and some of the years are relatively close, some not.

We've cleaned up the data somewhat by removing punctuation and small tokens. This gets rid of a lot of the garbage. Next we've used colors to distinguish different kinds of tokens: red for stopwords, cyan for partial tokens, yellow for junk, green for token that start with capital letters, and black for everything else.

![aef9f](/pentagon-papers/aef9f.png)

We're displaying another hundred tokens, and we're running 7000001 iterations, about 70x more than for the initial run. The results here are substantially better, with some of the transcription differences for the same token showing up near each other, and with dates clustering fairly near each other in a couple of clusters.

This could do with more work; it would probably be better to have a dynamic view of the data rather than a static view, and it might be worth running a lot more iterations to see how much more the results can converge.

