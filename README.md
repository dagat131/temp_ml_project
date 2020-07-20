# 1. 데이콘 머신러닝 경진대회 소개 및 개요
- 주 제 : AI 알고리즘 활용 카드 사용 금액 예측

- 목 표 : 신용카드 사용 내역 데이터를 활용한 지역별, 업종별 월간 카드 사용 총액 예측

    - 신용카드 사용량을 분석을 통한  ‘Post COVID-19 시대’ 신용카드 사용량 예측 모델 개발

 - 주 최 : 제주특별자치도청, 제주테크노파크

 - 주 관 : DACON

- 웹사이트 : [제주 신용카드 빅데이터 경진대회](https://dacon.io/competitions/official/235615/overview/)

# 2. 데이터 구성
## (1) 데이터셋 개요
※ 카드이용지역, 업종, 거주지역 등 준식별자로 구성된 카드 사용 내역 (출처: BC카드)

- 해결해야 하는 문제
 - 2020.04, 2020.07 기간 내 지역, 업종 별 월간 총 사용 금액 예측

- 훈련데이터 : 201901-202003.csv (2.07 GB)
    + 2019.01 ~ 2020.03 기간 내 카드 데이터

- 테스트 데이터 : 202004.csv (116 MB)
    + 2020.04 기간 내 카드 데이터 (7/28 공개)

- 제출양식 : submission.csv (64 KB)

## (2) 데이터 정의서
- REG_YYMM : 년월
- CARD_SIDO_NM
- CARD_CCG_NM
- STD_CLSS_NM
- HOM_SIDO_NM
- HOM_CCG_NM
- AGE
- SEX_CTGO_CD
- FLC
- CSTMR_CNT
- AMT
- CNT

## (3) 참고
- 모든데이터는 [구글 클라우드 빅쿼리](https://cloud.google.com/bigquery/what-is-bigquery?hl=ko)는 적재하였고, 아래와 같이 불러와서 머신러닝 프로젝트 수행

```python

```