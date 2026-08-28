<!-- GitHub 프로필 메인 페이지 (minkim7529) -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:A5B4FC,100:67E8F9&height=220&section=header&text=AI%20Engineer%20%EA%B9%80%EB%AF%BC%EC%84%9D%EC%9E%85%EB%8B%88%EB%8B%A4&fontSize=32&fontColor=1E293B&animation=fadeIn&fontAlignY=40&desc=RAG%20%2F%20LLM%20Fine-tuning%20%2F%20AI%20Backend&descAlignY=62&descSize=16" alt="header" width="100%"/>

[![GitHub](https://img.shields.io/badge/GitHub-minkim7529-181717?style=for-the-badge&logo=github)](https://github.com/minkim7529)
[![Email](https://img.shields.io/badge/Email-kms7529%40naver.com-03C75A?style=for-the-badge&logo=naver&logoColor=white)](mailto:kms7529@naver.com)

</div>

<br>

> 대구대학교 AI학과에 다니면서 RAG, LLM 파인튜닝 쪽 프로젝트를 주로 해왔습니다.
> 요즘은 knowledge-assistant를 계속 붙잡고 검색 품질을 올리는 중이고, 만든 걸 실제로 배포까지 해보는 걸 중요하게 생각합니다.

<div align="center">

![Status](https://img.shields.io/badge/💼-AI_Engineer_취업_준비중-06B6D4?style=flat-square)
![Award](https://img.shields.io/badge/🏆-대구대학교_공학제_최우수상-4F46E5?style=flat-square)
![LLM](https://img.shields.io/badge/🧠-LLM_Fine--tuning_(LoRA)-06B6D4?style=flat-square)
![Team](https://img.shields.io/badge/🤝-팀_프로젝트_5회-4F46E5?style=flat-square)

</div>

<br>

## 🔭 지금 하고 있는 것

- [x] 벡터 검색 + 키워드 검색 하이브리드 구조 짜고 RRF로 병합
- [x] Llama 3.1 8B LoRA 파인튜닝으로 도메인 특화 모델 학습
- [ ] 재순위화(reranking) 실험 더 다듬기
- [ ] RAGAS 같은 RAG 평가 방법론 공부하고 적용해보기

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

문서와 이미지를 올려두면 나중에 그 안에서 찾아 답해주는 개인용 RAG 어시스턴트입니다. 벡터 검색과 키워드 검색을 같이 돌려서 RRF로 합치고, Gemini로 한 번 더 순위를 매긴 다음 근거를 인용해 스트리밍으로 답합니다. eval 코드를 따로 짜서, 뭔가 바꿀 때마다 검색이 실제로 좋아지는지 확인하면서 작업하고 있습니다.

`Next.js` `FastAPI` `Gemini API` `MariaDB/MySQL`

[GitHub →](https://github.com/minkim7529/knowledge-assistant)

</td>
</tr>
<tr>
<td colspan="2">

### 🎙️ 로컬 LLM 보이스 컴패니언 — Ollama ↔ Gemini 백엔드 실험
`개인 프로젝트 · 오픈소스(Open-LLM-VTuber) 기반 실험`

[Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber)를 가져다가 로컬 모델(Ollama)과 Gemini를 번갈아 붙여보면서 답변 품질을 비교했습니다. 7B급 로컬 모델은 캐릭터 관계를 반대로 말하거나(정체성 역전), 한자가 섞여 나오거나, 같은 말을 반복하는 문제가 있어서 하나씩 코드로 대응했습니다. temperature를 올려서 표현을 다양하게 만들어보려던 실험은 결국 별 효과가 없다는 걸 확인하고 되돌렸는데, 이 결과도 그냥 버리지 않고 주석으로 남겨뒀습니다.

`Ollama` `Gemini API` `Python` `Edge TTS`

[GitHub →](https://github.com/minkim7529/vtuber-ollama-gemini-experiments)

</td>
</tr>
<tr>
<td width="35%"><img src="https://raw.githubusercontent.com/minkim7529/legal-consultation-ai/master/images/ai-lawyer-ui-mockup.png" width="100%"/></td>
<td width="65%">

### ⚖️ 법률상담 AI
`대구대학교 졸업작품 · 5인 팀` · 🏆 **공학제 최우수상**

Llama 3.1 8B를 LoRA로 파인튜닝해서 만든 법률상담 AI입니다. 변호사 상담이 30분에 5~10만원인 현실에서, 돈과 시간 부담 없이 1차 자문 정도는 받을 수 있게 만들어보자는 게 출발점이었습니다. 베이스 모델은 Llama 2, Mistral, Gemma를 직접 비교해보고 골랐습니다.

`Llama 3.1 8B` `LoRA` `Unsloth`

[GitHub →](https://github.com/minkim7529/legal-consultation-ai)

</td>
</tr>
<tr>
<td width="35%"><img src="https://raw.githubusercontent.com/minkim7529/hackathon-seolstudy/master/images/page-01.png" width="100%"/></td>
<td width="65%">

### 📚 설스터디
`블레이버스 제4회 MVP 개발 해커톤 · 6인 팀`

멘토가 학습 플랜을 짜고 멘티가 공부 기록을 남기면, 그 데이터를 보고 피드백을 주고받는 1:1 코칭 서비스입니다. 저는 프론트엔드를 맡아서 App Router 구조를 짜고 상태관리를 담당했습니다.

`Next.js App Router` `TailwindCSS` `Zustand`

[GitHub →](https://github.com/minkim7529/hackathon-seolstudy)

</td>
</tr>
<tr>
<td width="35%"><img src="https://raw.githubusercontent.com/minkim7529/goods-shop/master/images/homepage.png" width="100%"/></td>
<td width="65%">

### 🛍️ Goods Shop
`2024.08 · 개인 프로젝트 (약 1개월, 단독 진행)`

좋아하는 카카오톡 이모티콘 굿즈를 파는 사이트가 마땅히 없어서 직접 만들어본 Java 웹 쇼핑몰입니다. 기획부터 구현까지 혼자 했고, 회원가입/로그인, 장바구니, 게시판까지 한 달 정도 걸려서 완성했습니다.

`Java` `JSP/Servlet`

[GitHub →](https://github.com/minkim7529/goods-shop)

</td>
</tr>
</table>

<br>

## 🧭 협업 경험

프로젝트마다 맡은 역할이 조금씩 달랐습니다.

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

궁금한 프로젝트 있으면 편하게 연락 주세요.

</div>
