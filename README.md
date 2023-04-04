As part of the final tests of TheBridge Data Science Bootcamp, participants were requested to monitor the school's Twitter account using the knowledge acquired during the course. This technical test was followed by a subsequent technical interview, where candidates had the opportunity to present and defend their work, as well as to answer questions related to the world of Data Science.

<div id="header" align="center">
  <img src="https://github.com/MNievas12/ds_thebridge_11_22/blob/main/1-Ramp_Up/Presentaciones/img/TheBridge_logo.png" width="800"/>
</div>

<h2>Project tasks</h2>

1. **Extraction and collection of tweets** mentioning the @TheBridge_Tech account, from the beginning of the bootcamp (November 21) until its end (March 7).
2. Storage of the collected data in a **SQL database deployed on AWS**, divided into two normalized tables: (tweets, users)
3. Conducting a **small exploratory data analysis** to answer the following business questions:
  a. What is the tweet with the greatest social impact?
  b. Which user mentions the school the most?
  c. In which month were the most tweets published?
  d. What are the most frequent words?
  e. What kind of mathematical correlation do you find among the public metrics?
  f. Did you draw any additional conclusions from your analysis?
4. **Using the pre-trained sentiment analysis model** provided, participants had to determine the sentiment of the tweets.
  a. What were the predictions? How did you interpret the results?
  b. Which variables are the most important in the model?
  c. How could the model be improved?
  d. What other opportunities can you think of where other ML models could be applied?
5. Finally, participants were required to prepare a maximum **5-minute presentation**, in which they would present the data and conclusions obtained.

<h2>Repository files</h2>

- Datos_Twitter_TheBridge.xls &rarr; A document containing all the data of the tweets that will be used for processing
- Presentation Spanish.pptx &rarr; Powerpoint with the presentation that was done on March 10th
- README.md
- Technical test.ipynb &rarr; A report where you can find the development of the entire coding and monitoring process, along with brief explanations and conclusions
- sentiment_model &rarr; pre-trained model used for this work

<h2>Necessary libraries</h2>

```
demoji==1.1.0
eli5==0.13.0
langdetect==1.0.9
matplotlib==3.5.3
nltk==3.8.1
pandas==1.3.5
pickleshare==0.7.5
PyMySQL==1.0.2
regex==2022.10.31
seaborn==0.12.1
snscrape==0.3.4
```

Thank you so much for your attention! Do not hesitate in getting in contact with me for any question, comment or collaboration.
