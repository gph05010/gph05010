## Profile

Python과 SQL을 활용해 데이터를 수집·정리하고, 프로젝트 목적에 맞게 분석 가능한 형태로 가공하는 경험을 쌓고 있습니다.

채용공고 데이터 분석 프로젝트, 공공데이터 기반 의약품 설명서 문장 분류 프로젝트, STT 기반 말하기형 인지검사 발화 분석 프로젝트를 진행하며 데이터 전처리, 라벨 기준 정리, 모델 결과 비교, 발화 분석 로직 구현, DB 구조 설계 및 산출물 문서화 과정을 경험했습니다.

아직 특정 직무나 분야를 하나로 단정하기보다는, 데이터를 바탕으로 문제를 정리하고 결과를 설명 가능한 형태로 만드는 일에 관심을 두고 있습니다.

---

## 관심 있는 작업

* Python과 SQL을 활용한 데이터 전처리 및 분석
* 채용공고, 서비스 데이터 등 실제 데이터를 활용한 요구사항·패턴 분석
* 텍스트 데이터 정리, 분류 기준 설정, 모델 결과 비교
* STT 기반 발화 텍스트 분석 및 LLM 평가 결과 검토
* 분석 결과와 프로젝트 산출물을 문서로 정리하는 작업

---

## 사용 경험

### Language

* Python
* SQL
* Java

### Data / Analysis

* pandas
* scikit-learn
* TF-IDF
* KLUE-RoBERTa
* Jupyter Notebook
* Google Colab

### Backend / DB

* Oracle DB
* Spring Boot
* REST API

### Tools

* Git
* GitHub

---

## 주요 프로젝트

### TrendBridge - GitHub 기반 개인 기술 스택 분석 및 채용공고 매칭 서비스

취업 준비생이 자신의 보유 기술과 채용공고에서 요구하는 기술을 비교하고, 부족한 기술스택과 관련 공고를 확인할 수 있도록 구성한 팀 프로젝트입니다.

* 채용공고 데이터 2,412건 중 분석에 활용 가능한 884건을 선별하고 전처리
* 약 200개의 기술스택 키워드를 검토해 표기 차이, 동의어, 카테고리 분류 기준 정리
* 기술스택별 등장 빈도와 월별 언급 변화 분석을 통해 트렌드 시각화에 활용할 데이터 정리
* 사용자 보유 기술과 공고 요구 기술을 비교하는 매칭 분석 및 부족 기술스택 산출 기준 정리
* 공고 조회, 즐겨찾기 기능 구현 과정 참여
  
* [TrendBridge Team Repository](https://github.com/hap728/KDT-4team-Project)
  전체 서비스 코드 및 프로젝트 소개가 있는 팀 레포지토리입니다.
* [TrendBridge Data Analysis](https://github.com/gph05010/TrendBridge-Data-Analysis)
  팀 프로젝트 중 제가 담당한 채용공고 데이터 분석 작업을 별도로 정리한 개인 작업 기록 저장소입니다.

---

### 의약품 설명서 문장 분류 기반 복약정보 탐색 프로젝트

공공데이터 기반 의약품 설명서 텍스트를 활용해 복약정보 유형을 분류하는 프로젝트입니다.

* 의약품개요정보 Open API를 활용한 의약품 설명서 텍스트 데이터 수집 및 정리
* 효능, 복용법, 주의사항, 상호작용, 부작용, 보관법 등 복약정보 유형 기준으로 문장 단위 데이터셋 구성
* Python과 pandas를 활용한 결측치 처리, 컬럼 통합, 텍스트 정제, 중복 제거 등 전처리 수행
* TF-IDF 기반 베이스라인 모델과 KLUE-RoBERTa 기반 분류 모델의 성능 비교
* Accuracy, Macro F1, 혼동행렬을 활용한 모델 성능 및 오분류 사례 분석

* [관련 레포지토리](https://github.com/gph05010/Medication-Info-Text-Classification)

---

### 말하기형 인지검사 발화 분석 및 LLM 평가 프로젝트

STT 기반 발화 텍스트를 활용해 인지검사 응답을 분석하고, 평가 로직과 데이터 구조를 정리한 프로젝트입니다.

* 제시된 발화 분석 지표를 바탕으로 반응시간, 반복어 비율, 평균 문장 길이, 화행 적절성의 산출 방식과 평가 적용 방식 정리
* Python을 활용한 반복어 비율, 평균 문장 길이 등 주요 발화 분석 로직 구현
* LLM 기반 화행 적절성 평가 프롬프트 설계 및 응답 사례별 채점 결과 테스트
* 수행기록, 문항별답변결과, 발화분석결과, 리포트 등 DB 구조 설계
* 요구사항정의서, 테이블명세서, ERD, 빅데이터분석정의서 등 프로젝트 산출물 작성

- Team Repository: [팀 레포지토리](https://github.com/2026-SMHRD-KDT-LangIntelligence-8/GitFinalProjectJH/tree/main)
- Analysis Folder: [데이터 분석](https://github.com/2026-SMHRD-KDT-LangIntelligence-8/GitFinalProjectJH/tree/main/analysis)
