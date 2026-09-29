# **BitShot**

**BitShot - finder of seed phrases & private keys in images**

## **Description**

**BitShot's purpose is to find screenshots, images and photos that contain seed phrases and private keys from crypto wallets.** It was created with a purpose of having a high precision and fast tool that also covers various formats, including seeds/keys encoded in QR codes, in taken photos that are blurry or low light/quality and photos of handwritten/printed mnemonics (for example on a piece of paper). It will find both typical 2 columns mnemonic format or mnemonic written in 1 line or any other format for mnemonics and private keys.

## **Features**

- Scans recursively through all subfolders, will scan full disk if pointed at root directory

- GUI and CLI versions for both Windows and most of Linux distros

- Saves findings and found seeds/keys in separated folder and in csv/json formats

- GUI has a panel for observing findings and copying their content

- Supported language for mnemonics is English, image's interfaces can be in any language

- Seed phrases format: 12, 15, 18, 21, 24, 25, and 33 words, wordlists: bip39 slip39, monero and pgp

- Private keys: raw hex, Ethereum 0x format, WIF, encrypted BIP38, and extended keys. Additionally the formats used by Solana, Cardano, Tezos, Stellar, XRP, Sui, Mina and Qubic

- Tested speed: 5 minutes for a folder of around 2'500 screenshots taken with smartphone. A library of 10,000 mixed photos, images and screenshots would take about 15 minutes on 8-core laptop

- Possibility to scan only for mnemonics, private keys and QR codes detection are optional and can be turned off

- Sensitivity of detection can be adjusted as well as CPU cores to utilise. Scanner has pause/resume functions if working with big sets of images and need to pause

**Demo interface is available on website**

**Demo video:** https://youtu.be/53BW8a2PJJc?si=DDAQdWvvN3XGvjqM

**Showcase of BitShot usage with scraped GitHub images:** https://youtu.be/l2EqIn6CD8s?si=izJvSTBzVzGyz1qd

## **Contacts & Links**

**Website** - https://bitshot.org

**XMPP/Jabber:** bitshot@jabbim.club
