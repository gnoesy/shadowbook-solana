# Perps Confidential Program (Arcium MXE)

This module represents the confidential execution layer of ShadowBook.

Here, position data is handled in encrypted form.
Liquidation checks and PnL calculations compute privately using Arcium.

Nothing inside this layer exposes trader intent publicly.

This directory will contain:

- Encrypted position struct
- Private liquidation logic
- Private PnL computation
- Minimal settlement output
