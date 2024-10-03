# StellarPay

Project Visual

##About Me

Züleyha Uslu is a passionate Mathematical Engineering student at Yildiz Technical University. Her love for problem-solving led her to participate in the Rise In Full Stack bootcamp, where she gained valuable skills in web development. Through this experience, Züleyha enhanced her coding abilities and broadened her understanding of full stack technologies, preparing her for a future in both software development and engineering. Her dedication to learning and exploring new areas of technology reflects her ambition to excel in her field.

##Description

StellarPay is a blockchain-based payment and messaging platform built on the Stellar network. It allows users to send payments and messages securely, without the need for complex key management. StellarPay supports regular payments, transfers to multiple recipients, and provides easy access to transaction history. It is designed to be user-friendly, enabling people to manage their finances with just a few clicks. The platform ensures fast, low-cost transactions, making it ideal for both personal and business use. With StellarPay, users can also set up recurring payments for subscriptions or salary disbursements, making financial management more efficient. The goal of StellarPay is to leverage the power of blockchain to create a simple, secure, and transparent financial solution for everyone.

##Vision

StellarPay envisions a world where sending money and messages is as easy and secure as sending a text. By leveraging the Stellar blockchain, we aim to provide fast, low-cost transactions to everyone, regardless of location or financial status. Our platform will empower individuals and businesses by simplifying financial management, increasing transparency, and reducing transaction costs. StellarPay’s vision is to foster global financial inclusion, enabling people in underserved regions to participate in the digital economy and helping businesses streamline their payment processes efficiently and securely.

##Project Roadmap/Future Plans

Develop a Stellar smart contract to handle payments and messaging functions.
Key variables include:
senderAddress: Address of the payer.
receiverAddress: Address of the payee(s).
amount: Payment amount.
message: Optional message accompanying the transaction.
schedule: For recurring payments.
transactionHistory: To store transaction records.
2. Implement Payment Functionality:

Create functions to:
Transfer payments between users (sendPayment).
Handle multiple recipients (multiSendPayment).
Schedule recurring payments (schedulePayment).
3. Add Messaging Feature:

Build a secure messaging function (sendMessage) that allows users to send messages with or without payments.
4. Transaction History and Notifications:

Develop a getTransactionHistory function for users to view their past transactions.
Integrate a notification system to alert users of incoming payments and messages.
5. Front-End Development:

Design a simple UI for sending payments, setting up recurring payments, and messaging.
Ensure a smooth user experience with wallet integration for Stellar accounts.
Display transaction history and notification pop-ups for new messages/payments.
6. Testing and Deployment:

Test the smart contract functions and UI on the Stellar test network.
Once verified, deploy the project to the Stellar mainnet for live use.

##The Tech We Use

Rust and Web3

##Smart Contract Adress

www.linkedin.com/in/zuleyhauslu

##Setup Environment

# StellarPay

StellarPay is a decentralized payment and messaging platform built on the Stellar blockchain. It allows users to send payments and messages securely, with features like recurring payments and multi-recipient transfers.

## Features
- Send payments on the Stellar network
- Schedule recurring payments
- Transfer to multiple recipients
- Secure messaging with transactions
- View transaction history

## Prerequisites
Before installing StellarPay, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- Stellar SDK (`npm install stellar-sdk`)
- A Stellar testnet account (for testing purposes)

## Installation

1. **Clone the repository:**


   git clone https://github.com/yourusername/StellarPay.git
Navigate to the project directory:


cd StellarPay
Install dependencies:

If you're using npm:


npm install
Or if you're using yarn:


yarn install
Set up environment variables:

Create a .env file in the root of the project and add your Stellar testnet account details:


STELLAR_NETWORK=testnet
STELLAR_SECRET_KEY=your_testnet_secret_key
STELLAR_PUBLIC_KEY=your_testnet_public_key
Run the application:

To start the development server, run:


npm start
Or with yarn:


yarn start
Access the application:

Open your browser and go to http://localhost:3000 to interact with StellarPay.

Testing
You can test smart contract functions on the Stellar testnet using the provided test scripts:


npm run test
Deployment
When ready, deploy to the Stellar mainnet following the deployment instructions in the project.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

arduino


This README gives users a clear step-by-step guide to installing and running the project, with necessary environment setup details.
