# AITD (Artificial Intelligence Trends Dataset)

Collocations and metadata are in ```collection.csv``` \
Markup is in ```trends_markup.csv``` \
Dataset statistics are described in our paper [... et al. "Incremental Topic Modeling for Scientific Trend Topics Extraction"](http://...) \
All ids of authors and papers are from Semantic Scholar ORD.

## Structure of the *collection.csv*:
- ```trend_name``` — trend name
- ```paper_ids``` — subset of papers related to the trend
- ```key_collocations``` — trend keywords
- ```trend_name_synonyms``` — possible trend names

## Structure of the *trends_markup.csv*:
- ```paper_id``` - paper id
- ```collocations``` - collocations extracted from the paper with TopMine algorithm [El-Kishky, Ahmed, et al. "Scalable topical phrase mining from text corpora." Proceedings of the VLDB Endowment 8.3 (2014): 305-316.APA](http://hanj.cs.illinois.edu/pdf/vldb15_ael-kishky.pdf)
- ```title``` - paper title
- ```in_links``` - papers which have this paper in references
- ```out_links``` - papers which this paper has in references
- ```conference``` - сonference at which the article was published
- ```authors_ids``` - ids of the authors
- ```conf_pub_date``` - date at which the the article was published at the conference
- ```arxiv_pub_date``` - date at which the the article was published at the arXiv.org
