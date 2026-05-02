# 🎮 Game Price Alert

An automated workflow built with [Make](https://make.com) that monitors a video game's price on a retailer website and sends a Gmail notification when the price drops below a defined threshold.

## How It Works

1. **Scheduler (Tools)** — Triggers the workflow on a set interval
2. **HTTP GET Request** — Fetches the game's product page
3. **Text Parser x2** — Extracts the game title and current price using pattern matching
4. **Price Drop Check (Filter)** — Compares the current price against your threshold
5. **Gmail** — Sends an email alert with the game title and new price if the condition is met

## Features

- Fully no-code / low-code automation
- Configurable price threshold
- Email notifications via Gmail
- Easily adaptable to track any product on any website

## Built With

- [Make](https://make.com) 
- HTTP module
- Text Parser (Regex pattern matching)
- Gmail integration

## Use Case

Never miss a sale. Set your target price once and get notified automatically — no manual checking required.
