# OpenLedger Auto Claim Bot

An automated bot for claiming daily rewards on OpenLedger Testnet.

Register: [https://testnet.openledger.xyz](https://testnet.openledger.xyz/?referral_code=pkf36oc2fa)
## Features

- Automatic daily reward claiming
- User information display
- Streak tracking
- Countdown timer for next claim
- Colorful console output
- Error handling

## Prerequisites

- Node.js (v14 or higher)
- npm (Node Package Manager)

## Installation

1. Clone this repository

```bash
git clone https://github.com/im-hanzou/OpenLedger-DailyClaim.git
cd OpenLedger-DailyClaim
```

2. Install dependencies

```bash
npm install
```

## Getting Started

1. Register on [OpenLedger Testnet](https://testnet.openledger.xyz/?referral_code=ikurpd77ae)

2. Get your JWT Token

- Login to your OpenLedger Testnet account
- Go to Dashboard
- Press F12 or right-click and select 'Inspect' to open Developer Tools
- Go to Network tab
- Look for any request and find the 'Authorization' header value
- Copy the token (it starts with "Bearer ")

3. Create edit data.txt file in the project root`

4. Run the bot

```bash
node main.js
```

## Features Explanation

- **User Info**: Displays your address, ID, and referral code
- **Claim Details**: Shows your tier, daily point allocation, and claim status
- **Streak Info**: Tracks your consecutive daily claims
- **Auto Claim**: Automatically claims rewards when available
- **Countdown Timer**: Shows time remaining until next claim


## Error Handling

The bot includes comprehensive error handling:

- Token reading errors
- API request failures
- Network issues
- Invalid responses

If any error occurs, the bot will:

1. Log the error with details
2. Wait for 1 hour
3. Attempt to retry the operation

## Contributing

Feel free to fork this repository and submit pull requests for any improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This bot is for educational purposes only. Use it at your own risk. The developer is not responsible for any account-related issues or potential losses.
Source : https://github.com/Galkurta/
