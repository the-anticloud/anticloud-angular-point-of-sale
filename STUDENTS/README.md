# Students — ANGULAR_POINT_OF_SALE

**Project:** ANGULAR_POINT_OF_SALE  
**Category:** POS_SYSTEMS  
**Upstream:** https://github.com/tariqbuilds/hunts-point-pos.git  
**Pinned commit:** `7073a9c0a408b88faf2acc9b00282b4e257dae5a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e5dc087d7e714178fa811628301eaff9478c64375f6843c1375f6ac775ddb91d`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `7073a9c0a408b88faf2acc9b00282b4e257dae5a`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `e5dc087d7e714178fa811628301eaff9478c64375f6843c1375f6ac775ddb91d`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
