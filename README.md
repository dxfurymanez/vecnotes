# vecnotes

Search my markdown notes by meaning, not keywords

## Installation

```bash
pip install -r requirements.txt
```

## Highlights

- Interactive REPL and one-shot modes
- Reranks by recency when scores tie
- Vectors cached to .npy so re-runs are instant
- sentence-transformers when available, TF-IDF fallback

## Examples

```bash
python search.py ./notes
>> how do I back up my database?
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   └── dependabot.yml
├── docs/
│   ├── configuration.md
│   ├── faq.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .editorconfig
├── .gitignore
├── CONTRIBUTING.md
├── SECURITY.md
├── requirements.txt
└── search.py
```

## Development

```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python -m pytest -q
```

## License

MIT licensed, see LICENSE.
