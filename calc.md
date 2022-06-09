# Acckenn Calc

Acckenn Calc is an autonomously crypto tax calculator designed by tax accountants who have experience and understanding of crypto transactions.

## Supported Exchanges

| Exchanges  |   |
| ---------- | - |
| Bitkub     | [Bitkub export txn history](https://support.bitkub.com/hc/en-us/articles/360000338012-FAQ-Where-can-I-export-my-transaction-history-) |
| Satang Pro | [Satang Pro export txn history](https://satang.zendesk.com/hc/en-us/articles/6285729839257-How-to-export-coin-transactions-history) |
| Zipmex (coming soon) | [Zipmex export txn history](https://zipmex.com/id/en/support/trading/how-can-i-view-my-trading-history-id/) |
| Bitazza (coming soon) | [Bitazza export txn history](https://bitazzahelp.freshdesk.com/en/support/solutions/articles/44002257234-where-can-i-export-my-transaction-history-) |

## Transaction Type

Acckenn Calc is only as accurate as the data you provide it. This means it's essential that you keep records of ALL crypto transactions, which includes not just trades but also records of spending, income, gifts sent or received, etc.

### Buy

The `Buy` transaction type records the exchange of fiat for cryptoasset, or one cryptoasset for another.

This could be for one for the following reasons.
- Fiat-to-crypto (acquisition)
- Crypto-to-crypto (disposal)

As a disposal transaction, it is applicable for Capital Gains tax.

### Sell

The `Sell` transaction type records the exchange of one cryptoasset for another, or for fiat currency.

This could be for one for the following reasons.
- Crypto-to-crypto (disposal)
- Crypto-to-fiat (disposal)

As a disposal transaction, it is applicable for Capital Gains tax.

### Deposit

A `Deposit` is a transfer transaction record, indicating the receipt of cryptoasset tokens to a wallet you control. For example, you might have deposited tokens to a wallet on a cryptocurrency exchange.

Deposit should NOT be used to record transfers to someone else's wallet, this would be categorised as either a `Sent` or a `Spend`.

There should always be an equivalent `Withdraw` transaction record for every deposit, since tokens are always moving out of one wallet into another.

Deposits and Withdrawals are not taxable events, but paying the transfer fee is.

The Deposit type can also be used to record fiat deposits into an exchange. Although this is not used for tax calculations, it will be used for auditing purposes.

### Withdraw

A `Withdraw` is a transfer transaction record, indicating tokens being sent from a wallet you control. It is always used in combination with a `Deposit` transaction.

It is important that any withdraw fee paid is specified, the withdraw quantity should be the net amount (after fee deduction).

It's corresponding Deposit quantity should match the Withdraw quantity, this is important, as the transfers will be removed from the tax calculations.

The Withdraw type can also be used to record fiat withdrawals from an exchange.

### Received

The `Received` transaction type is used to record cryptoasset tokens received as a gift.

A gift received is not taxed as income.

### Sent

A `Sent` is a disposal transaction record, which identifies cryptoasset tokens sent as a gift.

As a disposal transaction, it is applicable for Capital Gains tax.

### Income

The `Income` transaction type is used to identify tokens received as income, for example `Airdrop`, `Mining`, `Staking`, `Interest` or `Dividend`.

These transaction records will appear within your income tax report.

### Spend

A `Spend` is a disposal transaction record, which is used to capture the spending of tokens on goods or services.

As a disposal transaction, it is applicable for Capital Gains tax.

## Price Data API

Acckenn Calc allows you to get the latest and historic prices of cryptoassets. Its use is not strictly required as part of the process of completing your transactions but provides a useful insight into the prices (1 min avg. price) that Acckenn Calc will assign when it comes to value your cryptoassets in Thai baht.

**Data Sources:** The following price data sources are used.
- Bitkub
- Satang Pro
- Binance