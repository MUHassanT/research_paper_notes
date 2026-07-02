# research_paper_notes

Research paper summaries, literature reviews, and insights at the intersection of **artificial intelligence** and **cybersecurity** — adversarial machine learning, intrusion detection, malware classification, and related areas.

This repo is a running log of papers I read as I build toward research experience and grad school applications (MS/PhD in CS). Every note follows the same structure so old notes stay useful instead of turning into a pile of half-finished thoughts.

## 📂 Structure

```
research_paper_notes/
├── papers/
│   ├── adversarial-ml/          # adversarial examples, robustness, attacks/defenses
│   ├── intrusion-detection/     # network/host-based IDS, anomaly detection
│   ├── malware-classification/  # static/dynamic analysis, ML-based detection
│   ├── nlp-security/            # NLP/speech applied to security, or security of NLP models
│   └── misc/                    # anything that doesn't fit cleanly yet
├── templates/
│   └── paper-summary-template.md
├── resources/
│   └── reading-list.md          # queue of papers to read next, with source/priority
├── LICENSE
└── README.md
```

Each paper gets its own markdown file inside the relevant `papers/<topic>/` folder, named like:
`YYYY-firstauthor-shorttitle.md` (e.g. `2023-goodfellow-adversarial-examples.md`).

## 📝 Note format

Every summary uses [`templates/paper-summary-template.md`](templates/paper-summary-template.md) — citation, TL;DR, problem, method, results, critique, and how it connects to other papers I've read. Keeping the format consistent makes it much easier to go back and actually use these notes later (e.g. when writing a lit review or prepping for an interview).

## 🎯 Focus areas

- **Adversarial ML** — robustness, attacks, defenses, evasion
- **Intrusion detection** — anomaly detection, network traffic classification
- **Malware classification** — feature engineering, static/dynamic analysis with ML
- **NLP × security** — where language models and security intersect

## 📖 Currently reading

See [`resources/reading-list.md`](resources/reading-list.md) for the active queue.

## Why this exists

I'm a first-year CS student building toward research experience and eventually grad school. This is less "polished portfolio" and more "honest paper trail" — happy to have it critiqued or used by anyone else working through the same papers.

## License

MIT — see [LICENSE](LICENSE).
