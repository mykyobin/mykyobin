# 금교빈

금융 도메인의 백엔드·AI 개발자를 지향합니다 · SSAFY 16기 Python 트랙

검증 가능한 AI 서비스를 만듭니다. 지금은 SQLD와 정보처리기사를 준비하고 있습니다.

## 주요 경험

### 안심피싱

**2026 금융 AI Challenge 우수상 (신한은행장상)** · 주최 금융보안원 · 1,388팀 참가 · [대회 페이지](https://daker.ai/public/hackathons/2026-finance-ai-challenge)

AI가 사기범 역할로 실제 전화를 걸고, 예고 훈련과 불시 훈련의 대응을 비교해 리포트로 보여 주는 보이스피싱 대응훈련 서비스입니다. 4인 팀에서 AI 파트를 맡았습니다.

| 통화 테스트 | 응답 보완 | 지연 개선 |
|:--|:--|:--|
| 약 100회 | 약 50건 | 최대 16초 → 2~4초 |

- **판정 신뢰성**: LLM 판정은 통화 원문과 대조해 근거가 없으면 폐기하고, 점수는 서버가 고정 가중치로 계산
- **안전 통제**: 사기 시나리오 5종과 통화 규칙 설계, 실제 기관명·비밀정보 요구를 막는 녹취록 자동 감사
- **지연 개선**: STT → LLM → TTS 구조를 실시간 음성 모델(OpenAI Realtime)로 전환

### StarTrace

**SSAFY 프로젝트** · [저장소](https://github.com/mykyobin/StarTrace)

별지도에서 별을 눌러 질문하면 위키백과·NASA 문서를 근거로 답하는 천문학 RAG 서비스입니다.

- **검색**: LangGraph `retrieve → generate` 파이프라인, Chroma 벡터 검색 (유사도 / MMR)
- **근거 표시**: 답변에 실제로 인용한 근거만 원문 링크와 함께 표시하고, 문서에 없으면 "확인되지 않습니다"로 답함
- **품질 관리**: FastAPI 서버, LLM을 호출하지 않는 pytest 테스트 50개, API 사용량·비용 기록

## 기술

<img src="https://skillicons.dev/icons?i=python,django,fastapi,git" alt="Python, Django, FastAPI, Git" height="40" />

![LangGraph](https://img.shields.io/badge/LangGraph-2F3437?style=flat-square&logo=langchain&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-2F3437?style=flat-square)

## 연락

[mykyobin123@gmail.com](mailto:mykyobin123@gmail.com)
