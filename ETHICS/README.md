# Ethics — OPENFRAMEWORKS

**Project:** OPENFRAMEWORKS  
**Category:** ARTIST_TOOLS  
**Upstream:** https://github.com/openframeworks/openframeworks  
**Pinned commit:** `74d2770153dc65fda03a483cc61f69230ce43e79`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `5c35355a778e552b2c6a76347881b33d46f7b5184ee3383b1b579bcc42239313`  
**Date:** October 2026

## Position

OPENFRAMEWORKS is packaged for offline deployment with a verifiable audit trail. The
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
