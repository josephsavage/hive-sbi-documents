# 💲 Pending Balances & Upvote Delivery

### Member rshares Balances

When an account is enrolled in Hive SBI, we begin tracking an rshares balance for that member.&#x20;

{% hint style="info" %}
rshares are the unit that Hive uses to calculate rewards. Whenever you upvote, the witness checks your VP% and SP to calculate how many rshares your upvote is worth.&#x20;

When a post pays out, the witnesses check the rshares balance against the total reward pool to calculate the appropriate HP and HBD payouts.
{% endhint %}

This is the actual value used to track your upvote values on Hive, and the method that Hive SBI uses to track your pending upvote value.

### Value Sources

There are currently three sources of value that contribute to each member's pending upvote value. How each source works is more fully described in our [**FAQ**](frequently-asked-questions.md), but the sources are _Standard Units_, _Bonus Units_, and _Enrollment Rewards_.

#### Pending Value

Picture separate water sources that fill a pending vote tank for each member. The flow from each source into the tank is dependent on enrollment level or delegation. Increasing your enrollment or delegation will immediately increase the size of that source, and therefore the rate at which it contributes value to the tank.

_**It takes time for the rate change to impact the total pending value in the tank.**_

#### Value Delivery

To prevent 'dust' penalties, the minimum upvote we deliver is $0.021 per post, and we will only deliver up to 33% of pending value at a time. Each time a member posts, we check their rshares balance, and open the 'valve' if their pending value is large enough to support a minimum upvote.&#x20;

#### Voting Accounts

When the valve is opened, one of our voting accounts is activated to deliver the upvote. We select the highest VP account that can deliver the entire upvote size. If no account can deliver enough rshares to fulfill the vote, we vote from as many accounts as it takes to deliver the whole value. If we vote from all ten and still can't deliver the value, the valve closes and only the amount we can deliver is removed from the tank.

{% hint style="warning" %}
Our maximum deliverable vote value per post is a function or our current HP and VP levels, along with the HIVE price. If you plan on a significant increase in your Hive SBI levels, check with us to determine whether it will cause accrual rates that are too high for your posting frequency!
{% endhint %}

***

## Recommended Hive SBI Levels

_Note: this section is **not** financial advice, but could help you have a better SBI experience._

We recommend that you target at least $3 worth of Hive SBI levels to receive a weekly upvote, or $20 worth for a daily upvote. (Divide 20 by HIVE price in USD to estimate HSBI total needed). Lower subscription levels will still receive regular upvotes, but they will be less frequent.

Increasing your Hive SBI subscription increases your upvote frequency. Once your subscription is high enough for your tank refill rate to power an upvote on every post, then increasing your subscription will increase your upvote sizes instead.
