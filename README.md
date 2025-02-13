# Telegram Solana Trading Bot
Solana Trading Bot running on Telegram

## Bot Link
[Dog_Solana_Bot](https://t.me/Dog_Solana_Bot)

## Overview
The Solana Trading Bot is an advanced and automated cryptocurrency trading tool designed for Solana-based decentralized exchanges (DEXs). It offers seamless token management and trading capabilities with cutting-edge features such as sniping, limit orders, portfolio tracking, and more. This bot is optimized for speed, accuracy, and scalability.

## Features
1. Sniping Features
- Automatically monitor and execute trades on newly listed tokens for early entry.
2. Multi-DEX Trading
- Buy and sell tokens across multiple decentralized exchanges on Solana, ensuring liquidity optimization.
3. Limit Orders
- Set custom buy/sell price limits to automate trades at your desired levels.
4. Wallet Portfolio Management
- Track the portfolio of tokens in your wallet with real-time updates.
5. Referral System
- Incentivize users with a built-in referral system for enhanced user engagement.
6. Token Watchlist
- Create and maintain a watchlist of tokens to monitor price changes and market activity.

## Installation
1. clone the repository onto ubuntu 20.04
2. install python 3.10
3. install the dependencies into venv via `cd solbot && make dev`
4. run the bot in dev mode do `make run` inside project root directory
5. to deploy the bot in background do `make solbot`
6. to kill running bot do `make kill`

## systemd commands
- check status `systemctl status dogbot.service`

- start service `sudo systemctl start service.service`

- stop service `sudo systemctl stop service.service`

- restart service `sudo systemctl stop service.service`

Here are the commands to check the logs

- check the logs `journalctl -u dogbot.service -e`

- follow logs in real time `journalctl -u dogbot.service -f`

- check specific after time `journalctl -u dogbot.service --since "2024-11-18 17:15:00"`

- check time range  `journalctl -u dogbot.service --since "2024-11-18 17:15:00" --until "2024-11-18 18:00:00"`

- list boots `journalctl -u dogbot.service --list-boots`

- check previous boot logs `journalctl -b -1`

## Author
Click here to contact [Author(idioRusty)](https://t.me/idioRusty)
