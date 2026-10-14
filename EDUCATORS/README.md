# Educators — INVENTREE

**Project:** INVENTREE  
**Category:** SUPERMARKETS  
**Upstream:** https://github.com/inventree/InvenTree  
**Pinned commit:** `9478c25a70696feddafbff139e6f41d3b0abe78d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cb1bcde8962aea99c581444de7976761867570277743d59c6b071426637f68cf`  
**Date:** October 2026

## Teaching with INVENTREE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `cb1bcde8962aea99c581444de7976761867570277743d59c6b071426637f68cf` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
