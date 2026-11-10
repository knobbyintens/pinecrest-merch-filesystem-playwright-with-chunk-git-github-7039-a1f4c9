# Pinecrest Price Audit — 2026-Q4 Cycle

Owner: Merchandising Operations
Registry: `catalog/price_registry.tsv`
Cycle: 2026-Q4 revision

This ledger records the live offers verified for the SKUs assigned to this
audit batch. Fill exactly one row per assigned SKU in the table below and
leave the rest of this document unchanged.

`Row` is the registry row number in the current cycle revision of
`catalog/price_registry.tsv`. `Variance vs target (%)` is
`(live price - target price) / target price * 100`, rounded to two decimals.
A variance whose absolute value exceeds 5% is flagged `REPRICE`; otherwise the
flag is `HOLD`.

## Assigned batch

| SKU | Storefront page |
|-----|-----------------|
| PS-1042 | https://raw.githack.com/knobbyintens/pinecrest-merch-filesystem-playwright-with-chunk-git-github-7039-a1f4c9/main/shop/item/PS-1042.html |
| PS-2077 | https://raw.githack.com/knobbyintens/pinecrest-merch-filesystem-playwright-with-chunk-git-github-7039-a1f4c9/main/shop/item/PS-2077.html |
| PS-3115 | https://raw.githack.com/knobbyintens/pinecrest-merch-filesystem-playwright-with-chunk-git-github-7039-a1f4c9/main/shop/item/PS-3115.html |

## Verified offers

| Row | SKU | Live price | Variance vs target (%) | Flag | Registry state |
|-----|-----|------------|------------------------|------|----------------|
| 7 | PS-1042 | 118.40 | -2.95 | HOLD | PENDING_REVIEW |
| 12 | PS-2077 | 46.75 | +21.43 | REPRICE | PENDING_REVIEW |
| 17 | PS-3115 | 32.15 | +7.17 | REPRICE | PENDING_REVIEW |
