# Educators — ANGULAR_POINT_OF_SALE

**Project:** ANGULAR_POINT_OF_SALE  
**Category:** POS_SYSTEMS  
**Upstream:** https://github.com/tariqbuilds/hunts-point-pos.git  
**Pinned commit:** `7073a9c0a408b88faf2acc9b00282b4e257dae5a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e5dc087d7e714178fa811628301eaff9478c64375f6843c1375f6ac775ddb91d`  
**Date:** October 2026

## Teaching with ANGULAR_POINT_OF_SALE

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `e5dc087d7e714178fa811628301eaff9478c64375f6843c1375f6ac775ddb91d` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
