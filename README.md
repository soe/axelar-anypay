# Anypay powered by Axelar
Making cross-chain payment simple with just a link (i.e: Stripe Payment Link)

With Anypay you can share your personalized payment link, and others can easily pay from any chain supported by Axelar.
Payers and payees no longer need to worry of losing tokens and go through numerous steps of hassels.

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
