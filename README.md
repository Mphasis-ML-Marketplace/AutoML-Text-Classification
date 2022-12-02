# AutoML-Text-Classification

## Product Overview

This solution provides an AutoML piepline which takes in an input csv that contains the labelled text data for any usecase along with a JSON file that contains the desired preprocessing steps that need to be used on the text data. The preprocessed data is then vectorized using different embeddings. Based on the train/test split in the input JSON, multiple ML models are trained using the various embeddings using the concept of AutoML. Once the models are trained and tuned, a leaderboard is returned to the user. The leaderboard contains the models sorted based on the chosen metric, all the metrics relevant to the models, and hyperparameter and embeddings used in the respective models. This will help the user in determining the best model for the text classification task at hand and the chosen model can be replicated or fine-tuned further in the future.


## Product Highlight
* This solution is tested on various text classfication problems both binary as well as multiclass classification. The solution extracts the text columns and the preprocessing techniques from JSON input provided by the user, thus making the methodology flexible for any text classification usecase.
* This solution can be used by individuals and companies in sectors like e-commerce, manufacturing, retail, etc. to perform text classification on data with both binary or multi-class labels. Some examples include categorizing email as spam or not, classifying the text reviews of different products or bucketing reviews into different sentiments.
* DeepInsights is a cloud-based cognitive computing platform that offers data extraction & predictive analytics capabilities. Need customized Image Analytics solutions? Get in touch!Mphasis DeepInsights is a cloud-based cognitive computing platform that offers data extraction & predictive analytics capabilities. Need Customized Deep learning and Machine Learning Solutions? Get in Touch!

## Amazon Marketplace Link
The product can be found [here](https://aws.amazon.com/marketplace/)
