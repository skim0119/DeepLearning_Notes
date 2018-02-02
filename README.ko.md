# 딥러닝 연습장

딥러닝과 여러 뉴럴네트워크 구현을 Ipython 주피터 노트북과 파이썬을 이용해 연습한 내용입니다. 내용은 대부분 영어로 작성되었습니다.

* Read this in other language: [English](README.md)

## 실행환경
- Python3.6
    - requirement.txt 안에 모든 파이썬 패키지가 들어있습니다. 
    - ``` $ pip install -r requirement.txt ``` 커맨드를 이용해 설치할수 있습니다. 
    - 주로 케라스(Keras)와 텐서플로(TensorFlow)를 이용해 작성했습니다. 
    - 텐서플로를 GPU(그래픽카드)와 함깨 사용하려면 requirement.txt 안에 tensorflow 패키지를 tensorflow-gpu 로 바꾸면 됩니다. 


## 목차
1. 회귀
    1. 간단한 선형 회귀
    2. 최소제곱법
    3. Single Hidden-layer Network Regression Practice
        - 활성화함수
2. 이미지 분류 w/ __Keras__
    1. Basic Classifier Practice
    - _(Note) Softmax_
    2. MNIST Classifier - Single Dense Layer
        1. Single Dense Layer w/ Visualization
    3. MNIST Classifier- Single Hidden Layer
    4. Mult-layered Neural Network
    5. Convolution Filter
        1. Pooling Layer
        2. MNIST Classifier - Convolution Network
        3. CIFAR10 Classifier - Convolution Network
        4. fashion_MINST - Convolution Network
    6. _RNN_
    
* 기울림 글씨는 아직 미완성된 노트라는 의미입니다.

## 참조
Some data was brought from https://github.com/Jpub/TensorflowDeeplearning jupyter_tfbook
