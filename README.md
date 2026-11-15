# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-11-16

# AI 뉴스 — 2026-11-16

## 🔥 GitHub Trending (Python)

- [bojieli/ai-infra-book](https://github.com/bojieli/ai-infra-book): 《深入理解 AI Infra》 오픈소스 책 원고임. 하드웨어 제약과 모델 구조에서 출발해 LLM 추론·학습 시스템 설계를 정량적으로 유도함. 본문·PDF·계산 도구·실험 코드 포함.
- [davila7/claude-code-templates](https://github.com/davila7/claude-code-templates): Claude Code용 에이전트·커맨드·스킬·훅·MCP·설정·모드를 모아 둔 오픈소스 레지스트리 겸 CLI임. 필요한 구성요소를 골라 바로 설치 가능함.
- [HKUDS/AutoSwarm](https://github.com/HKUDS/AutoSwarm): 여러 AI 에이전트를 하나로 묶어 컨텍스트 장벽 없이 협업시키는 프레임워크임. 에이전트들이 함께 일하는 과정을 지켜볼 수 있음.
- [PrefectHQ/fastmcp](https://github.com/PrefectHQ/fastmcp): MCP 서버·클라이언트를 Python답게 빠르게 만드는 라이브러리임. 데코레이터 기반으로 툴·리소스를 간단히 노출함.
- [huytieu/COG-second-brain](https://github.com/huytieu/COG-second-brain): AI 스킬 35개·에이전트 10개·인맥 CRM을 갖춘 자기진화형 세컨드 브레인임. 작업자가 자기 결과를 스스로 채점하지 않는 V-모델 검증 루프가 특징임. Claude Code·Cursor·Codex 등에서 동작함.

## 📄 Hugging Face Papers

- [Agent-R²: 실제 소스 데이터 합성으로 생산성 업무 에이전트 확장](https://huggingface.co/papers/2611.08219)
  실제 파일·문서를 바탕으로 업무 과제를 합성하는 프레임워크를 제안함. 4천 개 과제로 4B 에이전트를 SFT와 루브릭 기반 RL로 학습시켜, 더 큰 모델보다 실무형 작업과 파일 기반 추론에서 나은 성능을 냄.
- [다시 픽셀로: 잠재 비디오 확산 모델을 픽셀 공간으로 끌어올리기](https://huggingface.co/papers/2611.17336)
  현재 비디오 생성 모델은 VAE latent 공간에서 시공간을 압축해 학습함. 이 압축이 고해상도·제어형·인터랙티브 생성의 병목이 됨을 지적하고, 기존 latent 비디오 확산 모델을 픽셀 공간 생성으로 옮기는 방법을 제시함.
- [레퍼런스 기반 UAV 영상 안정화의 합의 포획 문제: 동적 도심 장면 벤치마크](https://huggingface.co/papers/2611.17190)
  호버링 드론 영상을 기준 프레임에 정합하는 안정화 파이프라인을 다룸. 기존 매칭 벤치마크는 카메라만 움직이는 상황이라, 움직이는 차량·보행자가 많은 도심에서는 정합이 동적 객체에 끌려가는 문제를 드러내는 벤치마크를 제안함.
- [TurtLES: 3D 난류 신경망 PDE 대리모델용 대규모 벤치마크](https://huggingface.co/papers/2611.09567)
  CFD 가속용 ML surrogate 연구에 현실적인 시간의존 난류 벤치마크가 부족한 문제를 해결하려 14TB 규모 3D 난류 실린더 유동 데이터셋을 공개함. 여러 신경 PDE 모델을 비교 평가함.
- [HiVe-Mem: 수평 메모리 확장과 수직 증거 구성을 결합한 멀티모달 에이전트 메모리](https://huggingface.co/papers/2611.12872)
  의미 시드를 관계 그래프로 넓히는 수평 확장과, 질의에 맞춰 이질적 증거를 조합하는 수직 구성을 번갈아 수행하는 메모리 프레임워크임. 장기 멀티모달 상호작용 성능을 높임.

## 🦉 GeekNews

- [AI가 코딩을 해결했다면, 왜 내 소프트웨어는 여전히 그대로일까?](https://www.youtube.com/watch?v=IRK8h67ol7Q)
  Jonathan Blow가 AI 코드 생성의 속도·비용 장점은 인정하면서도, 복잡한 소프트웨어의 품질과 사용자 경험이 실제로 좋아졌다는 증거는 없다고 지적함. 생산량과 완성도는 별개라는 주장임.
- [ggml v1.0.0 출시 — 폐기 예정 API 제거, FP8 지원, 백엔드 성능 개선](https://github.com/ggml-org/ggml/releases/tag/v1.0.0)
  llama.cpp의 텐서 연산 라이브러리 ggml이 1.0.0에 도달함. 폐기 예정 공개 API와 DIAGMASK 연산을 제거하고 YaRN 설정·FP8 지원을 확장했으며 여러 백엔드 성능을 개선함.
- [Claude Fable 5.2로 에이전트 1,000개 팀 안전하게 돌리기 — 페르마의 마지막 정리 형식화 실험](https://claude.dev/blog/safely-scaling-multi-agent-teams-with-fable-5-2/)
  Anthropic 연구진이 출시 전 Claude Fable 5.2로 리드 에이전트 1개와 헬퍼 999개를 운용해 페르마의 마지막 정리 증명을 Lean으로 형식화한 실험을 공개함. 대규모 멀티에이전트를 안전하게 확장하는 방법을 다룸.
- [ChatGPT 비즈니스 기능 소개](https://openai.com/ko-KR/index/introducing-businesses-chatgpt/)
  OpenAI가 기업이 ChatGPT 안에서 비즈니스 소유권을 등록하고 정보를 관리하며 고객과 소통할 수 있는 기능을 베타로 공개함. ChatGPT가 검색·상거래 접점으로 확장되는 흐름임.
- [테크 기업들이 프라이버시 개념을 다시 바꾸려 함](https://www.eff.org/deeplinks/2026/11/tech-companies-are-trying-shift-entire-concept-privacy-again)
  EFF가 AI 스마트 안경·녹음형 웨어러블이 착용자 한 명의 선택으로 주변 사람의 대화와 행동까지 기록한다고 지적함. 프라이버시 문제가 물리적 일상으로 확장되고 있다고 경고함.

---
## 📅 이전 날짜

- [2026-11-15](data/2026-11-15.md)
- [2026-11-14](data/2026-11-14.md)
- [2026-11-13](data/2026-11-13.md)
- [2026-11-12](data/2026-11-12.md)
- [2026-11-11](data/2026-11-11.md)
- [2026-11-10](data/2026-11-10.md)
- [2026-11-09](data/2026-11-09.md)
- [2026-11-08](data/2026-11-08.md)
- [2026-11-07](data/2026-11-07.md)
- [2026-11-06](data/2026-11-06.md)
- [2026-11-05](data/2026-11-05.md)
- [2026-11-04](data/2026-11-04.md)
- [2026-11-03](data/2026-11-03.md)
- [2026-11-02](data/2026-11-02.md)
- [2026-11-01](data/2026-11-01.md)
- [2026-10-31](data/2026-10-31.md)
- [2026-10-30](data/2026-10-30.md)
- [2026-10-29](data/2026-10-29.md)
- [2026-10-28](data/2026-10-28.md)
- [2026-10-27](data/2026-10-27.md)
- [2026-10-26](data/2026-10-26.md)
- [2026-10-25](data/2026-10-25.md)
- [2026-10-24](data/2026-10-24.md)
- [2026-10-23](data/2026-10-23.md)
- [2026-10-22](data/2026-10-22.md)
- [2026-10-21](data/2026-10-21.md)
- [2026-10-20](data/2026-10-20.md)
- [2026-10-19](data/2026-10-19.md)
- [2026-10-18](data/2026-10-18.md)