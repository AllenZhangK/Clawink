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
  <a href="#highlights-ko">핵심 특징</a> ·
  <a href="#architecture-ko">아키텍처</a> ·
  <a href="#from-connection-to-control-ko">도입부터 실행까지</a> ·
  <a href="#teams-and-scenarios-ko">적합한 팀</a> ·
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

<a id="highlights-ko"></a>

## 핵심 특징

Clawink의 차이를 짧게 잡으려면 먼저 이 세 가지를 보면 됩니다.

<table>
  <tr>
    <td valign="top" width="33%">
      <strong>이중 레일 구조</strong><br />
      계획 레일이 런타임 자산을 만들고 게시하며, 대화 레일은 게시된 자산만 사용해 실행합니다.
    </td>
    <td valign="top" width="33%">
      <strong>기존 시스템을 빠르게 흡수</strong><br />
      AI 제품 레이어를 처음부터 다시 만들지 않아도, 기존 시스템에 연결해 OpenClaw 기반을 더 빠르게 활용할 수 있습니다.
    </td>
    <td valign="top" width="33%">
      <strong>통제 가능한 실행과 가시성</strong><br />
      고위험 작업은 `preview -> confirm -> submit` 절차를 거치고, 실행 흐름과 결과 확인도 계속 추적할 수 있습니다.
    </td>
  </tr>
</table>

<a id="architecture-ko"></a>

## 아키텍처

계획 측은 검토 가능한 자산을 만들고, 실행 측은 게시된 자산만을 미리보기와 확인 절차 아래에서 실행합니다.

<p align="center">
  <img src="assets/clawink_arch_en.png" alt="Clawink architecture diagram" width="1400" />
</p>

<a id="from-connection-to-control-ko"></a>

## 도입부터 실행까지

1. **시스템 연결**: Swagger, OpenAPI, Markdown을 가져오고 인증을 정리해 실제 시스템 능력에 도달합니다.
2. **운영 자산 공개**: API, 화면 동작, 업무 의존 관계를 워크플로와 능력 자산으로 정리해 런타임용으로 게시합니다.
3. **AI 실행**: 사용자는 목표를 말하고, Clawink가 라우팅, 미리보기, 확인, 실행, 결과 정리까지 맡습니다.

## 실제로 얻게 되는 것

- **업무 시스템을 맡길 수 있는 AI 워크스페이스**: 연결, 계획, 실행, 인증, 관측, 거버넌스를 한 운영면에서 다룰 수 있습니다.
- **최종 사용자를 위한 AI 제품 레이어**: 사용자가 목표를 말하면 Clawink가 조회, 실행, 결과 반환으로 연결합니다.
- **비즈니스 팀을 위한 운영 콘솔**: 계획 결과가 일회성 프롬프트 출력이 아니라 워크플로, 자산, 게시 상태, 실행 로그로 남습니다.
- **기술 팀을 위한 안정적인 기반**: 모델, Skill, MCP, 연동 대상을 늘려도 주 실행 체인을 갈아엎지 않고 확장할 수 있습니다.

<a id="teams-and-scenarios-ko"></a>

## 적합한 팀과 시나리오

- **제품 팀**: 기존 백오피스, 내부 도구, SaaS를 대화 가능하고 실행 가능한 AI 제품으로 발전시키고 싶은 팀
- **복잡한 UX를 가진 시스템 팀**: 사용자가 복잡한 메뉴, 화면 흐름, 운영 규칙을 외우지 않도록 만들고 싶은 팀
- **플랫폼 / 통합 팀**: 여러 시스템, 관리자 화면, API 진입점을 하나의 AI 운영면으로 모으고 싶은 팀
- **실행 중심 제품 팀**: AI가 설명만 하는 것이 아니라 조회, 미리보기, 확인, 실행까지 담당하길 원하는 팀
- **전달 / 거버넌스 팀**: AI가 업무를 수행해도 리스크 제어, 인증 관리, 실행 가시성, 감사 가능성을 유지하고 싶은 팀

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
- 현재 프리뷰 단계의 협업 방식은 [CONTRIBUTING.md](CONTRIBUTING.md)를 참고하세요.
- 보안 이슈는 [SECURITY.md](SECURITY.md)의 비공개 보고 절차를 따라 주세요.
- 실제 도입 판단은 코드 공개 이후 문서와 로드맵을 기준으로 진행하는 편이 안전합니다.
