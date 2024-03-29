# English to French NMT 
This project is about Neural Machine Translation which is an approach to machine translation that uses an artificial neural network to predict the likelihood of a sequence of words, typically modeling entire sentences in a single integrated model.<br><br>
This project is implemented using Seq2Seq model with the use of attention mechansim.<br><br>
Attention is a technique that is meant to mimic cognitive attention. This effect enhances some parts of the input data while diminishing other parts , which is further explained in this paper by <b>Dzmitry Bahdanau, Kyunghyun Cho, Yoshua Bengio</b> [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473).<br><br>
The Dataset used in this project [English-French Translation Dataset](https://www.kaggle.com/datasets/dhruvildave/en-fr-translation-dataset).<br>
<h2>Abstract</h2>
Neural machine translation is a recently proposed approach to machine translation.
Unlike the traditional statistical machine translation,
the neural machine translation aims at building a single neural network that can be jointly tuned to maximize
the translation performance. The models proposed recently for
neural machine translation often belong to a family of encoder-decoders and consists
of an encoder that encodes a source sentence into a fixed-length vector from
which a decoder generates a translation. In this paper,
we conjecture that the use of a fixed-length vector is a bottleneck in improving the performance of this
basic encoder-decoder architecture,
and propose to extend this by allowing a model to automatically (soft-)search for parts of a source sentence
that are relevant to predicting a target word, without having to form these parts as a hard segment
explicitly.
With this new approach, we achieve a translation performance comparable to the existing state-of-the-art phrase-based system on the task of English-to-French translation. Furthermore,
qualitative analysis reveals that the (soft-)alignments found by the model agree well with our intuition.<br><br>
<img decoding="async" src="https://github.com/Asem-Saber/English-to-French-NMT/blob/main/Attention%20mechanism.png" alt="" />
<h2>Results</h2> 
<img decoding="async" src="https://github.com/Asem-Saber/English-to-French-NMT/blob/main/Model%20Results.png" alt="" />
