# ErrorHandling Contract

This is a Solidity smart contract which is uses the function assert, revert, and require functions in Solidity.


## License

In this contract MIT license will be used.

## Prerequisites

- Solidity ^0.8.0

## Description

# There are having a three functions.These are as follows:-

### 1.function Assert(uint number)

.doAssert(uint a, uint b) returns (uint)

.Demonstrates the usage of assert()

.This function takes two parameters a and b.

.It will return the sum of a and b if they are not equal. Otherwise, it will trigger an internal error and revert the transaction.

### 2.function divide(uint _numerator, uint _denominator)

 .This function  uses the `revert` function.
 
 .It is used to revert contract execution and provide an error messages.
 
 .It has two parameters  which are numerator and denominator to performs division.
 
 .If the numerator is less than denominator then it will reverts the transaction with an error message stating that the numerator should be greater than the denominator.
 
 .If the condition met, it will returns the result by dividing the numerator and denominator.
 
 ### updateValue(uint newValue)

.This function  uses the `require` function.

.Updates the contract's value with the provided newValue as a parameter. 

.Here there is a condition that only the contract owner can call this function.

## Usage

1. Make sure you have installed Solidity ^0.8.0
3. Compile and deploy the `ErrorHandling` contract to a supported Ethereum network.
4. Interact with the deployed contract by calling the available functions and providing the required parameters.
