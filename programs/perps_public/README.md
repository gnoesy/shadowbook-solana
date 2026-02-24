# Perps Public Program (Solana)

This module represents the public settlement layer of ShadowBook.

It is responsible for:

- Market configuration
- Encrypted position storage
- Settlement result recording
- On-chain anchoring of final PnL

It does NOT store readable position intent.
It only stores encrypted data and final settlement results.
