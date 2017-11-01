# PyData Warsaw 2017

PyData conferences are organized by NumFocus, a nonprofit supporting open source scientific computing (they support Numpy, Pandas, scikit-learn and Jupyter among other things).

Warsaw conference took place in Copernicus Science Centre. The conference spanned 3 days - one workshop + two conference days. I didn't attend workshops. Some of them seemed pretty basic, and others were not announced until the last week.

### Interpretability

One big topic of the conference was interpretability of machine learning models. The second keynote, [Towards Interpretable and Accountable Models](https://pydata.org/warsaw2017/schedule/presentation/58/) covered both technical and social aspect of the topic. It was the first talk that mentioned LIME and eli5 libraries. Interesting takeaway was that these libraries, in addition to their intended purpose, can help with debugging and with choosing models.

Radim Řehůřek's keynote, [Winning together: Bridging the gap between academia and industry](https://pydata.org/warsaw2017/schedule/presentation/63/) was, among other things, also mentioning the difference of interpretability standards in industrial and scientific setting. This talk also announced another library, [bounter](https://github.com/RaRe-Technologies/bounter) that NLP/text mining people should find useful: bounter (portmanteau of bounded counter) is a datastructure that has similar functionality to counter, albeit the answers it gives are approximate (it uses functionalities of probabilistic data structures such as HyperLogLog and Count-min Sketch).

* Debugging machine learning
* Visualizing neural nets
* Exploring Word2Vec

* Deep learning
    * Neural translation
    * Siamese RNN
    * Hand gesture recognition
    * Deep generative models
    * PyTorch

* Boosting