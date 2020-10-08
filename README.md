# WikiLingua: A Multilingual Abstractive Summarization Dataset #

This repo contains dataset introduced in the following paper: 

[WikiLingua: A New Benchmark Dataset for Multilingual Abstractive
Summarization](https://arxiv.org/abs/2010.03093) 

Download the dataset using [this link](https://drive.google.com/drive/folders/1PFvXUOsW_KSEzFm5ixB8J8BDB8zRRfHW?usp=sharing).

Please refer to this [Collab notebook](https://colab.research.google.com/drive/1HxonmcM7EOQVal2I6oTi9QWEP257BgDP?usp=sharing) to see how to align articles in other languages with the parallel English articles. 

## Reference ##
Please cite the following paper: 

```
@inproceedings{ladhak2020,
    title={WikiLingua: A New Benchmark Dataset for Multilingual Abstractive Summarization},
    author={Faisal Ladhak, Esin Durmus, Claire Cardie and Kathleen McKeown},
    booktitle={Findings of EMNLP, 2020},
    year={2020}
}
```

## Description ##

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

## License ##

- Article provided by wikiHow <https://www.wikihow.com/Main-Page>, a wiki building the world's largest, highest quality how-to manual. Please edit this article and find author credits at wikiHow.com. Content on wikiHow can be shared under a [Creative Commons license](http://creativecommons.org/licenses/by-nc-sa/3.0/).

- Refer to [this webpage](https://www.wikihow.com/wikiHow:Attribution) for the specific attribution guidelines. 
