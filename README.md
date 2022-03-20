# TextMiningMovieReview 
## 목차
  - [개요](#개요) 
  - [일정및팀원](#일정및팀원) 
  - [기능리스트](#기능리스트)
  - [주요화면](#주요화면)
  - [기술스택및환경](#기술스택및환경)
  - [레퍼런스](#레퍼런스)


## 개요

**프로젝트 목적 및 용도는 다음과 같다.**
- 공공API를 이용한 데이터 수집 및 크롤링 진행
- 수집된 데이터 가공 (전처리 및 군집화)
- 데이터 분석 진행 [ 아래에 자세히 설명 ]
- 가공된 자료를 이용하여 UI 제공

**데이터 분석의 과정은 다음과 같다.**
- 네이버 리뷰 크롤링 및 해당 크롤링 자료를 이용해 평점 회귀분석 및 대시보드
- 네이버 리뷰 크롤링 바탕 장르별 감성분석 [장르중 모험장르 분석]
- 모험장르의 흥행 최상위 영화 , 흥행 최하위 영화의 감성 비교  
  

**산출물 (발표자료, 최종보고서)**
- [자세히](https://github.com/tekies09/TextMiningMovieReview/tree/master/outputs)

## 일정및팀원
**📆 프로젝트 기간**
- 2019년 09월 01일 - 2019년 12월 1일 (3개월)


**프로젝트 역할 및 직책**

|직책|이름|역할|
|------|---|---|
|팀장|노문택| 데이터 수집 및 전처리 군집화 , 회귀 및 감성 분석 |
|조원|천회정| 시장 조사 및 아이디어 구성 , UI 구성  |

## 기능리스트

**메인기능**
- 분석된 자료를 시각화 된 차트를 보며 확인이 가능하다.
- 코멘트를 입력하면 해당 코멘트의 긍정 부정 감정을 분석해준다.

**서브기능**
- 네이버 영화 사이트에 자료를 크롤링하여 추출
- 공공API로부터 데이터 추출
- 추출된 데이터 전처리 및 군집화
- 단순회귀분석 및 형태소 분석등 머신러닝을 이용해 감성분석 제공

## 주요화면
![캡처](https://github.com/tekies09/TextMiningMovieReview/blob/master/img/Main.PNG)

## 기술스택및환경

**기술스택**
  
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  
  
**개발환경**

|환경|버전|설명|
|------|---|---|
| Python | 3.6.0 | 분석 및 크롤링 과정 진행 |
| JupyterNotebook | Anaconda3 | 파이썬 툴 |

## 레퍼런스
**레퍼런스**
- 한국어 정보 처리 : https://konlpy-ko.readthedocs.io/ko/v0.4.3/
- 네이버 리뷰 분석 : https://cyc1am3n.github.io/2018/11/10/classifying_korean_movie_review.html
- 영화 박스 오피스 : https://www.kofic.or.kr/
- 리뷰 및 영화 자료 출처 : https://movie.naver.com/
