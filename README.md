# Bitcoin Checker

<img src="https://bitcoin.org/img/icons/opengraph.png" alt="Bitcoin Logo" width="200">

## Overview

Bitcoin Checker is a simple, user-friendly web application that allows users to check Bitcoin wallet addresses and transaction hashes, view balances, and track transaction history. The application features a classic, retro UI inspired by the legendary Bitcointalk.org forum and provides real-time information using the Mempool.space API.

## Features

- **Address Balance Checking**: View the current balance of any Bitcoin address
- **Transaction Details**: Examine the details of specific Bitcoin transactions
- **Transaction History**: View the transaction history of a Bitcoin address
- **Real-time BTC to USD Conversion**: All Bitcoin values are automatically converted to USD (utilizing CoinDesk, CoinGecko, or Binance APIs)
- **Classic Retro UI**: Styled after the classic Bitcointalk.org forum for a nostalgic feel
- **Responsive Design**: Works on desktop and mobile devices

## Demo

You can try the live demo by visiting [Bitcoin Checker Demo](https://libraco.github.io/bitcoinchecker/)

## Technologies Used

- HTML5
- CSS3 (Classic Bitcointalk Theme)
- JavaScript (ES6+)
- Mempool.space API (Blockchain Data)
- CoinDesk / CoinGecko / Binance APIs (Price Data)
- Font Awesome for icons

## How to Use

1. Enter a Bitcoin address or transaction hash in the search box
2. Click "Check Balance" or press Enter
3. View the balance information and transaction history
4. For transaction hashes, view detailed input and output information

## Local Development

### Prerequisites

- A modern web browser
- Internet connection (to access the required APIs)

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/libraco/bitcoinchecker.git
   ```

2. Navigate to the project directory:
   ```
   cd bitcoinchecker
   ```

3. Open `index.html` in your web browser

## API Usage

This project uses the following endpoints to function:

**Mempool.space API** (For on-chain data)
- `/api/address/{bitcoin_address}` - Get address statistics and balances
- `/api/address/{bitcoin_address}/txs` - Get transaction history for an address
- `/api/tx/{tx_hash}` - Get detailed transaction information

**Price APIs** (Fallback mechanism for USD rates)
- `api.coindesk.com`
- `api.coingecko.com`
- `api.binance.com`

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Mempool.space API](https://mempool.space/docs/api/rest) for providing reliable Bitcoin data
- [Bitcointalk.org](https://bitcointalk.org/) for the UI inspiration
- [Font Awesome](https://fontawesome.com/) for the icons

## Donation

If you find this tool useful, please consider donating:

BTC: `bc1quhsqgufun9fnqr8e4ntexg6q4gv62kmknyc97l`

## Project Link

[https://github.com/libraco/bitcoinchecker](https://github.com/libraco/bitcoinchecker)

---

*Note: This is a tool for educational purposes. Always verify important Bitcoin transactions through multiple sources.*