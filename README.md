# 📰 AI 뉴스 데일리

> 마지막 업데이트: 2026-11-23

# AI 뉴스 — 2026-11-23

## 🔥 GitHub Trending (Python)

- [ZhuLinsen/daily_stock_analysis](https://github.com/ZhuLinsen/daily_stock_analysis): LLM 기반 다중 시장 주식 분석 시스템임. 여러 시세 소스와 실시간 뉴스를 모아 의사결정 대시보드와 자동 알림을 만들어주며, 비용 없이 정기 실행 가능함. 이번 주 1,500스타 넘게 받음.
- [microsoft/PyRIT](https://github.com/microsoft/PyRIT): Microsoft의 오픈소스 생성형 AI 레드티밍 툴킷임. 자동 스캔, 적응형 multi-turn 공격, 웹 UI로 LLM 시스템의 안전성 취약점을 점검함.
- [FujiwaraChoki/supoclip](https://github.com/FujiwaraChoki/supoclip): OpusClip의 오픈소스 대안임. 긴 영상을 AI로 분석해 숏폼 클립으로 자동으로 잘라줌.
- [vllm-project/vllm-ascend](https://github.com/vllm-project/vllm-ascend): vLLM을 Huawei Ascend NPU에서 돌리게 해주는 커뮤니티 하드웨어 플러그인임. NVIDIA GPU 외 가속기로 LLM 서빙을 확장함.
- [apache/airflow](https://github.com/apache/airflow): 워크플로를 코드로 작성·스케줄링·모니터링하는 Apache 플랫폼임. ML 파이프라인과 데이터 엔지니어링 작업 오케스트레이션의 사실상 표준임.

## 📄 Hugging Face Papers

- [Accord: 카메라 1대와 IMU만으로 하는 범용 온라인 메트릭 위치추정·밀집 매핑](https://huggingface.co/papers/2611.25279)
  VIO는 실제 스케일은 맞지만 지도가 듬성듬성하고, depth foundation model은 밀집하지만 스케일이 안 맞는 문제를 결합으로 풂. VIO 포즈로 조건화한 깊이 예측을 삼각측량 3D 점에 고정하고, 함께 보이는 이미지 간 깊이 일치(multi-view agreement)로 이미지별 스케일을 보정한 뒤 factor graph로 서브맵을 융합함.
- [SpecWM: 스트리밍 월드 모델에서 검증을 보정으로 바꾸기](https://huggingface.co/papers/2611.26211)
  작은 모델이 만든 영상 초안을 큰 모델이 검증하는 speculative 방식을 비디오 월드 모델에 적용한 학습 불필요(training-free) 추론 프레임워크임. 큰 모델의 latent velocity field로 검증하면서 얻은 보정값을 재사용해 Accept/Refine/Reject를 결정함. 화질·조작성·속도가 함께 개선됨.
- [TwinLab-Bench: 실제 연구실의 디지털 트윈에서 AI 과학자 평가](https://huggingface.co/papers/2611.26248)
  AI 과학자가 실험을 스스로 설계하는 능력을 평가하는 벤치마크임. 물리·생명과학·공학 연구실 52개 과제, 100종 이상의 실험 동작을 지원하고, 에이전트 보고서를 실제 연구실 기록의 숨겨진 정답과 비교해 채점함.
- [Direct3D-V3: VAE 없이 voxel 공간에서 바로 생성하는 Diffusion Transformer](https://huggingface.co/papers/2611.26511)
  기존 3D 생성은 형상을 latent로 압축한 뒤 생성했는데, 이 논문은 VAE를 아예 빼고 원본 SDF voxel 그리드를 DiT가 직접 학습·샘플링함. 이웃 voxel 간 implicit manifold 정규화로 구멍 난 표면을 억제하고 Marching Cubes로 메시를 뽑음.
- [가짜 성공, 조용한 실패: 로봇 조작 시뮬레이션 벤치마크의 성공 판정기 감사](https://huggingface.co/papers/2611.25179)
  시뮬레이션 벤치마크의 수작업 성공 판정 코드가 미완료 작업을 성공으로 치거나(phantom success) 다른 방식으로 완료한 걸 실패로 치는(silent failure) 문제를 다룸. LLM 기반 파이프라인 SimAudit이 지시문과 판정 코드를 비교해 불일치 상황을 재현하고, 다시점 렌더링으로 검증함. RoboTwin 2.0, RoboCasa 등에서 오류를 찾아냄.

## 🦉 GeekNews

- [Vint Cerf가 말하는 TCP/IP를 특허로 등록하지 않은 이유](https://seremot.com/p/vint-cerf-on-why-tcpip-was-never)
  TCP/IP는 미군 지휘통제와 동맹국 연결을 위해 개발됨. 25년 뒤 누가 동맹일지 알 수 없어 미래의 누구라도 쓸 수 있게 특허 없이 공개했다는 인터뷰임. 개방성이 인터넷 확산의 핵심이었다는 점을 짚음.
- [AGI 다음에는 무엇이 올까?](https://institute.deepmind.com/essays/what-comes-after-agi/)
  Google DeepMind 에세이임. 인간 수준 AGI는 지능의 상한이 아니며, 대규모 전문가 집단보다 적은 시간·자원으로 더 나은 성과를 내는 범용 초지능(ASI)이 다음 단계라고 봄. 그 사회적 영향과 대비 방향을 논의함.
- [UI SDK - AI 에이전트가 UI 기본 동작을 조합해 컴포넌트를 만드는 라이브러리](https://github.com/vercel-labs/ui)
  Vercel Labs가 공개함. 팝업 열기, 항목 선택, 타이핑으로 항목 찾기 같은 기본 동작을 재사용해 에이전트가 Select 등 맞춤 컴포넌트를 조립하게 함. 접근성과 일관성을 지키면서 AI 생성 UI 품질을 높이는 게 목표임.
- [초대형 Git 저장소의 개발 속도 높이기](https://developers.googleblog.com/accelerating-development-for-massive-git-repositories/)
  Google이 대규모 Git 프로젝트의 소스 동기화·빌드 병목을 줄이는 ABFS(Another Build File Service)를 오픈소스로 공개함. Android 같은 초대형 저장소에서 체크아웃과 빌드 시간을 크게 줄임.
- [추론 칩을 바이브 코딩하기](https://ankitg.me/blog/vibecoding-inference-chip/)
  FPGA 경험이 전혀 없는 상태에서 코딩 에이전트로 AWS FPGA에 LLM 추론 회로를 구현한 경험담임. 기준 출력과 비트 단위로 일치하는 결과를 얻음. 하드웨어 설계 영역까지 에이전트 코딩이 확장되는 사례임.

---
## 📅 이전 날짜

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
- [2026-10-24](data/2026-10-24.md)