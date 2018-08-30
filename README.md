# Webtoon_recommand_system (웹툰 분석 & 추천시스템)

#### Project maker : Bright Kim(김민우), Juno Kim(김준호)
--- 
# *introduce.*
- 소개 : 웹툰의 데이터를 활용한 사용자 웹툰 추천 시스템을 구현하는 프로젝트입니다.

- : 댓글 텍스트 분석을 통한 감정분석
  - 각 회차별 텍스트 분석을 통한 관계 
  - 신경망을 통한 웹툰 썸네일 - 사용자 호감도 및 반응 분석
  - 유사도 관계도 분석

---
# *Project Time line.*

### ◆ 2018-09-03(Mon)
> #### 주제 : 웹툰 관련 데이터 EDA 및 Data Featuring
>  (장소 : 스타벅스 학동역점)
>  - 크롤링 Data Merging
>  - EDA (그래프 및 피쳐의 영향도 분석)
>  - Feature Engineering
>  - 기초모델(LightGBM gbdt) 적용 및 importance 분석

### ◆ 2018-08-30(Thr)
> #### 주제 : 웹툰 관련 데이터 수집(크롤링 코드 연구)
>  (장소 : 스타벅스 논현역점)
>  - N사 웹툰 : bs4를 활용한 코드 작성 --> 웹툰정보, 웹툰회차 일부 코드 작성
>  - D사 웹툰 : request 및 json API활용 --> 웹툰정보, 웹툰회차정보 완료
>  - 데이터 간략 분석 및 모델회의(수집된 데이터 기준) 
>  - 다음 모임까지 각자 할것
>    - N사,D사 웹툰 회차별 댓글, 작가, 유저(id값으로 변경)
>    - 수집 데이터를 활용한 EDA 및 ipnyb 자료화
>    - 적합한 모델 탐색 및 추천시스템 연구

### ◆ 2018-08-28(Tue)
> #### 주제 : Data 확보 및 Data Storing 방식 설계
>  (장소 : 건대역 2번출구 엔젤리너스)
>  - 웹툰 제공 서비스 분석 및 데이터 수집 계획 수립
>  - DB 트리 및 스키마 계획(Draw ER Diagram)
>  - 크롤링 계획 수립
>  - Github Repository 생성
>  - 평일 중 : 크롤링 scrapy pipeline 구성 연구
>  - 다음 모임까지 각자 할것 :
>    - scrapy pipeline 연구
>    - Crawling File system 구성 및 테스트
>    - DATA EDA 개별 진행
>    - Recommend system 사전정보 수집
>    - Data alalysis fit model 정보 찾기 

### ◆ 2018-08-24(Fri)
> #### 주제 : 웹툰 분석 추천시스템 Project 결성
>  (장소: 성수역 패스트캠퍼스 C관)
>  - 프로젝트 팀 결성
>  - 프로젝트 주제 선정(웹툰 추천시스템)
>  - 프로젝트 데이터 간략 분석(N***, D**)
>  - 프로젝트 방향성 논의
>    - 데이터 수집(Crawling) --> 데이터 정형화 --> 모델링( & GradientBoost & NeuralNet) --> 추천서비스 --> 시범서비스화
