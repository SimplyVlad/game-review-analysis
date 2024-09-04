# Game Reviews Analysis

Using NLP models, an analysis of review texts is performed. First, in [data_processing.ipynb](https://gitlab.com/SimplyVlad/game-reviews-analysis/-/blob/main/data_processing.ipynb), we load and put the data in a form suitable for modelling. Second, in [toxicity_and_sentiment_extract.ipynb](https://gitlab.com/SimplyVlad/game-reviews-analysis/-/blob/main/toxicity_and_sentiment_extract.ipynb), further model specific processing is performed and then using two popular models - detoxify and vader, toxicity scores and sentiment classes are infered. The results are finally explored in [data_exploration.ipynb](https://gitlab.com/SimplyVlad/game-reviews-analysis/-/blob/main/data_exploration.ipynb) in the aim of answering 4 key research questions: <br>

1. Which are the most toxic games with more than 30 reviews?
2. Is there a correlation between negative sentiment and toxicity?
3. Is there a correlation between recommendation and toxicity?
4. How predictive is the sentiment of a text to the recommendation chance?


## Sources
Data: 
Apurva Pathak, Kshitiz Gupta, Julian McAuley Generating and Personalizing Bundle Recommendations on Steam. SIGIR, 2017.
Wang-Cheng Kang, Julian McAuley Self-attentive sequential recommendation. ICDM, 2018. 
Apurva Pathak, Kshitiz Gupta, Julian McAuley Item recommendation on monotonic behavior chains. RecSys, 2018.

## Roadmap
Use tf-idf to generate comments based recommendations.

## License
MIT License

## Project status
Active
