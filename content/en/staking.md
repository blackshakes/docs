---
title: Staking
description: Follow this guide to nominate our validator nodes on Kusama and Polkadot. 
position: 2
category: 'Staking'
---

## How to Nominate

Nominators are one type of participant in the staking subsystem of Polkadot, responsible for appointing their stake to the validators, the second type of participant.

Validators are active participants in the network that engage in block production.

## Setting up Stash and Controller keys

If you haven't already setup your accounts, follow the instructions in the [Accounts](/blog/accounts) page

## Using Polkadot{.js} UI

### Step 1: Bond your tokens

* Navigate to the [Polkadot-JS UI](https://polkadot.js.org/apps/#/staking).

* Click the "Account Actions" subsection ([link](https://polkadot.js.org/apps/#/staking/actions))

* Click the "+ Nominator" button

  ![setup nominator modal screenshot](https://wiki.polkadot.network/docs/assets/polkadotjs_nominate_button.png)

  

  Select a "value bonded" that is **less** than the total amount of DOT you have, leaving some left over to pay for transaction fees. Transaction fees are currently around 0.01 DOT, but are dynamic and based on a variety of factors. You should keep at least 1.5-2.0 DOT in your account to be on the safe side.

  Choose a payment destination that makes sense to you, do not use an exchange account. If you're unsure, choose "Stash account (increase amount at stake)" to simply acrue the rewards into the amount you're staking and earn compound interest.

  ![payment destination screenshot](https://wiki.polkadot.network/docs/assets/payout/01.png)

### Step 2: Nominate a validator

After bonding your tokens it is time to take action and nominate a validator node. Click on "Nominate" on an account you've bonded and you will be presented with another popup asking you to select a validator. Find the address for the Blackshakes Validator node for Kusama or Polkadot on the [Blackshakes Staking](http://www.blackshakes.net/staking) page.

![setup nominator screenshot](https://wiki.polkadot.network/docs/assets/polkadotjs_setup_nominator2.png)

Select our nominator, confirm the transaction, and you have successfully nominated. Nominations will become active in the next era, approximately 24 hours on Polkadot.

## Conclusion

You have successfully nominated our [validator node](/staking)



## Further exploration

[Learn](https://wiki.polkadot.network/docs/en/maintain-guides-how-to-unbond) how to stop nominating and unbond your tokens

