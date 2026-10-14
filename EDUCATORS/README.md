# Educators — OPENFRAMEWORKS

**Project:** OPENFRAMEWORKS  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/openframeworks/openframeworks  
**Pinned commit:** `74d2770153dc65fda03a483cc61f69230ce43e79`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5c35355a778e552b2c6a76347881b33d46f7b5184ee3383b1b579bcc42239313`  
**Date:** October 2026

## Teaching with OPENFRAMEWORKS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `5c35355a778e552b2c6a76347881b33d46f7b5184ee3383b1b579bcc42239313` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.
