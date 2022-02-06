---
emoji: 📝
title: 혼공머신 7-1. 인공 신경망 정리
date: '2022-01-19 00:42:00'
author: Sujin
tags: 혼공머신 머신러닝 딥러닝 인공신경망 MNIST
categories: 노트
---

### MNIST

- 딥러닝 처음 배울 때 많이 사용하는 데이터셋
- 손으로 쓴 0~9까지의 숫자로 이루어져 있음

### 패션 MNIST

- 10종류의 패션 아이템으로 구성되어있는 데이터셋
- MNIST와 크기와 개수가 동일하지만 숫자 대신 패션 아이템으로 이루어진 데이터

```python
# 패션 MNIST 데이터 다운로드
from tensorflow import keras
(train_input, train_target), (test_input, test_target) = \
    keras.datasets.fashion_mnist.load_data()
```