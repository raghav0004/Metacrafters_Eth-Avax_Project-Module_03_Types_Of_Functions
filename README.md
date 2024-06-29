
# Metacrafters_ETH+AVAX_Intermediate_Project_03_Submission


## CustomToken Smart Contract

The CustomToken smart contract showcases advanced error handling techniques in Solidity, specifically designed for managing deposit and withdrawal operations with rigorous condition checks using require statements. Additionally, the contract employs assert and revert to ensure robust error management and handle unexpected states effectively.

### Contract Explanation

The CustomToken contract is an ERC20 token named "Binance Coin" (symbol: "BNB"). It utilizes Solidity version 0.8.26 and inherits essential ERC20 functionalities from the OpenZeppelin library.

#### SPDX License Identifier

- The comment `// SPDX-License-Identifier: MIT` specifies that this contract is licensed under the MIT License, allowing permissive use of the code.

#### Pragma Directive

- `pragma solidity 0.8.26;` ensures compatibility with Solidity compiler version 0.8.26, providing stability and preventing version-related issues.

#### Importing OpenZeppelin ERC20

- `import "@openzeppelin/contracts/token/ERC20/ERC20.sol";` imports the ERC20 standard implementation from OpenZeppelin, enabling core functionalities like transfers and balance management.

#### Contract Definition

- The contract `MyToken` inherits from ERC20, initializing with the name "Binance Coin" and symbol "BNB" through its constructor.

#### Mint Function

- `mint(address _to, uint256 _amount)`: Creates new tokens and assigns them to `_to` address. Utilizes `_mint` function inherited from ERC20.

#### Burn Function

- `burn(uint256 _amount)`: Allows the sender to destroy `_amount` tokens, reducing total supply. Uses `_burn` function inherited from ERC20.

### Deployment

Deploy the contract using Remix IDE or other Ethereum development frameworks (like Hardhat & Foundry). Ensure to configure gas fees and specify the network for deployment.

By leveraging these functionalities and error handling mechanisms, the CustomToken contract provides a secure and compliant approach to managing ERC20 tokens on the Ethereum blockchain.

