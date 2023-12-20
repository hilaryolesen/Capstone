*News Article Sentiment Toward Climate Change in the Region Affected by Hurricane Ian*  
by Hilary Olesen

This project aims to discover if media sentiment toward climate change shifts after a costly hurricane in the region most affected by the hurricane. Futhermore, if there is a change, whether that change is continuous or if there is a specific window of time in which policy change is most likely to be effective.

Dataset columns (dataset available upon request only): Titles,	Dates,	Authors,	URLs,	Texts,	Source

Model used: Jochen Hartmann, "Emotion English DistilRoBERTa-base". [https://huggingface.co/j-hartmann/emotion-english-distilroberta-base/](https://huggingface.co/j-hartmann/emotion-english-distilroberta-base/), 2022.

Jupyter Notebook Descriptions:
* WebscrabeWINKmanyArticles.ipynb - used to gather dataset information from [WINK News](https://winknews.com/)
* WebscrabeFOXmanyArticles.ipynb - used to gather dataset information from [Fox 4](https://www.fox4now.com/)
* (Note: dataset information from the other two news sites, [ABC 7](https://abc-7.com/) and [NBC 2](https://nbc-2.com/), were obtained manually)
* ClimateOnly.ipynb - used to filter out non-climate-change-related articles that slipped in through websites' search function
* DataExploration.ipynb - preliminary exploration of the data with graphs
* Final7EmotionCapstoneDATA606.ipynb - main code with sentiment analysis and visualizations
