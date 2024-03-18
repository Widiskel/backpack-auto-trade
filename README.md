# auto_trade_backpack_exchange

Auto trade on Backpack exchange with Javascript:

## REQUIREMENT

- Have backpack account. If you dont have, regis ->[Here](https://backpack.exchange/refer/5da696b1-8472-49c3-b43d-7d1fc48845a5)
- Deposit atleast 10 USDC to backpack exchange

## SETUP

1. Create account: [Backpack](https://backpack.exchange/refer/5da696b1-8472-49c3-b43d-7d1fc48845a5)
2. run

```bash
git clone https://github.com/Widiskel/backpack-auto-trade.git
cd backpack-auto-trade
```

3. Create backpack API: https://backpack.exchange/settings/api-keys
4. Install NodeJS: [How to install Nodejs](https://www.geeksforgeeks.org/installation-of-node-js-on-windows) (Version >= v18.16.0)
5. Open file `index.js` and edit this to your `API_KEY` and `API_SECRET`:
6. run

```bash
npm install && node ./index.js
```

## NOTE

- This code will trade in pairs: $SOL/$USDC
- check your trading volume -> [HERE](https://api.backpack.exchange/wapi/v1/statistics/user/volume/quote/USDC?interval=month)

Source from: [solotop](https://github.com/solotop999/auto_trade_backpack_exchange.git)
