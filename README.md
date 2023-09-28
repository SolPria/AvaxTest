# AvaxTest Smart Contract

This is a Solidity smart contract named `AvaxTest` that demonstrates various error-handling mechanisms within Ethereum smart contracts. It includes three functions: `testRequire`, `testAssert`, and `testRevert`, each showcasing a different way to handle errors and conditions.

## Table of Contents

- [Smart Contract Overview](#smart-contract-overview)
- [Function 1: `testRequire`](#function-1-testrequire)
- [Function 2: `testAssert`](#function-2-testassert)
- [Function 3: `testRevert`](#function-3-testrevert)
- [Usage](#usage)
- [License](#license)

## Smart Contract Overview

The `AvaxTest` contract consists of three primary components:

- `num`: A public variable of type `uint256` that stores an unsigned integer.

## Function 1: `testRequire`

This function showcases the use of the `require` statement for error handling. It checks if the input value `x` is greater than 5 and, if not, reverts the transaction with an error message.

## Function 2: `testAssert`

The `testAssert` function demonstrates the `assert` statement. It verifies whether the input value `x` is greater than 10 and immediately halts execution with an exception if the condition is not met.

## Function 3: `testRevert`

`testRevert` illustrates the `revert` mechanism. It checks if the input value `x` exceeds 15 and explicitly triggers a revert with a custom error message if the condition holds true.

## Usage

To use this smart contract, you can follow these steps:

1. Deploy the `AvaxTest` contract to your desired Ethereum network.
2. Interact with the contract by calling the `testRequire`, `testAssert`, and `testRevert` functions with appropriate inputs to observe their error-handling behaviors.

## License

This contract is open-source and is released under the MIT License. You can find the license details in the contract file itself.

