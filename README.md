<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1F4D,100:1D6FD8&height=200&section=header&text=%EA%B8%88%EA%B5%90%EB%B9%88&fontColor=ffffff&fontSize=60&fontAlignY=38&desc=Finance%20Backend%20%C2%B7%20AI%20Developer&descAlignY=60&descSize=20" width="100%" alt="금교빈 · Finance Backend · AI Developer" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=1D6FD8&center=true&vCenter=true&width=600&lines=Finance+%C3%97+Backend+%C3%97+AI;%EA%B2%80%EC%A6%9D+%EA%B0%80%EB%8A%A5%ED%95%9C+AI+%EC%84%9C%EB%B9%84%EC%8A%A4%EB%A5%BC+%EB%A7%8C%EB%93%AD%EB%8B%88%EB%8B%A4" alt="Finance × Backend × AI" />
</p>

## 안녕하세요, 금교빈입니다 👋

금융 도메인의 **백엔드·AI 개발자**를 지향합니다.
지금은 SSAFY에서 Python 트랙을 배우고 있습니다.

<br>

## 🏆 수상

### 2026 금융 AI Challenge 우수상 (신한은행장상)
주최 금융보안원 · 후원 금융위원회 · 1,388팀 참가 · [대회 페이지](https://daker.ai/public/hackathons/2026-finance-ai-challenge)

**안심피싱 — AI 기반 불시 보이스피싱 실전 대응훈련 서비스**

AI가 사기범 역할로 실제 전화를 겁니다. 예고 훈련과 불시 훈련의 대응을 비교해 리포트로 보여 줍니다.

**역할: AI 파트 (4인 팀)**

- **통화 설계**: 사기 시나리오 5종과 통화 규칙 설계 (배역·말투·진행 단계, 거절·종료 대응)
- **안전 통제**: 훈련이 실제 피해로 이어지지 않도록 규칙 설계
  - 실제 기관명 사용 금지, 계좌·주민번호·인증번호를 숫자로 말하지 않음
  - 통화 종료 후 녹취록 자동 안전 감사 (실제 기관명, 비밀정보 요구, 역할 이탈 탐지)
- **판정 신뢰성**: LLM이 판단하고 서버가 점수를 매기는 구조 설계
  - LLM 판정마다 사용자의 실제 발화를 근거로 인용하고, 통화 원문에 없으면 판정을 폐기
  - 점수는 LLM 없이 위험 행동 7종·방어 행동 6종의 고정 가중치로 서버가 계산
- **검증과 개선**: 실제 통화 약 100회로 시나리오별 테스트
  - DB와 로그에서 예상 밖 응답 약 50건을 찾아 규칙을 보완
  - STT → LLM → TTS 구조를 실시간 음성 모델(OpenAI Realtime)로 바꿔 응답 지연을 **최대 16초 → 2~4초**로 단축

<br>

## 🚀 프로젝트

### [StarTrace](https://github.com/mykyobin/StarTrace) · SSAFY 프로젝트
별지도에서 별을 눌러 질문하면 위키백과·NASA 문서를 근거로 답하는 천문학 RAG 서비스입니다.

- LangGraph `retrieve → generate` 파이프라인, Chroma 벡터 검색 (유사도 / MMR)
- 답변에 실제로 인용한 근거만 원문 링크와 함께 표시하고, 문서에 없으면 "확인되지 않습니다"로 답함
- FastAPI 서버, LLM을 호출하지 않는 pytest 테스트 50개, API 사용량·비용 기록

<br>

## 🛠 기술 스택

<img src="https://skillicons.dev/icons?i=python,django,fastapi,html,css,git" alt="Python, Django, FastAPI, HTML, CSS, Git" />

![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

<br>

## 📚 준비 중인 자격증

SQLD · 정보처리기사 · 빅데이터분석기사 · 리눅스마스터 · AICE

<br>

## 📫 연락처

[![Gmail](https://img.shields.io/badge/mykyobin123@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:mykyobin123@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1F4D,100:1D6FD8&height=120&section=footer" width="100%" alt="" />
