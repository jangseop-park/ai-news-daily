# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-11-18

# AI 뉴스 — 2026-11-18

## 🔥 GitHub Trending (Python)

- [jingyaogong/minimind](https://github.com/jingyaogong/minimind): 64M 파라미터 LLM을 단 2시간 만에 처음부터 학습시키는 오픈소스 프로젝트임. 토크나이저·사전학습·SFT·RLHF까지 전 과정을 순수 PyTorch로 구현해 LLM 구조를 바닥부터 익히기 좋음.
- [usestrix/strix](https://github.com/usestrix/strix): 앱 취약점을 찾아 고쳐주는 오픈소스 AI 모의해킹(penetration testing) 도구임. AI 에이전트가 해커처럼 앱을 동적으로 공격해보고 실제 PoC로 검증함.
- [virgiliojr94/book-to-skill](https://github.com/virgiliojr94/book-to-skill): 기술 서적 PDF를 Claude Code skill로 바꿔주는 도구임. 작업 중에 책 내용을 참고·학습·활용할 수 있게 됨.
- [dograh-hq/dograh](https://github.com/dograh-hq/dograh): Vapi·Retell을 대체하는 셀프호스팅 오픈소스 음성 AI 플랫폼임. 온프레미스·BYOK로 Speech-to-Speech 또는 LLM/STT/TTS 조합을 쓸 수 있고, 시각적 워크플로 빌더·MCP·전화 연동을 지원함.
- [ComposioHQ/awesome-claude-skills](https://github.com/ComposioHQ/awesome-claude-skills): Claude 워크플로를 커스터마이즈하는 Claude Skills, 리소스, 도구를 모아둔 큐레이션 목록임.

## 📄 Hugging Face Papers

- [Sage S2.1 Flash 기술 보고서](https://huggingface.co/papers/2611.21072)
  과학적 근거 위에서 추론하고 인터랙티브 환경에서 행동하도록 설계된 320B 파라미터 범용 MoE 모델임. 분자 그래프·생물 서열 전용 인코더를 두고 스펙트럼은 측정값 패치 시퀀스로 표현함. 모달리티별 projector가 공유 backbone 입력 공간으로 매핑해 텍스트와 함께 처리함. 오늘 업보트 압도적 1위임.
- [SALA: 의미 정렬 잠재 행동으로 embodied foundation 모델의 이중 축 스케일링](https://huggingface.co/papers/2611.17110)
  로봇 상호작용 데이터는 수집 비용이 커서 1인칭 인간 영상을 latent action model(LAM)로 활용하는 방법이 주목받음. 잠재 행동을 의미적으로 정렬해 인간 영상과 로봇 데이터 양쪽 축으로 함께 스케일링할 수 있게 함. 픽셀 예측이 없어 world-action model보다 학습·추론 효율이 좋음.
- [Termination Lag: 코딩 에이전트는 일찍 풀고 늦게 멈춤](https://huggingface.co/papers/2611.14960)
  코딩 에이전트가 첫 정답 패치를 만든 뒤 실행을 끝내기까지의 단계 수(termination lag)를 모델 5종·프레임워크 2종·SWE-bench 3종에서 측정함. 성공 실행의 38~82%가 첫 소스 편집에서 이미 정답에 도달함. 불필요한 후속 단계가 비용만 키운다는 점을 보여줌.
- [OutfitterBench: 장기 자원 배분·약속 조율에서 LLM 에이전트 평가](https://huggingface.co/papers/2611.17933)
  에이전트의 선택이 미래 제약을 만드는 장기 과제(한정된 용량 약속, 기회비용 비교)를 평가하는 벤치마크임. 계획 실행 가능성 유지와 대안 대비 자원 배분 가치 판단 능력을 측정함.
- [Craftax에서 continuation 기반 LLM 진화로 프로그램 정책과 목표 컴파일러 만들기](https://huggingface.co/papers/2611.19537)
  코딩 에이전트가 시뮬레이터 피드백으로 코드 기반 정책을 합성하면 추론 시 모델 호출이 0회임. 장기 과제에서 국소 개선이 최종 성공을 해치는 문제와 목표 변경 시 재합성 비용 문제를 피드백 cascade와 goal compiler로 해결함.

## 🦉 GeekNews

- [Modern Web Guidance 1.0 - 코딩 에이전트에 최신 웹 개발 지침을 제공하는 스킬 모음](https://developer.chrome.com/blog/modern-web-guidance-v1?hl=ko)
  크롬팀이 코딩 에이전트에 웹 플랫폼 전문 지식, 권장사항, 브라우저 호환성 데이터를 제공하는 스킬 모음 1.0을 공개함. 에이전트가 성능·접근성·보안 측면에서 최신 모범 사례대로 코드를 짜게 도와줌.
- [AI 슬롭은 왜 이렇게 읽기 짜증날까?](https://zonderlabs.com/slop)
  AI 슬롭이 읽기 괴로운 이유는 불명확한 글쓰기에 있다는 분석임. 단어는 다 알아도 누가 무엇을 했는지, 요점이 무엇인지 다시 짚어야 하는 문장이 많다는 점을 사례로 짚음.
- [소프트웨어가 구조적으로 무너지고 있다](https://www.breck-mckye.com/blog/2026/11/software-is-breaking-down-at-a-systemic-level/)
  최근 Microsoft 서비스 장애와 PHP2Shell은 직접 원인은 다르지만, 서비스들이 복잡하게 얽혀 한 곳의 문제가 넓게 번진다는 공통점이 있다고 지적함. 소프트웨어 생태계의 구조적 취약성을 경고함.
- [Rust가 개발자로서의 나를 바꾼 방식](https://blog.startifact.com/posts/how-rust-changed-me/)
  Rust를 6년 넘게 쓰고 4년 이상 실무에 적용한 경험담임. 합 타입, 정적 디스패치, 소유권 등을 통해 타입·추상화·성능을 생각하는 방식이 달라졌다고 정리함.
- [새로운 풀스택 디자이너 - Figma 스케치에서 작동하는 데모까지](https://www.ycombinator.com/library/gc-the-new-full-stack-designer)
  AI가 구현을 가속하면서 디자이너 역할이 직접 만들고 시험하고 선별하는 쪽으로 확장되고 있음. Shopify 제품 디자인 스튜디오가 Figma 정적 시안 대신 작동하는 데모로 일하는 사례를 소개함.

---
## 📅 이전 날짜

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
- [2026-10-22](data/2026-10-22.md)
- [2026-10-21](data/2026-10-21.md)
- [2026-10-20](data/2026-10-20.md)