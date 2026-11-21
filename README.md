# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-11-22

# AI 뉴스 — 2026-11-22

## 🔥 GitHub Trending (Python)

- [github/spec-kit](https://github.com/github/spec-kit): GitHub이 만든 스펙 주도 개발(SDD) 툴킷임. 요구사항 명세를 먼저 쓰고 코딩 에이전트가 그 스펙대로 구현하도록 흐름을 잡아줌.
- [awslabs/cli-agent-orchestrator](https://github.com/awslabs/cli-agent-orchestrator): Claude Code, Kiro, Codex 같은 AI 코딩 CLI 여러 개를 격리된 tmux 세션에서 동시에 조율하는 멀티 에이전트 오케스트레이션 도구임. AWS Labs 공개.
- [agentscope-ai/agentscope](https://github.com/agentscope-ai/agentscope): 동작 과정을 눈으로 보고 이해·신뢰할 수 있게 만든 에이전트 개발·실행 프레임워크임. 멀티 에이전트 구성과 추적 기능을 제공함.
- [pytorch/torchtitan](https://github.com/pytorch/torchtitan): PyTorch 공식 생성형 AI 모델 대규모 학습 플랫폼임. FSDP·텐서/파이프라인 병렬화 등을 PyTorch 네이티브로 조합해 LLM 사전학습을 돌릴 수 있음.
- [XiaoYouChR/Ghost-Downloader-3](https://github.com/XiaoYouChR/Ghost-Downloader-3): 멀티스레드 가속을 지원하는 크로스플랫폼 다운로더임. 하루 774스타를 받으며 급상승함.

## 📄 Hugging Face Papers

- [언어 모델은 스스로 자기 가중치를 고쳐 쓸 수 있다](https://huggingface.co/papers/2611.21885)
  27B 모델에게 자기 가중치·채점 결과·자기 실행 권한을 주면, gradient나 학습 없이 추론만으로 실패 원인을 진단하고 해당 가중치를 직접 수정함(self-rewriting). 처음 보는 490문제에서 정확도가 6.6%p 오름. 자체 테스트로 검증된 수정만 제출하며 반복할수록 계속 개선됨.
- [Vision-Language-Action 모델에게 안전하게 멈추는 법 가르치기](https://huggingface.co/papers/2611.26239)
  금지된 작업을 처음부터 거부하는 VLA 정책도 작업 도중에 넘겨받으면 끝까지 수행해버리고, 멈추더라도 쥔 물체를 떨어뜨리는 문제가 있음. 정지 상태의 팔 명령과 일관된 그리퍼 목표를 학습시키는 SAFI(State-Aware Fallback Imitation)를 제안해 실행 중에도 안전하게 정지·유지하게 함.
- [System 1 에이전트: 로컬에서 빠르고 신뢰할 수 있는 에이전틱 AI](https://huggingface.co/papers/2611.21053)
  tool schema와 요청을 결정적 컴파일러로 객관식 질문으로 바꾸고, 원패스 결정 모델이 답하게 해서 텍스트 생성 없이 도구를 호출함. 157개 의료 도구·1,952개 요청에서 도구 선택 정확도 97.0%로 로컬 LLM 에이전트 18개 설정을 모두 앞섬. 지어낸 값(hallucination)이 0건임.
- [LLM 안의 CPU: 학습 없이 정확한 회로를 사전학습 가중치에 컴파일](https://huggingface.co/papers/2611.26450)
  학습 데이터·fine-tuning·외부 도구 없이 닫힌 형태(closed-form) 수식만으로 정확한 다자리 산술 회로를 사전학습 LM 가중치에 이식하는 기법임. RMSNorm 스케일 문제를 수학적으로 상쇄하면서 자연어 능력은 그대로 유지함.
- [Probing과 Steering은 같은 방향을 선호하는가](https://huggingface.co/papers/2611.19499)
  개념을 가장 잘 탐지하는 hidden state 방향(probe)과 모델을 그 개념으로 가장 잘 이끄는 방향(steering)이 다르다는 걸 3개 모델에서 보임. steering은 평균 차(mean difference)에 가까운 방향을 선호하며, 60개 조합 중 59개에서 이 차이가 유지됨.

## 🦉 GeekNews

- [우리는 개발자들에게 알리지도 않고 아키텍트로 승진시켰다](https://manidoraisamy.com/developer-to-architect.html)
  AI에 요구사항만 주고 아키텍처를 지정하지 않으면 성능·데이터 설계 결정까지 AI에 맡기게 된다는 글임. Google Forms 애드온 사례로, 이제 개발자에게 필요한 역량은 구현보다 설계 판단이라고 주장함.
- [Anthropic 수학자, Claude와 리만 가설·일반화 리만 가설 증명 발표](https://alpo.ge/remark.pdf)
  Anthropic의 수학자 Levent Alpöge가 Claude와 함께 리만 가설과 일반화 리만 가설(GRH)의 증명을 찾았다고 PDF로 발표함. 아직 수학계 검증 전 단계라 결과는 지켜봐야 함.
- [항상 작동하는 에이전트 구축하기](https://claude.com/ko/resources/articles/building-always-on-agents)
  상시 작동 에이전트는 세션 간 맥락을 유지하고 사람 감독 없이 행동하지만, 실제로는 대부분 대기하다 이벤트가 오면 짧게 실행되는 구조임. 트리거·상태 저장·권한 설계 방법을 정리한 Anthropic 가이드임.
- [Inkling 2 Mini - 노트북에서 실행하는 반복형 트랜스포머 모델](https://thinkingmachines.ai/news/inkling-2-mini/)
  Thinking Machines Lab이 Inkling 2 Mini를 오픈 웨이트로 공개함. 총 264억 파라미터지만 약 20GB 메모리로 노트북에서도 로컬 실행 가능한 반복형(recurrent) 트랜스포머 구조임.
- [Codex로 일하는 새로운 방식 [영상]](https://www.youtube.com/watch?v=IPh9YsWvDQk)
  Codex 하네스가 CLI, 데스크톱 앱, ChatGPT, Slack, Agents API로 확장되며 로컬 코딩뿐 아니라 클라우드 장기 작업과 여러 업무 도구 연동까지 다루게 됐다는 OpenAI 영상임.

---
## 📅 이전 날짜

- [2026-11-21](data/2026-11-21.md)
- [2026-11-20](data/2026-11-20.md)
- [2026-11-18](data/2026-11-18.md)
- [2026-11-17](data/2026-11-17.md)
- [2026-11-16](data/2026-11-16.md)
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