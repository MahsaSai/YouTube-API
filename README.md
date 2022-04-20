# YouTube-API
The process of retrieving video data and channel data using YouTube Data API
In this project we retrieve feeds related to videos, users, and playlists. We also can compare two or more YouTuber in different topics.
## requirements
Refer to this link https://developers.google.com/youtube/v3/getting-started
- Need a Google Account
- Creat a project in Google Developers Console
- Get API key (by click on Credentials section> Create credentials>API key) and use it in the project
- Then in in Dashboard section> Click on ENABLE API AND SERVICES bottom> search for YouTube API data V3> then click on Entable
### Quota Usage 
Please note the Quota allocation is 10,000 units per day.
- read operation usually costs 1 unit
- write operation usually costs 50 units
- search request costs 100 units
- upload request costs 1000 units
 
##Installation

'''bash
!pip install --upgrade google-api-python-client
'''

##Libraries

'''python
from googleapiclient.discovery import build
from dateutil import parser
import pandas as pd
from IPython.display import JSON
import json

# Data visualization 
import seaborn as sns
import matplotlib.pyplot as plt
import matplotlib.ticker as ticker

# NLP
import nltk
from nltk.corpus import stopwords
from nltk.tokenize import word_tokenize
nltk.download('stopwords')
nltk.download('punkt')
from wordcloud import WordCloud
'''

