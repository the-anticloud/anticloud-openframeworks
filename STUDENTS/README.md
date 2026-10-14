# Students — OPENFRAMEWORKS

**Project:** OPENFRAMEWORKS  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/openframeworks/openframeworks  
**Pinned commit:** `74d2770153dc65fda03a483cc61f69230ce43e79`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5c35355a778e552b2c6a76347881b33d46f7b5184ee3383b1b579bcc42239313`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `74d2770153dc65fda03a483cc61f69230ce43e79`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `5c35355a778e552b2c6a76347881b33d46f7b5184ee3383b1b579bcc42239313`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.
