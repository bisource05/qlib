# Notes on this fork

- Upstream: https://github.com/microsoft/qlib
- Fork: https://github.com/bisource05/qlib
- Source that led me here: https://x.com/carm1nee/article/2113257064352915664 ("The 10 Most Dangerous GitHub Repos in Trading", Carm1ne, Oct 22, 2026)
- Role in that stack: Research desk - quant platform

## What it is

Microsoft's AI-oriented quant platform: data in, models, then backtest, as the base layer that the automated research agent below builds on.

## Caution

Keep only factors and models that survive on data they were never trained or tuned on. Everything else is likely curve-fitting.

## Status

Forked Oct 27, 2026. Nothing here has been run, configured, or connected to any account, API key, or real money. Paper / dry-run first, and only after a walk-forward backtest with fees, a look-ahead check, and 30 days on paper.
