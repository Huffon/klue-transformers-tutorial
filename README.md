# KLUE + Transformers 튜토리얼 🤗

본 저장소는 [Transformers](https://github.com/huggingface/transformers), [Sentence Transformers](https://github.com/UKPLab/sentence-transformers) 등의 라이브러리를 활용해 태스크를 수행하기 위한 자연어 처리 모델을 손쉽게 훈련할 수 있는 방법에 대한 예제 노트북들을 다룹니다.

예제 제작을 위한 학습 데이터는 [KLUE](https://klue-benchmark.com/) 벤치마크 내 데이터를 활용하도록 합니다.

각 라이브러리가 빠른 기술의 발전으로 차후 활용법이 변할 수 있으므로, 라이브러리의 버전을 아래와 같이 고정시킨 채 실험 및 학습을 해주시는 것이 좋습니다.

본 저장소 내 노트북 제작을 위해 학습된 모델들은 모두 [허깅페이스 모델 허브](https://huggingface.co/Huffon)에 업로드해두었으니 사용하실 수 있습니다.

<br>

```
transformers==4.7.0
datasets==1.8.0
sentence-transformers==1.2.0
```

<br>

## 학습 컨텐츠

| Notebook     |      Description      |   |
|:----------|:-------------|------:|
| [문장 분류 모델 학습](https://github.com/Huffon/klue-transformers-tutorial/blob/master/natural_language_inference.ipynb) | **KLUE-NLI** 데이터를 활용하여 문장 분류 모델을 훈련하는 방법을 학습합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Huffon/klue-transformers-tutorial/blob/master/natural_language_inference.ipynb) |
| 토큰 분류 모델 학습 | **KLUE-NER** 데이터를 활용하여 토큰 분류 모델을 훈련하는 방법을 학습합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Huffon/klue-transformers-tutorial/blob/master/named_entity_recognition.ipynb) |
| 스팬 예측 모델 학습 | **KLUE-MRC** 데이터를 활용하여  스팬 예측 모델을 훈련하는 방법을 학습합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Huffon/klue-transformers-tutorial/blob/master/machine_reading_comprehension.ipynb) |
| [Sentence-BERT 모델 학습 및 활용](https://github.com/Huffon/klue-transformers-tutorial/blob/master/sentence_transformers.ipynb) | **KLUE-STS** 데이터를 활용하여 문장 임베딩이 가능한 [`Sentence-BERT`](https://arxiv.org/abs/1908.10084) 방식의 모델을 훈련하고, 활용하는 방법을 학습합니다. |[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Huffon/klue-transformers-tutorial/blob/master/sentence_transformers.ipynb) |
| [TIP: `zero-shot` 파이프라인 활용](https://github.com/Huffon/klue-transformers-tutorial/blob/master/zero_shot_classification.ipynb) | Transformers 라이브러리의 `zero-shot` 파이프라인을 활용해 *Zero-shot* 문장 분류를 수행하는 예제를 학습합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Huffon/klue-transformers-tutorial/blob/master/zero_shot_classification.ipynb) |

<br>

## 문의

```
허 훈 (huffonism@gmail.com)
```

