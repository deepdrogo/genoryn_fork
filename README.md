# Genoryn Krypton · Drogoz community showcase

> **Repository status: legacy source fork.** The code in this repository is GENORYN 1.1-era source, **not the current Krypton implementation**. This refreshed presentation showcases the independent upstream project supported by Drogoz Network. For current source, downloads and instructions, use [genoryn/genoryn](https://github.com/genoryn/genoryn) and [genoryn.io](https://genoryn.io/).



<div align="center">

<a href="https://genoryn.io/"><picture><source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/genoryn/genoryn/main/docs/images/banner-light.png"><img src="https://raw.githubusercontent.com/genoryn/genoryn/main/docs/images/banner-dark.png" width="100%" alt="Genoryn Krypton — quantum-resistant, private money"/></picture></a>

### Genoryn Krypton · Private digital cash, reimagined

**An independent open-source project supported by Drogoz Network.**

Rust-based digital cash with shielded transfers, a 21 million GNR cap,<br/>
a redesigned desktop wallet and GPU / CPU mining.

</div>

<table>
<tr>
<td valign="top" width="33%"><b>01 · Post-quantum design</b><br/><br/><sub>zk-STARK spending proofs and hybrid ML-KEM encryption, as documented by the project. No independent security audit yet.</sub></td>
<td valign="top" width="33%"><b>02 · Wallet &amp; verification</b><br/><br/><sub>Several wallets with individual passwords and one combined balance. Network charts, light-client verification or your own full node, private transfers and payment proofs.</sub></td>
<td valign="top" width="33%"><b>03 · GPU &amp; CPU mining</b><br/><br/><sub>KryptoHash proof of work with proportional mining rewards. The published schedule starts at 5 GNR per block, with halvings every 2,100,000 blocks.</sub></td>
</tr>
</table>

### Current Krypton interface

<table>
<tr>
<td width="50%"><a href="https://raw.githubusercontent.com/genoryn/genoryn/main/docs/images/wallet.webp?v=20261104"><img src="https://raw.githubusercontent.com/genoryn/genoryn/main/docs/images/wallet.webp?v=20261104" alt="Genoryn Krypton updated network overview and live charts" width="100%"/></a></td>
<td width="50%"><a href="https://raw.githubusercontent.com/genoryn/genoryn/main/docs/images/wallets.webp?v=20261104"><img src="https://raw.githubusercontent.com/genoryn/genoryn/main/docs/images/wallets.webp?v=20261104" alt="Genoryn Krypton multi-wallet tab with individual locks and combined balance" width="100%"/></a></td>
</tr>
<tr><td align="center">Network &amp; mining overview</td><td align="center">Several wallets, one total</td></tr>
<tr>
<td width="50%"><a href="https://raw.githubusercontent.com/genoryn/genoryn/main/docs/images/mining.webp?v=20261104"><img src="https://raw.githubusercontent.com/genoryn/genoryn/main/docs/images/mining.webp?v=20261104" alt="Genoryn Krypton mining controls and proportional reward display" width="100%"/></a></td>
<td width="50%"><a href="https://raw.githubusercontent.com/genoryn/genoryn/main/docs/images/proofs.webp?v=20261104"><img src="https://raw.githubusercontent.com/genoryn/genoryn/main/docs/images/proofs.webp?v=20261104" alt="Genoryn Krypton history and payment proof verification" width="100%"/></a></td>
</tr>
<tr><td align="center">GPU / CPU mining</td><td align="center">Payment proofs</td></tr>
</table>

<sub>Current project-published Krypton screenshots, reviewed November 4, 2026. The overview displays a mainnet-labelled snapshot; the multi-wallet, mining and proof views are devnet examples. Displayed balances, network figures and rewards are illustrative, time-specific UI content, not live statistics or earnings promises.</sub>

<div align="center">
<br/>
<b><a href="https://genoryn.io/">Website</a></b> ·
<a href="https://genoryn.io/explorer.html">Explorer</a> ·
<a href="https://github.com/genoryn/genoryn/releases/latest">Downloads</a> ·
<a href="https://genoryn.io/docs.html">Documentation</a> ·
<a href="https://github.com/genoryn/genoryn">Official source</a> ·
<a href="https://github.com/genoryn/genoryn/blob/main/SECURITY.md">Security</a>
<br/><br/>
<sub>Krypton is a new network, not a promise that legacy GENORYN wallets or balances migrate. Use current official instructions. Not independently audited; not investment advice.</sub>
</div>

<br/>



## About this repository

The existing Rust source and history are preserved unchanged. Its Cargo workspace identifies version 1.1.0 and contains the older GENORYN applications and libraries. The legacy RandomX / Orchard / Halo 2 implementation must not be confused with Krypton's KryptoHash / zk-STARK design.

- [Historical source documentation](LEGACY-README.md): retained setup, architecture and protocol details for this fork only.
- [Current official Krypton source](https://github.com/genoryn/genoryn): use this for current development.
- [Current official releases](https://github.com/genoryn/genoryn/releases/latest): obtain current software and verification instructions here.

This is a community-support presentation, not a claim that Drogoz Network owns or controls the independent protocol.
