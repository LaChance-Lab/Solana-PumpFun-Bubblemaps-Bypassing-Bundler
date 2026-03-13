# Stealth PumpFun Bundler

> Atomic Jito-bundled pool creation + multi-wallet buy snipe on PumpFun — all in a single bundle.

---

## How It Works

1. **Create Pool + Dev Buy** — Deploys the Meteora DBC pool and executes the developer's initial buy in the same transaction.
2. **Bundled Snipe Buys** — Additional wallets buy into the pool atomically via Jito bundles, guaranteeing inclusion in the same slot.
3. **Zero front-run risk** — Everything lands on-chain together or not at all.

---

## Example Bundle

| Step | Transaction |
|---|---|
| **Jito Bundle** | [`c08409...1944f6`](https://explorer.jito.wtf/bundle/c08409300bc804a7849c7e8d6eefeb894838014df56e00268062c7cc3e1944f6) |
| **Create Pool + Dev Buy** | [`5R4d2Q...664dv`](https://solscan.io/tx/5R4d2QLkQHZf4E1A4PYur2PC6HW1EYLuJjdzBXKruN4xDfRDmDmCno3sUok7LYQNttaakU9b8HQ5NMEas3i664dv) |
| **Buy 1** | [`5TkGs3...5Cqd`](https://solscan.io/tx/5TkGs3ExdCG91gMobrUCvyctk1pmfU9qiqot695TaHGVmW3J2U9y5GQN24NXxZ9sd9cvsnvCsUXWuE3Eu4Tn5Cqd) |
| **Buy 2** | [`56yq6J...7N57`](https://solscan.io/tx/56yq6JfbtHD8dLeon9G9ryNguM57kJLzznj7AvEDPXgztdGdRVS8cRw5FkvChPMZQUgPg67nEFPvCETjzcPt7N57) |

---

## Tech Stack

- **Solana** — on-chain execution
- **Meteora DBC** — Dynamic Bonding Curve pool program
- **Jito Bundles** — atomic multi-tx inclusion with tip
- **TypeScript** — bundler orchestration

---

## Contact

Reach out for custom builds or integration support:

**Telegram** — [@lachancelab](https://t.me/lachancelab)
