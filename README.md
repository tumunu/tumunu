# 👋 Kia orana, we’re **Tumunu**

Defensive forensic tools — built open‑source to **prove** skill, not just pitch it.

> **Tumunu** is a father–son project from Aotearoa /New Zealand focused on producing *defensible*, open‑source digital‑forensic tooling. Version `v0.1.0` ships a CLI that images disks bit‑for‑bit, verifies hashes, and writes a tamper‑proof audit log—ready for chain‑of‑custody.

<p align="center">
  <a href="https://tumunu.com"><img src="https://img.shields.io/badge/website-tumunu.com-blue?style=for-the-badge&logo=google-chrome" /></a>
  <a href="https://github.com/tumunu/tumunu.github.io/releases"><img src="https://img.shields.io/github/v/release/tumunu/tumunu.github.io?label=release&style=for-the-badge" /></a>
  <a href="https://github.com/tumunu/tumunu.github.io/stargazers"><img src="https://img.shields.io/github/stars/tumunu/tumunu.github.io?color=FCD535&style=for-the-badge&logo=github" /></a>
  <a href="https://github.com/tumunu/tumunu.github.io/network/members"><img src="https://img.shields.io/github/forks/tumunu/tumunu.github.io?color=E6007A&style=for-the-badge&logo=github" /></a>
</p>

---

## 🚀 Quick start

```bash
# 1 Download & verify (Linux example)
curl -LO https://github.com/tumunu/tumunu.github.io/releases/download/v0.1.0/tumunu-cli-linux-x86_64.tar.gz
curl -LO https://github.com/tumunu/tumunu.github.io/releases/download/v0.1.0/SHA256SUMS
sha256sum -c --ignore-missing SHA256SUMS    # should print OK

# 2 Extract & run
 tar -xzf tumunu-cli-linux-x86_64.tar.gz && cd tumunu-cli
 sudo ./tumunu image /dev/sdb --output-case=case_2025‑001 --hash=sha256
```

*macOS and Windows binaries are on the same release page.*

Full docs ➜ [Wiki Quickstart](https://github.com/tumunu/tumunu.github.io/wiki/Quickstart)

---

## ✨ Why Tumunu?

| Feature                            | What it means                                                                          |
| ---------------------------------- | -------------------------------------------------------------------------------------- |
| **Bit‑for‑bit imaging**            | Reads every sector, no write‑back, no surprises                                        |
| **Audit‑log JSON**                 | SHA‑256/BLAKE3 hashes + event timeline, ready for court                                |
| **Plugin framework**               | Inject custom classifiers or provenance logic in < 50 LOC                              |
| **Cross‑platform**                 | Native builds for Linux, macOS (Apple Silicon), Windows                                |
| **Language‑agnostic architecture** | Core in Rust; plugins or infra in Python, C#, Bicep—pick the right tool for each layer |
| **Pure CLI**                       | Pipeable output; integrate into your own IR tool‑chain                                 |

Roadmap & discussion in [Projects](https://github.com/tumunu/tumunu.github.io/projects).

---

## 🛠️ Built with

* **Rust** – high‑performance core CLI and imaging engine
* **Bash** – glue scripts and one‑liner helpers
* **Python** – prototype plugins and analysis utilities
* **C / C++** – low‑level disk I/O experiments
* **C# / . NET** – Vaults secure‑storage module and Windows helpers
* **Bicep** – Azure infrastructure‑as‑code templates and pipelines
* **JavaScript / TypeScript** – web front‑ends and helper tools
* **GitHub Actions** – CI, tests, binary releases
* **MkDocs Material** – documentation, served via GitHub Pages

---

## 🤝 Contributing / Hiring us

* **Open issues** labelled `good first issue` if you want to hack.
* PRs welcome; please follow the [CONTRIBUTING](CONTRIBUTING.md) guide.
* Need custom workflows, training, or on‑site imaging? **Email** [project@tumunu.com](mailto:project@tumunu.com) with the subject `Tumunu Consult`.

---

## 🌐 Connect

[![Website](https://img.shields.io/badge/website-tumunu.com-blue?style=for-the-badge\&logo=google-chrome)](https://tumunu.com)
[![Email](https://img.shields.io/badge/email-project@tumunu.com-D14836?style=for-the-badge\&logo=gmail\&logoColor=white)](mailto:project@tumunu.com)

---

© 2025 Tumunu • NZBN 9429044372194 • Wellington, Aotearoa & Enuamanu, Cook Islands
