# BongoTokenizer
  # Data preparation #


 * Wikipedia Bangla Articles:
      * Downloaded data bangla corpus from wiki-dump https://dumps.wikimedia.org/bnwiki/latest/
      * This data stored as **csv** format and stored in google drive
      * Each raw, we have 4 column:
          * **Id:**   Incremental integer number
          * **Title:** Title of that wiki article
          * **Text:** Whole article as text format
          * **URL:** Url to access that artcle
      * In this project, only *Text* column is being used

* Bangla Novels Data For Colloqual Texts
    * Downloaded 20+ novel data from https://archive.org/details/booksbylanguage_bengali
    * Open source kaggle data from https://www.kaggle.com/datasets/aagalib/complete-works-of-rabindranath-tagore
    * This data is already text format but there are many blank lines and spaces which has been removed in data pre-process stage
    * Stored data in Google Drive

After collecting data, all the combined in a text file and process for training.
Comprehensive Bangla language tokenizer
