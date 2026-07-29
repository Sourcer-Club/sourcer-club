# Sourcer.club

Free, open-source recruiter sourcing tools. No login, no infrastructure, no catch.

**Live at:** [sourcer.club](https://sourcer.club)

## Tools

- **[SignalScoper](https://sourcer.club/signal/)** — Spotlight search across 228 role profiles, persona + technical signal keywords.
- **[RepoScoper](https://sourcer.club/repo/)** — GitHub developer search through a recruiter's lens.
- **[ReputeScoper](https://sourcer.club/repute/)** — Stack Overflow developer search, expert-level signal.

## Structure

```
/                  landing page
/signal/           SignalScoper (+ roles.js)
/repo/             RepoScoper
/repute/           ReputeScoper (+ per-city data files, NOTICE.md for Stack Exchange data attribution)
```

Each tool is a single-file, zero-infrastructure HTML app. No build step — this repo is served as-is via Cloudflare Pages.

## License

Code: MIT, see [LICENSE](LICENSE).
ReputeScoper additionally bundles data under CC BY-SA 4.0 — see [repute/NOTICE.md](repute/NOTICE.md).

## About

Built by [John Rambo Rajendran](https://github.com/Sourcer-Club). Sourcing is a craft of research and signal-reading, not keyword matching.
