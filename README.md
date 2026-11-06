# Three Impact AI Search Observatory: open data

Measured data on how AI crawlers and AI assistants treat small-business websites, published by [Three Impact](https://threeimpact.com). Free to use under [CC BY 4.0](LICENSE).

| File | What it holds |
|---|---|
| `data/ai-crawlers.json`, `data/ai-crawlers.csv` | The [AI crawler registry](https://threeimpact.com/ai-crawler-registry): 32 AI agents and robots.txt tokens (OpenAI, Anthropic, Perplexity, Google, Apple, Microsoft, Meta, Amazon, ByteDance, Common Crawl, DuckDuckGo, Mistral, Cohere, You.com, AI2 and the shared `__usage_ai-training` group) with documented user agent, purpose, robots.txt behaviour, verification method and a link to the operator's own documentation. Checked 2026-11-06. |
| `data/observatory-q4-2026.json` | The [AI Search Observatory, Q4 2026 edition](https://threeimpact.com/ai-search-observatory): share of AI fetches by purpose, by bot and by operator, plus a six-month trend, from 12 small-business websites (crawls 2026-08-01 to 2026-10-30). |
| `data/observatory-q4-2026-bots.csv` | The per-bot table from the Observatory as a spreadsheet. |

## Method and privacy

Observatory figures come from server-side request logs of small-business sites hosted on cite-met, classified by user agent. They are aggregates only: no site is named, no per-site number is published, every figure covers at least five sites, and shares are site-weighted means so no single site can drive a figure. The full method and its limits are on the [Observatory page](https://threeimpact.com/ai-search-observatory#methodology). Please keep the sample size (12 sites) and the period next to any number you quote.

## Ownership

Three Impact is published by the team behind cite-met and Space & Story. The Observatory data comes from sites hosted on cite-met.

## Cite

See [CITATION.cff](CITATION.cff), or:

> Halat, M. (2026). *The AI Search Observatory, Q4 2026 edition.* Three Impact. https://threeimpact.com/ai-search-observatory

The files here are copies of the live downloads at `https://threeimpact.com/data/`, which are always the current version.
