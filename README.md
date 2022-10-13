# Exploratory Data Analysis on Twitter archive enhanced
## by Ismaheel Bello


## Dataset

> This project deals with the collection,cleaning,visualizing and analyzing of tweets from a Twitter handle <b>@dogrates</b> also
known as <b>#WeRateDogs</b>, this twitter handle is mostly known for rating people's dogs, and as well make comments about them.
For the scope of this Project we have 3 different dataset which are being gathered for Analysis. 
The first is the <code>twitter_archive_enhanced.csv</code> data, this dataset consist of <code>tweet_id</code> ,<code>tweet_text</code> and some other details of tweets rated by by <b>#WeRateDogs</b>, this dataset is made available by udacity.com, The second dataset is the <code>image_prediction.tsv</code> dataset, it was downloaded programatically <a href=' https://d17h27t6h515a5.cloudfront.net/topher/2017/August/599fd2ad_image-predictions/image-predictions.tsv'>here.</a> it consist of predictions of images rated by <b>#WeRateDogs</b> to get some specific information on them, including knowing if those rated images are dogs or not. The third dataset <code>tweet_json.txt</code> used in this project is gathered by using twitter API tweepy to gather additional information about the tweets. The analysis done in the project will not contain tweets beyond August 01 2017.

# Summary of findings

- The focus of this research work is based on dog tweets made by a popular twitter handle @dogrates, also known as #WeRateDogs. #WeRateDogs is known for rating people's dog. 1487 tweets was used for the
analysis of this research work, The tweets are between November 15 2015 and August 1st 2017. The data gathered contains several details about Dogs like Name, Breed, Stage etc. and ratings by #WeRateDogs
Out of breeds of dogs, that are being rated, it is observed that Pomeranian breed is the most rated Breed of Dog with an averge rating of 128.7% , followed by Saluki with an averge rating of 125%, followed by Briard
with an average rating of 123.3% followed by Tibetan mastiff with an average rating of 122.5%, followed by Border terrier with an average rating of 122%. These are the Top 5 most rated Dog Breeds.
Although no Dog Breed is rated below 50% , but the least is Japanese spaniel with an average rating of 50%, followed by Miniature schnauzer which is rated 83.3%, the other Dog Breeds are rated 90% and above.
Even though Pomeranian breed is the most rated Dog Breeds, the Breed with the highest retweet on Average is Flat-coated retriever,they have an Average retweet of 5300, followed by Afghan hound with an Average
retweet of 4765, followed by English springer with 4641, then Eskimo dog with 4390 retweet, and then Saluki with an averge retweet of 4113. These are the Top 5 Dog breeds with the Highest retweet by Twitter Users. Does the number of retweet of each Dog has any Association with the number of favorite Each Dog gets? The Simple answer is Yes. According to the analysis being carried out, The number of retweet has a Strong
Positive impact on the favorite count of each Dog. The more the retweet, the more the favorite each Dog gets, but the rating given to any dog does not have any Association with the number of retweet or favorite it get.

