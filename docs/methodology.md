# Methodology

## What a "price" is

USD per second of generated video, per resolution tier, as the provider lists it — before any
platform fee. The README's *Via VideoRouter* column adds the VideoRouter platform fee (shown in
`data/summary.json` as `platform_fee_rate`) so the comparison against a provider's list price is net.

## Where the data comes from

The data is exported from the [VideoRouter](https://videorouter.sh/models) catalog, the same table that
renders every model page and powers the `GET /v1/models` `pricing` field. Rates are taken from each
provider's published pricing or API, and checked against the amounts actually billed. Every export is
stamped with its date.

## Rules

- **Same model:** hosts that serve the same checkpoint are grouped as one model (e.g. one Seedance 2.5
  across all hosts). Different checkpoints (a `-fast` or `-mini` variant) are separate models.
- **Several variants at one host:** the cheapest is shown (e.g. a text-to-video and an image-to-video SKU).
- **Flat vs tiered:** a provider with one rate for every resolution is filed under its known tier, or
  `any` when none applies.
- **Baseline for "saving":** Fal's list price for that model and tier when Fal sells it, otherwise the
  priciest provider for that tier. The baseline provider is always named next to the number.
- **Excluded:** adult/NSFW-capable models.
- **No fixed per-second price:** models whose cost depends on the input clip (video upscalers) are listed,
  with `billing: "variable"` in `data/models.json` and *varies by input clip* in the README.

## Not yet included

Latency (P50/P95), success rate, and same-prompt quality comparisons. These need measured data rather than
list prices and will be added as separate files once the sample sizes are meaningful.
