# Staking in Compendia and how its approach differs from other (D)PoS networks

In this article, we'll be discussing **staking** and how it works in Compendia. There are several misconceptions out there that arise due to the way staking is utilized across different networks. Compendia use a novel way of staking, by combining the way it locks funds to earn more coins in recent proof-of-stake (PoS) networks - with the aspect of vote power traditionally seen in delegated proof-of-stake (DPoS) networks. 

## Staking in (D)PoS networks vs. Compendia

Staking (commonly misspelt as 'stacking' or 'steaking') is the process of leveraging an acquired amount of coins/tokens from a certain blockchain to contribute to the network, by holding them in an address and using an (either online or offline) wallet client to earn revenue based on the amount of coins/tokens held. 

#### PoS (proof-of-stake) networks
In traditional proof-of-stake networks such as Stratis or Cardano requires users to purchase a certain amount of coins, place those in an online wallet and letting the wallet client emulate a certain amount of computing power - which is in turn used to mine/forge new blocks to the blockchain. In more recent proof-of-stake networks such as Cosmos, users are required to lock their funds in an address - with a cooldown period added when wanting to unlock those funds. This way, coins are taken out of circulation rather than just being held (but still immediately spendable) as with Stratis/Cardano. In both situations, anyone can contribute to the network by staking and the more coins staked, the higher likelihood of mining/forging a new block and earning the block reward. You can earn individually from staking, or join a pool.

#### DPoS (delegated proof-of-stake) networks
In delegated proof-of-stake networks, such as ARK or EOS, there are only a set number of nodes (known as validators, block producers or delegates) that are allowed to forge new blocks. In ARK, there are 51 forging delegates and we will use this amount as an example. Contributors have to gain votes from other network participants, who pledge their account balance as votes, and once they have a total amount of votes that put them into the top 51, they will be able to forge blocks and earn rewards. The account balance of participants who vote for a forging validator remain unlocked and therefore it is possible to immediately spend funds held in an address. The amount of votes per address varies across different DPoS networks, but the principle is the same: one coin means one vote power. You can only earn individually if you are one of the top validators; otherwise, you have to vote and receive a portion of rewards from a forging validator.

#### Compendia
In Compendia, the above two methods are combined into a new dynamic: staking your BIND locks up your funds for a set period (3 - 6 - 12 months) as in proof-of-stake networks, but it does NOT grant the ability to earn. You will still need to vote for a sharing validator, like in delegated proof-of-stake networks. What does staking do then, if it does not let you earn on its own?

Staking your BIND for a set period applies a multiple (5x - 7.5x - 10x) to the voting power of your staked balance. This means that one staked BIND is no longer counted as one vote, but as 5 votes (or 7.5 votes, or 10 votes - depending on the lock period). This way it increases your potential earnings when you vote for a sharing validator. So, by pledging to lock your funds for a certain amount of time and thereby decreasing the circulating amount of BIND, you will be able to earn more with the same amount of coins than if you would not stake, and only vote.

When staking, your BIND will go through 5 different phases:
- Grace: when your stake transaction has been created, you have a 1 hour period in which you can cancel it.
- Powering: after the initial grace phase, your stake is powering up. There is no vote power bonus yet, and this phase takes 47 hours.
- Active: when the powering phase ends, your stake is active and now provides the bonus vote power that corresponds with your lock time.
- Release: after your lock period has passed, your staked coins will be released and grants half the initial vote power bonus.
- Redeemed: if your staked coins have been released, you can redeem them back to your wallet. After ~14 days, you have full control of your staked coins again.
- In the future, you'll be able to redeem your stake before the release period at the costs of having a portion of the deposit slashed.

## Securing the network
DPoS delegates/validators secure the blockchain through forging blocks, and in the case of Compendia, there are 47 validators (rather than the 51 in ARK) and each active validator forges one block every 6 seconds. Therefore 47 new blocks are forged every 4.7 minutes (6 * 47 = 282 seconds = 4.7 minutes). In a similar way to proof-of-work networks such as Bitcoin, a block contains transactions and the validator that forges them receives a proportion of the transaction fee (described in the Fee Removal Model further below)

## Supply inflation
DPoS chains typically have fixed inflation based over several years, this is to help control the coin supply in circulation. Inflation comes from Delegate/Validators forging new blocks as described above.  The effect of validators forging new blocks increases the supply by either ß3.9 per block (if ranked 6th to 47th), or ß4.84 per block (if ranked 1st to 5th).

#### The Compendia blockchain produces around ß1,753,200 per month

Block rewards are controlled through an annual milestone which is fixed in the current networks config.  This can only be updated if the 47 validators reach consensus and accept the potential change. The current milestones for BIND are as follows:

| Years |  Rewards (6-47) | Rewards (Top 5) | Average|
|:-------:|:-----------------:|:-----------------:|:--------:|
|  1-3  |  3.9            |  4.84           |  4     |
|  4-6  |  1.95           |  2.42           |  2     |
|  7-9  |  0.975          |  1.21           |  1     |


#### Deflationary effects
In general DPoS blockchains allow voters to vote, allocating their wallet weight to a specific delegate/validator and receiving rewards commensurate to weight.  This helps control inflation as the coins are out of supply when being used to vote, but the coins are not locked for a fixed time, a voter can move some or all funds at any time.

#### What differentiates Compendia from other DPoS networks?
The key difference is that staked coins are locked for a fixed period, either 3, 6, or 12 months (as described above).  The coins are effectively locked out of supply, by incentivising voters to lock their coins for the maximum period of 12 months.  This helps offset the increase in supply through forging rewards.

At the time of writing, ß11,816,021 is currently locked into staking, given the current BIND supply (i.e nOS to BIND) ß112,894,676, around 10% of all BIND in circulation is locked out of supply for the staking periods highlighted earlier. With the current staked coins, it would take just over 6 months for inflation to offset the monthly forging reward increase.

## Fee removal model
Compendia also offer another deflationary measure through a sophisticated fee removal model.

#### The [fee collection and removal model](https://docs.compendia.org/guide/economy.html#fee-removal-model) works as follows:
- 100% of collected fees up to the amount equal to the block reward in a block are permanently removed from circulation.
- 50% of any remaining collected fees are also removed from circulation.
- The other 50% is awarded to the forging validator.

This fee system helps with combating possible shifts in Vote Power going from voters towards validators during times of increased transaction activity on the network.

## Summary
The Compendia Team have a clear understanding of the tokenomics of a blockchain, lessons have been learned from earlier DPoS implementations and new strategies have been deployed to ensure a fairer, more balanced approach to DPoS tokenomics.

#### If you have enjoyed reading this blog please consider voting for validators [bfx](https://bindscan.io/wallets/bfx) & [cryptomaniac](https://bindscan.io/wallets/cryptomaniac). Thank you.
