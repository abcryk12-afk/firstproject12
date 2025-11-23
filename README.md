# firstproject12
# NovaStake – Crypto Staking Demo

یہ ایک سادہ Demo پروجیکٹ ہے جس میں:

- Backend: Node.js + Express (dummy staking API, کوئی real blockchain نہیں)
- Frontend: Static HTML + JavaScript pages (login, register, dashboard, stake, withdraw, history)

## Folder Structure

- [package.json](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/package.json:0:0-0:0) – Node dependencies اور scripts  
- [src/](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/src:0:0-0:0)
  - [server.js](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/src/server.js:0:0-0:0) – HTTP server start
  - [app.js](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/src/app.js:0:0-0:0) – Express app اور routes wiring
  - [data/store.js](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/src/data/store.js:0:0-0:0) – in-memory users, wallets, stakes, transactions
  - [middleware/auth.js](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/src/middleware/auth.js:0:0-0:0) – JWT auth middleware
  - [routes/auth.js](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/src/routes/auth.js:0:0-0:0) – register / login
  - [routes/wallet.js](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/src/routes/wallet.js:0:0-0:0) – wallet + dashboard summary
  - [routes/stake.js](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/src/routes/stake.js:0:0-0:0) – staking endpoints
  - [routes/transactions.js](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/src/routes/transactions.js:0:0-0:0) – transaction history
  - [routes/withdraw.js](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/src/routes/withdraw.js:0:0-0:0) – rewards withdraw
- Frontend pages (static):
  - [index.html](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/index.html:0:0-0:0) – landing page
  - [login.html](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/login.html:0:0-0:0) – login form
  - [register.html](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/register.html:0:0-0:0) – registration form
  - [dashboard.html](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/dashboard.html:0:0-0:0) – wallet + rewards overview
  - [stake.html](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/stake.html:0:0-0:0) – stake NST
  - [withdraw.html](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/withdraw.html:0:0-0:0) – withdraw rewards
  - [transactions.html](cci:7://file:///c:/Users/musma/OneDrive/Desktop/nwweb21/transactions.html:0:0-0:0) – history table

## Getting Started (Local)

### 1. Install dependencies

```bash
npm install
