# Visualization and Parspeech Sentiment Using Various Type of Dictionary Based Sentiment Analysis 

<p align="center">
  <img width="240" height= "120" src="https://raw.githack.com/yl17124/yl17124.github.io/master/images/hoc_NRC.gif">
  <img width="240" height= "120" src="https://raw.githack.com/yl17124/yl17124.github.io/master/images/bt_NRC.gif">
</p>




## Check the Speech Dataset

| Countries               |     Periods     |     Object Names    |          Dict Type          | Start Date & Year | Data Start-Date |    
|-------------------------|:---------------:|--------------------:|----------------------------:|:-----------------:|:---------------:|
| The UK House of Commons | 1988/11-2015/01 | hoc_MPs_Party_Year  |`FINN`, `NRC`, `Bing`,`LIWC` |     1988-11-22    |       1989    	|
| The Spanish Congresso   | 1989/11-2015/10 | cong_MPs_Party_Year |`FINN`, `NRC`, `Bing`,`LIWC` |     1989-11-21    |       1990      |
| The German Bundestag    | 1991/03-2013/09 | bt_MPs_Party_Year   |`FINN`, `NRC`, `Bing`,`LIWC` |     1991-03-12    |       1991      |
| The Dutch Tweede Kamer  | 1994/12-2015/11 | tk_MPs_Party_Year   |`FINN`, `NRC`, `Bing`,`LIWC` |     1994-12-20    |       1995      |
| The Czech Poslaneck     | 1993/01-2016/06 | psp_MPs_Party_Year  |`FINN`, `NRC`, `Bing`        |     1993-01-01    |       1993      |
| The Finnish Eduskunta   | 1991/04-2015/12 | ed_MPs_Party_Year   |`FINN`, `NRC`, `Bing`        |     2009-02-18	  |       2009      |
| The Swedish Riksdagen   | 1990/10-2015/12 | rd_MPs_Party_Year   |`FINN`, `NRC`, `Bing`        |     1992-04-01	  |       1992      |
- To include years that are greater than 4/6 months of data.
- Start date of `UK`, `Spanish`, `Dutch`data are less than  2/3 (8 months), so I exclude the first year of these data. 



## Lexicon Based Sentiment Scores
- FINN 
The AFINN lexicon is a list of English terms manually rated for valence with an integer between `-5 (negative)` and `+5 (positive)` by Finn Årup Nielsen between 2009 and 2011. 

- NRC    
The NRC Emotion Lexicon is a list of English words and their associations with eight basic emotions (anger, fear, anticipation, trust, surprise, sadness, joy, and disgust) and `two sentiments` (negative and positive). The annotations were manually done by crowdsourcing. Lexicon source: http://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm

- Bing
A list of English `positive` and `negative` opinion words or sentiment words (around 6800 words). This list was compiled over many years starting from our first paper (Hu and Liu, KDD-2004).  Data source :https://www.cs.uic.edu/~liub/FBS/sentiment-analysis.html