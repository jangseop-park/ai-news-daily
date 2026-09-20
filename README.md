# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-09-21

# AI 뉴스 — 2026-09-21

## 🔥 GitHub Trending (Python)

- [anthropics/financial-services](https://github.com/anthropics/financial-services): Anthropic의 금융 서비스용 Claude 레퍼런스 모음임. 투자은행·주식 리서치·PE·자산관리 워크플로용 에이전트, 스킬, 데이터 커넥터를 Claude Cowork 플러그인이나 Managed Agents API로 쓸 수 있음.
- [paperless-ngx/paperless-ngx](https://github.com/paperless-ngx/paperless-ngx): 커뮤니티가 운영하는 문서 관리 시스템임. 종이 문서를 스캔·인덱싱·아카이빙해 검색 가능한 디지털 보관함으로 만들어줌.
- [mihail911/modern-software-dev-assignments](https://github.com/mihail911/modern-software-dev-assignments): Stanford CS146S 'The Modern Software Developer' 강의 과제 레포임. AI 코딩 도구를 활용한 최신 소프트웨어 개발 방식을 실습함.
- [browser-use/browser-harness](https://github.com/browser-use/browser-harness): LLM이 브라우저에서 어떤 작업이든 끝까지 수행하도록 돕는 자가 복구형 하네스임. browser-use 팀이 만듦.
- [FareedKhan-dev/train-llm-from-scratch](https://github.com/FareedKhan-dev/train-llm-from-scratch): 데이터 다운로드부터 텍스트 생성까지 LLM을 처음부터 학습시키는 과정을 단순하게 보여주는 교육용 레포임.

## 📄 Hugging Face Papers

- [When2Think: 효율적인 하이브리드 추론 모델을 위한 난이도 인식 길이 제어](https://huggingface.co/papers/2609.19671)
  추론 모델이 쉬운 문제는 과하게, 어려운 문제는 덜 생각하는 비효율을 다룸. 일률적 길이 페널티 대신 문제 난이도에 맞춰 사고 길이를 조절하도록 학습시킴.
- [특권 정보는 온폴리시 자기 증류에 무엇을 더하는가?](https://huggingface.co/papers/2609.20612)
  정답이나 풀이를 본 자기 자신의 고정 사본에게서 배우는 OPSD를 분석함. 교사에게 준 추가 정보가 증류 자체의 효과를 넘어 실제로 얼마나 기여하는지 분리해서 측정함.
- [샘플 수만으로는 부족함: 후보 생성 전략이 LLM Test-Time Scaling의 에너지와 성능을 좌우함](https://huggingface.co/papers/2609.19499)
  Test-time scaling의 추론 예산을 후보 개수 N으로만 표현하는 관행을 비판함. 같은 N이라도 후보를 어떻게 생성하느냐에 따라 에너지 소비와 성능이 크게 달라짐을 보임.
- [FAMOS: 희소 관측으로부터의 Feed-Forward 3D 관절 모델링](https://huggingface.co/papers/2609.20817)
  소수의 단안 뷰만으로 관절형 물체를 모델링하는 방법임. 단일 관측과 카테고리 사전 지식에 의존하던 기존 방식과 달리 여러 희소 관측의 형상·움직임 단서를 통합함.
- [환경을 마스킹하지 말 것: 관측 감독이 RL에서 에이전트의 탐색 방식을 바꿈](https://huggingface.co/papers/2609.20715)
  에이전트 SFT에서 행동 토큰에만 loss를 주는 관행에 의문을 제기함. 환경 관측까지 예측 대상으로 학습시키면 이후 RL 단계에서 에이전트의 탐색 양상이 달라짐을 보임.

## 🦉 GeekNews

- [Jev 덕분에 구조화된 출력이 다시 흥미로워졌다](https://www.seangoedecke.com/jev-means-structured-output-is-interesting-again/)
  AI가 긴 답변 대신 프로그램의 의사결정 지점마다 빠르고 저렴한 판단을 제공하면 챗봇을 넘어선 새로운 종류의 응용이 가능해진다는 글임.
- [Stagehand v4, Playwright보다 2배 빠르고 토큰 효율 80% 높은 브라우저 자동화](https://github.com/browserbase/stagehand)
  AI 에이전트가 웹사이트를 조작하고 데이터를 추출하는 오픈소스 SDK임. Playwright와 비슷한 코드에 자연어 명령을 섞어 쓸 수 있음.
- [Claude Code, 이제 AGENTS.md도 지원](https://x.com/trq212/status/2101009392611278961)
  Claude Code 2.1.277부터 프로젝트에 CLAUDE.md가 없으면 AGENTS.md를 프로젝트 지침으로 자동 사용함. 여러 코딩 에이전트의 공통 지침 파일과 호환됨.
- [Agent-Native - 하나의 액션을 UI/에이전트/API에서 함께 쓰는 앱 프레임워크](https://github.com/BuilderIO/agent-native)
  기존 앱과 AI 에이전트를 따로 만들지 않고 한 애플리케이션 안에서 같은 기능과 데이터를 공유하게 하는 프레임워크임. 작업을 defineAction으로 한 번만 정의함.
- [AI 챗봇이 사람들의 생각을 바꾸는 데 전문가가 되고 있음](https://www.science.org/content/article/ai-chatbots-are-becoming-experts-changing-people-s-minds-what-s-their-secret)
  ChatGPT, Gemini, Claude가 정치적 쟁점 대화에서 세계 챔피언을 포함한 전문 토론자보다 높은 설득력을 보였다는 연구 결과임.

---
## 📅 이전 날짜

- [2026-09-20](data/2026-09-20.md)
- [2026-09-19](data/2026-09-19.md)
- [2026-09-18](data/2026-09-18.md)
- [2026-09-17](data/2026-09-17.md)
- [2026-09-15](data/2026-09-15.md)
- [2026-09-14](data/2026-09-14.md)
- [2026-09-13](data/2026-09-13.md)
- [2026-09-12](data/2026-09-12.md)
- [2026-09-11](data/2026-09-11.md)
- [2026-09-10](data/2026-09-10.md)
- [2026-09-08](data/2026-09-08.md)
- [2026-09-07](data/2026-09-07.md)
- [2026-09-06](data/2026-09-06.md)
- [2026-09-05](data/2026-09-05.md)
- [2026-09-04](data/2026-09-04.md)
- [2026-09-03](data/2026-09-03.md)
- [2026-09-02](data/2026-09-02.md)
- [2026-08-31](data/2026-08-31.md)
- [2026-08-30](data/2026-08-30.md)
- [2026-08-29](data/2026-08-29.md)
- [2026-08-28](data/2026-08-28.md)
- [2026-08-27](data/2026-08-27.md)
- [2026-08-25](data/2026-08-25.md)
- [2026-08-24](data/2026-08-24.md)
- [2026-08-23](data/2026-08-23.md)
- [2026-08-22](data/2026-08-22.md)
- [2026-08-21](data/2026-08-21.md)
- [2026-08-20](data/2026-08-20.md)
- [2026-08-19](data/2026-08-19.md)