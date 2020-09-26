# Visualization and Parspeech Sentiment using LIWC, FINN, Bing and NRC

## Check the Speech Dataset

| Countries               |     Periods     | Object Names |  
|-------------------------|:---------------:|-------------:|
| the Genman Bundestag    | 1991/03-2013/09 | bt.corpus    |
| the Spanish Congresso   | 1989/11-2015/10 | cong.corpus  |  
| the Finnish Eduskunta   | 1991/04-2015/12 | ed.corpus    |   
| the UK House of Commons | 1988/11-2015/01 | hoc.corpus   | 
| the Czech Poslanecká    | 1993/01-2016/06 | psp.corpus   |   
| the Swedish Riksdagen   | 1990/10-2015/12 | rd.corpus    |   
| the Dutch Tweede Kamer  | 1994/12-2015/11 | tk.corpus    |   


## Lexicon Based Sentiment Scores
- FINN 
The AFINN lexicon is a list of English terms manually rated for valence with an integer between `-5 (negative)` and `+5 (positive)` by Finn Årup Nielsen between 2009 and 2011. 

- NRC    
The NRC Emotion Lexicon is a list of English words and their associations with eight basic emotions (anger, fear, anticipation, trust, surprise, sadness, joy, and disgust) and `two sentiments` (negative and positive). The annotations were manually done by crowdsourcing. Lexicon source: http://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm

- Bing
A list of English `positive` and `negative` opinion words or sentiment words (around 6800 words). This list was compiled over many years starting from our first paper (Hu and Liu, KDD-2004).  Data source :https://www.cs.uic.edu/~liub/FBS/sentiment-analysis.html