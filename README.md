<img src='imgs/course.png' />

# [AI 이노베이션 스퀘어 기본과정 저녁반](https://realblack0.github.io/ai_lecture_fundamental/)

<div align="center">
  <h2 style='font-weight: bold; font-size:18px;'>주관</h2>
  <a href='https://www.msit.go.kr/web/main/main.do'>
    <img src='imgs/logo_MSICT.png'/>
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href='https://ai.koipa.or.kr/'>
    <img src='imgs/logo_IPA.png' width="200" hegiht="50" />
  </a>
</div>
<br/>


## 다운로드
아래의 이미지처럼 `Clone or download` -> `Download ZIP` 버튼을 누르셔서 자료를 받으실 수 있습니다.<br/>
<div align="center">
  <img src='imgs/howtodownload.png' /><br/>
</div>

혹은 다음과 같이 `git clone` 커맨드로 받으실 수 있습니다.
```dos
git clone https://github.com/realblack0/ai_lecture_fundamental.git
```

## 필기자료 키워드 목차
### [20200303 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200303%20기본저녁반%20필기자료.ipynb)
    - numpy
    - Fancy Indexing, Broadcasting, Universal Function, Factory Method, tensorflow의 MNIST 데이터셋 열어보기
    - shape, ndim, size, dtype, itemsize, arange, zeros, ones, full, _like, empty, linsapce, matrix, flat, copy, view, linalg, split, vsplit, hsplit, reshape, resize, stack, vstack, hstack, concatenate, dstack, r_, c_, s_, ix_, newaxis

### [20200304 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200304%20기본저녁반%20필기자료(numpy).ipynb)
    - numpy
    - fashion mnist 데이터셋 열어보기, IMDB 데이터 열어보기
    - nditer, finished, iternext, flatten, ravel

### [20200304 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200304%20%EA%B8%B0%EB%B3%B8%EC%A0%80%EB%85%81%EB%B0%98%20%ED%95%84%EA%B8%B0%EC%9E%90%EB%A3%8C(numpy%2C%20pandas%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%88%EB%9F%AC%EC%98%A4%EA%B8%B0).ipynb)
    - numpy, pickle, pandas
    - Serialize
    - loadtxt, genfromtxt, read_csv

### [20200304 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200304%20%EA%B8%B0%EB%B3%B8%EC%A0%80%EB%85%81%EB%B0%98%20%ED%95%84%EA%B8%B0%EC%9E%90%EB%A3%8C(pandas).ipynb)
    - pandas 
    - structured array, fancy indexing, tips 데이터 분석
    - info, head, tail, sample, describe, skew, kurt

### [20200305 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200305%20%EA%B8%B0%EB%B3%B8%EC%A0%80%EB%85%81%EB%B0%98%20%ED%95%84%EA%B8%B0%EC%9E%90%EB%A3%8C.ipynb)
    - pandas, pandas-profiling
    - 값 뽑기, 인덱스 조작, 멀티인덱스, Data Type, EDA
    - rename, loc, iloc, at, iat, set_index, reset_index, astype, corr, drop, duplecated, drop_duplicates

### [20200306 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200306%20%EA%B8%B0%EB%B3%B8%EC%A0%80%EB%85%81%EB%B0%98%20%ED%95%84%EA%B8%B0%EC%9E%90%EB%A3%8C.ipynb)
    - pandas
    - boolean indexing, predicate, str 메소드
    - isin, where, mask, query, startswith, endswith, in, split, strip, replace, concatenate, join, groupby, stack, unstack

### [20200309 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200309%20%EA%B8%B0%EB%B3%B8%EC%A0%80%EB%85%81%EB%B0%98%20%ED%95%84%EA%B8%B0%EC%9E%90%EB%A3%8C.ipynb)
    - pandas, fbprophet
    - aggregation, map 시리즈, Time Series(시계열 분석)
    - groupby, pivot_table, crosstab, map, apply, applymap, calender, time, datetime, to_datetime, resample, date_range, Period

### [20200310 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200310%20%EA%B8%B0%EB%B3%B8%EC%A0%80%EB%85%81%EB%B0%98%20%ED%95%84%EA%B8%B0%EC%9E%90%EB%A3%8C.ipynb)
    - pandas
    - Tidy Data, 추천시스템
    - concat, join, merge, append, melt, wide_to_long

### [20200311 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200311%20%EA%B8%B0%EB%B3%B8%EC%A0%80%EB%85%81%EB%B0%98%20%ED%95%84%EA%B8%B0%EC%9E%90%EB%A3%8C.ipynb)
    - pandas, folium
    - 추천시스템, 가짜 코로나19 지도

### [20200312 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200312%20%EA%B8%B0%EB%B3%B8%EC%A0%80%EB%85%81%EB%B0%98%20%ED%95%84%EA%B8%B0%EC%9E%90%EB%A3%8C.ipynb)
    - matplotlib, pdvega, folium
    - State Machine 방식, OOP 방식, style 변경, interactive 그래프, 한글 폰트 설정, GeoJson, TopoJson, Choropleth(단계구분도)

### [20200313 필기자료](https://github.com/realblack0/ai_lecture_fundamental/blob/master/notebooks/20200313%20%EA%B8%B0%EB%B3%B8%EC%A0%80%EB%85%81%EB%B0%98%20%ED%95%84%EA%B8%B0%EC%9E%90%EB%A3%8C.ipynb)
    - scikit-learn, folium
    - KNN, MLP, Choropleth(단계구분도)

## 문의사항
- issues page: https://github.com/realblack0/ai_lecture_fundamental/issues
- e-mail: realblack0@gmail.com
- AI 이노베이션 스퀘어: https://ai.koipa.or.kr/
- LMS 홈페이지: https://lms.koipa.or.kr/
