# Perpetuals Tracker

A browser-based investigation tool for tracking perpetual futures trading activity by wallet address. Built to support investigations into complex leveraged trading issues that are difficult to trace through standard blockchain explorers.


---

## The Problem

Perpetual futures transactions don't show up cleanly in standard blockchain explorers. They're deeply integrated with the Hyperliquid protocol, involve multiple transaction types (deposits, trades, withdrawals, liquidations), and require understanding the protocol's own data model to interpret correctly.

When a user reports an issue (a missing position, an unexpected liquidation, a failed deposit), you need to see their complete activity history within the protocol, not just raw on-chain transactions. This tool pulls exactly that.


---

## Features

- Full trade history for a wallet address: opens, closes, and partial fills
- Deposit and withdrawal history with timestamps and amounts
- Open position details including size, leverage, entry price, and PnL
- Liquidation event history
- Clean, readable layout designed for quick scanning during a support investigation
- Surfaces the full activity timeline needed to reconstruct what happened


---

## Stack

- **JavaScript**: core logic and API integration
- **HTML / CSS**: frontend interface
- **Hyperliquid API**: perpetual futures data source


---

## Notes

This is an internal tool and the live environment is not publicly accessible. Source code is not included as it contains environment-specific configurations. This README documents the project's purpose, design, and impact.
