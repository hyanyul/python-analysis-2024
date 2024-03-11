## 2일차 학습
- 빅데이터 학습

### 빅데이터 학습

#### 데이터 분석 기초(계속)

#### Pandas 학습(계속)

2. Pandas 내용 통합(merge, concat)

    ![concat결과](https://github.com/hyanyul/python-analysis-2024/blob/main/images/pa02.png?raw=true)

3. Pivot테이블

##### Pandas 2.0 이상 문제 확인
- 두 데이터를 합치기 위한 appenbd() 함수가 제거됨
    - https://pandas.pydata.org/docs/whatsnew/v2.0.0.html

- pd.concat() 함수로 대체

#### Numpy 학습
Numpy는 행렬처리 수치 계산을 손쉽게 할 수 있도록 도와주는 계산관련 라이브러리(많이 사용하지는 않음)
Scipy는 과학쪽에 특화된 계산관련 라이브러리
- DF에서 수치적으로 처리할 게 있으면 numpy로 변경한 다음, 계산 처리한 뒤 다시 DF로 변경

#### Matplotlib / Seaborn
Matplotlib, Seaborn은 데이터 시각화 라이브러리
Matplotlib 기본, Seaborn은 Matplotlib 확장버전