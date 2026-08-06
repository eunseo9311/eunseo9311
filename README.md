아래 전체를 그대로 복사해 GitHub 프로필 `README.md`에 붙여넣으면 됩니다.

```md
## Hi, I'm Eunseo Song 👋

CS undergraduate and product-minded open-source engineer working across **AI products, developer experience, and systems infrastructure**.

I notice friction, trace it to the underlying system, and keep building until the solution reaches real users.

[**Portfolio**](https://eunseo-profile-inky.vercel.app/) · [**LinkedIn**](https://linkedin.com/in/eunseo-song-65543a393) · [**Blog**](https://velog.io/@eunseo_song/posts)

---

### 🚀 Selected Work

- **UnivAI** — AI learning platform with **500K+ registered users worldwide**. As the sole engineer on a three-person team, built the product across its React frontend, Spring Boot backend, AI pipeline, and AWS infrastructure. Rebuilt the PDF processing pipeline to reduce processing time for a 2,000-page document from approximately 3 minutes to under 20 seconds. Reached **#1 in Education on the South Korean App Store**.

- **[CommitCat](https://github.com/eunseo9311/commit-cat)** — Cross-platform desktop companion that reacts to Git activity in real time. Built solo with Rust, Tauri, React, and TypeScript, and shipped across macOS, Windows, and Linux with an automated release pipeline. Earned **100+ GitHub stars within four days**.

- **[Eatssu](https://github.com/EAT-SSU/Server)** — Backend for a university dining platform serving 5K+ users. Reduced monthly incidents by 67% through stronger type and exception handling, and cut monthly server costs by approximately 85% through an RDS-to-EC2 Docker MySQL migration.

---

### 🛠 Open Source Contributions

- **[Hugging Face / Tokenizers](https://github.com/huggingface/tokenizers)** — Eliminated a full-vocabulary clone in `get_vocab_size(true)` with a zero-allocation calculation across the Rust core and Node binding, and added regression coverage for overlapping tokens ([#2074](https://github.com/huggingface/tokenizers/pull/2074)). A Hugging Face maintainer's local benchmark using the LLaMA-3 tokenizer configuration showed an improvement from approximately **5.70 ms to 1.35 µs—about 4,200×**. Merged.

- **[Verilator](https://github.com/verilator/verilator)** — Fixed an Apple clang build failure ([#7327](https://github.com/verilator/verilator/pull/7327)), added missing regression coverage ([#7328](https://github.com/verilator/verilator/pull/7328)), and improved eight vague diagnostic messages across seven source files ([#7329](https://github.com/verilator/verilator/pull/7329)). All three PRs merged.

- **[InsForge](https://github.com/InsForge/InsForge)** — Fixed inconsistent empty-string handling between single-record and bulk-write paths, added regression coverage, and helped resolve user-reported issue [#1429](https://github.com/InsForge/InsForge/issues/1429) through three merged PRs ([#1364](https://github.com/InsForge/InsForge/pull/1364), [#1444](https://github.com/InsForge/InsForge/pull/1444), [#1457](https://github.com/InsForge/InsForge/pull/1457)).

- **[GPGPU-Sim](https://github.com/gpgpu-sim/gpgpu-sim_distribution)** — Contributed a simulation correctness fix ([#338](https://github.com/gpgpu-sim/gpgpu-sim_distribution/pull/338)), removed unnecessary computation from the simulation loop ([#339](https://github.com/gpgpu-sim/gpgpu-sim_distribution/pull/339)), and consolidated 20 near-identical methods into one helper, removing 186 lines of duplicate code ([#340](https://github.com/gpgpu-sim/gpgpu-sim_distribution/pull/340)). All three PRs merged.

- **[Spring Initializr](https://github.com/spring-io/initializr)** — Modernized 31 files with idiomatic Java ([#1747](https://github.com/spring-io/initializr/pull/1747)) and investigated an external service outage affecting the documentation build ([#1757](https://github.com/spring-io/initializr/pull/1757)). Named as a contributor in the official v0.24.0 release notes.

- **[HelixDB](https://github.com/HelixDB/helix-db)** — Corrected the package name in the TypeScript SDK documentation ([#923](https://github.com/HelixDB/helix-db/pull/923)). Merged.

---

### 🔬 Research

**[LLM Jailbreak Comparative Study](https://github.com/eunseo9311/llm-jailbreak-study)** — Independent research conducted under Prof. Bong Jun Choi at Soongsil University's AI Security Lab.

Evaluated the adversarial robustness of Claude Sonnet and GPT-4o across four experiment types and nine prompt categories. Identified a turn-count reversal effect in extended multi-turn attacks: Claude's refusal rate shifted from 0% to 50%, while GPT-4o remained at 0%.

---

### 🧰 Stack

- **Systems:** Rust · C/C++ · Tauri
- **Backend:** Java · Spring Boot · MySQL
- **Frontend:** TypeScript · React · JavaScript
- **Cloud:** AWS EC2 · RDS · S3 · CloudFront · Route53 · CloudWatch
- **AI:** Python · Anthropic API · OpenAI API · Adversarial ML
```
