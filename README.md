# 🚀 MORI AI Platform

> Multi-Agent AI Platform for Emotion Analysis, Knowledge Retrieval, and Intelligent Decision Support

![Status](https://img.shields.io/badge/Status-In%20Development-blue)
![AI](https://img.shields.io/badge/AI-MultiAgent-green)
![RAG](https://img.shields.io/badge/RAG-Enabled-orange)
![MCP](https://img.shields.io/badge/MCP-Supported-purple)
![License](https://img.shields.io/badge/License-Apache%202.0-red)

---

## 📖 Overview

MORI AI Platform은 감성 분석(Emotion Analysis), 지식 검색(RAG), 멀티 에이전트 협업(Multi-Agent System), MCP(Model Context Protocol) 연동을 통합한 AI 서비스 플랫폼입니다.

사용자의 텍스트, 이미지 및 다양한 데이터를 분석하여 감정과 의미를 추론하고, AI 에이전트들이 협력하여 보다 정확한 결과와 인사이트를 제공하는 것을 목표로 합니다.

본 프로젝트는 한국ICT인재개발원 AI 응용 웹앱 풀스택 개발자 과정의 최종 프로젝트로 개발되었습니다.

---

## 🎯 Project Goals

- AI 기반 감성 분석 엔진 구축
- 멀티모달 데이터 분석
- RAG 기반 지식 검색 시스템 구축
- MCP 기반 AI Tool 연동
- Multi-Agent 협업 구조 구현
- Web · Mobile 통합 서비스 제공
- 실서비스 수준 AI 플랫폼 구축

---

## 🏛️ System Architecture

```text
┌─────────────────────────────────────┐
│            Client Layer             │
├─────────────────┬───────────────────┤
│ React Web       │ Android App       │
└────────┬────────┴─────────┬─────────┘
         │                  │
         └────────┬─────────┘
                  ▼
┌─────────────────────────────────────┐
│         Spring Backend API          │
│ Authentication · Service Logic      │
└─────────────────┬───────────────────┘
                  │
                  ▼
┌─────────────────────────────────────┐
│          Python AI Engine           │
├─────────────────────────────────────┤
│ Emotion Analysis Engine             │
│ RAG Engine                          │
│ Multi-Agent System                  │
│ MCP Integration                     │
└─────────────────┬───────────────────┘
                  │
        ┌─────────┴─────────┐
        ▼                   ▼
 PostgreSQL           Vector Database
                     (ChromaDB/FAISS)
```

---

## 🧠 Core Features

### Emotion Analysis Engine

- 이미지 감성 분석
- 텍스트 감성 분석
- 멀티모달 분석
- 감정 점수 산출
- 감정 분류 및 시각화

### Retrieval-Augmented Generation (RAG)

- 문서 검색
- 벡터 검색
- 의미 기반 검색
- 지식 기반 응답 생성

### Multi-Agent System

- Data Collection Agent
- Analysis Agent
- Learning Agent
- Validation Agent

### MCP Integration

- AI Tool 연결
- Context 공유
- 외부 서비스 연동
- Agent 확장성 확보

---

## 📦 Repository Structure

### 🌐 Web Frontend

Repository:
https://github.com/ICT-5-1TEAM-FINAL/react

기술 스택

- React
- TypeScript
- Vite
- TailwindCSS

주요 역할

- 사용자 인터페이스
- Dashboard
- 분석 결과 시각화
- 관리자 페이지

---

### 📱 Android Application

Repository:
https://github.com/ICT-5-1TEAM-FINAL/android

기술 스택

- Android
- Kotlin
- REST API

주요 역할

- 모바일 서비스 제공
- AI 분석 요청
- 결과 조회
- 사용자 편의 기능

---

### ⚙️ Backend API

Repository:
https://github.com/ICT-5-1TEAM-FINAL/spring

기술 스택

- Spring Boot
- Spring Security
- JPA
- REST API

주요 역할

- 인증/인가
- 비즈니스 로직
- API Gateway
- 데이터 관리

---

### 🤖 AI Engine

Repository:
https://github.com/ICT-5-1TEAM-FINAL/python

기술 스택

- Python
- FastAPI
- LangChain
- LangGraph
- OpenAI
- HuggingFace
- PyTorch

주요 역할

- 감성 분석 엔진
- RAG 시스템
- Agent Orchestration
- MCP 연동

---

## 🛠️ Technology Stack

| Layer | Technologies |
|---------|---------|
| Web | React, TypeScript |
| Mobile | Android, Kotlin |
| Backend | Spring Boot |
| AI | Python, FastAPI |
| LLM | OpenAI |
| Agent | LangGraph |
| RAG | LangChain |
| Database | PostgreSQL |
| Vector DB | ChromaDB, FAISS |
| DevOps | Docker, GitHub Actions |

---

## 👥 Team

ICT 5기 1팀 Final Project

---

## 📄 License

Apache License 2.0

---

## 🙏 Acknowledgements

한국ICT인재개발원

AI 응용 웹앱 풀스택 개발자 과정

---

### MORI AI Platform

Building Intelligent AI Services with Multi-Agent Collaboration
