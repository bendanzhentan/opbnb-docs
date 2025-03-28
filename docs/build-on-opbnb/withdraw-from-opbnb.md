---
title: Withdraw Tokens from opBNB
icon: code
index: yes
dir:
  order: 2
---

:::caution 
This is a living document and is susceptible to changes. 
:::

If you want to transfer your tokens from opBNB to BSC network, you can do so by using the [opBNB bridge dApp(Testnet)](https://opbnb-testnet-bridge.bnbchain.org/) or [opBNB bridge dApp(Mainnet)](https://opbnb-bridge.bnbchain.org), which is a tool that allows you to move your tokens across different networks.

Before you initiate the withdrawal process, you need to make sure that you have connected your wallet and switched to the opBNB network.

<img
  src={require('../../static/img/withdraw.png').default}
  alt="opBNB-bridge-withdraw"
  style={{zoom:"48%"}}
/>

Click withdraw button and confirm the transaction with your wallet. It will take a while to confirm.

<img
  src={require('../../static/img/withdraw-confirm.png').default}
  alt="opBNB-bridge-withdraw-confirmation"
  style={{zoom:"48%"}}
/>

There are 2 steps after you submit your withdrawal request. 

1. Your withdrawal will be part of a Layer 2 transaction that will be submitted to the Layer 1 BSC network. This means that your tokens will be locked on the opBNB network and unlocked on the BSC network. Then your withdrawal status will change to *Waiting for Proof*, which indicates that the transaction is pending verification.
2. You need to wait until the transaction is ready to be collected after the challenge window. The challenge window is a period of time during which anyone can challenge the validity of the transaction. If no one challenges the transaction, it will be finalized and you can collect your tokens on the BSC network.

![withdraw-status](../../static/img/withdraw-status.png)

3. Then you can collect your token. 

:::info:
The challenge window is shorter on the testnet of opBNB, so you can test the withdrawal process faster. On the mainnet of opBNB, the challenge window will be 7 days long.
:::

<!-- ## What is the withdrawal confirmation time?

The withdrawal confirmation time is XXX . -->