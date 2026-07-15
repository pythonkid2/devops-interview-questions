# Contributing

Thanks for helping improve this DevOps interview knowledge base!

## Ways to contribute

1. **Fix a bad question** — open a PR editing the Markdown under `questions/<topic>/`.
2. **Add a short answer** — fill _Short interview answer_ / _Detailed explanation_.
3. **Improve labels** — difficulty, topic, or company attribution.
4. **Report noise** — hiring posts misclassified as interview experiences.

## Guidelines

- Keep answers concise and interview-ready.
- Prefer concrete commands / diagrams over fluff.
- Link related questions when useful.
- Do not paste private / confidential employer data.

## Local regeneration

If you run the collector yourself:

```bash
python -m interview_intel.main generate
```

Please do not hand-move generated files into a different layout — change the generator instead.
