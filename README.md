# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-11-17

# AI 뉴스 — 2026-11-17

## 🔥 GitHub Trending (Python)

- [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill): 코딩 에이전트용 로컬 영상 편집 도구임. FFmpeg 도구 42종을 기계가 읽을 수 있는 계약과 MCP 서버로 묶어 Claude Code·Cursor·Codex에서 컷 편집, 자막, 리프레이밍, 음량 조정, 플랫폼별 내보내기를 처리함. 클라우드·API 키 없이 동작함.
- [ifixai-ai/iFixAi](https://github.com/ifixai-ai/iFixAi): AI 에이전트 독립 감사 도구임. 사람이 직접 돌리거나 에이전트가 스스로 실행해서 '에이전트가 해야 할 일을 제대로 하고 있는가'를 120초 안에 점검함.
- [google-research/paper-orchestra](https://github.com/google-research/paper-orchestra): Google Research의 AI 연구 논문 자동 작성용 multi-agent 프레임워크임. 여러 에이전트가 역할을 나눠 논문 초안 작성 과정을 자동화함.
- [mvanhorn/last30days-skill](https://github.com/mvanhorn/last30days-skill): 어떤 주제든 Reddit, X, YouTube, HN, Polymarket, 웹을 훑어 최근 30일 동향을 조사하고 근거 기반 요약으로 정리해주는 AI 에이전트 skill임.
- [isair/jarvis](https://github.com/isair/jarvis): 100% 로컬에서 도는 개인용 데스크톱 AI 비서임. 대화에 끼어들 수 있고 MCP 도구·자가학습 메모리를 무제한 지원함. WisprFlow 대체용 받아쓰기 기능도 있으며 macOS·Windows·Linux에서 실행됨.

## 📄 Hugging Face Papers

- [MIRIX-2.0: 멀티 에이전트 메모리 시스템](https://huggingface.co/papers/2611.12068)
  LLM 에이전트의 장기 메모리를 실용성·정확도·효율 모두 잡도록 설계한 multi-agent 메모리 시스템임. 파라메트릭 메모리의 학습 부담, 통합 시 정보 손실, 전체 기록 저장 시 검색 비용 문제를 함께 해결하려 함. 비교 시스템 중 QA 벤치마크 5개 중 4개에서 최고 정확도이며 LoCoMo 91.4%, LongMemEval-S 72.6% 달성함.
- [V-JEPA-LM: 정적 텍스트 정렬 표현을 넘어 동역학을 읽는 Video-Language 모델](https://huggingface.co/papers/2611.17831)
  V-JEPA 같은 world-model 영상 인코더는 방향·속도·순서·상태 변화를 학습하지만, 캡션/QA로 LLM과 붙이면 질문에 언급된 속성만 찾아 쓰고 동역학 정보는 버려진다는 문제를 지적함. 예컨대 frozen V-JEPA 특징에서 linear probe로는 속도를 87% 읽어내는데 VLM은 이를 못 씀. 인코더의 동역학을 실제로 읽도록 학습하는 방법을 제안함.
- [DySENSE: 위성 영상 기반 동적 시공간 에너지 합성·에뮬레이션](https://huggingface.co/papers/2611.17878)
  도시는 세계 에너지의 2/3, CO2 배출의 70% 이상을 차지함. 기존 연구는 기존 도시 예측 위주이고 세밀한 월별 에너지 데이터가 부족함. 위성 영상으로 미래 도시의 월별 동적 에너지 소비를 생성(generative)·에뮬레이션하는 프레임워크를 제안함.
- [G-CAST: 변화하는 요구에 대응하는 이커머스 에이전트의 통제된 지속 자기학습](https://huggingface.co/papers/2611.17814)
  쇼핑 대화 에이전트는 신규 카테고리·구매 시나리오 등 사용자 요구와 도구·skill·운영 절차(harness)가 계속 바뀜. 이런 변화 속에서 기존 능력을 해치지 않으면서 안전하게 지속 자기학습하도록 거버넌스를 둔 학습 프레임워크를 제안함.
- [Mobile AI Factory: 내 스마트폰 전용 특화 언어모델 만들기](https://huggingface.co/papers/2611.13509)
  온디바이스 SLM은 프라이버시·오프라인 장점이 있지만 작업·기기에 맞춘 파인튜닝과 크기 조정에 전문가 반복 작업이 필요함. 작업 명세와 대상 폰만 주면 orchestrator LLM이 하이퍼파라미터 튜닝, 데이터 마이닝 등을 스스로 결정해 파인튜닝·양자화된 SLM을 자동 생성하는 agentic 시스템임.

## 🦉 GeekNews

- [X.com을 처음부터 다시 구축하기 - 서버 3개를 하나로](https://blog.x.com/en/engineering/rebuilding-the-global-town-square-from-scratch)
  X가 기존 웹앱을 엔지니어 5명과 AI 코딩 에이전트로 6개월 안에 재구축함. 사용자용·검색 크롤러용·링크 미리보기용으로 나뉘어 있던 서버 3개를 하나로 통합함.
- [이제 거의 무엇이든 만들 수 있다. 무엇을 만들 가치가 있을까?](https://zchmael.substack.com/p/i-can-build-almost-anything-now-whats)
  AI 덕분에 더 많은 아이디어를 구현할 수 있게 됐지만, 만드는 즐거움과 계속 운영할 책임은 별개의 선택이라는 글임. 학습용·개인 도구·서비스 등 프로젝트 성격별로 무엇을 만들고 유지할지 판단 기준을 제시함.
- [DBDelve - Rust와 GPUI로 만든 가벼운 오픈소스 DB 클라이언트](https://github.com/ShayanAbbas1/dbdelve)
  Zed 에디터의 GPU 가속 UI 프레임워크 GPUI로 만든 Rust DB 클라이언트임. 같은 UI 코드로 맥/윈도우/리눅스에서 네이티브 실행되며 PostgreSQL 등을 지원함.
- [실전파 컴퓨터 과학자를 위한 도서 목록](https://nick-black.com/dankwiki/index.php?title=Book_list_for_streetfighting_computer_scientists)
  2025년판 추천 도서 목록임. 흔한 코딩 관행서 대신 언어, 운영체제, 네트워크, 알고리듬, 계산 이론을 깊이 익히는 책 위주로 구성됨.
- [AI 시대, 새로운 게임 개발자는 어떻게 탄생할까](https://www.a16z.news/p/gamings-next-origin-stories)
  a16z 글임. AI는 인디 개발자·도구 제작자·월드 빌딩 스튜디오를 대체하기보다 셋 모두의 작업을 가속한다고 봄. AI 에이전트가 Blender로 에셋을 만드는 등 새 개발 흐름을 소개함.

---
## 📅 이전 날짜

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
- [2026-10-22](data/2026-10-22.md)
- [2026-10-21](data/2026-10-21.md)
- [2026-10-20](data/2026-10-20.md)
- [2026-10-19](data/2026-10-19.md)