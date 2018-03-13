---
title: "Download"
date: 2018-01-12T01:30:50Z
draft: false

---


# Vertcoin Wallets

The Vertcoin Development team provides two different wallets that users can store their Vertcoin
on. Third parties provide both mobile and hardware wallets. There
is also the option to store your Vertcoins without electronics using a <a href="https://vertaddress.org/" target="_blank"> paper wallet</a>.

# Vertcoin Core (Most Secure)

This is the Vertcoin reference client (forked from upstream
<a href="https://github.com/bitcoin/bitcoin" target="_blank">Bitcoin Core</a> and forms the backbone of the Vertcoin Network.
Vertcoin Core is a trustless wallet meaning that you download and verify the entire
blockchain history for yourself. Additionally, you help to redistribute the blockchain
to new users, ferry transactions around the network and help prevent <a href="https://bitcoin.stackexchange.com/questions/61151/eclipse-attack-vs-sybil-attack" target="_blank">eclipse attacks</a>.
If you intend to mine Vertcoin, the Core wallet is a requirement. Our new Lightning Network Wallet will also include these features as well.

|Platform|
|--------|
|[Windows](https://github.com/vertcoin/vertcoin/releases/download/0.12.0/vertcoin-v0.12.0-windows-64bit.zip)|
|[MacOS](https://github.com/vertcoin/vertcoin/releases/download/0.12.0/vertcoin-v0.12.0-OSX-64bit.dmg)|
|[Ubuntu/Debian](https://github.com/vertcoin/vertcoin/releases/download/0.12.0/vertcoin-qt_0.12.0_amd64.deb)|
|[Other Linux](https://github.com/vertcoin/vertcoin/releases/download/0.12.0/vertcoin-v0.12.0-linux-64bit.zip)|
|[Linux (ARM)](https://github.com/vertcoin/vertcoin/releases/download/0.12.0/vertcoin-v0.12.0-linux-arm.zip)|
|<a href="https://github.com/vertcoin/vertcoin" target="_blank">Source Code</a>|

# Electrum-VTC

Electrum-VTC is a lightweight wallet forked from upstream <a href="https://github.com/spesmilo/electrum" target="_blank">Electrum</a> which does
not require you to download the full blockchain. The trade-off being that you are
trusting the miners that they have correctly verified the transactions in the blockchain.
Whilst this means there is no synchronization time, you are no longer working
trustlessly and not helping to redistribute the Vertcoin blockchain to new users.
Users should not mine into Electrum-VTC due to the load caused by many small payments
that is put on the Electrum servers. Users should use Vertcoin Core for mining instead.

|Platform|
|--------|
|[Windows (Installer)](https://github.com/vertcoin/electrum-vtc/releases/download/2.9.3.5/electrum-vtc-2.9.3.5-windows-setup.exe)|
|[Windows (Standalone)](https://github.com/vertcoin/electrum-vtc/releases/download/2.9.3.5/electrum-vtc-2.9.3.5-windows.exe)|
|[MacOS](https://github.com/vertcoin/electrum-vtc/releases/download/2.9.3.5/electrum-vtc-2.9.3.5-macosx.dmg)|
|[Linux](https://github.com/vertcoin/electrum-vtc/releases/download/2.9.3.5/electrum-vtc-2.9.3.5.tar.gz)|
|<a href="https://github.com/vertcoin/electrum-vtc" target="_blank">Source Code</a>|

# Mobile Wallets

Currently there are only third-party mobile wallets availible for VTC. We are working
on bringing you development team provided wallets on Android and iOS and are in the
approval stage of this process. In the meantime, currently there is only <a href="https://play.google.com/store/apps/details?id=com.coinomi.wallet" target="_blank">Coinomi</a>
on Android that supports VTC.

# Hardware Wallets

A hardware wallet allows you to store your Vertcoins without the private keys ever
having to leave the device. This prevents remote attackers or viruses on your computer
from redirecting or stealing your coins. Currently the only hardware wallet for VTC is
sold by <a href="https://www.ledgerwallet.com/" target="_blank">Ledger</a>.

# Paper Wallets

A paper wallet is simply a private key written on a piece of paper. This is known as
"cold storage" since access to the coins is not stored digitally and is thus not
susceptible to viruses or hardware failure. Paper wallets are not easy to spend however
and thus are suitable for long-term storage. The private key from the paper wallet
can be imported into Electrum-VTC or Vertcoin Core at a later date and spent from there.

|Wallet Generator|
|----------------|
|<a href="https://vertaddress.org" target="_blank">Vertaddress</a>|
|<a href="https://walletgenerator.net/?currency=Vertcoin" target="_blank">WalletGenerator</a>|

# Third Party Wallets

These are wallets that are not produced by the Vertcoin development team and don't into any of
the other categories. 

## Exodus

<a href="https://www.exodus.io/" target="_blank">Exodus</a> is a multicoin desktop wallet that relies on backend servers to provide blockchain data to
the wallet which enables instant synchronisation but is completely trusted as far as we can tell.
Exodus is closed-source but allows you to keep your private keys. Vertcoin is still in beta on Exodus
so you will need to enable it from the settings page. 
