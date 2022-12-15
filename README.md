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

## Demo video

[![Watch the video](/public/assets/anypay-video-screenshot.png)](https://vimeo.com/780526823)

Demo video link: https://vimeo.com/780526823

## Impacts and potentials

Web3 is scary for most typical users due to scams and loss of assets.
However, it has huge potentials for financial accessiblity and inclusion.

Use-case of straight forward payment without worrying about various chains and tokens is powerful.

Get paid among friends and families for splitting costs.
Get paid as creators and freelancers for their works.
Get paid as businesses by sending invoices as payment requests.

With Axelar's cross chains capabilities, espcially deposit addresses,
web2's popular payment UXs (i.e Stripe, Patreon, Gumroad, etc) can be implemented easily on web3.
