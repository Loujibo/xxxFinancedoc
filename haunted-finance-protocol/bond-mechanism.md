# Bond Mechanism

![](<../.gitbook/assets/06 Halloween-Pack\_Presentation-06.png>)

### What are $SKULL (Bonds)?

Bonds are unique tokens that can be utilized to help stabilize $FRANKENSTEIN price around peg (1 FTM) by reducing circulating supply of $FRANKENSTEIN if the TWAP (time-weighted-average-price) goes below peg (1 FTM).

### When can I buy $SKULL (Bonds)?

$SKULL can be purchased only during contraction periods, when **TWAP of** $FRANKENSTEIN **is below 1**.

At the beginning of every new epoch during contraction periods, $SKULLs are issued in the amount of 3% of current $FRANKENSTEIN circulating supply, with a max debt amount of 35%. This means that if bonds reach 35% of circulating supply of $FRANKENSTEIN , no more bonds will be issued.

{% hint style="info" %}
$SKULL TWAP (time-weighted average price) is based on $FRANKENSTEIN price TWAP from the previous epoch as it ends. This mean that $FRANKENSTEIN TWAP is real-time and $SKULL TWAP is not.
{% endhint %}

### Where can I buy $SKULL (Bonds)?

You can buy $SKULLs if any are available, on the **Bonds** page at [https://Hauntedfinance.app/BED](https://hauntedfinance.app/BED) anyone can buy as many $SKULLs as they want as long as they have enough $FRANKENSTEIN to pay for them.

There is a limit of available $SKULLs per epoch during contraction periods (3% of $FRANKENSTEIN's current circulating supply), and are sold first-come-first-serve.

### Why should I buy $SKULL (Bonds)?

First and most important reason is Bonds help maintain the peg, but they are not the only measure in place to keep the protocol on track.

$SKULLs don't have an expiration date, so you can view them as an investment in the long-term health of the protocol to be redeemed for a premium at a later date.

#### Incentives for holding $SKULL

The idea is to reward $SKULL buyers for helping the protocol, while also protecting the protocol from being manipulated by big players.

So after you buy $SKULL using $FRANKENSTEIN, you get 2 possible ways to get your $FRANKENSTEIN back:

1. Sell back your $SKULL for $FRANKENSTEIN **while the peg is between 1 - 1.1** (1 FTM) with no redemption bonus. This is in place to prevent an instant dump as soon as peg is recovered.
2. Sell back your $SKULL for $FRANKENSTEIN **while the peg is above 1.1** (1FTM) with a bonus redemption rate

The longer you hold, the more both the protocol and you benefit from $SKULLs.

{% hint style="success" %}
Example:

1. When $FRANKENSTEIN= 0.8, burn 1 $FRANKENSTEIN to get 1 $SKULL ($SKULL price = 0.8)
2. When $FRANKENSTEIN = 1.15, redeem 1 $SKULL to get 1.105 $FRANKENSTEIN ($SKULL price = 1.27)
{% endhint %}

So, which one is better?

If I buy $FRANKENSTEIN at 0.8, and hold it until 1.15 and then sell, I'm getting +0.35$ per $FRANKENSTEIN

But, if I buy $FRANKENSTEIN at 0.8, burn it for $SKULL, and redeem it at 1.15, I'm getting 1.105 $FRANKENSTEIN\* 1.15 ($FRANKENSTEIN current price) = 1,271 (+0.47$) per $SKULLredeemed.

But what if getting back to peg is taking too long ?

We will adjust our use cases, to have different behaviors on contraction and expansion periods to benefit both $FRANKENSTEIN and $SKULL holders when needed.

### What is the formula to calculate the $SKULL redemption bonus?

To encourage the redemption of $SKULL for $FRANKENSTEIN when $FRANKENSTEIN's TWAP > 1.1 and in order to incentivize users to redeem bonds at a higher price, $SKULL redemption is designed to be more profitable with a higher $FRANKENSTEIN TWAP value. The $SKULL to $FRANKENSTEIN ratio is 1:R, where R can be calculated using the formula as shown below:

![](../.gitbook/assets/微信图片\_20220312215943.jpg)

### When can I swap $SKULL for a premium?

You can only redeem $SKULLs for a premium when the previous epoch's TWAP is greater than 1.1.
