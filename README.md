# effector-landing

Interactive landing page for [effectorHQ](https://github.com/effectorHQ) — a type system for AI agent capabilities.

## Usage

Open `index.html` directly in a browser, or serve it:

```bash
npx serve .
# or
python3 -m http.server 8080
```

## What's inside

Six interactive sections in a single `index.html` file:

| Tab | What it shows |
|-----|--------------|
| **Overview** | Value proposition, paradigm table, three core primitives, repo catalog |
| **Capability Graph** | D3 force-directed graph — types as nodes, Effectors as edges |
| **Discovery** | Live type-indexed search demo with structural subtype matching |
| **Composition** | Pipeline builder with real-time type checking (TC_OK / TC_ERR_MISMATCH) |
| **Security** | effector-audit findings: permission drift, prompt injection, interface-permission mismatch |
| **ClawHub Data** | Charts from the 13,729-skill corpus analysis that grounds the effector-types stdlib |

## Deploy

The file is fully self-contained (D3.js loaded from CDN). Drop it anywhere static hosting is available:

```bash
# GitHub Pages — push to gh-pages branch, set root to /effector-landing
# Vercel / Netlify — drag and drop the folder
```

## Related repos

- [effector-spec](https://github.com/effectorHQ/effector-spec) — The specification
- [effector-types](https://github.com/effectorHQ/effector-types) — Standard type library
- [effector-graph](https://github.com/effectorHQ/effector-graph) — Discovery CLI
- [effector-compose](https://github.com/effectorHQ/effector-compose) — Pipeline engine
- [effector-audit](https://github.com/effectorHQ/effector-audit) — Security scanner

## License

This project is currently licensed under the [Apache License, Version 2.0](LICENSE.md) 。
