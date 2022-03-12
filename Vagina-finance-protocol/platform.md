# 💡 Platform

## Bathtub (Boardroom)

![](../.gitbook/assets/Hatchery.png)

* Epoch duration: 6 hours
* Any interaction with the Bathtub (staking/unstaking $LSHARE or withdrawing $LABIA rewards) will **lock your staked $LSHARE for 6 epochs and $LABIA rewards for 3 epochs.**&#x20;
*   Distribution of $LABIA during Expansion

    **90%** as Reward for Boardroom $LSHARE Stakers\
    **5%** goes to Community fund

    **5%** goes to DEV fund
* Epoch Expansion: The current expansion cap is based on the currently circulating $LABIA supply (see below for details). If there are bonds to be redeemed, 65% of minted $LABIA goes to the treasury until its sufficiently stocked to satisfy future bond redemption

| $LABIA Circulating Supply | Max $LABIA Minted |
| ------------------------ | ---------------- |
| Up to 1.5M               | 3% expansion     |
| Up to 5M                 | 2.5% expansion   |
| Up to 10M                | 2% expansion     |
| Up to 20M                | 1.5% expansion   |
| Up to 50M                | 1.25% expansion  |
| 50M+                     | 1% expansion     |

{% hint style="info" %}
The Bathtub **does not** print any rewards for $LSHARE stakers when the Bathtub TWAP < 1.01.
{% endhint %}

### Bathtub UI Information

Next **Epoch** indicates a countdown timer to the next epoch. (Each epoch duration lasts for 6 hours)                                                                                                              &#x20;

**APR** refers to the simple returns in USD value relative to the amount of $LSHARE staked (USD value).\
_Note: **** APR fluctuates from time to time and is dependent on certain factors such as:_

* Price of $LABIA
* Price of $LSHARE
* Amount of $LSHARE staked in Hatchery (Locked Value)

### Bathtub Debt Phase

A debt phase takes place during expansion epochs that start after a contraction period where there are still $LBOND to be redeemed.

65% of expansion during a debt phase is allocated to the treasury fund to prepare for subsequent $LBOND redemption down the road. This amount is always reserved, regardless of whether $LBOND holders are redeeming bonds or not.

Once enough $LABIA is sufficiently stocked in the treasury to satisfy the redemption of all circulating $LBOND, expansion rates will resume to normal.

## COOK

![](../.gitbook/assets/farm.png)

To incentivize healthy liquidity pools for the Breaking Finance protocol tokens, our LP COOKs have been seeded with $LSHAREs to be distributed as rewards to LP stakers across a time period of 12 months. The total $LSHARE rewards are distributed from each COOK as follows:

* $LABIA-FTM LP: 6,500 $LSHARE
* $LSHARE-FTM LP: 2,500 $LSHARE

## RV

![](../.gitbook/assets/bond.png)

$LBOND (bond tokens) are available for purchase when $LABIA falls below the 1 FTM peg. If $LABIA's TWAP is between 1.00 and 1.01, neither $LBOND nor $LABIA will be issued.

Check out the [Bonds Mechanism](broken-reference) section for a detailed breakdown of how bonds work.
