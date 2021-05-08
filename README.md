# Visualizing Parspeech Dataset's Sentiment Using Various Types of Sentiment Dictionaries 

<p align="center">
  <img width="400" height= "320" src="https://github.com/davidycliao/figures/blob/master/uk_top_animate.gif">
  <img width="440" height= "335"  src="https://raw.githack.com/davidycliao/figures/master/hoc_NRC.gif">
</p>

[Visualization & Data Curation](https://raw.githack.com/davidycliao/2019-SUMMER-RA/master/ParspeechV1.html) :orange_book:

<br/>


## Overview of the Speech Dataset
___ParlSpeech__ contains more than 3.9 million entire speeches in the key legislative chambers of the Czech Republic, Finland, Germany, the Netherlands, Spain, Sweden, and the United Kingdom. Speeches are annotated with date, speaker and party and collected by [Rauh, De Wilde and Schwalbach (2017)](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/E4RSP9). 

| Countries               |     Periods     |         Dict Type           | Data Start-Date |    
|-------------------------|:---------------:|:---------------------------:|:---------------:|
| The UK House of Commons | 1988/11-2015/01 |`FINN`, `NRC`, `Bing`,`LIWC` |       1989    	|
| The Spanish Congresso   | 1989/11-2015/10 |`FINN`, `NRC`, `Bing`,`LIWC` |       1990      |
| The German Bundestag    | 1991/03-2013/09 |`FINN`, `NRC`, `Bing`,`LIWC` |       1991      |
| The Dutch Tweede Kamer  | 1994/12-2015/11 |`FINN`, `NRC`, `Bing`,`LIWC` |       1995      |
| The Czech Poslaneck     | 1993/01-2016/06 |`FINN`, `NRC`, `Bing`        |       1993      |
| The Finnish Eduskunta   | 1991/04-2015/12 |`FINN`, `NRC`, `Bing`        |       2009      |
| The Swedish Riksdagen   | 1990/10-2015/12 |`FINN`, `NRC`, `Bing`        |       1992      |

<br/>


## Lexicon Based Sentiment Scores

[**AFINN**](https://github.com/fnielsen/afinn)  <br /> The AFINN lexicon is a list of English terms manually rated for valence with an integer between `-5 (negative)` and `+5 (positive)` by Finn Årup Nielsen between 2009 and 2011.<br />

[**NRC**](http://saifmohammad.com/WebPages/NRC-Emotion-Lexicon.htm)    <br /> The NRC Emotion Lexicon is a list of English words and their associations with eight basic emotions (anger, fear, anticipation, trust, surprise, sadness, joy, and disgust) and `two sentiments` (negative and positive). The annotations were manually done by crowdsourcing.<br />

[**Bing**](https://www.cs.uic.edu/~liub/FBS/sentiment-analysis.html)   <br /> A list of English `positive` and `negative` opinion words or sentiment words (around 6800 words). <br />

[**LIWC**](https://repositories.lib.utexas.edu/bitstream/handle/2152/31333/LIWC2015_LanguageManual.pdf)  <br /> Variables include `affect`, `positive emotion`, `negative emotion`, `anxiety`,`anger` and `sadness`. <br />


## Acknowledge 
We acknowledge the use of the High Performance Computing Facility, [CERES Cluster](https://hpc.essex.ac.uk/), and its associated support services at the University of Essex in the completion of my research projects.
