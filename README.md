# 심리 상담 및 정신 질환 분석 시스템

## 프로젝트 개요

### 프로젝트의 필요성과 목적

현대 사회에서 청소년들의 우울증 및 자살률이 급증함에 따라 이를 예방하고 사회적 손실을 줄이기 위한 대책이 필요합니다. 청소년들이 정신건강 문제를 스스로 점검하고, 간단한 상담을 받을 수 있는 시스템이 절실히 요구되고 있습니다. 본 프로젝트는 이러한 사회적 요구에 대응하며, 정신건강 문제를 예방 및 해결하기 위해 설계되었습니다.

### 프로젝트 목표

- **RAG (Retrieval-Augmented Generation)** 기반 시스템을 구축하여 감정을 분석하고 사용자의 정신 건강 상태를 진단합니다.
- **LLM (Large Language Model)** 을 활용하여 실시간으로 사용자 맞춤형 응답을 제공하며, 정확하고 신뢰성 있는 데이터를 제공합니다.
- 사용자의 상태를 LLM을 통해 간단한 정신질환 진단을 받을 수 있음.

## 주요 기능

1. **RAG 기반 데이터 검색 및 응답 생성**  
   RAG 시스템을 활용하여 기존 데이터베이스의 정보를 효율적으로 검색하고, LLM을 통해 사용자가 질문한 내용에 대한 최적의 답변을 생성합니다.

2. **감정 분석 및 진단**  
   사용자로부터 입력된 데이터를 바탕으로 감정을 분석하고, 사용자의 정신 건강 상태를 진단합니다.

3. **사용자 친화적 인터페이스 제공**  
   간단하고 직관적인 대화형 인터페이스를 통해 사용자가 스스로 감정 상태를 확인하고, 개선 방법을 찾을 수 있도록 돕습니다.

## 시스템 구성

### 주요 기술 스택

- **RAG 시스템**: OpenAI Llama와 같은 최신 NLP 모델을 사용하여 데이터 검색 및 응답 생성.
- **LLM 기반 응답 생성**: 대화형 AI를 통해 사용자에게 맞춤형 상담 및 감정 분석 서비스 제공.
- **Frontend**: React.js를 사용한 직관적인 사용자 인터페이스.
- **Backend**: Node.js 및 Python 기반 서버 아키텍처.
- **Database**: 사용자 데이터를 효율적으로 관리하기 위한 MongoDB.

## 기술 스택

## 시스템 플로우

![시스템 플로우](https://raw.githubusercontent.com/Psychological-Counseling-K-html/.github/refs/heads/main/profile/assets/system_architecture.png)

## 서비스 내용 예시

![서비스 내용 예시](https://raw.githubusercontent.com/Psychological-Counseling-K-html/.github/refs/heads/main/profile/assets/service_example.png)

## 프로젝트 진행 상황

- **1주차**: RAG 시스템 및 LLM 모델 선정, 요구사항 분석.
- **2주차**: 데이터베이스 설계 및 기본 시스템 아키텍처 구축.
- **3주차**: LLama3 모델 파인튜닝 및 FAISS 기반 VectorDB 설정 계획 수립.
- **4주차**: 크롤링 데이터 요약 모델 설계 및 질문/답변 데이터 처리.
- **5주차**: 벡터 DB와 LLM의 의미 기반 검색 최적화 및 도메인 특화 성능 테스트.
- **6주차**: VectorDB와 LLM 연동 및 실시간 서비스 배포.
- **7주차**: 리트리버 및 백엔드 시스템 성능 최적화와 상담사 챗봇 모델 고도화.
- **8주차**: 서버와 모델 간 설정 불일치 오류 수정 및 자동화 절차 강화.
- **9주차**: Llama 3 모델 파인튜닝 및 백엔드 시스템 재구축으로 안정성과 확장성 확보.

## 기대 효과

- 사용자 스스로 감정 상태를 분석하고 개선할 수 있는 접근성을 제공합니다.
- 정신 건강 문제를 조기에 발견하여 예방하는 데 기여합니다.
- 신뢰성 있는 데이터 기반 상담 서비스를 통해 사용자 만족도를 높입니다.

## Hugging Face

- [**신한은행 상담 LLM**](https://huggingface.co/juhoon01/ko_llama3_model_shinhan_4)
- [**네이버 지식IN 상담 LLM**](https://huggingface.co/datasets/doosup01/kpro_last-dataset)

### 필수 라이브러리

- sentence-transformers
- langchain-experimental
- langchain
- langchain_community
- langchain_core
- langchain-text-splitters
- langchain_openai
- faiss-cpu
- bs4
- ragas
