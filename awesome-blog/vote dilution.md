# Voter/Staking Reward Dilution

If you talk about voting & earning rewards on the Compendia Mainnet network, a word that you hear all the time is “dilution”, yet not everyone has a clear picture what that means for the voter.

In this blog post we will try to clarify how dilution and voting for high ranked validators doesn't always provide voters with the best return for their vote power. The basic principle is this: each validator forges the same amount of blocks and earns the same amount of block rewards per day: 1194 BIND (top 5 earn 25% more, total 1482 BIND). These rewards can be shared with their voters. A larger total of voters means less reward per BIND for each voter. This is called vote dilution. 

Secondly, the explorer ranks validators by the total vote power/influence of all their voters combined.  This is not a good measure for which validator will provide voters with the highest return for their vote.

Looking at the validator page of the [BIND Mainnet Explorer](https://bindscan.io/validators), we can see the number of votes across the 47 active validators differs wildly.


## What is voting, and why is it important?

For a validator to actively forge blocks (and thereby securing the network), they have to be in the top 47. In order to get there, they need votes from voters.

**Validators Types:**

**(i) Sharing Pool -** Typically a high sharing percentage public pool. Voters receieve rewards based on their total vote power.

**(ii) Contributing Validator -** A validator produces a proposal, including what they have done & plan to do for the community.  Voters can read these proposal by clicking on a validators name on the explorer.  If they have set a proposal, it will be visible for voters to read. These validators usually share a slightly lower percentage than public pools.

**(iii) Private Validator -** Typically someone who holds a significant amount of BIND, also known as "a whale". They typically do not share their rewards and forge blocks for themselves.


## Why does it matter to you as a voter? 

As a voter your aim is to find a validator who offers what you the voter wants. That might be someone who contributes to the ecosystem through tools, marketing, blogs et cetera.  Alternatively some voters wish to obtain the best ROI for their vote.


## What is staking, and why should I stake?

Staking is the process of locking your wallet balance for a fixed period - by doing this, you will be are rewarded with additional vote power/influence, which increases the total vote power/influence of your wallet.  Voters can choose between 3, 6 or 12 months lock period that increases the staked amounts vote power/influence by 5x, 7.5x or 10x respectively.


### Why is this beneficial?

When a voter locks their balance for a fixed period it has the following benefit:

**To the voter:** The portion of payouts that a voter receives when voting for a sharing validator, is a relative share of the total votes cast on that validator.

**To the wider community:**- It reduces the number of BIND in circulating supply for a fixed period of time.


## Model calculations

The aim of this section is to help clarify the effect validator share and vote weight have on reward payouts. We will give four examples with virtual validators.

(1) We are going to use some easier to understand numbers. Lets say a validator has 4,000,000 total vote power/influence.  A BIND validator produces circa 1,194 BIND per day (if ranked 6th to 47th position). Lets also say this validator shares 50% of their block rewards, about 597 BIND a day. In this hypothetical scenario, this means that for every 1,000 BIND voting for this delegate, 0.2985 BIND are rewarded to voters each day (1,000 / 4,000,000 * 597 = 0.14925 BIND).

(2) Now for comparison, we have another validator. They have 10,000,000 total vote power/influence, and this put them into the top 5. Assuming they share 100% of block rewards (1,482 BIND per day). This also means that for every 1,000 BIND voting for this delegate, 0.1482 BIND are rewarded to voters each day (1,000 / 10,000,000 * 1482 = 0.1482 BIND). 


### While the sharing percentages are very different, the basic outcome for the voter is roughly the same.

(3) Lets add a third and fourth validator into the mix. The third validator only shares 30% of his block rewards, but also has just 1,000,000 total vote power/influence voting for them. That means that every 1,000 BIND voting for him is rewarded with 0.4776 BIND per day (1,000 / 1000,000 * 1194 * 0,30 = 0.3582 BIND). So while he has the worst sharing percentage of our three examples, and is also ranked the lowest of the three, his hypothetical voters get 2.5 times as much reward as with the other delegates. 

(4) A fourth validator shares 10%, but has only 500,000 vote power/influence voting for them. Each 1,000 BIND voting for them is rewarded with 0.2388 BIND per day (1,000 / 500,000 * 1194 * 0.1 = 0.2388 BIND). This is only half as profitable as the third delegate, but still 1.6 times as profitable as the first two delegates.


### While the sharing percentages are lower, the smaller portion of total votes it needs to be divided through makes it more profitable.


## Summary

**We have used extreme examples here, but this has been done to demonstrate the principle of vote dilution and it's effects.**

Dilution of votes for BIND validators will adjust constantly based on vote weight. That is also the reason why reward sharing to voters fluctuates with every payment run. 

The community have built some very nice calculators that provide a rough estimate of the reward you can expect - but its not a number set in stone, as the amount of votes can change over time, and sometimes even share percentages are adjusted. Of course, as more people start voting for the lower sharing validators, their profitability will also start to drop. 

Therefore, it is advisable that you compare several validators every few weeks or months so you can vote for a different validator, maximizing your return. This, of course, is optional but recommended if you want to increase your ROI.

**[Validator made reward calculators](https://github.com/Bx64/Awesome-Compendia/#tools-validators)** 

Often, voting for a validator near the top of the explorer ranking is a trade-off between stability and rewards. A higher ranking validator might give you less reward per BIND voting, but he might also be at less risk to drop out of the forging delegates. The same principle applies to lower ranked validators: they will give you more reward per BIND voting, but it might be good to check wether they still remain in a forging position, every so often. So, if you want to maximise your rewards, dilution is something you have to understand and work with it.

But reward sharing is not everything and lots of delegates offer different things to their voters or to the community as a whole. So make sure to check the delegate proposals and check wether they are delivering what they have promised. In the end, you as a voter have the power to both punish and reward validators by casting your vote.
