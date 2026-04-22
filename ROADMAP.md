# Clawink Open-Source Roadmap

This roadmap describes how Clawink is intended to move from a private product codebase to a staged public release.

It is a release plan, not a contract. Scope and order can change as the product model stabilizes.

## Release Principles

- The internal repository remains the only source of truth.
- Public releases are published through one-way sync only.
- Public code is released through explicit white-list profiles.
- Each public phase must remain self-contained and maintainable.

## Phase 0: Public Preview

Current scope:

- Product overview
- Architecture diagrams
- Release roadmap
- Brand assets and repository metadata

Goal:

- Explain what Clawink is
- Set correct expectations
- Collect community feedback before opening runtime code

## Phase 1: Public Core Slice

Planned scope:

- Selected runtime modules
- Packaging metadata
- Minimal development workflow
- Basic CI for public code

Goal:

- Make the first public code release understandable and runnable
- Keep the surface area intentionally small

## Phase 2: Public Extension Surface

Planned scope:

- Selected Skills
- Integration examples
- Public-facing extension docs
- Clearer external contribution boundaries

Goal:

- Let external contributors understand where extensions belong
- Expose stable integration seams before widening the code release

## Phase 3: Broader Runtime Release

Planned scope:

- Wider runtime modules
- Stronger test coverage in public CI
- Better release notes and migration guidance

Goal:

- Expand the open-source surface without exposing unfinished internal structure

## Contribution Path

Before broader code release:

- Use Issues and Discussions for feedback and scenario sharing
- Community patches are reviewed manually and re-applied in the internal repository

After broader code release:

- Contribution rules will be documented in the public repository

