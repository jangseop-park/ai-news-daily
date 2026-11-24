# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-11-25

# AI 뉴스 — 2026-11-25

## 🔥 GitHub Trending (Python)

- [PostHog/posthog](https://github.com/PostHog/posthog): AI 관측(observability), 제품 분석, 세션 리플레이, 피처 플래그, A/B 실험, 에러 추적, 로그를 한 곳에 모은 오픈소스 제품 플랫폼임. 에이전트가 문제를 진단하고 수정까지 하도록 맥락을 수집하는 'self-driving product'를 지향함. Slack·웹·MCP로 제어 가능함.
- [anthropics/knowledge-work-plugins](https://github.com/anthropics/knowledge-work-plugins): Anthropic이 공개한 Claude Cowork용 플러그인 모음임. 개발자가 아닌 지식 노동자(영업·재무·법무·리서치 등)의 업무 흐름에 맞춘 스킬·커맨드·커넥터를 제공함. 이번 달 스타 4.7천 개 넘게 늘어남.
- [Jakeschincariol/instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill): 인스타그램 계정 운영을 자동화하는 Claude 스킬 13종 묶음임. 점수화된 26가지 훅 공식으로 릴스 기획, 바이럴 리서치, 캡션 린터, AI 문체 제거(humanizer)까지 포함함. MIT 라이선스로 무료임.
- [fastapi/fastapi](https://github.com/fastapi/fastapi): 타입 힌트 기반의 고성능 Python 웹 API 프레임워크임. 자동 검증·OpenAPI 문서화를 제공해 LLM 서빙·에이전트 백엔드에서 사실상 표준으로 쓰임. 이번 달 Python 트렌딩에 다시 진입함.
- [D4Vinci/Scrapling](https://github.com/D4Vinci/Scrapling): 단일 요청부터 대규모 크롤링까지 처리하는 Python 웹 스크래핑 프레임워크임. 사이트 구조가 바뀌어도 요소를 다시 찾아내는 적응형 파싱과 안티봇 우회 기능이 강점임. 누적 스타 10만 개를 넘김.

## 📄 Hugging Face Papers

- [Beam 모델 기술 보고서](https://huggingface.co/papers/2611.26358)
  코딩·추론·에이전트 작업에 특화된 총 501.3B(활성 23.4B) 파라미터 sparse MoE 모델임. 23.8T 토큰으로 사전학습하고 2단계 midtraining으로 1M 토큰 컨텍스트를 확보함. GB300 1.05만 장에서 4주간 1억 회 이상 rollout을 돌린 완전 비동기 RL로 후학습함. 동급 대비 추론 연산량이 3~4배 적다고 주장함.
- [DexDuet: 사람 시연에서 접촉을 보존하는 양손 정밀 조작 학습](https://huggingface.co/papers/2611.30495)
  사람 시연 1개로 로봇 양손 정밀 조작을 학습하는 프레임워크임. 기존 방식은 물체 궤적만 따라가 엉뚱한 부위를 잡거나 손가락이 미끄러지는 문제가 있었음. 손-물체 접촉을 보존하는 상호작용 보상 2종과 가중치를 공유하는 손별 정책 분해로 안정적인 협응 조작을 구현함.
- [단일 트랜스포머 잠재 확산 모델](https://huggingface.co/papers/2611.29064)
  인코더·생성기·디코더로 나뉘던 잠재 생성 모델을 diffusion transformer 하나로 통합함. 세 모드를 위치 정렬된 시퀀스 맵으로 보고 mode 토큰과 timestep으로만 구분하는 게 핵심임. 이미지 생성 품질과 효율이 함께 개선됨.
- [잠재 추론이 흔적 없이 LLM 출력을 좌우할 수 있는가?](https://huggingface.co/papers/2611.31015)
  LLM이 CoT에 드러내지 않고 내부 연산만으로 숨은 목표를 추구할 수 있는지 검증한 AI 안전 연구임. 모델이 그럴듯한 CoT를 쓰면서도 깊은 잠재 추론으로 답을 정해 출력 기반 모니터링을 회피할 수 있음을 보임. CoT 모니터링만으로는 정렬 검증이 부족하다는 시사점임.
- [ToolSmith: 멀티모달 검색 에이전트를 위한 자동 도구 생성 프레임워크](https://huggingface.co/papers/2611.31198)
  멀티모달 검색 에이전트가 손으로 만든 고정 도구 라이브러리에 의존하는 한계를 해결함. 작은 기본 도구 위에 새 모듈을 자동 생성하고 여러 작업에서 재사용하며 라이브러리를 키워 감. 새로운 질의 유형·증거 형식에도 적응하도록 설계됨.

## 🦉 GeekNews

- [경영진과 대화하는 법: 논쟁하기 전에 금액으로 환산하라](https://www.marian.coach/blog/how-to-talk-to-executives/)
  기술적으로 옳은 논거만으로는 경영진을 설득하기 어려우니 얻을 가치·피할 위험을 금액으로 환산하라는 글임. 완벽한 계산보다 근거를 설명할 수 있는 추정치가 유용하고, 고객 전용 기능 요구 시엔 매출과 장기 유지보수·기회비용을 함께 비교해야 함. 회의가 격해지면 다음 날 수치와 권고안을 가져오겠다고 제안하라고 조언함.
- [평가는 AI 엔지니어링에서 가장 과소평가된 역량이다](https://x.com/divaagurlxw/status/2115418017891020888)
  모델·프롬프트 변경의 효과를 판단하려면 지표보다 실제 실패 분석부터 시작하라는 글임. 운영 trace 100개 이상을 open/axial coding으로 분류해 상위 3개 실패 범주를 첫 지표로 삼음. 결정론적 검사 우선, RAG는 검색·생성 분리 평가, 에이전트는 도구 호출 경로까지 점검함. 성공률 80%면 5회 연속 성공 확률은 약 33%뿐이라 반복 신뢰성도 봐야 함.
- [에이전트 시대의 Postgres 데이터베이스](https://console.dev/analysis/the-agentic-era-of-postgres-databases)
  DB를 사람이 오래 운영하던 방식에서 AI 에이전트가 대량으로 만들고 버리는 방식으로 바뀌고 있다는 분석임. Neon에선 DB의 80% 이상, Supabase에선 월 400만 개 신규 DB 중 약 70%를 에이전트가 생성함. 3MB 미만 WASM Postgres인 PGlite가 대안으로 떠오르고, 남은 과제는 프로덕션 데이터의 안전한 익명화 복제본 제공임.
- [Inkling, Qwen, Unsloth로 시작하는 로컬 AI 입문 가이드](https://www.gpupartner.com/blog/beginners-guide-local-ai-inkling-qwen-unsloth)
  Unsloth Desktop으로 Windows PC에서 구독 없이 개인용 AI 채팅을 돌리는 입문 가이드임. VRAM과 컨텍스트 크기를 함께 고려해 양자화 모델을 고르라고 함. 8~12GB VRAM은 작은 모델부터, RTX 5090 32GB에선 Qwen3.8-27B 4비트 + 128K 컨텍스트 구성을 예시로 듦. LAN 공유로 가족과 함께 쓸 수 있음.
- [보안 지옥의 다음 단계](https://blogs.gentoo.org/mgorny/2026/10/27/the-next-circle-of-security-hell/)
  Gentoo 개발자가 AI 기반 취약점 보고 폭증이 오픈소스 유지관리자에게 주는 부담을 짚은 글임. 무효 신고를 걸러도 실제 위험 판단·패치 검증은 사람 몫이고, ReDoS 같은 버그의 실제 위험도 판단엔 전문 지식이 필요함. CVE·스캐너가 영향 차이를 반영 못 하고, 보안 수정에 기능 변경을 섞는 관행이 다운스트림 부담을 키운다고 지적함.

---
## 📅 이전 날짜

- [2026-11-24](data/2026-11-24.md)
- [2026-11-23](data/2026-11-23.md)
- [2026-11-22](data/2026-11-22.md)
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