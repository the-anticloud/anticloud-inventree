# Independent Insurance — INVENTREE

**Project:** INVENTREE  
**Category:** SUPERMARKETS  
**Upstream:** https://github.com/inventree/InvenTree  
**Pinned commit:** `9478c25a70696feddafbff139e6f41d3b0abe78d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `cb1bcde8962aea99c581444de7976761867570277743d59c6b071426637f68cf`  
**Date:** October 2026

## Why AI-specific cover matters

Deploying AI in a regulated sector creates liability surfaces that ordinary
technology cover does not reach: inference liability, audit-trail liability,
data-breach liability and IP-infringement liability.

## How this project's architecture reduces insurable risk

| Risk | Cloud AI | INVENTREE with AIOSS |
|---|---|---|
| Audit-trail loss | high — vendor-controlled logs | low — append-only chain, verifiable offline |
| Data breach in transit | high — data transits external servers | low — no external endpoint |
| Compliance violation | high — cannot satisfy air-gap requirements | low — structural |
| IP liability | moderate | low — pinned provenance chain |

## Evidence package for an insurer

- AIOSS chain verification for head `cb1bcde8962aea99c581444de7976761867570277743d59c6b071426637f68cf`
- The 16-check register with per-check evidence hashes
- Framework control mapping in `BENCH.json`

## Contact

lois@0-1.gg
