# MORI AI Platform

AI 기반 감성 분석 및 지식 추론 플랫폼

---

## 프로젝트 소개

MORI AI Platform은 이미지, 텍스트, 음성 등 다양한 데이터를 분석하여 감정과 의미를 추론하는 AI 서비스 플랫폼입니다.

본 프로젝트는 한국ICT인재개발원 AI 응용 웹앱 풀스택 개발자 과정 최종 프로젝트로 진행되었으며, 멀티 에이전트 구조와 RAG(Retrieval-Augmented Generation) 기술을 활용하여 실서비스 수준의 AI 플랫폼 구축을 목표로 합니다.

---

## 프로젝트 목표

- AI 기반 감성 분석 엔진 구축
- 멀티모달 데이터 분석
- RAG 기반 지식 검색
- MCP(Model Context Protocol) 연동
- Agent 기반 자동화 구조 구현
- 웹 서비스 플랫폼 구축

---

## 시스템 구성

```text
┌─────────────────────────────┐
│        React Frontend       │
└──────────────┬──────────────┘
               │
               ▼
┌─────────────────────────────┐
│      Spring Backend API     │
└──────────────┬──────────────┘
               │
      ┌────────┴────────┐
      ▼                 ▼
┌─────────────┐  ┌─────────────┐
│ Python AI   │  │ PostgreSQL  │
│ Engine      │  │ & Vector DB │
└─────────────┘  └─────────────┘
```

---

## Repository Structure

### Frontend

- Repository: https://github.com/ICT-5-1TEAM-FINAL/react
- React
- TypeScript
- Vite
- TailwindCSS

### Backend

- Repository: https://github.com/ICT-5-1TEAM-FINAL/spring
- Spring Boot
- Spring Security
- JPA

### AI Engine

- Repository: https://github.com/ICT-5-1TEAM-FINAL/python
- FastAPI
- LangChain
- LangGraph
- OpenAI
- HuggingFace
- PyTorch

---

## 주요 기능

### Emotion Analysis

- 이미지 감성 분석
- 텍스트 감성 분석
- 멀티모달 감정 분석
- 감정 스코어링

### RAG System

- 문서 검색
- 벡터 검색
- 지식 기반 응답 생성

### Multi-Agent

- Data Agent
- Analysis Agent
- Learning Agent
- Validation Agent

### MCP Integration

- Tool 연결
- 외부 서비스 연동
- Context 공유

---

## Development Environment

| Category | Stack |
|-----------|--------|
| Frontend | React |
| Backend | Spring Boot |
| AI | Python |
| Database | PostgreSQL |
| Vector DB | ChromaDB |
| Container | Docker |
| CI/CD | GitHub Actions |

---

## Team

ICT 5기 1팀 Final Project

---

## License

MIT License
