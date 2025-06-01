# Bitcoin Checker

![Bitcoin Logo](https://bitcoin.org/img/icons/opengraph.png)

## Overview

Bitcoin Checker is a simple, user-friendly web application that allows users to check Bitcoin wallet addresses and transaction hashes, view balances, and track transaction history. This tool provides real-time information about Bitcoin addresses and transactions using the Blockchain.com API.

## Features

- **Address Balance Checking**: View the current balance of any Bitcoin address
- **Transaction Details**: Examine the details of specific Bitcoin transactions
- **Transaction History**: View the transaction history of a Bitcoin address
- **Real-time BTC to USD Conversion**: All Bitcoin values are automatically converted to USD
- **Responsive Design**: Works on desktop and mobile devices

## Demo

You can try the live demo by visiting [Bitcoin Checker Demo](https://your-github-username.github.io/bitcoinchecker/) (update this link after deployment)

## Screenshots

*Add screenshots of your application here*

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- Blockchain.com API
- Font Awesome for icons

## How to Use

1. Enter a Bitcoin address or transaction hash in the search box
2. Click "Check Balance" or press Enter
3. View the balance information and transaction history
4. For transaction hashes, view detailed input and output information

## Local Development

### Prerequisites

- A modern web browser
- Internet connection (to access the Blockchain.com API)

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-github-username/bitcoinchecker.git
   ```

2. Navigate to the project directory:
   ```
   cd bitcoinchecker
   ```

3. Open `bitoinchecker.html` in your web browser

## API Usage

This project uses the following Blockchain.com API endpoints:

- `/rawaddr/{bitcoin_address}` - Get address information and transactions
- `/rawtx/{tx_hash}` - Get detailed transaction information
- `/ticker` - Get current BTC to USD exchange rate

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

- [Blockchain.com API](https://www.blockchain.com/api) for providing Bitcoin data
- [Font Awesome](https://fontawesome.com/) for the icons

## Contact

Your Name - [your-email@example.com](mailto:your-email@example.com)

Project Link: [https://github.com/your-github-username/bitcoinchecker](https://github.com/your-github-username/bitcoinchecker)

---

*Note: This is a tool for educational purposes. Always verify important Bitcoin transactions through multiple sources.*