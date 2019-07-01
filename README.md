# Toxic Comments Classifier

Problem- Discussing things you care about can be difficult. The threat of abuse and harassment online means that many people stop expressing themselves and give up on seeking different opinions. Platforms struggle to effectively facilitate conversations, leading many communities to limit or completely shut down user comments.


This is a *Random Forest Classifer* model trained on  a large number of **Wikipedia** comments which have been labeled by human raters for toxic behavior.

 The types of toxicity are:
 
* toxic
* severe_toxic
* obscene
* threat
* insult
* identity_hate

The RFC model classifies each comment into one (or more) of the above mentioned comments-toxicity classes.

The dataset is preprocessed with **NLTK** before fitting to the model.

---
**Dataset License**: The dataset under CC0, with the underlying comment text being governed by Wikipedia's CC-SA-3.0