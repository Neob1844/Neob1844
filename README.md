# Neob @ Sovereign Stock Token — SOST

Building a native Proof-of-Work Layer 1 that runs on ordinary CPUs and RAM, written from scratch.

## Sovereign Stock Token — SOST

**ConvergenceX** · **cASERT** · **DTD**

A CPU Proof-of-Work blockchain with its own consensus algorithm (ConvergenceX). Since block #25,000 each block reward is split **50% to the miner and 50% to the DTD** (the on-chain distribution draw among recent miners). No ICO. No Premine. No VCs.

| | |
|---|---|
| 🌐 Website | [sostcore.com](https://sostcore.com) |
| ⚙️ Core | [sost-core](https://github.com/Neob1844/sost-core) — C++ node, miner and wallet CLI (ConvergenceX PoW, cASERT difficulty) |
| 📄 Whitepaper | [Whitepaper v4.6](https://sostcore.com/sost-whitepaper.html) ([PDF](https://sostcore.com/whitepaper.pdf)) |
| 🔎 Explorer | [sostcore.com/sost-explorer.html](https://sostcore.com/sost-explorer.html) |

| Key facts | |
|---|---|
| Genesis block | **March 15, 2026 — 18:00:00 UTC** |
| Block time | 600 s target |
| Maximum supply | 4,669,201.54789641 SOST (smooth emission decay, no halvings) |
| Coinbase maturity | 1,000 blocks |
| Reward split | 50% miner / 50% DTD since block #25,000 (V15) |
| Live consensus | V16 |

**History of the reward split:** blocks 0–24,999 paid 50% to the miner, 25% to the Gold Funding Vault and 25% to the PoPC Pool. Since V15 (block #25,000) those two addresses receive no new emission; their existing balances stay on chain and fund the DTD Jackpot. SOST is **not** backed by gold and is not redeemable for gold or any other asset.

**In development, not active on mainnet:** the V17 upgrade (candidate in testing, activation not decided) and the SOST ↔ wSOST bridge (local test networks only).

The code has not been audited by an independent security firm. See [SECURITY.md](https://github.com/Neob1844/sost-core/blob/main/SECURITY.md).

---

## ⚠️ Legacy Disclaimer

The repository `Sovereign-Stock-Token/SOST-Token` (2021) is **deprecated, abandoned, and completely unrelated** to this project. That was an early ERC-20 token concept that was never launched. The current Sovereign Stock Token — SOST is a Native PoW L1 chain with a novel consensus algorithm (ConvergenceX) designed and built entirely from scratch — not a fork of Bitcoin, RandomX, Ethash, or any existing codebase. See [sostcore.com](https://sostcore.com).
