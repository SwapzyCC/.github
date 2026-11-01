<p align="center">
  <a href="https://swapzy.cc"><img src="logo.png" width="96" height="96" alt="Swapzy"></a>
</p>

<h1 align="center">Swapzy</h1>

<p align="center">
  <b>A crypto wallet that lives in your Discord.</b><br>
  Hold, send and swap USDT, USDC, ETH, BNB, POL, SOL, LTC and BTC without leaving the chat.
</p>

<p align="center">
  <a href="https://swapzy.cc"><img src="https://img.shields.io/badge/swapzy.cc-website-111111?style=for-the-badge" alt="Website"></a>
  <a href="mailto:support@swapzy.cc"><img src="https://img.shields.io/badge/support-support%40swapzy.cc-5865F2?style=for-the-badge" alt="Support"></a>
</p>

---

### What it does

- 💰 **Hold**: deposit USDT, USDC or the native coin of six chains, and see one balance instead of six wallets.
- ⚡ **Send**: tip another Discord user instantly and for free, or withdraw to any outside address for a flat, published fee.
- 🔁 **Swap**: trade between supported assets, across chains, at a rate quoted before you commit.

No app to install, no extension, no seed phrase. Your Discord account is your account.

> [!IMPORTANT]
> **Swapzy is custodial.** Your balance is credited to your Discord account and
> settled from wallets Swapzy controls. That is what makes free transfers between
> users possible, and it means you trust Swapzy the way you trust an exchange.
> Keep long-term savings somewhere you hold the keys.

### Chains

| Chain           | Native | USDT | USDC |
| --------------- | :----: | :--: | :--: |
| Ethereum        |  ETH   |  ✅  |  ✅  |
| BNB Smart Chain |  BNB   |  ✅  |  ✅  |
| Polygon         |  POL   |  ✅  |  ✅  |
| Solana          |  SOL   |  ✅  |  ✅  |
| Litecoin        |  LTC   |  —   |  —   |
| Bitcoin         |  BTC   |  —   |  —   |

### Open source

The node-side services we build for UTXO chains are public under BSD-3-Clause and run
anywhere Docker does.

| Project | What it is | Image |
| ------- | ---------- | ----- |
| [**ltc-replay**](https://github.com/SwapzyCC/ltc-replay) | Durable ZMQ tap and replay service for a Litecoin Core node, pruned nodes included. A consumer that restarts asks for what it missed instead of losing deposits. | `ghcr.io/swapzycc/ltc-replay` |
| [**btc-replay**](https://github.com/SwapzyCC/btc-replay) | The same service for a Bitcoin Core node. | `ghcr.io/swapzycc/btc-replay` |

### Contact

- Website: [swapzy.cc](https://swapzy.cc)
- Support and security reports: [support@swapzy.cc](mailto:support@swapzy.cc)
