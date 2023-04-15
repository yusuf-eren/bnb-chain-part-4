# BNB Smart Chain - Part 4

## In this case, I deployed BEP20 token to testnet.

## How to Run?

1. Go to your metamask and add BNB Smart Chain to your networks.
2. Go to account details > 12 keyword phrase. Copy and paste it into `secrets.json` mnemonic.
3. Switch to your testnet account and visit https://testnet.binance.org/faucet-smart/ to collect test coins (0.1 BNB)


```
npm install
```

```
npx hardhat compile
```

```
npx hardhat run --network testnet scripts/deploy.js
```