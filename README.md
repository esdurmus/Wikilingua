# Wikilingua: A Multilingual Abstractive Dataset #

This repo contains dataset introduced in the following paper: 

[WikiLingua: A New Benchmark Dataset for Multilingual Abstractive
Summarization](<link>) 

The dataset includes ~770k article and summary pairs in 18 languages from WikiHow. We extracted gold-standard article-summary alignments across languages by aligning the images that are used to describe each how-to step in an article.

The table below shows number of article-summary pairs with a parallel article-summary pair in English. 
______________________________
| Language    | Num. parallel |
| ----------- | --------------|
| English     |   141,457     |
| Spanish     |   113,215     |
| Portuguese  |    81,695     |
| French      |    63,692     |
| German      |    58,375     |
| Russian     |    52,928     |
| Italian     |    50,968     |
| Indonesian  |    47,511     |
| Dutch       |    31,270     |
| Arabic      |    29,229     |
| Vietnamese  |    19,600     |
| Chinese     |    18,887     |
| Thai        |    14,770     |
| Japanese    |    12,669     |
| Korean      |    12,189     |
| Hindi       |     9,929     |
| Czech       |     7,200     |
| Turkish     |     4,503     |

* **data/** includes the full dataset. 
* **splits/** includes train, validation and test splits (for Spanish, Russian, Vietnamese and Turkish) used in our experiments. 

## Reference ##

Please cite the following paper: 







