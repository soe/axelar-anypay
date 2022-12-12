# Anypay powered by Axelar
Anypay is the simplest way to get paid in crypto from various chains powered by Axelar

Anypay makes cross-chain payment simple with just a link (i.e: Stripe Payment Link)

![anypay payment forms](/public/assets/anypay-main.png)

With Anypay you can share your personalized payment link via email or DM, and others can easily pay from any chain supported by Axelar.

Payers and payees no longer need to go through numerous steps of hassels and to worry about losing cryptos along the way.

## Instructions

```sh
# copy .env
cp .env.example .env

# install dependencies
yarn

# (if local) 1st terminal: launch local cross-chain development
# (if testnet) skip this, no need to deploy contract
yarn local-dev:start

# start the ui
yarn dev
```
