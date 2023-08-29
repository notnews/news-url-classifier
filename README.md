## News URL Classifier

Use strings in the URL to classify the kind of news. 

Data from: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/OTJMYQ

Hard/soft news labels for ~ 300 articles hand-coded. 

### Reference

1. See this paper: https://osf.io/krhmq

  "Finally, we point curious researchers to the paths of URLs, which often contain human-readable  text  similar  to  titles.   For  example,  from  the  URL https://www.theguardian.com/politics/2023/aug/01/boris-johnson-swimming-pool-newts-oxfordshire, one could use “boris johnson swimming pool newts oxfordshire” as input for an NLP classifier. Although we know of no studies doing so, this seems like an intriguing possibility."

2. For regex versions from Bakshy et al., see https://github.com/themains/rdomains/blob/master/R/not_news.R#L9 and https://github.com/notnews/notnews/blob/master/notnews/soft_news_url_cat_us.py
