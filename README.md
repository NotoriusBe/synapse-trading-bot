# Solarus trading bot☀️
[![Static Badge](https://img.shields.io/badge/Telegram-Channel-Link?style=for-the-badge&logo=Telegram&logoColor=white&logoSize=auto&color=blue)](https://t.me/+pB6j65Kv7cdjZmU0)

<img width="494" height="115" alt="image" src="https://github.com/user-attachments/assets/a6f5b562-4b04-4f25-a17c-9d29ca57b540" />

# Descritpiton
**Solarus is an open-source intelligent trading bot designed to generate trading signals by leveraging live market data, social media sentiment, and historical patterns. It features multiple modes of operation, backtesting, an AI-powered engine, and seamless integration with Telegram for real-time monitoring and control.**

# Main Features
- Automatically generates trading signals based on real-time market conditions, executes buy/sell orders using those signals(optional), and sets optimal stop-loss and take-profit levels.
- Backtesting Support: Simulate your own or the bot’s trading strategy on historical market data to evaluate performance, fine-tune parameters, and optimize results—without risking real capital.
- Self-Training: Solarus continuously learns from the user’s trading results, adapting its strategies and enhancing its overall intelligence over time. With each update, we also train Solarus.
- **Your** Strategy Optimization: Solarus analyzes your custom trading strategy using machine learning and market data, then suggests targeted improvements.
- Simple Interface and configuration: Intuitive control via Telegram bot or web UI.
- Manual mode: Snipe selected tokens at optimal price , define preferred stop-loss and take-profit levels, and apply their own custom trading strategies for complete control and precision.
- Notifications: The bot keeps you informed throughout the trading process with real-time updates via Telegram.
- Price-predicton: Solarus forecasts individual token prices by analyzing current market trends, the Fear and Greed Index, and historical price patterns.
- Financial Management: Solarus monitors your overall trading performance, tracking cumulative profit and loss in real time. Before initiating any trade, it alerts you to potential risks.


# Supported exchanges📊
<div align="center">
<img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/fccfee8d-363f-4899-a11f-b1a5e762077c" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/98e2a287-a0e3-4879-ba8c-228071aedc5d" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/cdd71c2d-e631-4e35-b2ee-2a9523299448" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/3fc9045c-bcb1-4b46-855c-46ae3e0a62de" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/9c6ac09d-5cd0-45cf-bec1-6e0f22939436" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/174a6f5c-3f27-4c51-9b67-1e31afd88848" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/79c87fa6-2054-455b-ac09-b9081b49b0c7" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/ea1a462e-538b-4c92-95b2-a412da06b133" />
<img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/93ba8805-b125-427a-8efe-d4a6b7c3f3f6" /> <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/1cb29c49-1d49-429d-855c-62689fdf59d6" /> <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/adaad38c-7eeb-464c-a4d4-bf9c654959aa" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/7ef99064-fb16-460a-8e8d-4e1169658f8e" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/a454dbbe-36ac-4543-b6f2-eca98f5a1b7f" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/443423fc-4aa1-49ac-aad9-066fe22f9a2c" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/63c15d29-45ea-41a4-a21c-51a7ce543245" />  <img width="120" height="100" alt="image" src="https://github.com/user-attachments/assets/79d3870a-dc39-446e-8970-f7090372479a" />  
 </div>

# Installation 
**Requirements**:
- Python 3.10+
- Git
- Pip
- 2v CPU, 2GB DDR4, 2GB disk space

**To install the bot, follow the steps below**:
```shell
git clone https://github.com/braindotcode/solarus-trading-bot
cd solarus-trading bot
run.bat
```
 **OR**
 ```shell
git clone https://github.com/braindotcode/solarus-trading-bot
cd solarus-trading bot
pip install -r requirements.txt
python bot.py
```
To connect Solarus to telegram bot:
1. Put your bot token and chat id in **config.json**
2.
 ```shell
cd solarus-trading bot
python solarus.py --telegram
```
3. To control the bot via Telegram use RPC commands:


| Command | Description |
|----------------------------|:-------------------------------------------------------------------------------------------------------------:|
| `/start`     | Start the bot |       
| `/stop`               | Stop the bot |
| `/stats`              |  Show statistics of your account(balance, trade history, overall profit) |
| `/mode` | Switch trading mode |
|`/status` | Show current operating mode |
| `/autotrade_on` | Enable automatic trading based on generated signals |
| `/autotrade_off` | Disable auto trading |
| `/snipe TOKEN` | Buy selected token instantly at market price or snipe desired price |
| `/sell TOKEN` | Sell selected token instantly at market price |
| `/strategy_suggest` | AI-analyzed strategy recommendations based on your performance |
| `/backtest *strategy name*` | Run backtesting simulation for a saved strategy |
| `/help` | Show full list of commands |

*This is not the full list of RPC commands. To view the complete list, type /help in the bot.*

# Disclaimer
Use the bot at your own risk. I assume for responsibility of your trading results and consequences of using the software. Dont risk the money which you afraid to lose. Be wise.

# Support

***Help/bug reports***

If you have any difficulties or encountered bugs, please join our telegram [community](https://t.me/+9j5RcKMfT5s4M2Q0)

If you have any ideas on how to improve the bot, feel free to contact me on [Telegram](https://t.me/@Hhubbinmo3)

***Buy me a coffee***

If you want to leave me a tip, my bitcoin address is `bc1q3zykl6k0jyk864kdeqdfq6hudfr3ry8wksrr6u`


**Don't forget to put stars!** ⭐













