# Clawink Open-Source Roadmap

Clawink is being opened in stages.

This roadmap is meant to help the community understand what is available now, what is coming next, and how the public repository will evolve over time.

It is a directional plan, not a fixed contract. Scope and ordering can change as the product model stabilizes.

## Current Stage

The public repository is currently in the **Preview** stage.

What is public today:

- Product overview
- Architecture diagrams
- Brand assets
- Open-source roadmap

What is not public yet:

- Core runtime code
- Product implementation details
- Full developer workflow
- Public contribution workflow for source code

The goal of this stage is to explain the product clearly, set the right expectations, and collect feedback before opening code in larger slices.

## Near-Term Focus

The next public milestone is the first **Public Core Slice**.

Current preparation priorities:

- Define a clean public code boundary
- Separate public-facing modules from internal-only structure
- Make the first public release understandable and maintainable
- Keep the first release small enough to support properly

The first code drop is expected to focus on a minimal but coherent surface rather than broad coverage.

## Release Track

### Stage 0: Preview

Scope:

- README and project positioning
- Architecture and operating model
- Brand assets and public metadata

Outcome:

- The project can be understood before code is opened
- Community expectations stay aligned with the actual release state

### Stage 1: Public Core Slice

Target scope:

- Selected runtime modules
- Packaging metadata
- Minimal developer workflow
- Basic CI for the public repository

Outcome:

- The first code release is small, readable, and supportable
- External developers can begin to understand the runtime surface

### Stage 2: Public Extension Surface

Target scope:

- Selected Skills
- Integration examples
- Public-facing extension docs
- Clearer boundaries for external contributions

Outcome:

- External builders can see where extensions belong
- The public project starts to gain stable integration seams

### Stage 3: Broader Runtime Release

Target scope:

- Wider runtime modules
- Better public test coverage
- Stronger release notes and migration guidance

Outcome:

- The open-source surface grows without exposing unfinished internal structure
- The project becomes easier to evaluate and adopt technically

## How Public Releases Work

Clawink uses a **one-way sync** model:

- The internal repository remains the source of truth
- Public releases are published from approved white-list profiles
- The public repository receives staged snapshots, not raw internal development history

This keeps the public surface cleaner and reduces the risk of exposing unstable or internal-only structure.

## Community Participation

What helps most right now:

- Share target scenarios and system types you want Clawink to support
- Open Issues for product feedback, integration needs, and release expectations
- Follow the public milestones instead of assuming the repository is already feature-complete

Before broader code release:

- Feedback and use cases are more valuable than code patches
- Source-code contributions are handled manually and may first be applied in the internal repository

After broader code release:

- Public contribution rules will be documented in the repository

## Release Principles

- Release in slices, not all at once
- Prefer clean boundaries over broad exposure
- Keep every public phase self-contained and maintainable
- Publish only what can be explained and supported responsibly
