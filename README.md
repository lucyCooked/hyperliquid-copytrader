I'll update the README to include download instructions:

# HyperLiquid Copy Trader

Copy trading application for HyperLiquid.

## Download
1. Go to the [Releases](https://github.com/lucyCooked/hyperliquid-copytrader) section
2. Download the latest version for your operating system
3. Extract the downloaded file

## Prerequisites
- Python 3.8+
- Pip package manager
- Linux server with SSH access

## Installation

1. Install Python 3.8+:
   - Download the installer from [python.org](https://www.python.org/downloads/)
   - Run the downloaded .pkg file
   - Follow the installation wizard
   - Verify installation: `python3 --version`

2. Install required Python packages:
```bash
pip install -r requirements.txt
```

3. Install PM2 globally:
```bash
npm install pm2 -g
```

4. For Mac users, build the application:
```bash
python build_mac.py
```

The built application will be in the `dist` folder.

## Configuration
1. Server details (required for connection):
   - Server address
   - Username
   - Password

2. Trading configuration:
   - Address to copy trade
   - Your Web3 wallet address
   - Private key from API
   - Position multiplier

## Security Notice
- Never share private keys
- Use secure SSH connections
- Store credentials safely
- The application uses keyring for secure credential storage

## License
MIT License
