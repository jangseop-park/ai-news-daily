# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-09-22

# AI 뉴스 — 2026-09-22

## 🔥 GitHub Trending (Python)

- [mvt-project/mvt](https://github.com/mvt-project/mvt): 모바일 기기 포렌식으로 스파이웨어 등 침해 흔적을 찾아주는 Mobile Verification Toolkit임. Android·iOS 백업과 로그를 분석해 알려진 침해 지표(IOC)와 대조함.
- [zhouxiaoka/autoclip](https://github.com/zhouxiaoka/autoclip): AI 기반 영상 클리핑·하이라이트 자동 생성 도구임. 긴 영상에서 핵심 장면을 뽑아 2차 창작용 클립으로 편집해 줌.
- [docling-project/docling](https://github.com/docling-project/docling): PDF·DOCX 등 각종 문서를 생성형 AI가 쓰기 좋은 구조화 포맷으로 변환하는 문서 파싱 라이브러리임. RAG 파이프라인 전처리에 많이 쓰임.
- [TNT-Likely/PanWatch](https://github.com/TNT-Likely/PanWatch): 셀프호스팅 AI 주식 모니터링 도우미임. TradingAgents 멀티 에이전트 투자 판단을 통합했고 A주·홍콩·미국 주식 실시간 감시, 보유 종목 관리, 분석, 다채널 알림을 지원함.
- [cv-cat/DouYin_Spider](https://github.com/cv-cat/DouYin_Spider): Douyin(중국판 TikTok)을 리버스 엔지니어링한 크롤러임. 주요 API, DM, 라이브 방송 모니터링 기능을 제공함.

## 📄 Hugging Face Papers

- [IntBMoE: 전원 참여형 Mixture-of-Experts를 위한 블록 단위 조건화 기반 전문가 합성](https://huggingface.co/papers/2609.21346)
  MoE에서 토큰당 참여 전문가 수, 실제 연산 수, 메모리에 올리는 파라미터 수를 독립적으로 조절할 수 없다는 한계를 지적함. 블록 단위 조건화로 전문가를 합성해 연산·메모리 비용은 낮게 유지하면서 모든 전문가가 출력에 기여하도록 하는 구조를 제안함.
- [OmniVChat: 네이티브 오디오-비주얼 대화를 위한 데이터 합성, 벤치마크, 학습](https://huggingface.co/papers/2609.21465)
  사용자의 음성과 영상을 별도 텍스트 질문·캡셔닝·음성인식 없이 omni 모델이 직접 받아 답하는 대화 과제 OmniVChat을 정의함. 부족한 실사용 데이터 문제를 합성 데이터로 풀고, 평가 벤치마크와 학습 방법까지 함께 제시함.
- [Paint-Anything: 이미지 생성과 편집을 위한 통합 임의 색상 제어](https://huggingface.co/papers/2609.20816)
  24비트 hex 값으로 객체 색을 정확히 지정하는 any-color 제어를 다룸. 전용 색 표현이나 특수 추론 절차 없이 hex 프롬프트라는 공통 인터페이스를 객체 단위 색상 감독으로 학습해 생성과 편집을 하나로 통합함.
- [Designer-RSI: 사용자 트래픽에서 절차 기억을 진화시키는 에이전트형 그래픽 디자인](https://huggingface.co/papers/2609.22086)
  고정된 프런티어 모델이 230개 이상의 도구로 전문 디자인 소프트웨어를 조작하고, 자연어 스킬로 된 외부 절차 기억이 경험에서 재사용 가능한 디자인 절차를 쌓고 다듬는 지속 적응 프레임워크임. 모델 재학습 없이 기억만으로 성능이 개선됨.
- [BI-Agent와 BI-Bench: End-to-End 비즈니스 인텔리전스 자동화를 향하여](https://huggingface.co/papers/2609.20886)
  Power BI·Tableau 같은 BI 작업에서 테이블 탐색, 데이터 변환, 조인 구성, 질의 응답까지 전 과정을 LLM이 자동으로 수행할 수 있는지 연구함. 이를 평가하는 BI-Bench와 에이전트 BI-Agent를 제안함.

## 🦉 GeekNews

- [시니어 엔지니어의 파멸적 악순환](https://sunilpai.dev/posts/the-senior-engineer-death-spiral/)
  새 직장이나 승진 후 자신을 증명하려고 지나치게 야심 찬 작업을 떠맡고, 결과가 안 나올수록 더 오래 혼자 일하게 되는 악순환을 다룸. 작게 나눠 일찍 공유하는 게 탈출법임.
- [PostgreSQL 캐싱: 기본 동작과 추가 캐시의 선택 기준](https://www.pgcache.com/blog/postgresql-caching/)
  PostgreSQL은 데이터 페이지와 실행 계획은 캐싱하지만 쿼리 결과는 저장하지 않음. 데이터가 메모리에 있어도 같은 조회는 매번 다시 계산되므로 언제 별도 결과 캐시를 둘지 기준을 정리함.
- [AI가 무너뜨리는 공유의 문화](https://www.chesterwisniewski.com/post/2026-09-13-ai-is-destroying-the-creative-commons/)
  코드와 지식을 공개해 서로 배우고 재사용하던 문화가 AI 때문에 흔들리고 있다는 글임. 공유가 세상에 주는 선물이 아니라 창작자가 감당해야 할 부담으로 바뀌고 있다고 지적함.
- [Three.js로 브라우저에서 LLM 실행하기](https://ben3d.ca/blog/running-llms-in-the-browser-with-threejs)
  3D 그래픽 라이브러리 Three.js의 GPU 연산 기능으로 언어 모델을 돌리는 Three-LLM을 구현함. 별도 추론 서버 없이 브라우저에서 GPT-2, SmolLM2 등을 실행함.
- [Claude Code 개발자 보리스 처니: "나는 자주 틀린다"](https://borischerny.com/management,/product/2026/09/19/I-am-often-wrong.html)
  새로운 정보가 들어오면 문제 정의와 접근법, 목표까지 바꿔야 한다는 글임. 방향이 자꾸 바뀌는 것처럼 보여도 복잡한 문제를 푸는 데 필요한 반복일 수 있다고 함.

---
## 📅 이전 날짜

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
- [2026-08-28](data/2026-08-28.md)
- [2026-08-27](data/2026-08-27.md)
- [2026-08-25](data/2026-08-25.md)
- [2026-08-24](data/2026-08-24.md)
- [2026-08-23](data/2026-08-23.md)
- [2026-08-22](data/2026-08-22.md)
- [2026-08-21](data/2026-08-21.md)
- [2026-08-20](data/2026-08-20.md)