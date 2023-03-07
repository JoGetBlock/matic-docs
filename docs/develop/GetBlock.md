---
id: getblock
title: Deploy a Smart Contract on Polygon using GetBlock
sidebar_label: Using GetBlock
description: Guide to deploy smart contracts using GetBlock
keywords:
  - docs
  - matic
  - polygon
  - getblock
  - create smart contract
  - deploy on polygon
image: https://wiki.polygon.technology/img/polygon-logo.png
---

Polygon node connection is an advantage for any dApp whether it's an on-chain game or trading bots. Polygon API endpoint by GetBlock is an instrument of choice for many early-stage teams. This is an easy step-by-step tutorial on how to create and deploy an ERC-20 smart contract on the Polygon Mumbai testnet using [Metamask](https://metamask.io/), Remix, and [GetBlock](https://getblock.io/nodes/matic/).

You will learn how to use GetBlock to create and deploy a smart contract on Mumbai Testnet using [GetBlock](https://getblock.io/) endpoints. 

## What you will do

Following the tutorial, you will:
1. Get started on GetBlock and access GetBlock test nodes
2. Create a wallet address with Metamask
3. Add balance to the wallet (using test tokens)
4. Use Remix to compile and deploy a Smart Contract
5. Check contract status

### Preparatory Steps

1. The first step is to [sign up with Getblock](https://account.getblock.io/sign-in) via wallet or email

  ![img](https://i.ibb.co/TKmT3nP/unnamed.png)

2. Create an endpoint for Mumbai Testnet

  ![img](https://i.ibb.co/P9csqmL/unnamed-1.png)

  Then enter Metamask and choose to connect a network manually, connect your Metamask to the Mumbai Testnet adding your GetBlock endpoint in the **RPC URL** line

  ![img](https://i.ibb.co/b7kmNPW/unnamed-1.png)
  ![img](https://i.ibb.co/26W1Djb/unnamed-2.png)

If you have zero balance in your account, you can request tokens from the [Mumbai faucet](/develop/tools/matic-faucet.md).

## Smart Contract Development

Go to the [official Remix](https://remix.ethereum.org/) website. Remix is a Web-based IDE for Ethereum smart contract development in Solidity. 

1. Let's take `Storage.sol` from Remix as our example of a smart contract.

  ![img](https://i.ibb.co/7JxRcS5/unnamed-2.png)

2. Deploy the smart contract.

  ![img](https://i.ibb.co/FHQvbb0/unnamed-3.png)

3. Choose the Injected provider as **Metamask**. Check that our smart contract has been created on the network.

  ![img](https://i.ibb.co/tXTZdcn/unnamed-5.png)

Smart contract URL: https://mumbai.polygonscan.com/address/0xa4d552dce0e26564ec1737638705584ce9ed351b

All done! Congratulations on deploying your smart contract.

This is how you deploy an easy Smart Contract on Polygon using Remix and GetBlock.

If you have any additional questions or would like to share your experience, feel free to join our [community of Web3 developers](https://discord.gg/Jb9UZZUHN7) who are always ready to chat. 
