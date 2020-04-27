# TARGER-Wrapper
This is a python wrapper of TARGER API

Original URL http://ltdemos.informatik.uni-hamburg.de/targer/

Original Paper https://www.aclweb.org/anthology/P19-3031v2.pdf

## Usage
Possible model [ibm_fasttext, pe_dep, pe_fasttext, pe_glove, wd_dep, wd_fasttext, wd_glove]

<pre><code>
tagger = Targer(model='pe_fasttext')

text = "Quebecan independence is justified. In the special episode in Japan, his system is restored by a doctor who wishes to use his independence for her selfish reasons."

tokens, labels, probs = tagger.classify(text)
</code></pre>
