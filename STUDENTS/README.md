# Students — TAILOR4J

**Project:** TAILOR4J  
**Category:** CLOTHING_MANUFACTURING  
**Upstream:** https://github.com/InderParmar/Tailor4Job.git  
**Pinned commit:** `1d9991c1c3efd7be7d551b6d4e53c6ef6d46da4d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `3fd7b6f3f62b965af2009c2475cc533ba1613c9213f715434870d914be749652`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `1d9991c1c3efd7be7d551b6d4e53c6ef6d46da4d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `3fd7b6f3f62b965af2009c2475cc533ba1613c9213f715434870d914be749652`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
