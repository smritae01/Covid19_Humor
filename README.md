# I’m out of breath from laughing! I think?

## A dataset of COVID-19 Humor and its toxic variants

Humor is a cognitive construct which predominantly evokes the feeling of mirth. The growing distress and agony during COVID-19 pandemic reemphasised the need to study humor and its role in our daily lives. In this paper, we present a well curated dataset of COVID-19 humor with rich and reliable annotation. Our dataset comprises over 4K reddit posts, memes and comments, annotated with labels namely humor type, topic, maladaptive vs adaptive, and the target of the humor.

### Data

All the required data for analysis in the paper is included in the /data folder of this repository.

- humor-posts.csv : humorous posts with their text

- non-humor-posts.csv : non-humorous posts with their text

- adaptive_posts.csv : adaptive humorous posts with their text

- maladaptive_posts.csv : original maladaptive posts without backtranslation improvement. 

- maladaptive_train_backtrans.csv : augmented maladaptive training set after back translation

- humor_labels.csv : humorous posts along with labels for Adaptive, Type, Category, Target and Stereotype

- Annotation Instructions.pdf : The set of instructions given to the human annotators to label the dataset

- BackTranslation.ipynb : Data-augmentation completed using back translation for the maladaptive posts for use in finetuned RoBERTa.