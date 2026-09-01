# Kairui Liu

**Technical AI Product Builder · NUS-ISS MTech AIS · Singapore**

I turn ambiguous AI capabilities into scoped requirements, evaluation criteria, failure boundaries, and production release gates. My work sits between product judgment and technical delivery: defining what an AI system should do, how it should fail safely, and what evidence is strong enough to ship.

## What I work on

- **AI product definition and evaluation:** system behavior, prompt and policy constraints, bad cases, acceptance criteria, and release gates.
- **Truthful and reliable product systems:** explicit data boundaries, safe degradation, privacy-aware architecture, and failure recovery.
- **Human-in-the-loop workflows:** AI proposes or assists; the user retains control over consequential state changes.
- **Technical product delivery:** translating product decisions into testable web, mobile, voice, and local-first systems.

## Selected work

### [ThinkBud](https://github.com/Jeffreyliu0131/thinkbud-ai)

An AI thinking coach for primary-school learners that uses Socratic prompts instead of revealing answers. Product constraints are enforced through server-side prompt construction, answer-leakage audits, multimodal input, and synthetic conversation tests.

**My role:** product mechanism, coaching-policy evolution, prompt and safety constraints, multimodal workflow, QA, and release decisions. Current validation is mainly family testing, so I do not claim broad adoption or measured learning outcomes.

### [Nianxing](https://github.com/Jeffreyliu0131/nianxing)

A local-first action and idea PWA where AI produces a reviewable organization draft and the user confirms every saved change. The system includes offline capture, optional account sync, revision conflict handling, and model-failure fallback.

**My role:** product loop, local-first and account-isolation boundaries, synchronization semantics, mobile interaction rules, acceptance behavior, and release verification. It is a working prototype, not evidence of external adoption.

### [Stock Portfolio](https://github.com/Jeffreyliu0131/stock-portfolio)

An iPhone-first portfolio PWA that separates exact financial truth from delayed market data and optional AI interpretation. The product uses decimal calculations, atomic restore rules, explicit missing-data behavior, and a security gate covering the complete dependency tree.

**My role:** product scope, PRD and ADR set, architecture, implementation, production release gates, incident diagnosis, and security hardening. The public snapshot uses synthetic data and currently passes 585 automated tests; it makes no investment-performance claim.

### [FrameText Camera Effects](https://github.com/Jeffreyliu0131/frame-text-demo)

An independent browser prototype for real-time camera effects, local MediaPipe face and hand signals, frozen capture snapshots, and non-destructive high-resolution export.

**My role:** interaction model, effect-state architecture, preview-to-capture consistency, non-destructive rendering boundary, asset provenance, and final verification. The public repository contains no employer code, company branding, credentials, internal documents, or real-person media.

### [Codex Notch](https://github.com/Jeffreyliu0131/codex-notch)

A native macOS notch and menu-bar companion for monitoring local and connected-Mac Codex tasks. It groups work across Git worktrees, shows weekly usage, distinguishes explicit approval requests from ordinary input, and surfaces approval-required states through an eight-second notch expansion plus privacy-safe local notifications.

**My role:** low-interruption interaction model, task and attention-state semantics, approval false-positive boundaries, notification data minimization, public-snapshot safety rules, synthetic QA, and release verification. The current public artifact passes CI but depends on undocumented local Codex implementation details; it does not claim external adoption or an official OpenAI integration.

## How I build

I use AI coding agents as implementation and review collaborators. I remain responsible for problem framing, scope, architecture constraints, acceptance criteria, reviewing changes, diagnosing failures, and deciding whether the evidence is strong enough to release. I do not treat generated code or a passing demo as proof of user value without tests, observable behavior, or external validation.

## Current focus

I am a full-time Master of Technology in Artificial Intelligence Systems student at NUS-ISS, seeking a full-time Singapore internship for **March-August 2027** in AI Product, AI Evaluation & Automation, or Applied AI / Product Deployment.

## Background

- **National University of Singapore · NUS-ISS** — MTech in Artificial Intelligence Systems, full-time, expected August 2027.
- **Pennsylvania State University** — B.S. in Computer Science, Mathematics minor, GPA 3.840/4.000.
- Experience across AI imaging product requirements, voice-AI implementation, mobile system testing, and independent product delivery.

[LinkedIn](https://www.linkedin.com/in/kairui-liu-ai-product/)
