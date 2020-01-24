# Bachelor/Data Science/Linnaeus University
##### tags: Text Classifcation, POS tagging, Noun Phrase Chunking, NER tagging, Text Summarization



## Directory tree

```
.
├── README.md
└── main
    ├── data
    │   ├── _subjects
    │   │   ├── biology
    │   │   ├── geography
    │   │   └── physics
    │   │ 
    │   ├── block_1.csv
    │   ├── block_2.csv
    │   └── block_3.csv
    │
    ├── utils
    │   ├── heatmap_sum.ipynb
    │   ├── heatmap_tc.ipynb
    │   ├── newsroom_dataset.ipynb
    │   ├── nlp.ipynb
    │   ├── nlp_tc.ipynb
    │   ├── np.ipynb
    │   ├── rouge.ipynb
    │   └── text.ipynb
    │
    ├── centroid.ipynb
    ├── gensim.ipynb
    ├── glove.ipynb
    ├── ner_pos.ipynb
    ├── nltk_ner_pos.ipynb
    ├── tc_svm.ipynb
    ├── textrank.ipynb
    └── textsum.ipynb
    

```
###### # This repo reflects mostly our final work in Jupyter Lab.

## Missing datasets and other sources (due to max size in repo)

###  GloVe

Create a directory in main called 'glove.6B' (or it comes with the zip with additional files) and download 'glove.6B.100d.txt' from: [Stanford](https://nlp.stanford.edu/projects/glove/) (glove.6b.zip, size 822MB)


### Cornells Newsroom (ROUGE test dataset)

You have to apply for it at [Newsroom](https://summari.es/download/). Place the 'train.jsonl.gz' (size approx 2GB) in _data_ directory.

### Subject corpus

In directory _data_ you will find our small balanced dataset in _\_subjects_, but the big unbalanced one did not fit this repo, otherwise placed in _data/subjects_ (in our Jupyter notebook).

### StanfordNERTagger 

To use StanforNERTagger you need to download [Stanford Named Entity Recognizer version 3.9.2](https://nlp.stanford.edu/software/stanford-ner-2018-10-16.zip) (instant download). For more information before download [Stanford](https://nlp.stanford.edu/software/CRF-NER.shtml). Place the directory in _main_.


