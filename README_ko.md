<p align="center">
  <img src="assets/clawink_logo.png" alt="Clawink — OpenClaw for Business Systems" width="800" />
</p>

<p align="center">
  <strong>Clawink — OpenClaw for Business Systems</strong><br />
  복잡한 업무 시스템을 AI가 다룰 수 있는 제품 레이어로 전환합니다.
</p>

<p align="center">
  시스템 연결 · 실행 가능한 기능 공개 · AI가 계획하고, 미리 보고, 확인하고, 실행
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="Apache 2.0 License" /></a>
  <img src="https://img.shields.io/badge/Open%20Source-Preview-black" alt="Open Source Preview" />
  <img src="https://img.shields.io/badge/Code%20Release-Planned-0A7EA4" alt="Code Release Planned" />
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="README_zh-CN.md">中文</a> ·
  <a href="README_ja.md">日本語</a> ·
  <a href="README_ko.md">한국어</a> ·
  <a href="README_es.md">Español</a>
</p>

<p align="center">
  <a href="#why-clawink-ko">왜 Clawink인가</a> ·
  <a href="#architecture-ko">아키텍처</a> ·
  <a href="#status-ko">현재 공개 상태</a> ·
  <a href="#roadmap-ko">로드맵</a> ·
  <a href="#community-ko">커뮤니티</a>
</p>

---

<a id="why-clawink-ko"></a>

## 왜 Clawink인가

대부분의 업무 시스템 문제는 기능 부족이 아니라, 사용 장벽이 너무 높다는 점에 있습니다.

사용자는 메뉴 구조, 화면 흐름, 권한, 운영 규칙을 먼저 이해해야만 시스템 기능을 제대로 활용할 수 있습니다. Clawink는 그 복잡성 위에 또 하나의 채팅 UI를 덧씌우는 것이 아니라, 시스템 능력을 AI가 안정적으로 이해하고 계획하고 실행할 수 있는 운영 레이어로 정리합니다.

Clawink는 서로 연결되지만 역할이 분리된 두 개의 레일 위에서 동작합니다.

- 계획 레일: 문서를 읽고 능력을 구조화하며, 워크플로 초안을 만들고 검증한 뒤 런타임 자산으로 게시합니다.
- 대화 레일: 게시된 자산만 소비하며, 메시지가 올 때마다 전체 능력을 현장에서 다시 조립하지 않습니다.

이 분리 구조 덕분에 Clawink는 단순한 채팅 셸이 아니라, 실제 업무 시스템을 위한 AI 운영 레이어가 됩니다.

<a id="architecture-ko"></a>

## 아키텍처

계획 측은 검토 가능한 자산을 만들고, 실행 측은 게시된 자산만을 미리보기와 확인 절차 아래에서 실행합니다.

<p align="center">
  <img src="assets/clawink_arch_en.png" alt="Clawink architecture diagram" width="1400" />
</p>

<a id="status-ko"></a>

## 현재 공개 상태

이 저장소는 Clawink의 공개 프리뷰 저장소입니다.

- 현재 공개된 내용은 제품 소개, 아키텍처, 공개 계획, 브랜드 자산뿐입니다.
- 핵심 런타임 코드와 제품 코드는 제품 메커니즘이 더 안정화될 때까지 내부 저장소에 유지됩니다.
- 이후 코드 공개는 내부 주 저장소에서 공개 저장소로의 단방향 동기화 방식으로 단계적으로 진행됩니다.

즉, Clawink는 오픈 프로젝트를 준비 중이지만, 지금 이 저장소는 아직 전체 코드 공개판이 아닙니다.

<a id="roadmap-ko"></a>

## 로드맵

공개 계획은 다음 네 단계로 진행됩니다.

1. 프리뷰 공개: README, 아키텍처, 로드맵, 브랜드 자산 공개
2. 코어 공개: 일부 런타임 모듈, 패키징 구조, 최소 개발 흐름 공개
3. 확장면 공개: 일부 Skill, 통합 예제, 외부 확장 문서 공개
4. 더 넓은 공개: 공개 범위를 점차 넓히고 CI와 커뮤니티 기여 흐름 정비

자세한 내용은 [ROADMAP.md](ROADMAP.md)를 참고하세요.

<a id="community-ko"></a>

## 커뮤니티

- 저장소를 주시하여 공개 마일스톤을 확인하세요.
- Issues 또는 Discussions를 통해 사용 시나리오, 연동 요구, 피드백을 공유해 주세요.
- 실제 도입 판단은 코드 공개 이후 문서와 로드맵을 기준으로 진행하는 편이 안전합니다.

