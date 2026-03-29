# P2P Trade Bot Binance
 P2P Trade Bot Binance - This is automated trading and hold a position in the glass
 
 P2PTradeBot - follows competitors' prices and changes prices in your ads making them more beneficial for the user than others
 
 This bot also has a name - step or follow the competitor's price, because the bot will beat the prices of sellers according to the criteria you specify in the bot settings, and your ad will always be more profitable for the 
 user

 Can pursue a specific seller or only seller merchants, or pursue all sellers, filtering out only by the minimum ad amount

<img id="main_image_73" src="https://py-dev.top/components/com_jshopping/files/img_products/Market-Following_P2P_Strategy.png" alt="P2P Trade Bot Binance" title="P2P Trade Bot Binance">


Advantages of the P2P Trade Bot in trading on the Binance cryptocurrency exchange:
The bot is multi-processor - this allows the bot to efficiently process large amounts of data and perform tasks in the background


### In this bot, you can configure each ad according to different criteria:
 

<b>Number One</b> Function: This function enables autopilot trading. It places your ad at the top of the order book  and constantly keeps it in the first position (Top 1)

<b>Competitor</b> Function: This function allows you to track a specific competitor. The bot will continuously adjust your price to compete with the specified competitor.

<b>Filter</b> Function: This function is based on the volume of assets in the ad. The bot will prioritize ads that match your specified volume criteria.

<b>Threshold</b> Function: This function sets a price threshold above which the bot will not place a price if you are buying cryptocurrencies, or below which if you are selling.

<b>Payment Methods</b> Function: This function filters ads based on accepted payment methods.

<b>Merchant or All Users</b> Function: This function filters ads based on the type of seller. It can follow only merchants or all sellers.

<img id="main_image_73" src="https://py-dev.top/images/p2ptradebot/menu_bot.jpg" alt="P2P Trade Bot Binance" title="P2P Trade Bot Binance">

#### Demo

#### Binance P2P arbitrage bot:

<a href="https://www.youtube.com/watch?v=xoh3P3f1yGI" target="_blank"><img src="https://img.youtube.com/vi/xoh3P3f1yGI/0.jpg" alt="P2PTradeBot" style="width:259px;height:194px;"></a>

#### P2P Bot Binance for Windows:

<a href="https://www.youtube.com/watch?v=gpsGdiBdFSA" target="_blank"><img src="https://img.youtube.com/vi/gpsGdiBdFSA/0.jpg" alt="P2PTradeBot" style="width:259px;height:194px;"></a>

#### New version of Bot:

<a href="https://www.youtube.com/watch?v=NDMAyKulNr8" target="_blank"><img src="https://img.youtube.com/vi/NDMAyKulNr8/0.jpg" alt="P2PTradeBot" style="width:259px;height:194px;"></a>


####  Similar developments:
******************************************************************************************
Automatic purchase of orders on Binance P2P  https://github.com/pydevtop/binance_p2p_bot
******************************************************************************************


 #### Installing
Instructions for installing and configuring the P2P Trade Bot Binance
To manage the Binance P2P bot software, you need to create and connect a telegram bot
#### 1. Registering a new Telegram bot
Detailed instructions for registering a new telegram bot: https://py-dev.top/registering-telegram-bot

The resulting API key for your telegram bot will need to be copied and added to the config.ini configuration file located in the bot folder

Example: BOT_TOKEN = '5017012087:AAGXATlZLS3l25SxVbXIxXVcOPNqkT1Q5ig' # token BotFather

#### 2. API keys to connect to Binance
We create or take existing API Key and Secret Key to connect to the Binance API on the binance website in your account in the section - API Management

APIKey and Secret Key also need to be copied and added to the bot configuration file config.ini
#### 3. Install Python
Detailed instructions on how to install Python on Windows: https://py-dev.top/installing-python

Go to the settings of the bot itself

Go to the C drive folder:
In the folder of drive C: unpack the archive P2PTradeBot.zip

Go to the P2PTradeBot folder and click on the start.bat file to start the bot

```
 25/12/2025 – Version 1.0.9 (Critical Update) 
 Important: P2P Ads Update

- Binance has changed the logic for P2P advertisement ranking and updates.  
- The bot behavior has been updated to correctly sync prices, limits, and ad status according to the new API rules.  
- An advanced configuration mode has been implemented: settings can be applied globally to all banks or individually per bank (as in version 1.0.7).  
- Fixed issues where ads could stop updating, lose ranking, or become desynchronized.  
- This update is mandatory to keep ads visible, competitive, and operating reliably.
```
```
08/02/2026 – Version 2.0.0  

BTC Restriction Check

- A full check for BTC position restrictions has been added using the Binance P2P API.  
- If a competitor’s advertisement requires a BTC balance, that advertisement is excluded from price calculations.  
- The bot does not compete with sellers who cannot actually execute trades.  
- This prevents incorrect price drops and preserves a realistic and stable trading strategy.  
```
```
 Seller Activity Check (Beta)  
- A real activity check for sellers on the Binance platform has been added.  
- If a seller remains inactive for more than 20 minutes, the bot skips price updates based on that advertisement.  
- This prevents competition with inactive or non-responsive listings.  
- This feature is currently in Beta and may be refined in future versions.
```
```
 14/02/2026 – Version 2.1.0  

Smart Self-Detection (User ID Based)  
- The bot now identifies your own advertisements using your Binance User ID instead of your nickname.  
- Your User ID is automatically detected and securely saved at startup.  
- No manual configuration is required.  
- Eliminates self-competition and prevents incorrect price calculations.  
- Significantly improves trading accuracy and positioning logic.  

Dedicated Ads Synchronization Module  
- A new separate script for ads synchronization has been introduced.  
- Advertisement management is now fully decoupled from the core trading engine.  
- Improves performance, stability, and update flexibility.  
- Prepares the system for future advanced advertisement automation features.  

Improved Start & Restart Stability  
- Enhanced process management for cleaner startup and restart behavior.  
- Previous bot instances are now properly closed before launching a new session.  
- Eliminates duplicate Telegram polling conflicts (Error 409).  
- Prevents multiple browser instances from running simultaneously.  
- Ensures a smoother, more stable operational cycle — even after freezes or unexpected interruptions.  

```
## 🚀 29/03/2026 – Version 2.2.0

### ⚡ Dynamic Market Strategy (New Core Logic)
- Introduced fully dynamic price recalculation on every cycle  
- The bot now moves with the market instead of using static pricing  
- Continuously adapts to live market conditions  
- Ensures every trade stays within a profitable threshold  

---

### 🧠 Counter Order Book Strategy
- Works strictly from the opposite side of the order book  
- Buy → analyzes sellers | Sell → analyzes buyers  
- Uses real executable market prices instead of passive competition  
- Improves pricing accuracy and market positioning  

---

### 📊 Altcoin Pricing Logic Upgrade
- Integrated spot-based price calculation (USDT + fiat rate)  
- Includes Binance fees and target profit (%)  
- Calculates maximum safe entry price  
- Prevents unprofitable trades in volatile markets  

---

### 💵 Stablecoin Dynamic Logic
- Dynamic threshold recalculation based on market price  
- Tracks selected order book position in real time  
- Updates pricing every cycle using fees and fixed profit  
- Ensures stable and consistent spread trading  

---

### 🎯 Competitor-Only Mode
- Ability to target specific traders  
- Filters out all other market participants  
- Provides precise control over pricing strategy  

---

### 🛡️ Profit Protection System
- All calculations include Binance fees and profit margin  
- Blocks unprofitable trades automatically  
- Maintains mathematically safe execution  

---

### 🔁 Real-Time Market Adaptation
- Recalculates prices, thresholds, and positions every cycle  
- Fully synchronized with market movement  
- Eliminates static pricing behavior  

---

### 💎 Summary
Version 2.2.0 introduces a fully dynamic pricing system where the bot:
- moves with the market  
- adapts in real time  
- and always operates within a profitable range  

## ✅ System Requirements

### 🖥️ Operating System
- Windows 10/11  
- macOS  
- Linux (Ubuntu, Debian, etc.)

### 🐍 Python Version
- Python 3.10 or higher

### 📄 Description
- The bot is written in **pure Python** and is **fully cross-platform**.
- Compatible with all major desktop operating systems.
- Only the **startup method** may vary slightly depending on the platform:
  - `.bat` file for **Windows**
  - `.sh` shell script for **Linux/macOS**


## Buy P2P Trade Bot Binance
https://py-dev.top/application-software/p2p-trade-bot-binance

## Contacts
Telegram: @morgan_sql<br>
Telegram channel: https://t.me/pydevtop

## License and Usage Notice

This project is licensed under the MIT License.

⚠️ However, unauthorized copying, redistribution, publication, or forking of this repository in a way that falsely attributes authorship or contributor status is strictly prohibited.

The author (PyDev) does not consent to being listed as a contributor in unauthorized forks or copies of this repository.

If you find any unauthorized fork or copy that misuses the author’s name, please report it to GitHub Support.

Author: PyDev

