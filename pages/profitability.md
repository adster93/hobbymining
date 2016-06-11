---
title: "Is Bitcoin Mining Profitable in 2016?"
permalink: "/mining-profitability/"
seotitle: "Is Bitcoin Mining Profitable or Worth It in 2016?"
layout: page
---
The early days of Bitcoin mining are often described as a gold rush. Satoshi Nakomoto’s invention of Bitcoin, [“a peer-to-peer electronic cash system,”](https://bitcoin.org/bitcoin.pdf) opened up an entirely new frontier, not just of freedom but of profit. Those with a strong interest in such things, namely cypherpunks, cryptographers, technically-minded libertarians and assorted hackers, were first to stake their claim.

_But is there still gold in them thar hills?_

The fact is that Bitcoin mining has grown from a handful of early enthusiasts to a cottage industry to a specialised industrial-level venture. The easy money was scooped out long ago and what remains is buried under the cryptographic equivalent of miles of hard rock.

Today, only those with specialised, high-powered machinery are able to profitably extract bitcoins. While mining is still technically possible for anyone, those with underpowered setups will find more money is spent on electricity than is generated through mining.

![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image002.png)

## Common Mining Terms

![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image004.png)

To understand Bitcoin mining in any depth, it helps to know a few basic technical terms:

**Block:** a group of Bitcoin transactions, as collected from current pending transactions and entered into an ever-growing record of blocks (aka “the blockchain”) by a miner. A new block is created on average every ten minutes.

**Proof of Work Hashing:** this is the function miners perform in order to define a new block. PoW hashing ensures the proper function of the Bitcoin blockchain. Miners compete to solve a cryptographic “puzzle,” known as a _hash._ There are no shortcuts in this process, which can only be solved with raw computational power. By correctly hashing the current block, miners _prove_ their investment of _work_ and are rewarded with a certain number of newly-created bitcoins.

**Block Reward:** the number of newly-created bitcoins. This number was initially set to 50, halved to 25 in late-2012 and will halve again to 12.5 in mid-2016\. This halving process continues, approximately every four years (or every 210,000 blocks), until all 21 million bitcoins are created. This is the only way in which new bitcoins can be created; by miners according to the code’s rate and limit.

**Hashrate:** a measure of a miner’s computational power. The higher their relative power, the more solutions (and hence, block rewards) they’re likely to find. Initially measured in hash per second (**H/s**), due to the increasing speed of mining hardware. H/s was soon commonly pre-fixed with [SI units](https://en.wikipedia.org/wiki/SI#Prefixes) as follows:

*   **Kilohash = KH/s** _(thousands of H/s)_, then
*   **Megahash =** **MH/s** _(millions of H/s)_, then
*   **Gigahash = GH/s** _(billions of H/s)_, then
*   **Terahash =** **TH/s** _(trillions of H/s)_, and even
*   **Petahash =** **PH/s** _(quadrillions of H/s)_.

**Difficulty:** with hashrate shooting up over the years, it would seem blocks would be found by miners ever more rapidly. Bitcoin’s Difficulty measure is what prevents this from happening, ensuring blocks are found roughly every 10 minutes. When total hashrate rises, the Difficulty of POW hashing adjusts upwards - and the inverse also applies. Difficulty auto-adjusts every two weeks (or 2016 blocks).

**BTC / XBT exchange rate:** the current fiat price of Bitcoin; critical for calculating profitability.

**W/xHash/s:** Watts per hashrate per second. Electricity is the major on-going cost of Bitcoin mining. The price paid per Watt will greatly influence profitability.

**Mining Pool:** unless you command a tremendous hashrate, your odds of solving a block by yourself (i.e. “solo-mining”) are extremely low. By banding together with other miners in a so-called pool, your combined odds of solving a block rise proportional to the [pool’s total hashrate](https://blockchain.info/pools). Whenever they solve blocks, pools reward individual miners according to their contributed hashrate (minus commissions and the like).

![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image006.png)

## Calculating Mining Profitability

With these terms in mind, it’s possible to calculate the _current_ profitability of Bitcoin mining for your circumstances. Note that the _future_ profitability of mining cannot be reliably predicted. This is due to the ever-changing nature of the Difficulty modifier and the BTC price, in particular.

To begin, we must select a suitable ASIC mining rig. To aid in selection, the Bitcoin Wiki provides a handy [mining hardware comparison](https://en.bitcoin.it/wiki/Mining_Hardware_Comparison):

![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image008.png)  

The [AntMiner S7](/bitmain-antminer-s7/) is a modern mining rig which offers a good hashrate for its power consumption. It’s pretty much the cutting edge of mining tech so we’ll select it for our example. The S7 is available for[$609 on Amazon](http://amzn.to/26frgMW) or [$450 from BitMain](https://www.bitmaintech.com/productDetail.htm?pid=00020160510034707221GxQ3Yr280661), shipping excluded. Power supply units will add another $150 or so to the price. 

![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image010.png)  

Next, we need to enter the S7’s specs and cost, as well as other info such as power cost and pool fees, into a suitable number-cruncher. CoinWarz.com offers a [good mining profitability calculator](http://www.coinwarz.com/calculators/bitcoin-mining-calculator), which automatically fills in the current _BTC price, Difficulty_ and _block reward_ info.

![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image012.png)

We are using the default _power cost_ of 10c (USD), which is standard for China, but likely to be much higher elsewhere. To determine your own power cost, check [worldwide electricity prices](https://en.wikipedia.org/wiki/Electricity_pricing#Global_electricity_price_comparison) or your utility bill for the exact price. The 2.5% _Pool Fee_ is for AntPool. Smaller pools will generally offer lower or even no fees, but keep in mind they will seldom find blocks. The fees and reward structures of various pools are compared in [this list](https://en.bitcoin.it/wiki/Comparison_of_mining_pools).

Once all the necessary info is entered, hit _Calculate_ for the profitability result:

![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image014.png) _Not a bad result! $800 per year and you can use the miner’s excess heat to warm your home._

## The American Scenarios

Before getting too excited, let’s recalculate using the average _power cost_ per kWh in the USA (~12.5c) and the 12.5 BTC _block reward_ which becomes the new standard in 45 days or so (see [Bitcoin Clock](http://bitcoinclock.com/) for an up-to-date estimate):

![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image016.png)  

It’s not looking so great now. It appears the average American miner makes only $500 a year, assuming difficulty and price hold steady. However, this is a dangerous assumption! As this article was being written, Bitcoin’s hashrate unexpectedly jumped by a massive 30 percent!

![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image018.png)

The compensatory Difficulty spike, expected on the day following reports of this spike, completely alters the previous equation:

_![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image020.png)_

If we bump up the Difficulty in the mining calculator by the corresponding 30%, all profit evaporates! $500 is lost over one year’s worth of mining.

**Unexpected Profit Loss: Difficulty Spikes, Price Crashes, Equipment Failures, Power Cuts, Shipping Delays & More**

![](file://localhost/Users/Jordan/Library/Caches/TemporaryItems/msoclip/0/clip_image022.png)

The above example serves as a perfect illustration of the risks inherent in Bitcoin mining. It’s quite possible that even some big, corporate miners will take strain from such a steep Difficulty spike. The home miner really has no chance to compete in such a challenging environment, unless they have access to free or extremely low-cost electricity…

Also bear in mind that the rate of obsolescence in Bitcoin mining hardware is extremely fast! If (pre-)ordering any such equipment, be aware that potential manufacturing, shipping, customs or other delays could end up being very costly as difficulty rises or price falls during the interim.

There are plenty of other things which can wrong, and such downside risks must always be factored into any sound business plan.

## The Chinese Scenarios

For interest’s sake, let’s examine the situation of Chinese miners, who represent the bulk of Bitcoin mining power for good reason. The results may help us better predict the post-halving Bitcoin environment, as [this article](https://bitcoinaverage.com/blog/what-you-ought-to-know-about-the-july-bitcoin-block-reward-halving) attempts to do.

## Hobby Miners

Certain Chinese regions are over-supplied with electricity, which is also often subsidized. This makes for a really low power cost, which we’ll assume to be 7c for a miner in the right province. Further, most mining hardware is fabricated in China and so can likely be purchased cheaper (and received sooner) by denizens of the Middle Kingdom. We’ll assume a ¾ hardware price.

## Results:

* A small-time Chinese miner with a single S7 connected to AntPool could have made over $1000 annually before the Difficulty spike. That’s twice the profit of their American counterpart!
* After the halving and Difficulty spike, the same miner would lose about $40 per year. For a Bitcoin enthusiast, this is an easily-acceptable loss.

## Industrial Miners

Large-scale mining operations will locate proximate to cheap power sources in remote provinces. Hydro-electric power from dams is a popular option. We can assume a very low _power cost_ for such enterprises, let’s say 5c. Such operations also buy _hardware_ in bulk so we’ll assume they get S7s at half-price, $325\. One thousand S7 units seems a plausible number, which allows us to simply add three zeros to _hash rate_, _hardware_ and _power costs_. Finally, such setups often run their own pools and so we’ll assume zero pool fees.

## Results:

* Before the halving and Difficulty spike, the operation would net $1.4m annually.
* After the halving and Difficulty spike, the operation would profit by about $200k annually.

$200k isn’t great considering the initial hardware investment is $325k. Given the other costs involved in mining, such as property, salaries, maintenance, etc. it appears that marginal mining operations will be forced out of business post-halving. Only those with the latest and greatest hardware and the cheapest electricity are likely to survive. The only wild card is the Bitcoin price. If it rises sufficiently it’ll allow less efficient miners to keep the lights on for longer.

## Conclusion

The average home miner will struggle to recoup the cost of mining hardware and electricity. Profitability is highly unlikely given the current circumstances. The situation may improve in future once ASIC mining hardware innovation reaches the point of diminishing returns. That, coupled with cheap, hopefully sustainable power solutions may once again make Bitcoin mining profitable to small individual miners around the world. This would also greatly improve the decentralisation of the Bitcoin network, hardening it against legislative risk.