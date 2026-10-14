# Students — INVENTREE

**Project:** INVENTREE  
**Category:** SUPERMARKETS  
**Upstream:** https://github.com/inventree/InvenTree  
**Pinned commit:** `9478c25a70696feddafbff139e6f41d3b0abe78d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cb1bcde8962aea99c581444de7976761867570277743d59c6b071426637f68cf`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `9478c25a70696feddafbff139e6f41d3b0abe78d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `cb1bcde8962aea99c581444de7976761867570277743d59c6b071426637f68cf`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
