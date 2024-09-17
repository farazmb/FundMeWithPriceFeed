# FundMeSmartContract

## About

This is a crowd-sourcing smart contract that allows users to fund with ETH, using Chainlink price feeds to ensure the minimum funding in USD.

## Getting Started

### Requirements

- [Node.js](https://nodejs.org/)
- [Hardhat](https://hardhat.org/)
- [Chainlink](https://chain.link/)

### Quickstart

1. **Clone the Repository**

    ```bash
    git clone https://github.com/yourusername/FundMeSmartContract.git
    cd FundMeSmartContract
    ```

2. **Install Dependencies**

    ```bash
    npm install
    ```

3. **Deploy the Contract**

    ```bash
    npx hardhat run scripts/deploy.js
    ```

4. **Run Integration Tests**

    ```bash
    npx hardhat test
    ```

    To simplify running tests, add a script to your `package.json`:

    ```json
    "scripts": {
        "test": "npx hardhat test"
    }
    ```

    Then run:

    ```bash
    npm test
    ```

## Programmatic Verification

You can verify the contract programmatically using custom Hardhat or Truffle scripts.

## Push to GitHub

1. **Commit Changes**

    ```bash
    git add .
    git commit -m "Add integration tests and setup instructions"
    ```

2. **Push to GitHub**

    ```bash
    git push origin master
    ```