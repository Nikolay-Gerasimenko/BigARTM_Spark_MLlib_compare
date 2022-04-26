# AITD (Artificial Intelligence Trends Dataset)

Collocations and metadata are in *collection.csv*
Markup for our AITD is in *trends_markup.csv*
Dataset statistics are described in our paper [Gerasimenko et al. "Incremental Topic Modeling for Scientific Trend Topics Extraction"](http://...)

## Structure of the *collection.csv*:
- ```trend_name``` - trend name
- ```paper_ids``` - subset of papers related to the trend (ids from Semantic Scholar ORD)
- ```key_collocations``` - trend keywords
- ```trend_name_synonyms``` - possible trend names

## Structure of the *trends_markup.csv*:
- ```paper_id``` - papers id (ids from Semantic Scholar ORD)
- ```collocations``` - collocations extracted from paper with TopMine algorithm [El-Kishky, Ahmed, et al. "Scalable topical phrase mining from text corpora." Proceedings of the VLDB Endowment 8.3 (2014): 305-316.APA](http://hanj.cs.illinois.edu/pdf/vldb15_ael-kishky.pdf)
- ```title``` - papers title
- ```in_links``` - papers which has this paper in references
- ```out_links``` - papers which this paper has in references
- ```conference``` - сonference at which the article was published
- ```authors_ids``` - papers authors (ids from Semantic Scholar ORD)
- ```conf_pub_date``` - date of publication of the article at the conference
- ```arxiv_pub_date``` - date of publication of the article at the arXiv.org
