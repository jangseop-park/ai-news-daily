# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-11-21

# AI 뉴스 — 2026-11-21

## 🔥 GitHub Trending (Python)

- [zhouxiaoka/autoclip](https://github.com/zhouxiaoka/autoclip): 링크 하나로 긴 영상을 숏폼으로 자동 편집해주는 오픈소스 AI 데스크톱 도구임. 팟캐스트·인터뷰·강의 영상을 잘라 자막·썸네일·게시 문구까지 만들고 TikTok, Reels, YouTube Shorts 등에 맞춰줌.
- [Tracer-Cloud/opensre](https://github.com/Tracer-Cloud/opensre): CI/CD 신뢰성을 위한 오픈소스 AI 에이전트임. 파이프라인 실패 원인 분석과 운영(SRE) 업무를 에이전트로 자동화하는 것을 목표로 함.
- [FlashML-org/FreeVideo](https://github.com/FlashML-org/FreeVideo): 가진 컴퓨터로 영상 생성을 돌리게 해주는 도구임. MiniMax H3 모델을 VRAM 8GB·RAM 16GB에서도 실행하고, 하드웨어에 맞춰 가속 경로를 자동으로 고름.
- [phone-harness/phone-harness](https://github.com/phone-harness/phone-harness): AI 에이전트가 스마트폰을 직접 조작하게 해주는 하네스임. 앱 실행·터치·입력 같은 휴대폰 작업을 에이전트 도구로 연결함.
- [superdesigndev/treg](https://github.com/superdesigndev/treg): '에이전트 도구용 OpenRouter'를 표방하는 프로젝트임. 여러 에이전트 도구를 하나의 레지스트리·인터페이스로 묶어 골라 쓰게 해줌.

## 📄 Hugging Face Papers

- [AltRA-Test: 공통 주석자 없이 LLM 심사위원을 검증하는 통계 검정](https://huggingface.co/papers/2611.26073)
  LLM이 사람 주석자를 대체해도 되는지 판단하는 통계 검정임. 기존 Alt-Test는 모든 항목을 같은 주석자가 달아야 했지만, AltRA-Test는 항목마다 주석자가 달라도 bootstrap 재표집으로 비교함. 보통 약 100개 항목이면 충분하고 기존 방법보다 대체 판단이 정확함.
- [Diffusion Transformer의 RL 후학습은 사실상 Activation Steering이다](https://huggingface.co/papers/2611.26627)
  RL 후학습으로 얻은 이미지 품질·텍스트 렌더링·구성 정확도 향상 대부분이 고정된 steering vector 몇 개로 재현된다는 연구임. SD3.5-M에서 RL LoRA보다 65배 적은 파라미터로 대부분의 이득을 회복함. 개선의 상당 부분이 프롬프트별 변환이 아니라 일정한 shift라는 뜻임.
- [LLM 기반 Weight-Space Programming을 위한 비전 모델 학습](https://huggingface.co/papers/2611.26408)
  LLM이 신경망 가중치를 직접 고치는 weight-space programming을 비전 모델에서 평가한 벤치마크임. LLM 5종이 CNN·ViT를 재라벨링·오류 수정 과제로 편집한 2,600여 건을 성공률·부작용·정확도 손실로 채점함. 편집하기 좋게 학습시키면 성공률이 달라지는지 비교함.
- [지시 기반 절차 영상에서 실시간 실수 감지](https://huggingface.co/papers/2611.25567)
  사람이 절차를 수행하는 1인칭 영상을 보면서 작업 지시문과 비교해 실수를 실시간으로 잡는 모델임. 어떤 단계를 시도했는지 식별·위치를 찾고 정상/변형/실수/교정 등으로 분류함. 회복 가능한 시점에 알려주는 보조 AI를 목표로 함.
- [두 번 들은 비평: LLM 시대 동료 심사의 주장 수준 균질화](https://huggingface.co/papers/2611.26286)
  학회·저널 리뷰 간 지적 사항 중복도를 측정한 연구임. ICLR 리뷰 중복도가 2026년 12.0%에서 2027년 21.3%로 뛰었고, 세 번째 리뷰가 새로 짚는 문제 수도 줄었음. LLM 생성으로 판정된 리뷰끼리 더 비슷해 비평 다양성이 줄고 있음을 보여줌.

## 🦉 GeekNews

- [Kiri - 무료 ngrok 대안을 내장한 경량 Docker Desktop 대체재](https://github.com/libracoder/kiri)
  기존 Docker 이미지·CLI·Compose·buildx를 그대로 쓰는 맥/윈도우/리눅스용 컨테이너 런타임임. kiri share 명령으로 로컬 앱을 공개 HTTPS 주소로 바로 공유 가능함. 명령 하나로 Kubernetes 클러스터 생성, Docker Desktop·OrbStack 데이터 가져오기, 60초 유휴 시 VM 절전도 지원함.
- [DaisyRose-27B - 장시간 에이전트 작업에 강화학습을 적용한 Qwen3.8-27B 기반 모델](https://www.radixark.com/blog/daisyrose-27b)
  RadixArk가 Qwen3.8-27B에 작업 1,200개로 H200 144대·18일간 강화학습한 모델을 공개함. Terminal-Bench 4.1 pass@1이 5.6%→12.0%로 오름. 비동기 학습으로 GPU 시간 57% 절감했고 BF16·FP8·NVFP4 가중치를 Apache-2.0으로 풀었음.
- [Show GN: OpenDocKit - HWP부터 PDF·엑셀까지 문서를 LLM용 Markdown으로 바꾸는 파이썬 라이브러리](https://news.hada.io/topic?id=37495)
  RAG·에이전트 입력용 문서 변환 라이브러리임. PDF·DOCX·PPTX·XLSX·HWP/HWPX 등을 함수 하나로 읽고, 병합 셀 복원·테두리 없는 표 인식·수식 LaTeX 변환까지 처리함. 페이지 단위 섹션을 제공해 청킹과 출처 표기에 쓰기 좋음.
- [AI는 왜 로컬로 향하는가](https://thedataexchange.media/pete-warden-moonshine/)
  Moonshine Voice 개발자 Pete Warden 인터뷰임. 로컬 AI의 장벽은 이제 모델 품질보다 사용성이라고 봄. API 요금이 없어지면 새로운 앱이 가능해지고, 음성 인터페이스는 200ms 이하 응답이 중요하며, 추론 병목은 메모리 대역폭이라고 설명함.
- [nginx2root - nginx 원격 코드 실행 취약점 5개와 Linux 커널 권한 상승 취약점](https://xint.io/blog/nginx2root-remote-code-execution)
  Xint가 nginx 비인증 RCE 취약점 5개와 Linux SCTP 커널 취약점을 공개함. 가장 광범위한 CVE-2026-123007은 HTTP/2 활성화 서버(1.9.5~1.31.8)에 영향을 줌. 연계 시 root 획득·컨테이너 탈출까지 가능하며, stable 1.30.7 / mainline 1.31.9 이상으로 업데이트해야 함.

---
## 📅 이전 날짜

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
- [2026-10-22](data/2026-10-22.md)