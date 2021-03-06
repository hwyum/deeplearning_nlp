# deeplearning_nlp
deeplearning framework으로 nlp 문제 해결을 구현한 소스 모음

### 1. Gluon Tutorial : Recurrent Neural Networks (RNNs) for Language Modeling
* source: https://gluon.mxnet.io/chapter05_recurrent-neural-networks/simple-rnn.html
* low level implementation using nothing but mxnet.ndarray and mxnet.autograd
* Dataset: "The Time Machine", 어린왕자(kor)
* Notebook: [gluon_rnn_practice](https://nbviewer.jupyter.org/github/hwyum/deeplearning_nlp/blob/master/gluon_rnn_practice.ipynb), [gluon_rnn_practice_kor](https://nbviewer.jupyter.org/github/hwyum/deeplearning_nlp/blob/master/gluon_rnn_practice_kor.ipynb)
  * 한국어 실험은 잘 되지 않은데, 어린왕자의 길이가 짧아서 학습 데이터 셋이 충분하지 않은 것으로 보임

### 2. Paper : Convolutional Neural Network for Sentence Classification (2014)
* Reference: https://nbviewer.jupyter.org/github/aisolab/TF_code_examples_for_Deep_learning/blob/master/Sentence%20classification%20by%20MorphConv.ipynb (김보섭님)
* Dataset: Naver movie review
* Notebook: [colab notebook](https://nbviewer.jupyter.org/github/hwyum/deeplearning_nlp/blob/master/Implementing_a_CNN_for_Text_Classification_in_TensorFlow.ipynb)
