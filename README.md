# The Security Trade Lifecycle

- [Overview](#overview)
- [Trade Capture](#trade-capture)

## Overview

The securities trade lifecycle includes several discrete steps that must be completed for a successful trade.
1. Trade Capture
2. Trade Enrichment
3. Trade Confirmation
4. Trade Settlement
5. Reconciliation

<img src="./static/lifecycle.png" />


A *trade* is a legal agreement to buy or sell goods in exchange for cash. The *buyer* receives the goods and pays cash simultaneously. The *seller* delivers the goods and receives cash simultaneously.

A *trade execution* is an agreement to undertake a specific securities trade on specific terms between two parties.

Trade executions were historically created between traders on the "trading floor". Market makers advertise their prices on "pitches" (cards).

Today, trades are typically completed in order-driven markets or quote-driven markets.

Orders (unfulfilled executions) are facilitated on an *order-driven market*, in which a buyer and seller are matched based on the terms of the trade. Order-driven markets are usually categorized by automatic electronic execution.

In contrast, *quote-driven markets* are based around bid/ask price quotes that attract investors.

In order to make a trade, market makers/trades need immediate knowledge of whether new trades result in profit or loss. This requires knowledge of the current trading position and its average price.

> The *current trading position* is the accumulated effect of all purchases and sales. 
>
> E.g., Marco performs the following trades:
> | Activity | Shares | Position |
> | --- | --- | --- |
> | Buy | 500 | 500 |
> | Buy | 200 | 700 |
> | Sell | 150 | 550 |
> | Buy | 70 | 620 |

**How is a trade execution initiated?**

*From the perspective of an institutional investor (e.g., hedge fund, asset manager):*
1. Investment manager makes an investment decision
2. Investment manager communicates an order to the executing broker (e.g., buy 10 million shares at market price)

*From the Broker's perspective:*
1. Salesperson records detail of order, including:
    - client account at "block" level or client account at "allocation" level
    - buy or sell
    - quantity
    - specific security
    - desired price (e.g., limit, market)
2. Salesperson forwards order to trader

When an order is received by the broker, it acts as an agent or principal.
- **Agent**: broker attempts to find a 3rd party willing to trade on the terms of the order (typically for a commission/brokerage fee)
- **Principal**: broker trades off of trading book, thereby increasing/decreasing its current position for that security

## Trade Capture