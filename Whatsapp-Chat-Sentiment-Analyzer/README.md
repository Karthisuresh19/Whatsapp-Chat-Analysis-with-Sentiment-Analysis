
# Whatsapp chat sentiment analyzer

After battling numerous errors, finally completed making Whatsapp Chat Sentiment analyzer, my first data analysis project. It is based on SentimentIntensityAnalyzer class from "nltk.sentiment.vader" module. If you ever wonder who is the most positive person in your whatsapp group of let say 200+ or less members then this is what you are looking for.
Not only posititve user, you can see the following results on overall group & individual as well :

- Monthly Activity map(Positive, Neutral, Negative)
- Daily Activity map(Positive, Neutral, Negative)
- Weekly Activity map(Positive, Neutral, Negative)
- Daily timeline(Positive, Neutral, Negative)
- Monthly timeline(Positive, Neutral, Negative)
- Percentage Contribution(Positive, Neutral, Negative)
- Word Cloud(Positive, Neutral, Negative)
- Most Common words(Positive, Neutral, Negative)
- Most user(Positive, Neutral, Negative)

You just have to perform the following task in order to get analysis.
- Export whatsapp chat (24 hour format).
- Browse the file.
- Click Show Analysis.


## Run locally

Create new project in pycharm and add above files. After that open terminal and run the following command. This will install all the modules needed to run this app. 

```bash
pip install -r requirements.txt
```

To run the app, type following command in terminal. 
```bash
streamlit run app.py
```

## Libraries

- streamlit
- matplotlib
- seaborn
- nltk
- collection
- wordcloud
- urlextract
- emoji


