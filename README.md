# Trump gab analysis
This analysis will consider social media posts from a new platform: http://gab.ai. 

The sample of this data is present here:
https://www.dropbox.com/s/izcasxrsqr3dowo/gabai.0013.json.gz?dl=0

The data file contains messages as json records, with one serialized json record per line.

### Analysis of the sample data set in general

The notebook [gab_ai_data_analysis](GAB_AI_DATA_ANALYSIS.ipynb) contains basic analysis answering the following questions: 
- Number of messages/gabs are in this dataset.
- Number of  users authored messages are in this dataset.
- The mean/median/max/min number of messages authored by a user.
- The 10 users with the most messages, and the number of messages each.
- The 5 most commonly included links.
- The 10 most commonly used words,
- Plot of the number of messages sent by day. x-axis day, y-axis number of messages

### Analysis about the gabs mentioning [Donald Trump](TRUMP_GAB_ANALYSIS.ipynb)

This notebook analyses gabs associated with donald trump.
