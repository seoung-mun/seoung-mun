# 최승문 (CHOI SEOUNG MUN)

**AI 기능을 "그럴듯한 답"이 아니라 "검증 가능한 흐름"으로 만드는 개발자**

- 🔧 Spring Boot · FastAPI 백엔드와 LangGraph 에이전트를 함께 다룹니다
- 🎯 관심사: LLM 출력 검증 구조, 상태 있는 에이전트 워크플로, 강화학습 서비스화

## 프로젝트

| 프로젝트 | 무엇 | 내 역할 | 핵심 판단 | 링크 |
|---|---|---|---|---|
| **Odyssey** — 동적 재무 플래너 | 소비 이력 기반 월별 지출 계획 + 재계산 (2026 금융 AI Challenge) | BE/AI (기여도 40%) | 금액·절감률은 결정론 계산+몬테카를로만 생성, LLM은 설명만. 숫자 불일치 시 2회 재검증 → 48개 사례 첫 답변 일치율 41.7%에서 최종 불일치 0건 | [odyssey-finance-ai](https://github.com/seoung-mun/odyssey-finance-ai) |
| **PuCo** — Puerto Rico RL 플랫폼 | WebSocket 5인 멀티플레이 + PPO 에이전트 대전 웹 | Web/서버/배포 (기여도 33%) | 모델 환경이 2회 바뀌는 동안 학습 결과 JSON을 어댑터로 자동 연결해 UI 재작성 없이 베타까지 진행 | [puco_test](https://github.com/seoung-mun/puco_test) |
| **GoodPartner** — AI 여행 플래너 | LangGraph + FAISS RAG + Google Maps 일정 생성/수정 | 에이전트 워크플로 설계 | 선호를 하나씩 묻는 방식 폐기 → Planner/Editor 분리로 1회 요청 초안 + 부분 수정. 지도 API 실패 시 Haversine fallback | [good_partner](https://github.com/seoung-mun/good_partner) · [시연 영상](https://drive.google.com/file/d/1VH2m0IzGnyajpLCS0oUcWAZmtMV4Ktui/view) |

## 기술 스택

![Java](https://img.shields.io/badge/-Java_21-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangGraph](https://img.shields.io/badge/-LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![React](https://img.shields.io/badge/-React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Caddy](https://img.shields.io/badge/-Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=seoung-mun&layout=compact&hide_border=true&hide=jupyter%20notebook,html,css" height="150" />

## 연락

📫 csn98653580@gmail.com
