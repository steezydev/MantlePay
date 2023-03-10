<img src="./public/banner.png">

<p>
  <img src="https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white">
  <img src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white">
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white">
</p>

# MantlePay
## Overview

MantlePay is a blockchain-based platform that enables the creation of invoices and secure payments on the Ethereum network through the Mantle network. With MantlePay, sending and receiving payments become more convenient and efficient.

## Project Structure

- `dapp` - MantlePay Next.js front-end application to interact with the smart-contract.
- `contract` - MantlePay smart-contract built with Solidity

## Features

- Create invoices with specified amount, comment, payment wallet (optional), and invoice recipient (optional).
- Receive payment links for the created invoices that can be forwarded through any messenger.
- Notify the invoice recipient and display the unpaid invoice in their personal account by specifying their wallet.
- Option to specify a payment wallet for the funds, or have the funds sent to the wallet used to create the invoice.

## Technical details

MantlePay consists of two main components: a Solidity smart contract and a dapp that provides a user-friendly interface for interacting with the contract. The app operates on the <a target="_blank" href="https://www.mantle.xyz/">Mantle</a> network, which allows for fast, cheap and secure blockchain transactions on the Ethereum blockchain.

## How to use MantlePay

1. Install and set up a wallet that supports the Ethereum and Mantle networks.
2. Access the MantlePay dapp through your wallet or a web browser.
3. Create an invoice by specifying the amount, comment, payment wallet (optional), and invoice recipient (optional).
4. Forward the payment link for the created invoice to the desired recipient.
5. The invoice recipient can view the unpaid invoice in their personal account and make the payment through their own wallet.

## Conclusion

MantlePay provides a streamlined solution for secure payments on the blockchain. With its user-friendly interface and the added convenience of invoice creation and payment links, MantlePay offers a convenient and efficient alternative to traditional cryptocurrency transfers.
