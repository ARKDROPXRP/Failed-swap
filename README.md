# Failed-swap
Failed SHX-to-XLM Swap, 231,000 SHX Sent, No XLM Received, UI Not Updating

**Description**:
On May 25, 2025, at ~14:34 UTC, I initiated an SHX-to-XLM swap on StellarTerm using my Ledger Nano wallet (public key: GASWB7DAUKKZT5B45IN75MUZSKKLQVEOFDFKXWPKPD3TWCLKQQGVUB75). The transaction (hash: c8a9175474f03902b6b48771f1d025d9aeb928f5c6024daf62518c2cc257785d) is successful on Lumenscan (https://lumenscan.io/txns/c8a9175474f03902b6b48771f1d025d9aeb928f5c6024daf62518c2cc257785d), debiting 231,000 SHX to GC4GID52ZLKGCAAB5CL37HTZ3SBIR2RGYDFKJQVYWJ6BFNYLX4OCE7IZ, but no XLM was credited to my wallet. StellarTerm’s activity/swaps section has not updated, possibly due to a UI bug or insufficient liquidity in the SHX/XLM pair.

**Steps to Reproduce**:
1. Initiated SHX-to-XLM swap on StellarTerm.
2. Signed transaction with Ledger Nano.
3. Checked Lumenscan: 231,000 SHX sent, 0 XLM received.
4. StellarTerm UI shows no swap activity.

**Expected Behavior**:
XLM should have been credited to my wallet, or SHX refunded if the swap failed.

**Actual Behavior**:
No XLM received, SHX sent to GC4GID52…, UI not updated.

**Additional Info**:
- Contacted support@stellarterm.com with no response.
- Is GC4GID52… a StellarTerm market maker? Can the SHX be refunded?


**Environment**:
- Browser: [e.g., Chrome on Mac OS Saq
- Device: Ledger Nano
- Date: May 25, 2025
