# NLP paper implementation with PyTorch
The papers were implemented in using korean corpus 

### Classification
+ Using the [Naver sentiment movie corpus v1.0](https://github.com/e9t/nsmc)
+ Hyper-parameter search was not done. Instead, hyper-parameter was arbitrarily selected.

|                  | Train ACC (120,000) | Validation ACC (30,000) | Test ACC (50,000) |
| :--------------- | :-------: | :------------: | :------: |
| SenCNN           |  92.22%  |     86.81%     |  86.48%  |
| CharCNN          | 90.26% | 82.22% | 81.97% |
| ConvRec          | 89.34% | 81.98% | 81.94% |
| VDCNN            | 87.20% | 84.60% | 84.50% |
| SAN | 86.22% | 84.13% | 84.02% |

* [x] [Convolutional Neural Networks for Sentence Classification](https://github.com/aisolab/nlp_implementation/tree/master/Convolutional_Neural_Networks_for_Sentence_Classification) (SenCNN)
  + https://arxiv.org/abs/1408.5882
* [x] [Character-level Convolutional Networks for Text Classification](https://github.com/aisolab/nlp_implementation/tree/master/Character-level_Convolutional_Networks_for_Text_Classification) (CharCNN)
  + https://arxiv.org/abs/1509.01626
* [x] [Efficient Character-level Document Classification by Combining Convolution and Recurrent Layers](https://github.com/aisolab/nlp_implementation/tree/master/Efficient_Character-level_Document_Classification_by_Combining_Convolution_and_Recurrent_Layers) (as ConvRec)
  + https://arxiv.org/abs/1602.00367
* [x] [Very Deep Convolutional Networks for Text Classification](https://github.com/aisolab/nlp_implementation/tree/master/Very_Deep_Convolutional_Networks_for_Text_Classification) (as VDCNN)
  + https://arxiv.org/abs/1606.01781
* [x] [A Structured Self-attentive Sentence Embedding](https://github.com/aisolab/nlp_implementation/tree/master/A_Structured_Self-attentive_Sentence_Embedding) (as SAN)
  + https://arxiv.org/abs/1703.03130

### Language model
* [ ] Character-Aware Neural Language Models
  + https://arxiv.org/abs/1508.06615

### Named entity recognition
* [ ] Bidirectional LSTM-CRF Models for Sequence Tagging
	+ https://arxiv.org/abs/1508.01991
* [ ] End-to-end Sequence Labeling via Bi-directional LSTM-CNNs-CRF
	+ https://arxiv.org/abs/1603.01354
* [ ] Neural Architectures for Named Entity Recognition
	+ https://arxiv.org/abs/1603.01360


### Neural machine translation
* [ ] Effective Approaches to Attention-based Neural Machine Translation
	+ https://arxiv.org/abs/1508.04025
* [ ] Attention Is All You Need
	+ https://arxiv.org/abs/1706.03762

### Machine reading comprension
* [ ] Bi-directional attention flow for machine comprehension
	+  https://arxiv.org/abs/1611.01603
