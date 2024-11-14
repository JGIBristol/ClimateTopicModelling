# Contents

Code and instructions for applying [BERTopic Topic Modelling](https://maartengr.github.io/BERTopic/index.html) to free text survey responses from a survey of people's lived experiences during extreme weather events in Bristol. No data is stored in this repo. 

## BertTopic.ipynb
- This notebook loads in your data, trains your BERTopic model and saves some outputs including data tables and diagnostic plots.
- The data loading is left to give an example but will not run unless you have the required datasets in your working directory.
- They can however be easily modified to load in other datasets.
- This BERTopic model has commented out code that means you can run this as a ZeroShot model (you can dictate zeroshot terms in the data loading stage or manually deploy them) but it also runs fine unsupervised.

## icicleplots.ipynb
- This notebook loads in documents and their topics, puts them into custom categories (as defined by Eunice and Jo).
- Then outputs icicle plots with some customisation using plotly.

## TopicModellingWithBERT.pptx
- Slide deck for a talk Huw gave to the Bristol Climate group on 13/11/2024.
- Tried to keep text sparse on the slides but more denser in the notes so you can follow along!
- Recording of the Zoom talk can be found [here](https://bristol-ac-uk.zoom.us/rec/play/it1e_jdSi60M_9qBQY83W4VEceIC2mUWaJ-tjiEgEfu2jlN777YLeA_o7lPb2lnymRaK2hQyww4Z-g-q.WtNUX3wVk4mYSRp_?canPlayFromShare=true&from=share_recording_detail&startTime=1731492541000&componentName=rec-play&originRequestUrl=https%3A%2F%2Fbristol-ac-uk.zoom.us%2Frec%2Fshare%2Ft8_guVy18oUjCLJ3wqs4la1jZJT_BI1hpwDZHw7wraS9Bw1QQ6JxaNJzl4hsPBNY.w4cDp3zrSpNpJrFq%3FstartTime%3D1731492541000)
