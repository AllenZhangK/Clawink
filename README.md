<p align="center">
  <img src="assets/clawink_logo.png" alt="Clawink — OpenClaw for Business Systems" width="800" />
</p>

<p align="center">
  <strong>Clawink — OpenClaw for Business Systems</strong><br />
  Turn complex business systems into an AI-operable product layer.
</p>

<p align="center">
  Connect your system · Publish executable capabilities · Let AI plan, preview, confirm, and execute real work
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
  <a href="#why-clawink">Why Clawink</a> ·
  <a href="#architecture">Architecture</a> ·
  <a href="#status">Current Status</a> ·
  <a href="#roadmap">Roadmap</a> ·
  <a href="#community">Community</a>
</p>

---

## Why Clawink

Most business systems do not suffer from a lack of features. They suffer from friction.

Users often have to decode menus, flows, permissions, and operating rules before the system becomes truly usable. Clawink is designed to change that. It turns system capability into an AI-operable layer so people can move from "learn the system first" to "state the goal directly."

Clawink is built around two coordinated rails:

- Planning rail: reads docs, structures capabilities, drafts workflows, validates them, and publishes runtime-ready assets.
- Conversation rail: consumes only published assets during live conversations instead of rebuilding the full workflow on every message.

That split is what makes Clawink more than a chat shell. It is an operating layer for real business systems.

## Architecture

The planning rail and runtime rail are intentionally separated. Planning produces reviewed assets. Runtime executes only published assets under preview, confirmation, and operational guardrails.

<p align="center">
  <img src="assets/clawink_arch_en.png" alt="Clawink architecture diagram" width="1400" />
</p>

## Current Status

This repository is the public preview for Clawink.

- It currently publishes product overview, architecture, and roadmap.
- Core runtime and product code are still private while the product model is being stabilized.
- Public code release will happen in staged drops through a one-way sync process from the internal repository.

Clawink is being prepared as an open project, but this repository is not yet the full public code release.

## Roadmap

The open-source rollout is intentionally staged:

1. Preview repository: README, architecture, roadmap, and brand assets.
2. Public core slice: selected runtime modules, packaging, and minimal developer workflow.
3. Public extension surface: selected Skills, integration examples, and docs for external contributors.
4. Broader release: expanded runtime modules, stronger CI, and a clearer community contribution path.

See [ROADMAP.md](ROADMAP.md) for the current release path.

## Community

- Watch this repository for public release milestones.
- Use Issues and Discussions to share scenarios, integration needs, and feedback.
- Follow the roadmap before planning production adoption.

