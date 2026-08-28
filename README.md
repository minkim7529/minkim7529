<!-- GitHub 프로필 메인 페이지 (minkim7529) -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:A5B4FC,100:67E8F9&height=220&section=header&text=AI%20Engineer%20%EA%B9%80%EB%AF%BC%EC%84%9D%EC%9E%85%EB%8B%88%EB%8B%A4&fontSize=32&fontColor=1E293B&animation=fadeIn&fontAlignY=40&desc=RAG%20%2F%20LLM%20Fine-tuning%20%2F%20AI%20Backend&descAlignY=62&descSize=16" alt="header" width="100%"/>

[![GitHub](https://img.shields.io/badge/GitHub-minkim7529-181717?style=for-the-badge&logo=github)](https://github.com/minkim7529)
[![Email](https://img.shields.io/badge/Email-kms7529%40naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:kms7529@naver.com)

</div>

<br>

> **RAG 시스템**과 **LLM 파인튜닝**을 중심으로, 근거를 인용하며 답하고 실제로 배포되는 AI 서비스를 만듭니다.
> 대구대학교 AI학과에서 공부하며 ML·풀스택·임베디드를 넘나드는 팀 프로젝트를 진행해왔고, 현재는 RAG 검색·평가 방법론을 깊이 파고드는 중입니다.

<div align="center">

![Status](https://img.shields.io/badge/💼-AI_Engineer_취업_준비중-06B6D4?style=flat-square)
![Award](https://img.shields.io/badge/🏆-대구대학교_공학제_최우수상-4F46E5?style=flat-square)
![LLM](https://img.shields.io/badge/🧠-LLM_Fine--tuning_(LoRA)-06B6D4?style=flat-square)
![Team](https://img.shields.io/badge/🤝-팀_프로젝트_5회-4F46E5?style=flat-square)

</div>

<br>

## 🔭 지금 하고 있는 것

- [x] RAG 하이브리드 검색(pgvector 코사인 유사도 + Postgres BM25) 구현 및 RRF 병합
- [x] LLM(Llama 3.1 8B) LoRA 파인튜닝으로 도메인 특화 모델 학습
- [ ] RAG 검색 품질 재순위화 실험 고도화
- [ ] RAG 평가 방법론(RAGAS 등) 학습 및 적용

<br>

## 🧰 Tech Stack

<table>
<tr>
<td valign="top" width="50%">

**AI / ML**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Gemini API](https://img.shields.io/badge/Gemini%20API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![LoRA/Unsloth](https://img.shields.io/badge/Fine--tuning-LoRA%2FUnsloth-F7931E?style=flat-square)

**Database / Infra**
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

</td>
<td valign="top" width="50%">

**Language**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)

**Backend / Frontend**
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</td>
</tr>
</table>

<br>

## 🚀 Featured Projects

<table>
<tr>
<td colspan="2">

### 🔍 멀티모달 개인 지식 어시스턴트 ⭐ 현재 집중 프로젝트
`개인 프로젝트 · 진행 중`

문서(PDF/DOCX/TXT)와 이미지를 업로드하면 하나의 지식베이스에서 텍스트·이미지를 함께 검색(RAG)해, 출처를 인용하며 답하는 개인 지식 어시스턴트.
벡터 검색 + 키워드 검색 하이브리드 방식을 RRF로 병합하고, Gemini로 검색 결과를 재순위화한 뒤 근거 인용과 함께 스트리밍 응답을 생성합니다. 평가(eval) 파이프라인을 별도로 구축해 검색 품질을 계속 개선하고 있습니다.

`Next.js` `FastAPI` `Gemini API` `MariaDB/MySQL`

[GitHub →](https://github.com/minkim7529/knowledge-assistant)

</td>
</tr>
<tr>
<td width="35%"><img src="https://raw.githubusercontent.com/minkim7529/legal-consultation-ai/master/images/ai-lawyer-ui-mockup.png" width="100%"/></td>
<td width="65%">

### ⚖️ 법률상담 AI
`대구대학교 졸업작품 · 5인 팀` · 🏆 **공학제 최우수상**

Llama 3.1 8B를 LoRA로 파인튜닝해 만든 AI 법률상담 시스템. 변호사 상담(30분 5~10만원)의 비용·시간 제약 없이 1차 법률 자문을 받을 수 있는 것을 목표로 설계했으며, Llama 2 · Mistral · Gemma와 비교 실험 후 베이스 모델을 직접 선정했습니다.

`Llama 3.1 8B` `LoRA` `Unsloth`

[GitHub →](https://github.com/minkim7529/legal-consultation-ai)

</td>
</tr>
<tr>
<td width="35%"><img src="https://raw.githubusercontent.com/minkim7529/hackathon-seolstudy/master/images/page-01.png" width="100%"/></td>
<td width="65%">

### 📚 설스터디
`블레이버스 제4회 MVP 개발 해커톤 · 6인 팀`

멘토가 학습 플랜을 설계하고 멘티가 학습 현황을 기록하면 데이터 기반으로 피드백하는 1:1 코칭 크로스 플랫폼. 프론트엔드(App Router 설계, 상태관리) 담당.

`Next.js App Router` `TailwindCSS` `Zustand`

[GitHub →](https://github.com/minkim7529/hackathon-seolstudy)

</td>
</tr>
<tr>
<td width="35%"><img src="https://raw.githubusercontent.com/minkim7529/goods-shop/master/images/homepage.png" width="100%"/></td>
<td width="65%">

### 🛍️ Goods Shop
`2024.08 · 개인 프로젝트 (약 1개월, 단독 진행)`

카카오톡 이모티콘 굿즈 판매를 목표로 기획부터 설계·구현까지 혼자 진행한 Java 웹 쇼핑몰. 회원가입/로그인, 장바구니(수량 조절·합계 자동 계산), 게시판까지 전 과정을 단독으로 완성했습니다.

`Java` `JSP/Servlet`

[GitHub →](https://github.com/minkim7529/goods-shop)

</td>
</tr>
</table>

<br>

## 🧭 협업 경험

여러 팀 프로젝트에서 서로 다른 역할을 맡아왔습니다 — 담당 범위를 넓혀가며 프로젝트를 완주하는 것을 목표로 합니다.

| 프로젝트 | 팀 규모 | 담당 역할 |
|---|---|---|
| 법률상담 AI | 5인 | LLM 파인튜닝 |
| 설스터디 (해커톤) | 6인 | 프론트엔드 |
| Goods Shop | 1인 (솔로) | 기획 · 설계 · 구현 전체 |

<br>

## 🎓 About

| 항목 | 내용 |
|---|---|
| 학력 | 대구대학교 AI학과 (2020 ~ 2026 졸업) |
| 수상 | 대구대학교 공학제 최우수상 — 법률상담 AI (졸업작품) |

<br>

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=minkim7529&show_icons=true&hide_border=true&title_color=4F46E5&icon_color=06B6D4&text_color=333333" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=minkim7529&layout=compact&hide_border=true&title_color=4F46E5&text_color=333333" alt="Top Languages" />

</div>

<br>

<div align="center">

읽어주셔서 감사합니다 — 궁금한 프로젝트가 있으면 편하게 연락 주세요 🙌

</div>
