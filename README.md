# Evangelos Moschou

CS student focused on **AI agent engineering** — orchestration, evaluation, and
cost-efficient LLM delegation. Systems background (CUDA, C) meets applied ML, and
I build the frontend too when the project needs a face.

## What I've built

**AI agents**

- 🔁 **[contributor-sandbox](https://github.com/EvangelosMoschou/contributor-sandbox)** —
  delegation pipeline for cheap coding models: measured a 15M-token exploration cost in a
  real run, designed the prompt/sandbox process that removes it, and shipped the safety
  checklist + cost-analysis tooling.
- 🌉 **[dsh-agent-bridge](https://github.com/EvangelosMoschou/dsh-agent-bridge)** —
  run a coding agent as a tool-callable subagent over the Agent Client Protocol, with a
  deterministic verification gate that stamps unverified output instead of trusting it.

**Full-stack & frontend**

- 🏋️ **[NexusFit](https://github.com/EvangelosMoschou/NexusFit)** —
  white-label gym platform in Next.js 15 / React 19: marketing site, member portal, admin
  CMS and an AI workout copilot, multi-tenant over SQLite with offline/PWA mode, rate
  limiting and signed sessions. One config object re-brands the whole app; Docker + Caddy
  deploy and 9 Vitest suites included. AGPL-3.0.
- 🍳 **[CookBook](https://github.com/EvangelosMoschou/CookBook)** —
  recipe + culinary-jobs platform: React 18 / TypeScript / Vite 6 front end over an
  Express 5 + SQLite API, responsive from 375 px phones to desktop. The UI doubles as a
  **spec-conformance harness** — every Gherkin acceptance scenario from the SRS can be
  driven into its exact state live, so each criterion is demonstrated rather than described.

**Systems & performance**

- ⚡ **[PaDS_Project4](https://github.com/EvangelosMoschou/PaDS_Project4)** —
  parallel BFS & Afforest connected components in CUDA: direction-optimizing traversal,
  delta-varint compression, 3.6B-edge Friendster graph runs.
- 📡 **[Embedded_assignment](https://github.com/EvangelosMoschou/Embedded_assignment)** —
  multithreaded real-time collector in C for the Bluesky Jetstream firehose on a Raspberry
  Pi Zero W (ARMv6). 86,394 of 86,400 one-second samples, p99 deadline jitter 845 µs,
  **zero dropped frames** across 3.4M messages — plus the analysis and the report.

**Applied ML**

- 📈 **[TradingAgentCI](https://github.com/EvangelosMoschou/TradingAgentCI)** —
  deep RL trading agents on Gymnasium/gym-anytrading (A2C baseline, modular pipeline).
- 🧠 **[NN-Project3](https://github.com/EvangelosMoschou/NN-Project3)** —
  ResNet-style convolutional autoencoder for CIFAR-10 with masked learning and a joint
  MSE+SSIM loss.

## Now

- Building: a Kubernetes/Docker platform project — containerized ML inference served on a
  cluster with CI/CD, GitOps, and autoscaling.
- Open for entry-level roles where agents do the work and I make them reliable.
