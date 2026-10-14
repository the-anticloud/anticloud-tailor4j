# Ethics — TAILOR4J

**Project:** TAILOR4J  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/InderParmar/Tailor4Job.git  
**Pinned commit:** `1d9991c1c3efd7be7d551b6d4e53c6ef6d46da4d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3fd7b6f3f62b965af2009c2475cc533ba1613c9213f715434870d914be749652`  
**Date:** October 2026

## Position

TAILOR4J is packaged for offline deployment with a verifiable audit trail. The
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
