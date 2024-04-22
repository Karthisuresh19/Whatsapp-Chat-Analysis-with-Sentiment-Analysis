
# Whatsapp chat sentiment analyzer

This is my first data analysis project which involves NLP topics. Designed a Streamlit web app for interactive data exploration. Analyzed WhatsApp chat data, studied trends and sentiments using VADER. If you want to know some insights about your chats and contacts in WhatsApp, the created web app provides you those insights. It leaves you with various information like most frequently contacted person, most active person in a group, most frequently used words and also provides sentiment analysis of the chat with a particular contact saying how positive or negative is that particular contact.
You can see the following results on overall group & individual as well :

- Monthly Activity map(Positive, Neutral, Negative)
- Daily Activity map(Positive, Neutral, Negative)
- Weekly Activity map(Positive, Neutral, Negative)
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


