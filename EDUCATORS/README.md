# Educators — TAILOR4J

**Project:** TAILOR4J  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/InderParmar/Tailor4Job.git  
**Pinned commit:** `1d9991c1c3efd7be7d551b6d4e53c6ef6d46da4d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3fd7b6f3f62b965af2009c2475cc533ba1613c9213f715434870d914be749652`  
**Date:** October 2026

## Teaching with TAILOR4J

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `3fd7b6f3f62b965af2009c2475cc533ba1613c9213f715434870d914be749652` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
