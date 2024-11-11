
# Zerodha Varsity

## Introduction

- Options are traded in the Indian markets for over 15 years, but the real liquidity was available only since 2006
- An Option is a tool for protecting your position and reducing risk
- A buyer of the call option has the right and the seller has an obligation to make delivery
- The option seller is also called the option writer
- At the time of agreement the option buyer pays a certain amount to the option seller, this is called the 'Premium' amount
- The agreement happens at a pre-specified price, often called the **'Strike Price'**
- The option buyer benefits only if the price of the asset increases higher than the strike price
- If the asset price stays at or below the strike, the buyer does not benefit, for this reason it always makes sense to buy options when you expect the price to increase
- Statistically the option seller has higher odds of winning in an typical option
contract
- The directional view has to pan out before the expiry date, else the option will expire worthless.

## Option Jargons

- It makes sense to buy a call option only when one anticipates an increase in the price of an asset
- The strike price is the anchor price at which both the option buyer and option writer enter into an agreement
- The underlying price is simply the spot price of the asset
- Exercising of an option contract is the act of claiming your right to buy the options contract at the end of the expiry
- Similar to futures contract, options contract also have an expiry. Option contracts expire on the last Thursday of every month
- Option contracts have different expiries - the current month, mid month, and far month contracts
- The option buyer benefits only if the price of the asset increases higher than the strike price
- Premiums are not fixed, in fact they vary based on several factors that act upon it
- Options are cash settled in India.

## Long Call Payoff and Short Call Trade

- It makes sense to be a buyer of a call option when you expect the underlying price to increase
- If the underlying price remains flat or goes down then the buyer of the call option loses money
- The money the buyer of the call option would lose is equivalent to the premium (agreement fees) the buyer pays to the seller/writer of the call option
- Intrinsic value (IV) of a call option is a non negative number
- `IV = Max[O, (spot price - strike price)]`
- The maximum loss the buyer of a call option experiences is to the extent of the premium paid. The loss is experienced as long as the spot price is below the strike price
- The call option buyer has the potential to make unlimited profits provided the spot price moves higher than the strike price
- Though the call option is supposed to make a profit when the spot price moves above the strike price, the call option buyer first needs to recover the premium he has paid
- The point at which the call option buyer completely recovers the premium he has paid is called the breakeven point
- The call option buyer truly starts making a profit only beyond the breakeven point (which naturally is above the strike price).

## Put Buy and Put Sell

- Buy a Put Option when you are bearish about the prospects of the underlying. In other words, a Put option buyer is profitable only when the underlying declines in value
- The intrinsic value calculation of a Put option is slightly different when compared to the intrinsic value calculation of a call option
- IV (Put Option) = Strike Price - Spot Price
- The P&L of a Put Option buyer can be calculated as P&L = [Max (0, Strike Price - Spot Price)] - Premium Paid
- The breakeven point for the put option buyer is calculated as Strike - Premium Paid

