# Ethics — ANGULAR_POINT_OF_SALE

**Project:** ANGULAR_POINT_OF_SALE  
**Category:** POS_SYSTEMS  
**Upstream:** https://github.com/tariqbuilds/hunts-point-pos.git  
**Pinned commit:** `7073a9c0a408b88faf2acc9b00282b4e257dae5a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `e5dc087d7e714178fa811628301eaff9478c64375f6843c1375f6ac775ddb91d`  
**Date:** October 2026

## Position

ANGULAR_POINT_OF_SALE is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.
