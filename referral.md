**Referral Program — Summary**

**Purpose**
A system that encourages users and businesses to invite others to the platform. Rewards are
given when certain conditions are met.

## 1. Entities

- **Business** – business operators on the platform.
- **User (Client)** – end users who consume services.

## 2. Reward Distribution (MVP Approach)

For the MVP:

- No automated payment system.
- The platform will **generate reports of earned rewards**.
- **Payments will be sent manually** to bank accounts.

# 3. Referral Scenarios

## 1. Business → User (MVP priority)

A business invites users via a referral link.

The business receives a reward when all of the conditions are met:

1. Registers using the referral link provided by the business.
2. The user has to have at least some number (some hard coded number in the source code but placed in a place easy to find and change)  of complete (finished) booking services before the inviting business receives reward.
3. The services that the user books that count towards this can be of any business but the inviting business.

## 2. User → User

A user invites another user.

The inviting user receives a reward when the invited user:

1. Registers using the referral link.
2. Uses services across different businesses (at least 2 different and also with some minimum baseline)


## 3. Business → Business

A business invites another business.

The inviting business receives a reward when the invited business:

1. Registers using the referral link.
2. Activates a **paid license/subscription**.

For MVP:

- Since subscriptions are not implemented yet, this event will simply be
    **tracked/logged**.

## 4. User → Business

Possible but **rare**.
Not planned for the MVP (or not planned at all).

# 4. Two-Sided Rewards

The referral system rewards **both sides** :

- **Inviter** receives referral bonuses.
- **Invited user** receives a bonus such as:
    o discount for the first service.

# 5. Fraud Prevention / Limits

To prevent abuse:

- A **maximum number of rewards per month** per inviter.
- Users can invite unlimited people, but **bonuses are capped**.
- In future perhaps some anti-fraud system

# 6. Implementation Notes


For MVP the system should include:

- Referral links.
- Tracking of:
    o inviter
    o invitee
    o registration
    o service usage events
- Bonus calculation logic.
- Monthly bonus limits.
- Reward reports for manual payouts.

The **database structure should support all referral scenarios** , even if only **Business →
User** is active in the MVP.


