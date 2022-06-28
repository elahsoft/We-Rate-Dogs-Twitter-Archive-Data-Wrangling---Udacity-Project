# WeRateDogs Twitter Archive Dataset Exploration
## by Opara Febechukwu Chinonyerem


## Dataset

> This project is investigating the tweet archive of Twitter user @dog_rates also known as WeRateDogs. They rate people's dogs with a humorous comment about the dog. The rating comes with a denominator of 10 and the numerator is always greater than 10. The project is investigating three datasets.

    The enhanced twitter archive
    Data gathered from twitter API (retweet count, favorite count)
    Image Predictions File: Which is the output gotten by running the dog's image through a neural network. Columns include:
        tweet_id: The last part of the tweet url after "status/"-> https://twitter.com/dog-rates/status/88,,,,921
        TP1: The algorithm's number 1 prediction for the image in the tweet.
        TP1_conf: How confident the algorithm is in its number 1 prediction.
        TP1_dog: Whether or not the number 1 prediction is a breed of dog.
        TP2: The algorithm's second most likely prediction.
        TP2_conf: How confident the algorithm is in its number 2 prediction.
        TP2_dog: Whether or not the number 2 prediction is a breed of dog. e.t.c
 
Insights

> Rating Numerator has 12 as the modal value.

> The values of tp3_confidence has an exponential distribution.

> The values of tp1_confidence is bimodal.

> The values of tp2_confidence are seeming exponentially distributed as well.

> Floofer is the least classification of dogs at WeRateDogs archive.

> Many dogs were not classified to be under any growth category.
