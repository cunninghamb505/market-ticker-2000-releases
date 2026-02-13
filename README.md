# Market Ticker 2000

A real-time scrolling stock ticker bar for Windows that floats on top of all your windows.

**Created by Brandon Cunningham**

---

## Download

**[Download the latest release](https://github.com/cunninghamb505/market-ticker-2000-releases/releases/latest)**

Download  via the realease and install app. .

---

## Summary

Market Ticker 2000 puts a sleek scrolling ticker bar at the top of your screen showing live stock prices, crypto, market indices, and breaking news. It stays on top of all windows so you never miss a move. Fully customizable with themes, fonts, colors, alerts, and more.

## Features

### Live Market Data
- **Stock quotes** — SPY, DOW, NQ, AAPL, MSFT and any ticker you want
- **Crypto** — BTC, ETH, DOGE, and any crypto pair from Yahoo Finance
- **Market indices** — S&P 500, Dow Jones, Nasdaq Composite
- **Sparkline charts** — Tiny intraday price graphs next to each symbol
- **Market status** — Shows MARKET OPEN / CLOSED / PRE-MARKET / AFTER-HOURS
- **News headlines** — Breaking news from Yahoo Finance and MarketWatch
- **Auto-refresh** — Quotes update every 60 seconds (configurable)

### Customization
- **4 color themes** — Dark, Light, Bloomberg (terminal-style), Ocean
- **Custom colors** — Pick your own background, gain/loss colors
- **Fonts** — Any system font, adjustable size
- **Opacity** — Make the bar semi-transparent
- **Scroll speed & direction** — Scroll left or right, speed 1-10

### Interaction
- **Pause on hover** — Freeze scrolling to read a quote
- **Click to open chart** — Click any symbol to open Yahoo Finance in your browser
- **Drag to reposition** — Drag the bar anywhere vertically
- **Global hotkey** — Press Ctrl+Shift+T to show/hide from anywhere
- **Auto-hide** — Bar disappears after a delay, reappears on hover

### Alerts & More
- **Price alerts** — Get a Windows notification when a stock crosses your price
- **Multi-monitor** — Choose which monitor to display on
- **System tray** — Right-click the tray icon for quick controls

## How to Use

### 1. Download & Run
1. Download `MarketTicker2000.zip` from the [Releases page](https://github.com/cunninghamb505/market-ticker-2000-releases/releases/latest)
2. Extract the zip to any folder
3. Run `MarketTicker2000.exe`
4. A ticker bar appears at the top of your screen

### 2. System Tray
Look for the icon near your clock. Right-click it for the menu:
- **Show/Hide** — Toggle the ticker bar
- **Refresh Now** — Force a data refresh
- **Settings** — Open the settings dialog
- **Exit** — Close the app

### 3. Settings
The settings dialog has 5 tabs:

**General** — Add/remove symbols, set refresh interval, choose monitor, position, scroll direction

**Appearance** — Pick a theme, customize font, colors, opacity, scroll speed

**Features** — Toggle sparklines, market status, news, hover pause, click-to-chart, auto-hide, hotkey

**Alerts** — Set price alert rules like `AAPL > 200` or `SPY < 400`

**About** — App info and credits

### 4. Examples

**Add more symbols:**
```
SPY, DIA, QQQ, AAPL, MSFT, TSLA, NVDA, AMZN, GOOG, BTC-USD, ETH-USD
```

**Set display aliases** (so "DIA" shows as "DOW"):
```
DIA=DOW, QQQ=NQ, BTC-USD=BTC, ETH-USD=ETH
```

**Set price alerts:**
```
AAPL > 200; SPY < 400; BTC-USD > 100000
```

**Change the hotkey:**
```
Ctrl+Shift+T   (default)
Ctrl+Alt+M     (example)
```

## Security & Antivirus

Some antivirus software may flag this app as suspicious. This is a **false positive** — it happens because the app is built with PyInstaller, which bundles Python into an executable.

To verify the app is safe:
- **VirusTotal scan** — Each release includes a link to the VirusTotal scan results so you can check for yourself
- **No data collection** — The app only connects to Yahoo Finance, Google Finance, and MarketWatch for stock data and news. It does not collect, store, or transmit any personal information
- **Open distribution** — The zip contains the exe alongside its dependencies as separate files (not packed into a single file), which reduces false positives

## System Requirements

- Windows 10 or 11
- Internet connection (for live quotes)

## License

Copyright (c) 2026 Brandon Cunningham. All rights reserved.
