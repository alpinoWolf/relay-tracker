# Relay Stats Tracker 🌉

A clean, lightning-fast web application to track your true cross-chain volume and routes on the Relay Protocol. No wallet connection required. 100% free community tool.

**Live Demo:** [alpinowolf.github.io/relay-tracker](https://alpinowolf.github.io/relay-tracker/)

## ✨ Features
* **No Wallet Connection:** Completely safe. Just paste any EVM, Solana, or Bitcoin address.
* **Macro Stats:** See your total bridged volume, transaction count, and unique chains used.
* **Fee Breakdown:** Track exactly how much you've paid in network gas versus Relay protocol fees.
* **Route Analysis:** View your most frequent bridging routes (e.g., Base → Arbitrum).
* **Transaction History:** Drill down into individual transactions with dates and amounts.
* **Shareable Cards:** Generate and download a premium glassmorphism stat card for 𝕏 (Twitter).

## 🛠️ How It Works
* **Frontend:** Pure HTML/CSS/JS with a custom glassmorphism dark-mode UI.
* **Backend:** Serverless Cloudflare Worker proxy to safely query the Relay API.
* **Data Handling:** Custom mathematical logic to handle decimal shifts across different blockchain architectures (EVM 18 decimals, Solana 9 decimals, Bitcoin 8 decimals).

## ⚠️ Disclaimer
Data is sourced directly from on-chain APIs. Values are approximate and may not reflect hidden routes, subsidized gas, or native token fluctuations. Some zero-volume transactions (like token approvals) are logged naturally as part of the cross-chain routing process. Not financial advice.

## ☕ Support the Builder
This tool was built by [@alpinoWolf](https://twitter.com/alpinoWolf) for the web3 community. It is 100% free with no ads, VC money, or paywalls. If it saved you time, tips are always appreciated but never expected.

* **EVM (ETH/Base/Arb):** `0x6249723445128956aaa6251ec6fda192c386ed3c`
* **Solana (SOL/USDC):** `6KEFH6L7jDrGbAmEpoFmm98z6TEVXGh1XXaxiu84ZtYF`
* **Bitcoin (BTC):** `bc1q9ehq9x08pdcqmca9elqm0l6t2d0a2e8kqypshz`
