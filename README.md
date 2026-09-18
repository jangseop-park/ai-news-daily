# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-09-19

# AI 뉴스 — 2026-09-19

## 🔥 GitHub Trending (Python)

- [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector): AI 에이전트 스킬용 보안 스캐너임. Claude Code, Codex, MCP 스킬을 설치하기 전에 취약점, 악성 패턴, 프롬프트 인젝션, 데이터 유출, 공급망 위험을 탐지함. 스킬 생태계가 커지면서 설치 전 검증 도구로 주목받음.
- [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling): 단일 요청부터 대규모 크롤링까지 처리하는 적응형 웹 스크래핑 프레임워크임. 사이트 구조가 바뀌어도 요소를 다시 찾아내는 적응형 파싱이 특징임. 하루 300개 이상 스타를 받음.
- [shiyu-coder/Kronos](https://github.com/shiyu-coder/Kronos): 금융 시장의 '언어'를 학습한 파운데이션 모델임. 캔들(K-line) 시계열 데이터를 토큰화해 사전학습했고 가격 예측 등 금융 시계열 태스크에 활용 가능함.
- [microsoft/agent-lightning](https://github.com/microsoft/agent-lightning): Microsoft가 만든 AI 에이전트 학습 프레임워크임. 기존 에이전트 코드를 거의 바꾸지 않고 강화학습 등으로 에이전트를 훈련·최적화할 수 있게 해줌.
- [tirth8205/code-review-graph](https://github.com/tirth8205/code-review-graph): MCP와 CLI용 로컬 우선 코드 인텔리전스 그래프임. 코드베이스의 영속적인 지도를 만들어 AI 코딩 도구가 필요한 부분만 읽게 함. 코드 리뷰와 대형 레포 작업에서 컨텍스트를 크게 줄였다는 벤치마크를 제시함.

## 📄 Hugging Face Papers

- [DeepSeek-V4.1-Flash: KV Cache 압축의 한계에 도전](https://huggingface.co/papers/2609.19969)
  장기 에이전트 워크로드가 입력 중심으로 바뀌면서 prefill 비용과 KV cache 용량·대역폭이 배포 비용의 병목이 됐다고 진단함. 백본 552B 파라미터의 멀티모달 MoE 모델로 최대 100만 토큰 컨텍스트를 지원함. Causal Encoder-Decoder(CED) 구조로 decode 때는 토큰당 16B, prefill 때는 8B만 활성화해 에이전트 워크로드의 비용 효율을 크게 높임.
- [EOS 토큰이 어긋날 때: On-Policy Distillation의 길이 팽창 이해하기](https://huggingface.co/papers/2609.20511)
  On-policy distillation에서 학생 모델 응답이 지나치게 길어지는 현상의 원인을 분석함. base 학생과 post-trained 교사가 서로 다른 EOS 토큰에 종료 확률을 두는 불일치가 주요 원인임을 Qwen3, Llama, Gemma에서 확인함. 디코딩 stopping set만 맞추는 것으로는 부족하고, 기능적으로 동등한 EOS 토큰들을 하나의 종료 행동으로 묶어 다루면 길이 팽창이 크게 완화됨.
- [JEPA-Anything: 서로 다른 세계를 아우르는 예측 모델 학습](https://huggingface.co/papers/2609.20800)
  도메인에 상관없이 쓸 수 있는 월드 모델링 프레임워크임. JEPA를 확장한 orthogonal predictive factorization(OPF)으로 잠재 타깃을 상보적 요소로 분해해 전용 경로에서 학습한 뒤 다시 결합함. 비전, 생물학, 임상 궤적, 제어, 분자동역학, 물리장, 날씨 등 7개 도메인에서 표현 학습·개입 예측·OOD 일반화·장기 동역학을 평가함.
- [MiniMax-H3는 물리 세계를 추론할 수 있는가? Omni-Modal 생성 모델 평가](https://huggingface.co/papers/2609.18323)
  텍스트·이미지·비디오·오디오를 통합 생성하는 MiniMax-H3를 대상으로 물리 세계 추론 능력을 평가함. 멀티모달 정렬이 월드 추론을 개선하는지 묻고, 네 가지 상보적 차원으로 구성된 평가 프레임워크를 제안함. 프롬프트가 정답 영상과 거의 일치하던 기존 평가와 달리 omni-modal 입력을 적극 활용하도록 설계됨.
- [RiskChainBench: 난독화된 플랫폼 메시지 복원과 증거 기반 웹 조사 벤치마크](https://huggingface.co/papers/2609.16900)
  이모지, 동음이의어, 글자 분해 등으로 유도 문구를 숨기는 플랫폼 악용 캠페인 탐지를 위한 벤치마크임. 600개 세션에서 만든 3,600개 복원 입력과 사람이 라벨링한 600개 로컬 웹 환경을 짝지음. 모델이 먼저 메시지·의도·목적지를 복원한 뒤 VLM 웹 에이전트로 해당 사이트를 조사해 증거 인용 위험 리포트를 작성하게 하여 두 단계를 함께 평가함.

## 🦉 GeekNews

- [모두가 제정신을 잃었다](https://www.netmeister.org/blog/everybodys-lost-their-minds.html)
  AI 대응이 하루 업무의 75% 이상을 차지하면서 일의 즐거움까지 잃었다는 경험에서 출발한 글임. 윤리와 실제 효과를 따지지 않고 밀어붙이는 조직의 AI 도입 열풍을 비판함.
- [마틴 파울러: 나는 LLM이 마음에 들지 않는다](https://martinfowler.com/articles/2026-dont-like-llms.html)
  LLM의 생산성 향상 가능성과 유용성은 인정하지만 직접 대화할 때는 거부감이 앞선다는 글임. 유용한 답과 지어낸 내용을 똑같이 확신에 찬 어조로 말하는 점을 핵심 문제로 꼽음.
- [Jevlike - 문장 대신 선택지별 확률을 반환하는 Jev 방식의 오픈소스 모델](https://github.com/vinnylarouge/jevlike)
  TypeSafe의 Jev처럼 문장 대신 선택지별 확률을 반환하는 모델을 직접 학습하고 실험할 수 있게 만든 오픈소스 프로젝트임. 매번 달라지는 자유 텍스트 대신 구조화된 확률 출력을 얻을 수 있음.
- [OpenSpec - 코딩 에이전트와 구현 전에 명세를 맞추는 개발 도구](https://openspec.dev/)
  대화 기록에만 남아 있던 요구사항을 명세와 구현 계획으로 정리해주는 도구임. 사람이 먼저 검토한 뒤 AI가 코드를 작성하도록 흐름을 잡아줌. 변경 작업마다 제안서 등 문서를 남기는 spec-driven 방식임.
- [Bonsai 2 27B, 성능 98.2%를 유지하며 모델 크기를 5.9GB로 압축](https://prismml.com/news/bonsai-2-27b)
  PrismML이 Qwen3.8 27B 기반의 3진(ternary) 가중치 모델을 공개함. 전체 정밀도 모델 대비 크기를 9배 이상 줄여 5.9GB로 만들면서 종합 벤치마크 성능의 98.2%를 유지했다고 밝힘.

---
## 📅 이전 날짜

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
- [2026-08-18](data/2026-08-18.md)
- [2026-08-17](data/2026-08-17.md)