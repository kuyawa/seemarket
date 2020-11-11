# SeeMarket.one

## Prediction Markets on Harmony Network

[SeeMarket.one](https://seemarket.one)

![SeeMarket](docs/seemarket.png)

SeeMarket is a port of polymarket.com to showcase the simplicity, speed and low cost of developing apps on Harmony. Developers can use all tools available like Remix and Truffle to create, test and deploy smart contracts easily both on testnet and mainnet, gas use is the lowest in the market being Harmony the cheapest and fastest blockchain of all with less than 5 secs finality.

## Similarities

SeeMarket and PolyMarket share the same vision of providing a platform for prediction markets, creators can register events with possible outcomes and voters can express their opinion by betting on their preferred options. At event date, a winner option is selected and all money is awarded to those who selected that option proportionally to the total money collected and the quantity of votes submitted in a winner take all scenario. 

## Key differences

PolyMarket uses Pools, Tokens and Trading because they took the commonly used pool contracts (Uniswap, Balancer) and adapted them to their core adding innecessary complexity and technical debt. Trading share tokens (buy, sell) before events end is allowed but senseless, adding innecessary liquidity to pools is another key difference we don't need.

SeeMarket was thought from the beginning to use a specifically tailored contract that would allow to register events with all its options as part of the contract, storing all votes inside the contract without the need for pools, liquidity, tokens or trading, just vote and count. That's a great advantage UI wise since the user isn't bothered with complex financial jargon. In SeeMarket, one vote has ONE value and users can submit as many votes for as many options as they wish, no need to trade, buy, sell or add liquidity.

Another key difference is in PolyMarket you have to sign up and provide an email which in decentralized apps has no place, that drives away users that want to try the app without being bothered. In SeeMarket we ask for nothing, users can try the app right away with their own wallet, no questions asked, period. SeeMarket does not collect information about the users, does not serve as custodian of any money and does not provide accounts or addresses, all interaction is done directly on-chain by the user with their own wallet of choice.

So in essence, both DApps share the same vision but differ in the smart contract implementation, Prediction markets is a great idea and it could be imlemented easily on Harmony Network in just a couple of weeks.

