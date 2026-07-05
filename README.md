# radar-notes

Automated daily scan archive for **@ericsson-kuma**. Every entry here is a real,
dated snapshot produced by cron jobs on my dev box — **no hand editing, no
padding**. Files only appear on days a scan actually returned something.

- [`github/`](github/) — daily GitHub contribution-radar digest (good-first-issues
  and recently-active repos matched to my focus areas), archived from `gh-radar`.
- [`papers/`](papers/) — daily arXiv paper-radar digest (new papers scored for
  relevance by a local LLM), archived from `paper-radar`.

Layout is `github/YYYY-MM-DD.md` and `papers/YYYY-MM-DD.md`. Generated and pushed
by `gh-keepalive daily`; a day with nothing to archive is skipped, not filled.
