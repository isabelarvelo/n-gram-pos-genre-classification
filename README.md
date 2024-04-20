# Leveraging N-Gram Part-of-Speech Tag Sequences for Automatic Genre Classification 

This study investigates the distinctive linguistic structures between fiction and non-fiction texts using n-gram part-of-speech (POS) tag sequences. By analyzing a corpus of English texts from Project Gutenberg, we examine how these structures capture genre-specific language patterns and assess the effec-tiveness of incorporating longer n-gram sequences in a binary classification task. Statistical analysis reveals that verbs and pronouns are the most characteristic POS tags in fiction, while adpositions and conjunctions are more prevalent in non-fiction. Logistic regression models trained on unigram and 1–4-gram POS features achieve high accuracy in genre classifica-tion, with the 1-4-gram model performing slightly better. However, the marginal improvement suggests that additional information provided by longer n-grams may not significantly enhance the model's discriminative power. The findings offer insights into the linguistic differences between genres and highlight the potential of using POS tags for automated genre classification in various applications, such as book recom-mendation systems and library cataloging.

## Data 

The data used in this study is too large to uploade directly into GitHub, but can be downloaded from HuggingFace using the code in `data_download.ipynb`. Please note that the raw csv files will take up over 2 GB of space each. After running the code in the relevant notebook, you should have two csv files with raw data: 

* `gutenberg_books_raw.csv`
* `gutenberg_books_raw_2.csv`

## Analysis 

The code for this analysis can be found in and and reproduced using `pos-n-gram-agc.ipynb`. 

If you have any question sabout the paper or the code used to produce the analysis, please reach out to Isabel Arvelo (isabel.c.arvelo@vanderbilt.edu). 


