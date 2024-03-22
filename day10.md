## 10일차 학습
- 빅데이터 실습
    - 통계 분석 리뷰
    - 머신러닝 실습

### 빅데이터 실습
#### 통계 분석 리뷰
    - 그래프를 사용한 기술통계분석    
    - 히트맵을 사용한 상관분석

##### 와인 품질 분석(계속)
- [캘리포니아 어바인 대학 연구소](https://archive.ics.uci.edu/dataset/186/wine+quality)
- 기존 웹사이트 데이터 다운로드 방식에서 어바인 연구소에서 데이터 다운로드 모듈 개발(python import 형식) 다운로드
- 기술통계, 기존방식의 분석 사용
- 회귀분석, 기존의 데이터만으로 선형회귀를 도출

![회귀분석시각화](https://raw.githubusercontent.com/hugoMGSung/bigdata-analysis-2024/main/images/ba012.png)

##### 타이타닉 생존자 분석
- seaborn 모듈내 샘플데이터 셋
- 생존자 상관분석 : 두 변수간에 상관관계를 유추
- 0.0 ~ 1.0 사이 상관계수 값
- 0.5 ~ 0.9 의 결과가 나오는 변수들끼리 재분석
- 결측치 검색, 제거

![상관분석히트맵](https://raw.githubusercontent.com/hugoMGSung/bigdata-analysis-2024/main/images/ba014.png)