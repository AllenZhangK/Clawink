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
  <a href="#architecture-ja">アーキテクチャ</a> ·
  <a href="#status-ja">現在の公開状況</a> ·
  <a href="#roadmap-ja">ロードマップ</a> ·
  <a href="#community-ja">コミュニティ</a>
</p>

---

<a id="why-clawink-ja"></a>

## Clawink とは

多くの業務システムの課題は、機能不足ではなく、使いこなすまでの摩擦にあります。

利用者は、メニュー構造、画面遷移、権限、操作ルールを理解して初めて機能を使いこなせます。Clawink は、その複雑さの上にチャット UI を重ねるのではなく、システムの能力そのものを AI が理解し、計画し、実行できる操作レイヤーへ整理します。

Clawink は、連携しながらも役割を分けた 2 本のレールで構成されます。

- 計画レール: ドキュメントを読み取り、能力を構造化し、ワークフローを下書きし、検証してランタイム資産として公開します。
- 対話レール: すでに公開された資産だけを使い、会話のたびに能力全体をその場で組み直しません。

この分離があるからこそ、Clawink は単なるチャット窓口ではなく、実システム向けの AI 操作レイヤーになります。

<a id="architecture-ja"></a>

## アーキテクチャ

計画側は公開可能な資産を生成し、実行側は公開済み資産のみを、プレビューと確認の制御下で実行します。

<p align="center">
  <img src="assets/clawink_arch_en.png" alt="Clawink architecture diagram" width="1400" />
</p>

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
- 本格導入の判断は、コード公開後の資料とロードマップを基準にしてください。

