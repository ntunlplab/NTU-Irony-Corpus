# NTU Irony Corpus

# Introduction
The NTU Irony Corpus consists of more than 1,000 microblog messages collected from the Plurk website. All the messages in the corpus are in Traditional Chinese and have been confirmed to be ironic. They are marked with three types of labels: (1) ironic word/phrase , (2) context, and (3) rhetoric element.

# Format
Example:


```xml
<context sentiment="pos">才剛買的書，竟然掉頁了，</context>這品質<rhetoric>也太</rhetoric><ironic sentiment="neg">好</ ironic>了<rhetoric>吧</rhetoric>
```

Tag description:


\<cmessage\> represents a single ironic message posted in Plurk.  
\<cironic\> represents the ironic word or phrase in each ironic message. The sentiment attribute indicates whether the word or phrase is positive or negative.  
\<ccontext\> represents contextual information. The sentiment attribute indicates whether it is positive or negative.  
\<crhetoric\> represents rhetorical elements.  

# Download
Please go to [resources page](http://nlg.csie.ntu.edu.tw/nlpresource/irony_corpus/) to access resources.

# How to Cite the Corpus
Please cite the following paper when referring to the NTU Irony Corpus in academic publications and papers.

Yi-jie Tang and Hsin-Hsi Chen (2014). “Chinese Irony Corpus Construction and Ironic Structure Analysis.” Proceedings of the 25th International Conference on Computational Linguistics (COLING 2014), 23-29 August 2014, Dublin, Ireland.
