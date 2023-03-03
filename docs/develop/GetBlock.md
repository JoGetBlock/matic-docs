id: GetBlock
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
image: https://wiki.polygon.technology/img/polygon-wiki.png

## Overview 

Polygon node connection is an advantage for any dApp: from on-chain games to trading bots. Polygon (MATIC) API endpoint by GetBlock is an instrument of choice for many early-stage teams.This is an easy step-by-step tutorial on how to create and deploy an ERC-20 smart contract on the Polygon test network using a virtual wallet [(Metamask)](https://metamask.io/), Risk, and [GetBlock](https://getblock.io/nodes/matic/).

## What you will learn

To create a smart contract in this tutorial, you will learn how to use GetBlock to:

Create a smart contract on Polygon (Mumbai) using [GetBlock](https://getblock.io/) endpoints. 

## What you will do

Following the tutorial, you will:
1. Get started on GetBlock and access GetBlock test nodes
2. Create a wallet address with Metamask
3. Add balance to the wallet (using test tokens)
4. Use Remix to compile and deploy a Smart Contract
5. Check contract status

### Preparatory Steps

1. So the first step is to [sign up with Getblock](https://account.getblock.io/sign-in) via wallet or email

![img](https://i.ibb.co/TKmT3nP/unnamed.png)

2. Create an endpoint for polygon Tesnet (Mumbai)

![img](https://i.ibb.co/P9csqmL/unnamed-1.png)

Then enter Metamask and choose to connect a network manually, connect your Metamask to the Polygon Testnet Network adding your GetBlock endpoint to the “RPC URL” line

![img](https://i.ibb.co/b7kmNPW/unnamed-1.png)
![img](https://i.ibb.co/26W1Djb/unnamed-2.png)

If you have a no balance in your account, you can request tokens on mumbai faucet here: https://mumbaifaucet.com/

## Smart Contract Development

Go to [Remix](https://remix.ethereum.org/) (Remix is a web-base Integrated Development Environment (IDE) for Ethereum smart contract development in Solidity).
Let's take “Storage.sol” from Remix as an example of a contract

![img](https://i.ibb.co/7JxRcS5/unnamed-2.png)

Proceed by deploying 

![img](https://i.ibb.co/FHQvbb0/unnamed-3.png)

Choose the Injected provider “Metamask”

Check that our smart contract has been created on the Network 

![img](https://i.ibb.co/tXTZdcn/unnamed-5.png)

Smart contract URL: https://mumbai.polygonscan.com/address/0xa4d552dce0e26564ec1737638705584ce9ed351b

### Testing the Smart Contract 

There were 12 in the storage. To check, change the value to 14.

![img](https://i.ibb.co/gtW34mp/unnamed-6.png)

In the “Store” field, enter the number 14 and save it on the network after confirming the operation in Metamask.

Waiting for the transaction to be added to the network block.

Then we make sure that the saved value has changed from 12 to 14

![img](https://i.ibb.co/XxcNqNN/unnamed-8.png)

All done! Congratulations on deploying your smart contract.

This is how you deploy an easy Smart Contract on Polygon using Remix and GetBlock.

If you have any additional questions or would like to share your experience, feel free to join our [community of Web3 developers](https://discord.gg/Jb9UZZUHN7) who are always ready to chat. 





