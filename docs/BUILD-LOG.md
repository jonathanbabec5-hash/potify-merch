# November 25, 2026 · POTIFY Merch Directory

**Question.** Connect the book, film and games to a real merchandise destination.

**Source and change.** potify-first-cycle at `7bc29685d6decd1f3d1bbbb0216f837bc7701a51`. Exact official store and tote destinations from the published book view. New integration reference; no order data or live catalog synchronization.

**Observed result.** The public entry page returned HTTP 200 and rendered local content in Chromium at a 390 × 844 viewport.

```sh
node --test tests/project.test.mjs
```

**Next acceptance check.** From a sample referral, open the intended listing and reconcile a consenting test order with the platform if available.

**Owner and decision.** Chance owns the public release and approves campaign copy. Product stock, pricing, order export and current conversion are unknown. The reference never processes payment.

This dated record describes the developer package. Verify remote commit and tree in the publication receipt before announcing a GitHub release.
