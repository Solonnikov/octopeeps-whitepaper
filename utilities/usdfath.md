# $FATH

**Fathom ($FATH) is the native utility token of the OctoPeeps ecosystem, deployed on the Polygon blockchain.**

* Symbol: $FATH
* Contract: `0xFc5B2a8947DFd3f7BD2ffE11e97238240aF5F868`
* Total ever created: 150,000,000 $FATH
* Minting: permanently disabled

### The supply is final

$FATH was minted as NFT staking rewards from a fixed cap. In September 2026 that programme ended and the contract was permanently closed.

* 25 Sep 2026 - final staking snapshot, all reward rates set to zero, 22,507,834.46 $FATH airdropped to 161 wallets
* 27 Sep 2026 - the remaining unminted supply was sent to the burn address, every minting permission was removed, and contract ownership was renounced

No one can mint another $FATH - not the team, not anyone. The `owner()` function returns the zero address and every minting permission has been removed. From here $FATH only moves between holders.

### A note on the number you see on explorers

Polygonscan shows a total supply of 100,000,000, while 150,000,000 tokens really exist.

This is a quirk of the contract, not hidden supply. The 50,000,000 minted at deployment was created through a path that does not increment the counter the `totalSupply()` function reports; only the 100,000,000 minted afterwards as staking rewards is counted. Every token in every wallet is real and verifiable, and because minting is renounced, neither number can ever increase.

### What $FATH is used for

* Minting NFTs - Octo Kiddos 2.0 can be minted with $FATH
* The on-chain casino - Loot Cave, Coin Toss, Dice Den, Fortune Wheel and Derby Dash all run on $FATH: <https://octopeeps.com/play>
* Raid Boss - community boss hunts in Discord, with $FATH rewards
* Bocto - pay for your subscription in $FATH: <https://bocto.octopeeps.com/en/pricing>
* Badges - the FATH Millionaire badge for holders of 1,000,000 or more: <https://octopeeps.com/dapps/tba>
* Raffle Market - buy raffle tickets

### How to earn $FATH

Staking has ended, but $FATH is still earned by beating the Raid Boss in Discord, winning in the on-chain casino, and through community giveaways, raffles and campaigns. These pay out from the community treasury, not from new supply.

### How to buy $FATH

* QuickSwap, deepest liquidity: [FATH / POL](https://dapp.quickswap.exchange/swap?type=best&from=ETH&to=0xFc5B2a8947DFd3f7BD2ffE11e97238240aF5F868&chainId=137)
* Any Polygon DEX aggregator - 1inch, Jumper, OKX DEX
* Chart and liquidity: [DexScreener](https://dexscreener.com/polygon/0xFc5B2a8947DFd3f7BD2ffE11e97238240aF5F868)

Always verify the contract address before swapping: `0xFc5B2a8947DFd3f7BD2ffE11e97238240aF5F868`
