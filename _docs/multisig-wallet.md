---
title: Multisig Vault General
tags:
  - usage
  - featured
---
A Multisig Vault is a wallet with multiple keys. This allows you to exponentially increase security (if used correctly) or for shared custody as well. Shared custody is when you want to share a wallet with a group of people.

Multiple devices are advised. The Vault will work with other BlueWallet apps and PSBT compatible wallets, like Electrum, Specter, Coldcard, Cobo vault, etc. It is advised that you use multiple devices, and consider store these devices in multiple locations if you see it is fit for your use case.

{% include image.html img="tip2.png" alt="Multisig bitcoin wallet" %}

## Editing Keys

You can create all Vault keys in the same device, and remove or edit these keys later. Having all keys on the same device has the equivalent security of a regular Bitcoin wallet. As advise above, please consider multiple devices from the start.

{% include image.html img="tip3.png" alt="Multisig bitcoin wallet" %}

## Vault Backups

On the wallet options you will find your Vault backup and watch-only (coordination) backup. This backup is like a map to your wallet. It is essential for wallet recover in case you lose one of your seeds. 

{% include image.html img="tip4.png" alt="Multisig bitcoin wallet" %}

## Importing Vaults

To import a Multisig, use your multisig backup file and use the import feature. If you only have extended keys and seeds, you can use the individual import fields on the Add Vault creation option.

{% include image.html img="tip5.png" alt="Multisig bitcoin wallet" %}

## Advanced options

By default BlueWallet will generate a 2of3 Vault. To create a different quorum or to change the address type, activate the advanced options in the Settings.