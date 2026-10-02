# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-10-03

# AI 뉴스 — 2026-10-03

## 🔥 GitHub Trending (Python)

- [Panniantong/Agent-Reach](https://github.com/Panniantong/Agent-Reach): AI 에이전트에게 인터넷 전체를 보는 눈을 달아주는 CLI임. Twitter·Reddit·YouTube·GitHub·Bilibili·샤오홍슈를 API 비용 없이 읽고 검색함.
- [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector): AI 에이전트 스킬용 보안 스캐너임. Claude Code·Codex·MCP 스킬을 설치하기 전에 취약점, 악성 패턴, 프롬프트 인젝션, 데이터 유출, 공급망 위험을 탐지함.
- [tile-ai/tilelang](https://github.com/tile-ai/tilelang): 고성능 GPU/CPU/가속기 커널 개발을 간소화하는 도메인 특화 언어(DSL)임. 타일 단위 추상화로 커널 작성 생산성을 높임.
- [Friedrich-M/UniMate](https://github.com/Friedrich-M/UniMate): SIGGRAPH Asia 2026 논문 코드임. 다양한 스켈레톤 구조의 캐릭터를 하나의 통합 모델로 애니메이션함.
- [getsentry/sentry](https://github.com/getsentry/sentry): 개발자 중심의 에러 트래킹·성능 모니터링 플랫폼임. 앱 오류를 실시간으로 수집하고 원인을 추적함.

## 📄 Hugging Face Papers

- [On-Policy vs Off-Policy 학습? 증류 역학에 대한 체계적 연구](https://huggingface.co/papers/2609.35259)
  기존 SFT와 RL 비교는 여러 변수가 동시에 바뀌어 롤아웃 정책의 효과를 분리하기 어려웠음. 롤아웃 정책만 통제해 on-policy 학습이 망각 감소·희소 업데이트·일반화에 실제로 기여하는지 체계적으로 검증함.
- [Looped Transformer를 (거의) 공짜로 더 잘 디코딩하기](https://huggingface.co/papers/2610.02185)
  Looped Transformer는 공유 블록을 반복 실행해 파라미터 효율을 얻지만, 표준 디코딩은 초기 루프의 중간 상태를 버림. 약한 초기 루프와 강한 후기 루프 예측을 정렬해 추가 비용 거의 없이 디코딩 품질을 높임.
- [X-Tree: 재사용 가능한 경험을 토큰화해 효율적인 에이전트 일반화 달성](https://huggingface.co/papers/2609.32993)
  SFT·RLVR은 모든 토큰을 균일하게 다뤄 작업 간 반복되는 서브 프로시저 구조를 무시함. 재사용 가능한 루틴을 토큰화해 계층적으로 학습시켜 적은 궤적으로도 에이전트 일반화를 높임.
- [비디오 생성 모델: 사후 학습과 정렬에 대한 서베이](https://huggingface.co/papers/2610.00812)
  대규모 사전학습된 비디오 모델도 인간 의도 추종, 시간적 일관성, 물리·안전 제약을 잘 못 지킴. 비디오 생성 모델의 사후 학습(post-training)과 정렬 기법을 체계적으로 정리함.
- [Where-OPD: 합성 장면으로 공간 유도하는 MLLM의 On-Policy 자기증류](https://huggingface.co/papers/2610.02117)
  언어 모델에서 효과적인 on-policy 자기증류를 멀티모달 LLM으로 확장함. 합성 장면으로 공간 정보를 특권 입력으로 주어 교사 역할을 하게 하고, 공간 추론 능력을 끌어올림.

## 🦉 GeekNews

- [벡터 데이터베이스여, 안녕](https://turbopuffer.com/blog/rip-vector-database)
  turbopuffer가 벡터 검색 전용 DB에서 다양한 검색·집계를 처리하는 범용 검색 엔진으로 확장함. v3에서 데이터 저장 구조를 개편 중이며 '벡터 DB'라는 카테고리 자체가 사라지는 흐름을 짚음.
- [바이브 코딩한 웹사이트를 디자이너가 만든 것처럼 보이게 한 방법](https://railcode.dev/blog/vibe-coded-website)
  코딩 에이전트로 개성 있는 웹사이트를 만들려면 한 번에 좋은 결과를 기대하기보다 여러 시안에서 마음에 드는 요소를 골라 반복적으로 다듬어야 함. 구체적인 반복 워크플로를 공유함.
- [AI 네이티브 회사에서 일한다는 것](https://www.elenaverna.com/p/what-its-like-to-work-at-an-ai-native)
  Lovable에서는 AI가 개별 생산성 향상에 그치지 않고 직무 경계, 의사결정, 정보 흐름, '일을 잘한다'는 기준까지 바꾸고 있음. 세분화된 역할이 사라지고 제너럴리스트가 부상함.
- [AI는 어떻게 여기까지 왔고 어디로 가는 중인가](https://substack.com/home/post/p-216691876)
  VC 투자자 Akshay Mehra의 글임. 5년 전 마켓플레이스·버티컬 SaaS·네오뱅크 피치가 넘쳤던 시장이 자본 집약적 AI 인프라 중심으로 재편된 과정을 짚고, 다음 투자 기회를 전망함.
- [Pi Durable - 중단된 작업을 이어가는 AI 에이전트 하네스](https://earendil.com/posts/pi-durable/)
  장시간 실행되는 AI 에이전트 앱을 위한 실험적 하네스임. 터미널 코딩 에이전트 Pi 1.0과 별도로 공개됐으며, 작업 상태를 저장해 프로세스가 중단돼도 이어서 실행할 수 있게 함.

---
## 📅 이전 날짜

- [2026-10-02](data/2026-10-02.md)
- [2026-10-01](data/2026-10-01.md)
- [2026-09-30](data/2026-09-30.md)
- [2026-09-29](data/2026-09-29.md)
- [2026-09-28](data/2026-09-28.md)
- [2026-09-27](data/2026-09-27.md)
- [2026-09-26](data/2026-09-26.md)
- [2026-09-22](data/2026-09-22.md)
- [2026-09-21](data/2026-09-21.md)
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