# BankDapp

## Overview
BankDapp is a decentralized application designed to provide basic banking functionalities in a secure and user-friendly manner. With BankDapp, users can create an account by providing their name, account number, ID, and PIN. Additionally, users can check their account balance by entering their account number and PIN. This Dapp leverages blockchain technology to ensure transparency, security, and reliability, making it an ideal solution for those seeking a modern and accessible banking experience.


## Key Features
Account Creation: Users can easily create a new bank account by providing the necessary information such as name, account number, ID, and PIN.

Balance Checking: Users can securely check their account balance by entering their account number and PIN.

## How to Use
### Creating an Account

Open BankDapp in your web browser.

Fill in the form with your name, account number, ID, and PIN.

Click the "Create Account" button to register your account.

### Checking Balance

Open BankDapp in your web browser.

Enter your account number and PIN in the respective fields.

Click the "Check Balance" button to view your account balance.
BankDapp is a simple decentralized application that allows users to create a bank account and check their account balance.

## Screenshots
![Screenshot 2025-02-14 004358](https://github.com/user-attachments/assets/af8859f1-9f91-4be5-9ef6-681586007e0b)

![Screenshot 2025-02-14 004443](https://github.com/user-attachments/assets/680909ba-a88f-47ef-8abb-414970253da6)


## Tech Stack

- **Blockchain**: Ethereum (using Solidity for smart contract development)
- **Smart Contracts**: Written in Solidity
- **Backend**: Truffle framework (for smart contract management)
- **Frontend**: HTML, CSS, JavaScript (interacting with the blockchain via Web3.js)

## Installation

### Prerequisites

- Install Node.js, which is required to manage the project's dependencies.
- Install Truffle, a framework for smart contract development.
- Install Ganache, a personal blockchain for Ethereum development.

  ### Steps to Run the Project

1. **Clone the repository** to your local machine:
    ```bash
    git clone https://github.com/Jaysi1701/Dapp-Bank.git
    ```
2. **Navigate into the project folder**:
    ```bash
    cd Dapp-Bank
    ```
3. **Install all necessary dependencies** using Node.js and npm (Node Package Manager):
    ```bash
    npm install
    ```
4. **Start Ganache** to run a local Ethereum blockchain for testing.
5. **Compile the smart contracts** to prepare them for deployment:
    ```bash
    truffle compile
    ```
6. **Migrate the smart contracts** to the local Ethereum blockchain using Truffle:
    ```bash
    truffle migrate
    ```
7. **Launch the frontend** by opening the project in any HTTP server (like the Live Server extension in Visual Studio Code or another local server).









