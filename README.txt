AR MINING BOT — Telegram Mini App starter

Design: Oilinx-inspired beige/gold dashboard with Home, Mining, Tasks, Referral, TON Wallet,
Deposit, Withdraw, Account, and Admin sections.

Run demo:
1. Extract the ZIP.
2. Open index.html in a browser.
3. For Telegram, deploy on an HTTPS host and configure a bot via Telegram's BotFather.

This is a front-end prototype only:
- All balances/rewards are simulated; no real mining or earnings happen.
- Deposit/withdraw forms only create local demo requests; no crypto is transferred.
- Wallet connection is not configured.
- Admin controls are local and insecure.
- For production, implement server-side Telegram initData verification, a database, real referral/task
  validation, rate limits, authenticated admin roles, secure TON Connect integration, and audited
  payment handling. Never collect seed phrases/private keys.
