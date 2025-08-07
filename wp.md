
# HITS4FUN: The Zero-Day Volatility Betting Protocol

## Overview

**HITS4FUN** is a decentralized on-chain protocol that enables users to speculate on intraday volatility through simplified, game-like options strategies with zero risk of liquidation. Built on **Base**, HITS4FUN transforms the traditionally complex world of zero-day options (0DTE) into a low-barrier experience for crypto traders and degen gamblers alike.

There is no token at this stage. The protocol is currently in public whitelist phase, offering early access to tickets that will become usable once the platform launches in mainnet.

---

## Vision

Zero-day options are one of the fastest-growing instruments in traditional finance. We aim to bring this explosive format into DeFi — in a radically simplified and gamified way.

<img style="max-width:100%;" alt="card-1" src="https://github.com/user-attachments/assets/592e7db5-ba9d-46b5-b3f0-82a9f2a5805d" />

With HITS4FUN:

- There is no need to guess market direction
- There is no liquidation risk
- There are no variable funding rates
- There is no complexity

Just one question: **Will the price break out of the range today?**

Our goal is to make high-frequency volatility exposure as easy and fun as placing a bet.

---

## Core Strategy: Range Breakout

At launch, HITS4FUN supports a single strategy:

### 🎯 **Range Breakout**

<img style="max-width:100%;" alt="Graph1" src="https://github.com/user-attachments/assets/7960bf5e-1a49-4d35-b160-14881c32427d" />


- You buy a ticket before the U.S. trading session opens
- Your ticket becomes active during the session
- If the price **breaks out** of a predefined range (either up or down), your ticket wins
- The **further** it breaks out, the **higher** the payout
- If the price stays within the range, your ticket expires

There is no need to choose direction. You're betting on **volatility**, not price action.

---

## Strategy Lifecycle: Three Phases

Each daily strategy runs through three distinct stages:

1. **Open**

<img style="max-width:100%;" alt="card-strategy-new14" src="https://github.com/user-attachments/assets/7c8e16bf-7287-45e6-a141-9c6436756925" />

   - Users may buy tickets
   - The range is not yet known
   - Starts several hours before the U.S. session

2. **Active**

   <img style="max-width:100%;" alt="card-strategy-new15" src="https://github.com/user-attachments/assets/fe278fe2-5044-485a-8062-ae9b2cf520b9" />


   - U.S. session begins
   - Range is calculated and locked
   - Bets are frozen
   - Ticket outcomes will be determined after session ends

3. **Expired**

   <img style="max-width:100%;" alt="card-strategy-new16" src="https://github.com/user-attachments/assets/21588cdd-2f81-4706-b430-725bd2e8e716" />


   - Session ends
   - Final price is compared to range boundaries
   - Payouts are calculated and distributed

---

## Ticket Economics & Payout

Tickets are fixed-price entries into a shared prize pool.

- The cost is determined based on market volatility
- The payout depends on how far the price moves **beyond** the range
- Winning tickets receive a proportional share of the prize pool

In case of a narrow move or no breakout, the ticket burns and no payout is granted.

---

## Oracle & Price Data

- HITS4FUN uses an internal price oracle integrated with **Deribit**, a leading options exchange
- The range boundaries are calculated based on **implied volatility** and real-time market data
- Opening and closing prices are captured from Deribit at U.S. session start and end

The system is **fully autonomous** and on-chain verifiable.

---

## Risk Model & Hedging

To ensure sustainability, all user bets are internally hedged:

- When a user buys a breakout ticket, HITS4FUN opens **straddle positions** (long + short) at the range boundaries
- If price breaks out — the hedge wins, and those profits fund the user’s payout
- If price stays inside the range — the ticket is lost, and the hedge is closed near breakeven

This model creates a **self-balancing loop** where:

- Payouts are real, not subsidized
- Risk is contained
- Treasury stays healthy

---

## User Journey

<img style="max-width:100%;" alt="card-2" src="https://github.com/user-attachments/assets/e7d507f2-d2d4-4f5b-8c54-d4c4c4ec8fb6" />


1. **Connect Wallet**
2. **Select Asset**
3. **Buy Ticket**
4. **Wait for Session Start**
5. **Session Ends**
6. **Check Results & Claim**
7. **Referral Rewards (Optional)**

---

## Referral Program

Early users can earn rewards by inviting others to the protocol.

- Every user has a unique referral code or link
- Referrers earn **cashback** on every ticket purchase by their invitees
- The cashback percentage increases with volume
- Cashback is calculated even for **losing tickets**

---

## Early Access & Whitelist Benefits

The protocol is now in **Whitelist Phase**. Early participants who purchase tickets now will:

- Lock in a **20% discount** on ticket prices
- Become eligible for future **airdrop** rewards
- Be first to access the live strategies on mainnet
- Receive **cashback** on ticket purchases — even for failed tickets

---

## Links

Website: [https://hits4.fun](https://hits4.fun)  
Twitter: [https://twitter.com/hits4fun](https://twitter.com/hits4fun)  
Telegram: [https://t.me/hits4fun](https://t.me/hits4fun)

*This whitepaper is a living document and will be updated as the protocol evolves.*
