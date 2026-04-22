<p align="center">
  <img src="assets/clawink_logo.png" alt="Clawink — OpenClaw for Business Systems" width="800" />
</p>

<p align="center">
  <strong>Clawink — OpenClaw for Business Systems</strong><br />
  複雑な業務システムを、AI が扱えるプロダクトレイヤーへ。
</p>

<p align="center">
  システムを接続する · 実行可能な能力を公開する · AI が計画し、プレビューし、確認し、実行する
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
  <a href="#why-clawink-ja">Clawink とは</a> ·
  <a href="#highlights-ja">特徴</a> ·
  <a href="#architecture-ja">アーキテクチャ</a> ·
  <a href="#from-connection-to-control-ja">接続から運用まで</a> ·
  <a href="#teams-and-scenarios-ja">向いているチーム</a> ·
  <a href="#status-ja">現在の公開状況</a> ·
  <a href="#roadmap-ja">ロードマップ</a> ·
  <a href="#community-ja">コミュニティ</a>
</p>

---

<a id="why-clawink-ja"></a>

## Clawink とは

多くの業務システムの課題は、機能不足ではなく、使いこなすまでの摩擦にあります。

利用者は、メニュー構造、画面遷移、権限、操作ルールを理解して初めて機能を使いこなせます。Clawink は、その複雑さの上にチャット UI を重ねるのではなく、システムの能力そのものを AI が理解し、計画し、実行できる操作レイヤーへ整理します。

もし自社で AI プロダクトレイヤーをゼロから作る余力がまだないなら、Clawink はより現実的な選択肢です。既存システムに Clawink を接続することで、OpenClaw の Agent 基盤、計画と実行の主チェーン、拡張モデルをより早く取り込めます。

Clawink は、連携しながらも役割を分けた 2 本のレールで構成されます。

- 計画レール: ドキュメントを読み取り、能力を構造化し、ワークフローを下書きし、検証してランタイム資産として公開します。
- 対話レール: すでに公開された資産だけを使い、会話のたびに能力全体をその場で組み直しません。

この分離があるからこそ、Clawink は単なるチャット窓口ではなく、実システム向けの AI 操作レイヤーになります。

<a id="highlights-ja"></a>

## 特徴

Clawink の違いを短くつかむなら、まずは次の 3 点です。

<table>
  <tr>
    <td valign="top" width="33%">
      <strong>二本レール構成</strong><br />
      計画レールがランタイム資産を生成して公開し、対話レールは公開済み資産だけを使って実行します。
    </td>
    <td valign="top" width="33%">
      <strong>既存システムを素早く取り込める</strong><br />
      AI 製品レイヤーをゼロから作り直さなくても、既存システムに接続することで OpenClaw の基盤をより早く活用できます。
    </td>
    <td valign="top" width="33%">
      <strong>実行を制御しながら可視化できる</strong><br />
      高リスク操作は `preview -> confirm -> submit` を通し、実行の流れや結果確認も追える形を保ちます。
    </td>
  </tr>
</table>

<a id="architecture-ja"></a>

## アーキテクチャ

計画側は公開可能な資産を生成し、実行側は公開済み資産のみを、プレビューと確認の制御下で実行します。

<p align="center">
  <img src="assets/clawink_arch_en.png" alt="Clawink architecture diagram" width="1400" />
</p>

<a id="from-connection-to-control-ja"></a>

## 接続から運用まで

1. **システムを接続する**: Swagger、OpenAPI、Markdown を取り込み、認証を整えて実システムの能力へ到達します。
2. **運用資産として公開する**: API や画面操作、業務依存をワークフローと能力資産に整理し、ランタイム用に公開します。
3. **AI に実行させる**: ユーザーは目的を伝え、Clawink がルーティング、プレビュー、確認、実行、結果整理まで担います。

## 得られるもの

- **業務システムを引き受けられる AI ワークスペース**: 接続、計画、実行、認証、可観測性、ガバナンスを一つの面で扱えます。
- **実利用者向けの AI プロダクトレイヤー**: ユーザーが目的を述べると、Clawink が問い合わせや実行、結果返却に落とし込みます。
- **業務チーム向けの運用コンソール**: 計画結果は一時的なプロンプト出力ではなく、ワークフローや資産、公開状態、実行ログとして残ります。
- **技術チーム向けの安定した土台**: モデル、Skill、MCP、連携先を広げても主実行系を壊さずに拡張できます。

<a id="teams-and-scenarios-ja"></a>

## 向いているチームとシナリオ

- **プロダクトチーム**: 既存の管理画面、社内ツール、SaaS を会話可能かつ実行可能な AI 製品へ進化させたい。
- **UX が複雑なシステムを抱えるチーム**: ユーザーに複雑な画面遷移や操作規則を覚えさせたくない。
- **プラットフォーム / 連携チーム**: 複数システムや管理画面、API の入口を一つの AI 操作面にまとめたい。
- **実行型のプロダクトチーム**: AI を説明役にとどめず、検索、プレビュー、確認、実行まで担わせたい。
- **導入 / ガバナンス重視のチーム**: AI 実行時もリスク制御、認証管理、監査性を保ちたい。

<a id="status-ja"></a>

## 現在の公開状況

このリポジトリは、Clawink の公開プレビュー用リポジトリです。

- 現在公開しているのは、製品紹介、アーキテクチャ、公開計画、ブランド素材のみです。
- コアのランタイムコードと製品コードは、プロダクト設計が固まるまで内部リポジトリに残します。
- 今後のコード公開は、内部主リポジトリから公開リポジトリへの一方向同期で段階的に行います。

つまり、Clawink はオープン化を進めていますが、この時点ではまだ完全な公開コード版ではありません。

<a id="roadmap-ja"></a>

## ロードマップ

公開計画は、次の 4 段階で進めます。

1. プレビュー公開: README、アーキテクチャ、ロードマップ、ブランド素材を公開。
2. コア公開: 一部ランタイムモジュール、パッケージ構成、最小の開発フローを公開。
3. 拡張面の公開: 一部 Skill、統合例、外部拡張ドキュメントを公開。
4. より広い公開: 公開対象を段階的に増やし、CI とコミュニティ導線を整備。

詳細は [ROADMAP.md](ROADMAP.md) を参照してください。

<a id="community-ja"></a>

## コミュニティ

- リポジトリをウォッチして公開マイルストーンを追ってください。
- Issues や Discussions で利用シナリオや統合要望、フィードバックを共有してください。
- 現在のプレビュー段階での協力ルールは [CONTRIBUTING.md](CONTRIBUTING.md) を参照してください。
- セキュリティに関する報告は [SECURITY.md](SECURITY.md) の私的報告手順に従ってください。
- 本格導入の判断は、コード公開後の資料とロードマップを基準にしてください。
