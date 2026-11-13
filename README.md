# 김민석 · AI / LLM Engineer

법률 도메인 파인튜닝, 로컬 LLM 실패 유형 분석, AI를 연결한 서비스 구현을 해왔습니다. 프로젝트마다 담당 역할과 기술적 결정, 확인 가능한 코드·학습 기록을 함께 정리합니다.

**[포트폴리오 사이트](https://minkim7529.github.io/ai-engineering-portfolio/)** · [이메일: kms7529@naver.com](mailto:kms7529@naver.com)

대구대학교 AI학과 졸업(2026) · 법률상담 AI 졸업작품으로 공학제 최우수상

## 대표 프로젝트

### 1. 법률상담 AI · 도메인 파인튜닝

학생 4인 팀 졸업작품(지도교수: 김희철). Llama 3.1 8B를 법률 질의응답에 맞춰 학습하고 Gradio로 시연했습니다.

- **담당:** 모델·데이터셋 조사, 학습 코드, 성능 개선·분석, 웹 프로그래밍 개발
- **핵심 결정:** 4bit 모델에 LoRA를 적용하고 반복·미완결 문장을 후처리
- **공개 근거:** 53,480건 · 1 epoch · 1,671 step 학습 기록, 노트북, 데이터 샘플, 어댑터 설정

`Python` `PyTorch` `LoRA / Unsloth` `Gradio`

[코드와 학습 기록](https://github.com/minkim7529/legal-consultation-ai) · [프로젝트 설명](https://minkim7529.github.io/ai-engineering-portfolio/projects/legal-consultation-ai.html)

### 2. 로컬 LLM 보이스 컴패니언 · 출력 품질 보정

[Open-LLM-VTuber](https://github.com/Open-LLM-VTuber/Open-LLM-VTuber) 기반 개인 확장 프로젝트. Ollama와 Gemini를 교체하며 소형 로컬 모델의 실패 유형을 다뤘습니다.

- **담당:** Ollama 네이티브 백엔드, 스트리밍 필터, 정체성 역전 가드, 반복 발화 보정
- **핵심 결정:** 모델 교체 실험과 규칙 기반 보정을 구분하고, 효과가 적었던 temperature 변경은 되돌림
- **공개 근거:** 직접 수정한 15개 파일의 패치와 실패 유형별 대응 기록

`Python / asyncio` `Ollama` `Gemini API` `Edge TTS`

[변경 패치와 실험 기록](https://github.com/minkim7529/vtuber-ollama-gemini-experiments) · [프로젝트 설명](https://minkim7529.github.io/ai-engineering-portfolio/projects/vtuber-companion.html)

### 3. StockPilot · AI 서비스 구현과 검증

시세·뉴스와 Gemini 판단을 연결한 Windows 주식 분석·모의투자 앱입니다.

- **구현:** Electron UI, 로컬 API, 시세 수집, AI 판단, 모의 장부와 주문 검증
- **핵심 결정:** 모의·실계좌 경로 분리, 중복 주문과 오래된 시세 차단, 오류·호출 한도 처리
- **검증:** 2026.11.14 공개 코드 기준 자동 테스트 **79개 통과**. 가짜 응답 기반 검증이며 실제 운용 성과와는 별개

`JavaScript / Node.js` `Electron` `Gemini API` `node:test`

[코드와 테스트](https://github.com/minkim7529/ai-stock-trading-program) · [프로젝트 설명](https://minkim7529.github.io/ai-engineering-portfolio/projects/ai-stock-trading-program.html)

## 기술 경험

- **모델·LLM:** PyTorch, LoRA/Unsloth, Ollama, Gemini API, 프롬프트·출력 후처리
- **서비스:** Python, FastAPI, Gradio, Node.js, Electron
- **웹·데이터:** TypeScript, Next.js, Tailwind CSS, Java/JSP, MariaDB/MySQL

## 그 외 프로젝트와 협업

- **[설스터디](https://github.com/minkim7529/hackathon-seolstudy):** 6인 팀 해커톤. Next.js 기반 학습 코칭 서비스의 프론트엔드와 상태관리 담당
- **[Goods Shop](https://github.com/minkim7529/goods-shop):** 개인 프로젝트. Java MVC 쇼핑몰 기획·설계·구현
- **[피부질환 분류 알고리즘](https://github.com/minkim7529/skin-disease-classifier):** 3인 팀. 데이터 정제, 모델 학습 및 실행 담당
- **[졸음방지 독서대](https://github.com/minkim7529/drowsy-reading-stand):** 2인 팀. CNN 눈 상태 분류와 하드웨어 설계 발표 기록
