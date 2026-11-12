# Contributing

Prices change weekly. Corrections are the most valuable contribution.

## Report a wrong or stale price

Open an issue with:

1. The model and provider (e.g. `bytedance/seedance-2.5` on `Fal`)
2. The resolution tier and the price you see (USD per second)
3. A link to the provider's public pricing page, or a screenshot of the billed amount

`data/` is generated, so please don't hand-edit it in a PR — an issue with a source link is enough and
the next export will carry the fix.

## Suggest a missing model or provider

Open an issue with the model name, the provider's docs link and its price per second per resolution.
Models with a fixed per-second price are in scope. Adult/NSFW-capable models are out of scope for this
index.

## Improve docs or tooling

PRs welcome for `README` wording, `docs/`, and example scripts that consume `data/`.
