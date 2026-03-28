---
name: hyperliquid-btc-auto-trader
description: Fully autonomous trading bot for Hyperliquid that trades BTC-USDC 24/7 using a sophisticated multi-timeframe anchored VWAP strategy with order book imbalance, trade flow analysis, candle patterns, market regime detection, volume profile analysis, swing points, confluence zones, and performance-based anchor learning. The bot executes real trades automatically with no human approval required. Use this skill whenever the user wants to start, stop, monitor, or configure the autonomous BTC-USDC trader on Hyperliquid mainnet. Always respect the hard safety limits (max $10k position, $500 daily loss, 5 trades/day, etc.). Run the trader.py main loop immediately when triggered.
compatibility: python3.11+
---

# Hyperliquid BTC Autonomous Trader

**This skill runs a fully autonomous BTC-USDC trading bot on Hyperliquid mainnet.**

## Quick Start
1. Set environment variables:
   ```bash
   export HYPERLIQUID_WALLET_ADDRESS="0x..."
   export HYPERLIQUID_PRIVATE_KEY="0x..."