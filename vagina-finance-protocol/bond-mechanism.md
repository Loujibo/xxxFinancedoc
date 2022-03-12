# 💵 Bond Mechanism

![](../.gitbook/assets/13.jpg)

### What are $LBOND (Bonds)?

Bonds are unique tokens that can be utilized to help stabilize $LABIA price around peg (1 FTM) by reducing circulating supply of $LABIA if the TWAP (time-weighted-average-price) goes below peg (1 FTM).

### When can I buy $LBOND (Bonds)?

$LBOND can be purchased only during contraction periods, when **TWAP of** $LABIA **is below 1**.

At the beginning of every new epoch during contraction periods, $LBONDs are issued in the amount of 3% of current $LABIA circulating supply, with a max debt amount of 35%. This means that if bonds reach 35% of circulating supply of $LABIA , no more bonds will be issued.

{% hint style="info" %}
$LBOND TWAP (time-weighted average price) is based on $LABIA price TWAP from the previous epoch as it ends.  This mean that $LABIA TWAP is real-time and $LBOND TWAP is not.
{% endhint %}

### Where can I buy $LBOND (Bonds)?

You can buy $LBONDs if any are available, on the **Bonds** page at [https://vaginafinance.app/BED](https://vaginafinance.app/BED) anyone can buy as many $LBONDs as they want as long as they have enough $LABIA to pay for them.

There is a limit of available $LBONDs per epoch during contraction periods (3% of $LABIA's current circulating supply), and are sold first-come-first-serve.

### Why should I buy $LBOND (Bonds)?

First and most important reason is Bonds help maintain the peg, but they are not the only measure in place to keep the protocol on track.&#x20;

$LBONDs don't have an expiration date, so you can view them as an investment in the long-term health of the protocol to be redeemed for a premium at a later date.

#### Incentives for holding $LBOND

The idea is to reward $LBOND buyers for helping the protocol, while also protecting the protocol from being manipulated by big players.

So after you buy $LBOND using $LABIA, you get 2 possible ways to get your $LABIA back:

1. Sell back your $LBOND for $LABIA **while the peg is between 1 - 1.1** (1 FTM) with no redemption bonus.  This is in place to prevent an instant dump as soon as peg is recovered.
2. Sell back your $LBOND for $LABIA **while the peg is above 1.1** (1FTM) with a bonus redemption rate

The longer you hold, the more both the protocol and you benefit from $LBONDs.

{% hint style="success" %}
Example:

1. When $LABIA= 0.8, burn 1 $LABIA to get 1 $LBOND ($LBOND price = 0.8)
2. When $LABIA = 1.15, redeem 1 $LBOND to get 1.105 $LABIA ($LBOND price = 1.27)&#x20;
{% endhint %}

So, which one is better?

If I buy $LABIA at 0.8, and hold it until 1.15 and then sell, I'm getting +0.35$ per $LABIA

But, if I buy $LABIA at 0.8, burn it for $LBOND, and redeem it at 1.15, I'm getting 1.105 $LABIA\* 1.15 ($LABIA current price) = 1,271 (+0.47$) per $LBONDredeemed.

But what if getting back to peg is taking too long ?

We will adjust our use cases, to have different behaviors on contraction and expansion periods to benefit both $LABIA and $LBOND holders when needed.

### What is the formula to calculate the $LBOND redemption bonus?

To encourage the redemption of $LBOND for $LABIA when $LABIA's TWAP > 1.1 and in order to incentivize users to redeem bonds at a higher price, $LBOND redemption is designed to be more profitable with a higher $LABIA TWAP value. The $LBOND to $LABIA ratio is 1:R, where R can be calculated using the formula as shown below:

![](../.gitbook/assets/WX20220304-090034@2x.png)

### When can I swap $LBOND for a premium?

You can only redeem $LBONDs for a premium when the previous epoch's TWAP is greater than 1.1.
