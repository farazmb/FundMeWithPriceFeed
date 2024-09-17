# FundMeSmartContract

## About

This is a crowd-sourcing application built with a smart contract that allows users to fund with ETH. It uses Chainlink price feeds to ensure minimum funding in USD.

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

    Deploy the contract with the Chainlink price feed address using Hardhat:

    ```bash
    npx hardhat run scripts/deploy.js
    ```

## Integration Tests

### How to Run Tests

1. **Install Testing Libraries**

    Ensure you have Hardhat and necessary testing dependencies installed.

2. **Run Tests**

    Execute the tests with:

    ```bash
    npx hardhat test
    ```

### PIT STOP! How to Make Running These Scripts Easier

To simplify running tests, you can add a script to your `package.json`:

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

You can verify the contract programmatically using Hardhat or Truffle scripts to interact with the deployed contract and check its state. Create custom scripts to automate verification tasks.

## Push to GitHub

1. **Commit Changes**

    ```bash
    git add .
    git commit -m "Add integration tests and setup instructions"
    ```

2. **Push to GitHub**

    ```bash
    git push origin main
    ```
