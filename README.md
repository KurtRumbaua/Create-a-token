# Project Title

MyToken is a basic digital currency (cryptocurrency) that can be created (minted) and destroyed (burned). It demonstrates how digital assets can be tracked and managed on a blockchain.

## Description

MyToken is a simplified representation of a digital currency (cryptocurrency) built on the Ethereum blockchain. It showcases the essential mechanisms behind how these tokens function, providing a foundation for understanding more complex token economies. Users can create new MyTokens through a minting process, increasing the total supply in circulation. Conversely, they can also destroy existing tokens through burning, reducing the overall supply. Each user's token balance is meticulously tracked, ensuring transparency and security. This contract serves as an educational tool and a starting point for developers who are exploring the world of blockchain and decentralized finance. 

## Getting Started

### Executing the Program

This section guides you through deploying and interacting with the `MyToken` contract using Remix IDE.

#### How to run the program:

1. **Clone the Repository:**
   * In Remix, open the "Workspace Actions" dropdown (down arrow icon).
   * Select "Clone Repository."
   * Paste the following URL: `https://github.com/KurtRumbaua/Create-a-token.git`
   * Click "OK" to clone the repository.

2. **Review the Contract:**
   * Open the `contracts` folder.
   * Examine `MyToken.sol` to understand its structure and functions.

3. **Compile the Contract:**
   * Click the Solidity compiler icon (wrench) in the sidebar.
   * Ensure the compiler version is set to 0.8.26 (or later).
   * Click "Compile MyToken.sol."

4. **Deploy the Contract:**
   * Go to the "Deploy & Run Transactions" tab.
   * Choose "MyToken" from the contract dropdown.
   * Click "Deploy." Confirm the transaction in MetaMask.

5. **Interact with the Contract:**
   * The contract's address will be under "Deployed Contracts."
   * Expand it to access the functions:
      * `mint(address _address, uint _value)`: Creates tokens.
      * `burn(address _address, uint _value)`: Destroys tokens.
      * `balances(address _address)`: Checks the balance of an address.
   * Enter the relevant address and token amount for each function.
   * Click the function name to execute it.
