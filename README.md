# Kite AI Auto-Bot

An automated interaction bot for Kite AI platform with multi-wallet and proxy support. 


## 🌟 Features

- Proxy support (HTTP/HTTPS/SOCKS)
- Rate limiting and retry mechanisms
- Multiple AI agents interaction
- Automatic question selection

## 📋 Prerequisites

- Node.js (v16 or higher)
- npm (Node Package Manager)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/deasaputra12/KiteAi-Auto-Bot.git
cd KiteAi-Auto-Bot
```

2. Install dependencies:
```bash
npm install
```

## 📝 Configuration

1. (Optional) Create a `proxies.txt` file for proxy support:
```
http://user:pass@host:port
socks5://user:pass@host:port
```

2. Create a `wallets.txt` file for multiple wallets:
```
0x1234567890abcdef1234567890abcdef12345678
0xabcdef1234567890abcdef1234567890abcdef12
```

## 🚀 Usage

Run the bot:
```bash
npm run start
```

The bot will prompt you to:
1. Choose connection mode (Direct/Proxy)
2. Choose wallet input mode (Manual/File)
3. Enter wallet address (if manual mode)

## ⚙️ Configuration Options

You can modify the following settings in `index.js`:

- `rateLimitConfig`: Adjust rate limiting parameters
- `agents`: Modify available AI agents
- `intervalBetweenCycles`: Change delay between interaction cycles

