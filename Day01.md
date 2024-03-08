# 1일차 학습
- 빅데이터 학습

## 빅데이터 학습

### 빅데이터 개요
- 정의
    - 디지털 환경에서 발생하는 대규모의 데이터
    - 대량의 데이터를 수집, 저장, 관리, 분석하는 하드웨어(HW)/소프트웨어(SW), 유통, 활용까지 포함
- [특징](https://velog.io/@garam/DE-%EB%B9%85%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%9D%98-%ED%8A%B9%EC%A7%953V-5V-7V)
- 기술
    - 순서적으로 데이터 생성 -> 수집 -> 저장 -> 분석(EAD, 머신러닝, 딥러닝) -> 표현(시각화)
    - 생성: IoT, 빅데이터 플랫폼
    - 수집: 빅데이터 플랫폼(하둡, Kafka 등, 데이터 마이닝)
    - 저장: 빅데이터 플랫폼(Kafka 등, 데이터 마이닝, NoSQL)
    - 분석: 통계, 머신러닝, 딥러닝, 자연어 처리, 패턴 인식, 이미지 프로세싱(Power BI, Tableau 등)   *BI: Business Intelligence
    - 표현: Visualization(Power BI, Tableau 등)

### 학습 교재
직장인을 위한 데이터 분석 실무 파이썬, 위키북스

- [실습 자료](https://github.com/Play-with-data/datasalon)(<> Code -> Download Zip)

### 파이썬 리뷰
이전에 [파이썬 기초 학습](https://github.com/hyanyul/python-2024) 종료

### 데이터 분석 기초
데이터 분석을 위한 리이브러리(모듈) 학습부터 시작
- Pandas: 데이터 처리 라이브러리
- Numpy: 수치 해석, 계산용 라이브러리
- Openpyxl: Excel, CSV, JSON 문서 데이터 로드 및 저장 라이브러리
- Selenium:  웹 크롤링 자동화 라이브러리
- BeautifulSoup: 웹 데이터 정제 라이브러리
- Mapplot.lib: 차트 표현용 라이브러리
- Seaborn: 시각화 라이브러리
- Folium: 지도 시각화 라이브러리
- TensorFlow: 머신러닝 라이브러리
- PyTorch: 머신러닝, 딥러닝 라이브러리
- 그 외 다양한 라이브러리 있음

추가 내용: [Kaggle.com](https://www.kaggle.com/)

#### Pandas 학습
데이터 분석(로딩, 처리 등) 라이브러리

1. Pandas 자료구조 
    
    ![Pandas 자료구조](https://github.com/hyanyul/python-analysis-2024/blob/main/images/pa01.png?raw=true)
    
    - 데이터프레임, 시리즈 
    - 데이터프레임 사용법
    - 데이터 통합

2. Intellisense로 느려짐
    - Ctrl + ,(설정) > TypeScript, Editor > Suggest 모두 해제
    - 필요한 것만 체크해서 사용