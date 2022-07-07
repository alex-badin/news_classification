# news_classification
Pipeline for news classification using zero-shot encoding:

1) load json-file with news (telegram format)
2) clean news texts 
3) filter news for key words
4) Zero-shot endcoding. Zero-shot can consist 2 levels with the following logic: 
    1) encode by first level of labels
    2) filter by one of the labels
    3) encode filtered texts by sub-labels.
