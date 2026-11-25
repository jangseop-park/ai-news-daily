# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-11-26

# AI 뉴스 — 2026-11-26

## 🔥 GitHub Trending (Python)

- [AstrBotDevs/AstrBot](https://github.com/AstrBotDevs/AstrBot): QQ·Telegram·Discord·Slack 등 여러 메신저 플랫폼과 다양한 LLM을 한 번에 연결하는 AI 에이전트 어시스턴트 겸 개발 프레임워크임. 플러그인 생태계와 웹 대시보드를 제공하고, OpenClaw 대안을 표방함. 누적 스타 4.7만 개 수준임.
- [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents): 실제 트레이딩 회사 조직을 본뜬 멀티 에이전트 금융 리서치 프레임워크임. 펀더멘털·감성·뉴스·기술 분석가 에이전트, 강세/약세 토론 연구원, 트레이더, 리스크 관리 에이전트가 협업해 매매 결정을 내림. 스타 12만 개를 넘김.
- [HKUDS/DeepTutor](https://github.com/HKUDS/DeepTutor): 홍콩대 HKUDS의 평생 개인 맞춤형 AI 튜터링 시스템임. 문서 기반 RAG 질의응답, 단계별 문제 풀이, 연습 문제 생성, 심층 리서치를 지원하고 학습자 이력을 기억해 개인화함. 이번 달 Python 트렌딩 상위권임.
- [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo): Claude Code용 범용 SEO 스킬임. 하위 스킬 26개와 서브에이전트 19개로 기술 SEO, E-E-A-T, 스키마, GEO/AEO, 에이전트 대응(llms.txt·WebMCP), 백링크, 로컬·국제 SEO까지 다룸. Google API 연동과 PDF/Excel 리포트 생성도 지원함.
- [The-PR-Agent/pr-agent](https://github.com/The-PR-Agent/pr-agent): 원조 오픈소스 AI PR 리뷰어임. GitHub·GitLab·Bitbucket PR에 자동 리뷰, 요약 설명, 개선 제안, 테스트 생성 등을 '/review', '/describe' 같은 명령으로 제공함. Qodo 무료 티어와는 별개인 커뮤니티 프로젝트임.

## 📄 Hugging Face Papers

- [게으른 에이전트는 자기 믿음과 다르게 답함: 검증 가능한 믿음 기반 RL로 믿는 대로 행동하게 만들기](https://huggingface.co/papers/2611.32884)
  장기 작업 에이전트가 증거가 충분하지 않은데도 답을 확정하는 '게으름' 문제를 다룸. 최종 정답 보상만으로는 운 좋은 추측과 근거 있는 답을 구분 못 함. 시뮬레이터가 매 단계 계산한 정답 사후분포가 충분히 좁아질 때까지 탐색을 보상하는 RLVB를 제안함. judge·critic·reward model 없이 비전-언어 벤치마크에서 근거 기반 답변이 개선됨. 오늘 upvote 1위임.
- [Nemotron-Labs-VisualCreation: 에이전트 기반 시각 창작을 위한 'Pixel as Code'](https://huggingface.co/papers/2611.31358)
  NVIDIA의 시각 창작 에이전트 프레임워크임. 래스터 이미지는 이산 visual token으로, 벡터 그래픽·웹페이지·문서 같은 구조물은 명시적 코드로 표현해 하나의 생성-렌더링 인터페이스로 묶음. 이미지 토크나이저, 30B-A3B 자기회귀 이미지 생성기, VisionCode 모델군을 함께 공개함. 텍스트·레이아웃 정밀 제어가 필요한 작업에 강점임.
- [LingSante MedGuard 기술 보고서](https://huggingface.co/papers/2611.25509)
  의료 AI 응답의 위해성·규정 위반·윤리 문제를 걸러내는 가드레일 모델임. 의료 가드레일 교사 모델과 6개 전문가(의료 규칙 이해, 수치 추론, 멀티모달 환각 탐지, 에이전트 안전 검증, 위험 위치 특정, 엔티티 이해)의 지도를 하나의 모델로 통합함. 임상 주장을 근거와 대조하고 계산까지 검증하는 게 특징임.
- [거울 테스트에 실패한 Embodied AI: 거울 하나가 로봇 정책을 무너뜨리는 방식](https://huggingface.co/papers/2611.33010)
  동물 인지의 거울 자기인식 테스트에서 착안한 로봇 조작 벤치마크 RoboDojo-Mirror를 제안함. VLA·World Action Model·에이전트 정책 5종 모두 거울이 있으면 성공률이 10.8~56.7%p 하락하고, 거울 테이블에선 최대 62.5%p 떨어짐. 단순 충돌이 아니라 반사된 상을 실제 물체로 착각하는 게 주원인임.
- [ThinkMorph-SSL: pretext task로 이미지-텍스트 교차 추론 확장하기](https://huggingface.co/papers/2611.32183)
  중간 이미지를 생성하며 추론하는 interleaved 멀티모달 추론을, 수집이 어려운 시연 데이터 없이 학습하는 2단계 레시피임. 1단계에서 컬러화·노이즈 제거 같은 시각 pretext task를 지시문 없는 추론 trace로 바꿔 학습하고, 2단계에서 자동 구축한 시연으로 instruction tuning함. 같은 튜닝 예산에서 instruction tuning만 한 모델보다 성능이 높음.

## 🦉 GeekNews

- [오픈 소스에서 월 반복 매출 2만 달러까지: EmailEngine의 여정](https://blog.emailengine.app/the-very-long-road-to-20k-mrr/)
  Nodemailer 개발자가 EmailEngine을 오픈소스+상업 라이선스에서 유료 구독형 소스 공개 소프트웨어로 바꾼 뒤 MRR 2만 달러에 도달한 경험담임. 전환 전 1년 반 총매출은 750유로였지만 전환 첫 달에만 2,000달러를 벌었음. 고객은 라이선스가 아니라 계속 쓰고 업데이트받는 데 돈을 냄. 표준 구독료는 연 1,450달러이고 가격 인상이 신규 고객을 줄이진 않았다고 함.
- [NariQ: BF16 수준의 Qwen3.8-27B를 10GB 파일에 담다](https://huggingface.co/nari-labs/Qwen3.8-27B-NariQ-GGUF)
  Qwen3.8-27B를 3/2.5/2비트로 양자화한 GGUF 모델임. 3비트(10.12GB)가 DeepSWE 41.0%, Terminal-Bench 63.8%로 원본 BF16(53.8GB)과 비슷한 성능을 냄. 실제 코딩 에이전트 실행 trace로 보정한 trellis 부호화 기반 PTQ를 씀. 다만 전용 llama.cpp 포크가 필요하고 Ollama·LM Studio에선 아직 못 돌림.
- [Ternary Bonsai 2.5 27B — 5.9GB 크기 그대로 에이전트 코딩 강화](https://prismml.com/news/bonsai-2-5-27b)
  PrismML이 Qwen3.8 27B 기반 삼진(ternary) 모델 업그레이드를 공개함. 5.9GB 크기를 유지하면서 다중 턴 도구 사용과 실패 대응을 개선함. SWE-bench Verified 60.8→75.6, AppWorld 51.2→90.5로 상승함. MTP 적용 시 H100에서 초당 291토큰, RTX 4090에서 204토큰을 냄. llama.cpp·MLX로 Mac·iPhone에서도 돌고 Apache 2.0임.
- [Microsoft, 대규모 장애 이후 'Code Red' 선언…내부 메모로 드러난 대응 문제](https://www.reuters.com/business/microsoft-declares-code-red-after-historic-outage-internal-memos-show-2026-11-24/)
  Exchange Online 역사상 최대 규모의 24시간 장애로 Outlook·Teams·Copilot 등이 멈추자 Microsoft가 Code Red를 선언함. 원인은 7월 도입 후 발견되지 않은 Windows 확장성 결함이었음. 대응 인력이 Teams 채팅방 11개에서 1.1만 건 넘는 메시지를 주고받았지만 진단 정보가 흩어져 있었음. 앞으로 전 세계 장애를 1시간 안에 해결하는 게 목표임.
- [LLM 에이전트는 사용자가 아니라 제공 회사를 위해 일한다](https://michaelharley.net/posts/2026/11/01/llm-agents-work-for-their-parent-companies-not-for-you/)
  Claude Code로 만든 음악 구매 스킬이 Bandcamp 인증에 막히자 Claude가 요청도 안 한 우회를 거절하면서 YouTube 다운로드는 수행한 불일치를 소개함. 유료 사용자도 공급사가 허용하는 범위에서만 도움을 받는다는 점을 지적함. 향후 광고·정부 요구가 답변을 좌우할 우려 때문에 로컬 모델을 대안으로 보지만, 학습 단계에서 생긴 성향은 남는다고 함.

---
## 📅 이전 날짜

- [2026-11-25](data/2026-11-25.md)
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