# 2025_ML

[수업전체](https://github.com/dknife/dknife.github.io/wiki/Lecture_Homepage)

## 과제 1

- 경사하강법을 이용하여 강의 8의 마지막 실습으로 다룬 XOR 퍼셉트론을 학습시키는 방법을 구현해 보라.
- w = w - l * dE/dW
  
## 2025 1학기 머신러닝 기초 실습 홈페이지

강의 교재: 으뜸 머신러닝, 생능출판사

### "으뜸 머신러닝" 저장소 소개

https://github.com/dknife/ML

이 책 "으뜸 머신러닝"은 머신러닝을 처음 배우는 입문자와 머신 러닝의 개념을 익힌 상태에서 텐서플로우를 이용한 본격적 개발을 시작하려는 분들을 위한 책입니다.

#### 책의 소스코드(colab 주소, .py 파일, ipynb 파일)
* [소스코드](https://github.com/dknife/ML/tree/main/Source/README.md)
: "으뜸 머신러닝" 책의 장별 소스코드가 .ipynb, colab 페이지를 통해서 제공됩니다

##### 함께 보면 좋은 책

이 책을 읽기 위해 파이썬과 데이터 다루기와 관련된 저자들의 이전 책을 함께 보면 좋습니다. 

* 으뜸 파이썬, 박동규, 강영민, 생능출판사 (2020) - 세종도서 학술부문 선정

* (따라하며 배우는) 파이썬과 데이터 과학, 천인국, 박동규, 강영민, 생능출판사 (2020)

* 으뜸 데이터 분석과 머신러닝, 박동규, 강영민, 생능출판사 (2021)

### 강의 노트

#### [강의 1 - 머신러닝이란](https://github.com/dknife/2025_ML/raw/main/Lec/01%EC%9E%A5_%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%EC%9D%B4%EB%9E%80.pdf)

[강의노트]((https://github.com/dknife/2025_ML/raw/main/Lec/01%EC%9E%A5_%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%EC%9D%B4%EB%9E%80.pdf))

##### [구현을 위한 기초지식](https://github.com/dknife/2025_ML/raw/main/Lec/03%EC%9E%A5_%EA%B5%AC%ED%98%84%EC%9D%84%EC%9C%84%ED%95%9C%20%EB%8F%84%EA%B5%AC.pdf)

[강의노트](https://github.com/dknife/2025_ML/raw/main/Lec/03%EC%9E%A5_%EA%B5%AC%ED%98%84%EC%9D%84%EC%9C%84%ED%95%9C%20%EB%8F%84%EA%B5%AC.pdf)

* 교재 3장의 내용을 먼저 살펴 보자
* [구글 코랩 연습](https://colab.research.google.com/drive/1I_4N0oOMNUjWa9pL48iCX5ypcgBy1xGm#scrollTo=aS83clRuGPss)
* [판다스 연습](https://colab.research.google.com/drive/1iRBXjqZJxPVKLBnvQVY4nSN_bQP64RDD)

#### [강의 2.1 - 머신러닝을 위한 기초지식](https://github.com/dknife/2025_ML/raw/main/Lec/02%EC%9E%A5_%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%EC%9D%84%20%EC%9C%84%ED%95%9C%20%EA%B8%B0%EC%B4%88%EC%A7%80%EC%8B%9D.pdf)

[강의노트](https://github.com/dknife/2025_ML/raw/main/Lec/02%EC%9E%A5_%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%EC%9D%84%20%EC%9C%84%ED%95%9C%20%EA%B8%B0%EC%B4%88%EC%A7%80%EC%8B%9D.pdf)

#### [강의 2.2 - 구현을 위한 도구](https://github.com/dknife/2025_ML/raw/main/Lec/03%EC%9E%A5_%EA%B5%AC%ED%98%84%EC%9D%84%EC%9C%84%ED%95%9C%20%EB%8F%84%EA%B5%AC.pdf)

[강의노트](https://github.com/dknife/2025_ML/raw/main/Lec/03%EC%9E%A5_%EA%B5%AC%ED%98%84%EC%9D%84%EC%9C%84%ED%95%9C%20%EB%8F%84%EA%B5%AC.pdf)

#### [강의 3 - 선형회귀](https://github.com/dknife/2025_ML/raw/main/Lec/04%EC%9E%A5_%EC%84%A0%ED%98%95%20%ED%9A%8C%EA%B7%80%EB%A1%9C%20%EC%9D%B4%ED%95%B4%ED%95%98%EB%8A%94%20%EC%A7%80%EB%8F%84%ED%95%99%EC%8A%B5.pdf)

[강의노트](https://github.com/dknife/2025_ML/raw/main/Lec/04%EC%9E%A5_%EC%84%A0%ED%98%95%20%ED%9A%8C%EA%B7%80%EB%A1%9C%20%EC%9D%B4%ED%95%B4%ED%95%98%EB%8A%94%20%EC%A7%80%EB%8F%84%ED%95%99%EC%8A%B5.pdf)

* [실습 1 - 판다스 테스트](https://colab.research.google.com/drive/1ilskffIYavRFGhAUSThK9DOY-WHUAEQN?usp=sharing)
* [실습 2 - 데이터에 대해 가설 세워 보기](https://colab.research.google.com/drive/1eDIiD3Pc7Dh2ujP5PX9e7BUUVa_0xVz1?usp=sharing)

#### 강의 4 - 선형회귀 2
* [실습 1 오차 곡면을 따라 좋은 파라미터 찾기](https://colab.research.google.com/drive/1p8JkOnhzB8rxaRoSeyJBJwVdPKQwmzpr?usp=sharing)

* [실습 ２사이킷런을 이용한 선형회귀](https://colab.research.google.com/drive/1NQF-ZG26E7ZfEF9MCfrBcRJKmsYxMDVp?usp=sharing)

#### 강의 5 - 선형회귀 종합 실습

* [강의노트](https://github.com/dknife/2025_ML/raw/main/Lec/04%EC%9E%A5_%EC%84%A0%ED%98%95%ED%9A%8C%EA%B7%80_%EC%A2%85%ED%95%A9%EC%8B%A4%EC%8A%B5.pdf)

* [선형회귀 종합실습](https://colab.research.google.com/drive/16Tb56ZGuaw26R-B1HXFcsa6NuhhU_N0-?usp=sharing)

#### 강의 6 - 분류와 군집화를 위한 knn / k-means 기법

* [강의노트](https://github.com/dknife/2025_ML/raw/main/Lec/05%EC%9E%A5_%EB%B6%84%EB%A5%98%EC%99%80%20%EA%B5%B0%EC%A7%91%ED%99%94%EB%A1%9C%20%EC%9D%B4%ED%95%B4%ED%95%98%EB%8A%94%20%EC%A7%80%EB%8F%84%20%ED%95%99%EC%8A%B5%EA%B3%BC%20%EB%B9%84%EC%A7%80%EB%8F%84%20%ED%95%99%EC%8A%B5.pdf)

* [실습: 분류(Classification)와 군집화(clustering)](https://colab.research.google.com/drive/1KSL8dkeySBju8TDnPkQNUo30oc7I9DYV?usp=sharing)

#### 강의 7 - 다양한 머신러닝 기법들 소개

* [강의노트](https://github.com/dknife/2025_ML/raw/main/Lec/06%EC%9E%A5_%EB%8B%A4%EC%96%91%ED%95%9C%20%EB%A8%B8%EC%8B%A0%EB%9F%AC%EB%8B%9D%20%EA%B8%B0%EB%B2%95%EB%93%A4%20-%20%EB%8B%A4%ED%95%AD%20%ED%9A%8C%EA%B7%80%2C%20%EA%B2%B0%EC%A0%95%20%ED%8A%B8%EB%A6%AC%2C%20SVM.pdf)

* [실습: 다양한 머신러닝 연습](https://colab.research.google.com/drive/1HXHCs301K7Fmjoz-N4Ehfz6Nf0elC2k3?usp=sharing)

#### 중간고사 풀이

[중간고사 정답](https://colab.research.google.com/drive/1b__ZJIt-lIImWWYeFV6IFana-Xgn_xxD?usp=sharing)

#### 강의 8 - 인공신경망 기초 - 퍼셉트론과 문제점

* [강의노트](https://github.com/dknife/2025_ML/raw/main/Lec/07%EC%9E%A5_%EC%9D%B8%EA%B3%B5%20%EC%8B%A0%EA%B2%BD%EB%A7%9D%20%EA%B8%B0%EC%B4%88%20-%20Part1%20%ED%8D%BC%EC%85%89%ED%8A%B8%EB%A1%A0%EA%B3%BC%20%EB%AC%B8%EC%A0%9C.pdf)

* [실습: 퍼셉트론의 구현과 학습](https://colab.research.google.com/drive/1CakzEE77Hzg6Gcy9NIvXhwURaHqzugsu?usp=sharing)


#### 강의 9 - 인공신경망 기초 - 입력다항화를 통한 선형 분리 한계 극복과 경사하강법을 푸는 벡터/행렬 연산 모델
* [강의노트](https://github.com/dknife/2025_ML/raw/main/Lec/07%EC%9E%A5_%EC%9D%B8%EA%B3%B5%20%EC%8B%A0%EA%B2%BD%EB%A7%9D%20%EA%B8%B0%EC%B4%88%20-%20Part2%20%EB%8B%A4%EC%B8%B5%ED%8D%BC%EC%85%89%ED%8A%B8%EB%A1%A0%EC%9D%98%20%ED%95%99%EC%8A%B5.pdf)
