# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-11-24

# AI 뉴스 — 2026-11-24

## 🔥 GitHub Trending (Python)

- [odoo/odoo](https://github.com/odoo/odoo): CRM·회계·재고·이커머스·인사 등 비즈니스 앱을 한 플랫폼에 모은 오픈소스 ERP임. Python 기반 모듈 구조라 필요한 앱만 골라 설치·확장 가능함.
- [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp): DaVinci Resolve Studio를 MCP 서버로 연결해 Claude 같은 AI 에이전트가 타임라인·미디어 풀·렌더링을 직접 조작하게 해줌. 영상 편집 자동화용임.
- [wshobson/agents](https://github.com/wshobson/agents): Claude Code·Codex CLI·Cursor·Copilot 등 여러 코딩 에이전트용 플러그인·에이전트·스킬·커맨드를 한 번 작성해 공통으로 쓰게 한 모음집임.
- [anthropics/skills](https://github.com/anthropics/skills): Anthropic이 공개한 Agent Skills 공식 레포임. 문서 작성·데이터 처리 등 Claude에 붙여 쓸 수 있는 스킬 예제와 템플릿 제공함. 이번 주 스타 3.8k 증가함.
- [soxoj/maigret](https://github.com/soxoj/maigret): 사용자명 하나로 6천여 개 사이트를 조회해 계정 존재 여부와 프로필 정보를 모아 보고서로 만드는 OSINT 도구임. 보안 조사·신원 확인용으로 쓰임.

## 📄 Hugging Face Papers

- [cmHC: 기하학적 수축으로 Hyper-Connections의 스트림 혼합 균형 맞추기](https://huggingface.co/papers/2611.27193)
  잔차 연결을 여러 스트림으로 확장한 mHC에서 혼합 행렬이 Birkhoff polytope의 꼭짓점 쪽이면 스트림이 따로 놀고, 중심 쪽이면 스트림 구분이 사라지는 트레이드오프를 이론적으로 밝힘. 기하학적 수축으로 혼합 정도를 조절하는 cmHC를 제안해 dense·MoE 대규모 사전학습의 안정성과 확장성을 개선함.
- [물체를 뚫고 지나가지 않는 월드 모델](https://huggingface.co/papers/2611.27963)
  인터랙티브 비디오 월드 모델이 장애물을 뚫고 지나가는 물리 오류를 평가하는 NoPeBench를 공개함. 오픈소스 모델 모두 실패하지만 DiT 은닉 상태에 관통 여부 정보가 이미 담겨 있음을 발견함. 고정된 DiT 위에 작은 예측 헤드를 붙인 NoPeWorld로 위험 행동을 안전한 행동으로 바꿔 물리 위반을 줄이고 zero-shot 일반화도 됨.
- [Clover-35B-A3B-Preview 기술 보고서](https://huggingface.co/papers/2611.24636)
  총 35B·활성 3B 파라미터의 MoE 확산(diffusion) 언어모델로 thinking 모드를 지원함. Gated Delta Networks를 block diffusion에 접목해 과거 문맥은 순환 메모리로, 현재 블록은 양방향 attention으로 처리함. SWE-bench Verified 73.6, Terminal-Bench 2.1 51.7을 기록했고 GB300 GPU 한 장에서 초당 680토큰 생성 속도를 보고함.
- [읽을 수 없는 글자 읽기: 텍스트 인식 초해상도에는 추론이 필요함](https://huggingface.co/papers/2611.15449)
  심하게 뭉개진 글자는 주변 픽셀만으로 복원이 안 되고 문맥·상식 추론이 필요하다는 문제를 제기함. 추론이 필요한 텍스트를 구분한 벤치마크 ReasonText와 검출 오류를 배제한 지표 GTTCA를 제안함. 최신 SR 모델 12개 모두 추론 필요 텍스트에서 성능이 크게 떨어짐을 확인함.
- [On-Policy 자기 증류로 라벨 없는 영상에서 미래 예측 추론 학습](https://huggingface.co/papers/2611.26954)
  VLM이 현재 영상에서 다음 사건·행동을 예측하도록, 과거-미래 영상 쌍을 자기지도 신호로 쓰는 on-policy self-distillation 프레임워크 Future-OPSD를 제안함. foresight score 기반 대조 이점으로 미래 클립 중 정말 중요한 정보만 배우게 해 추가 주석이나 LLM 감독 없이 예측·계획 성능을 높임.

## 🦉 GeekNews

- [HUMAN.md - AI 시대 창작자를 위한 선언문](https://www.human-md.ai/)
  AI 시대에 창작자가 지켜야 할 태도를 정리한 선언문임. 인간의 가치는 안목뿐 아니라 의도적인 규칙 파괴, 뜻밖의 경험에서 얻는 영감, 사람을 위한 창작에 있다고 강조함.
- [Fast-Anything: 전체를 Rust로 재작성하지 말고, 느린 5%만 재작성하라](https://github.com/EL4CTEO/fast-anything)
  앱의 병목 함수를 찾아 코딩 에이전트가 그 함수만 Rust로 이식하게 하는 도구임. 실제 호출 기록으로 결과가 같은지 검증한 뒤 교체해 안전하게 성능을 끌어올림.
- [AI 시대, 컴퓨터공학과 소프트웨어공학적 사고의 가치](https://okky.kr/articles/1566284)
  바이브 코딩 확산으로 CS 전공이 무의미하다는 주장이 늘지만, 시스템을 설계하고 문제를 구조화하는 공학적 사고는 AI 시대에 오히려 더 중요해진다고 주장하는 글임.
- [이제 우리는 모두 주니어 인재다](https://tomtunguz.com/we-are-all-junior-talent-now/)
  AI의 진짜 가치는 같은 일을 빨리 하는 효율화가 아니라 회사가 할 수 있는 일 자체를 재구상하는 데 있다고 봄. AI와 일하는 방식이 너무 빨리 바뀌어 경력과 상관없이 모두가 다시 배우는 주니어 입장이 됐다고 지적함.
- [내 미술 작품 웹사이트의 기술 아키텍처가 꽤 마음에 든다](https://klauria.tech/klauria-art/)
  방문자에게는 정적 사이트처럼 빠르게 서빙하면서, 운영자는 웹 기반 CRUD UI로 작품과 메타데이터를 수정하게 만든 미술 작품 사이트 구조를 소개함. 단순하지만 실용적인 하이브리드 설계 사례임.

---
## 📅 이전 날짜

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
- [2026-10-25](data/2026-10-25.md)