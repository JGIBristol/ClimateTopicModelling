# Contents

Code and instructions for applying [BERTopic Topic Modelling](https://maartengr.github.io/BERTopic/index.html) to free text survey responses from a survey of people's lived experiences during extreme weather events in Bristol. No data is stored in this repo. 

## ZeroShotBertTopic.ipynb
- This notebook loads in your data, trains your BERTopic model and saves some outputs including data tables and diagnostic plots.
- The data loading is left to give an example but will not run unless you have the required datasets in your working directory.
- They can however be easily modified to load in other datasets.
- Slightly misleading name. This BERTopic model has commented out code that means you can run this as a ZeroShot model (you can dictate zeroshot terms in the data loading stage or manually deploy them) but it also runs fine unsupervised.

## TopicModellingWithBERT.pptx
- Slide deck for a talk Huw gave to the Bristol Climate group on 13/11/2024.
- Tried to keep text sparse on the slides but more denser in the notes so you can follow along!
