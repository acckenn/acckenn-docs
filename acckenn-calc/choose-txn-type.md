---
order: 2
icon: horizontal-rule
tags: [Crypto Tax Report]
---

# Choose Txn Type

Acckenn Calc is **only as accurate as the data you provide it.** This means it's essential that you keep records of all crypto transactions, which includes not just buy or sell but also records of spending, income, gifts sent or received, etc.

### Buy

The `Buy` transaction type records the exchange of fiat for cryptoasset, or one cryptoasset for another.

This could be for one for the following reasons.
- **Fiat-to-crypto (acquisition)**
- **Crypto-to-crypto (disposal)**

### Sell

The `Sell` transaction type records the exchange of one cryptoasset for another, or for fiat currency.

This could be for one for the following reasons.
- **Crypto-to-crypto (disposal)**
- **Crypto-to-fiat (disposal)**

As a disposal transaction, it is applicable for Capital Gains tax.

### Deposit

A `Deposit` is a transfer transaction record, indicating the receipt of cryptoassets to a wallet you control. For example, you might have deposited cryptoassets to a wallet on a cryptocurrency exchange.

Deposit should NOT be used to record transfers to someone else's wallet, this would be categorised as either a `Sent` or a `Spend`.

**There should always be an equivalent `Withdraw` transaction record for every deposit, since cryptoassets are always moving out of one wallet into another.**

**Deposits and Withdrawals are not taxable events, but paying the transfer fee is.**

The Deposit type can also be used to record fiat deposits into an exchange. Although this is not used for tax calculations, it will be used for auditing purposes.

### Withdraw

A `Withdraw` is a transfer transaction record, indicating tokens being sent from a wallet you control. It is always used in combination with a `Deposit` transaction.

**It is important that any withdraw fee paid is specified, the withdraw quantity should be the net amount (after fee deduction).**

**It's corresponding Deposit quantity should match the Withdraw quantity, this is important, as the transfers will be removed from the tax calculations.**

The Withdraw type can also be used to record fiat withdrawals from an exchange.

### Received

The `Received` transaction type is used to record cryptoassets received as a gift.

**A gift received is not taxed as income.**

### Sent

A `Sent` is a disposal transaction record, which identifies cryptoassets sent as a gift.

**As a disposal transaction, but it is not applicable for Capital Gains tax.**

### Income

The `Income` transaction type is used to identify tokens received as income, for example `Airdrop`, `Mining`, `Staking`, `Interest` or `Dividend`.

**These transaction records will appear within your income tax report.**

### Spend

A `Spend` is a disposal transaction record, which is used to capture the spending of tokens on goods or services.

**As a disposal transaction, it is applicable for Capital Gains tax.**