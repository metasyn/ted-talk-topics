# TED 2013: a topical exploration

I'm doing some document clustering and maybe some topic modeling with this data
set.

[View the Ipython Notebook
here](http://nbviewer.ipython.org/github/metasyn/ted-talk-topics/blob/master/ted.ipynb).

## The Data
[OPUS](http://opus.lingfil.uu.se/TED2013.php) provided the data, with credits
due to Jörg Tiedemann for his inspiring work in parallel corpus linguistics.

* ~1179 TED Talks

## The Methods

### Clustering
* tokenized bag-of-words approach
* term frequency - inverse document frequency (tf-idf) measurements
* singular value decomposition (SVD) for inital dimensionality reduction
* t-stochastic neighbor embedding (t-SNE) for further dimensionality reduction,
    if we want any chartable results that is
* k-means clustering for cluster analysis


### Topic Modeling
I'd like to explore
* latent dirichlet allocation
* pachinko allocation machines
* latent semantic analysis
* latent semantic indexing
