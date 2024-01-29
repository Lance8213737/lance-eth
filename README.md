MyToken Solidity Smart Contract

Overview

This Solidity smart contract, named MyToken, is a basic implementation of a token with minting and burning functionalities. It operates on the Ethereum blockchain and is released under the MIT License.

Contract Details

Token Information
Name: lans
Abbreviation: lansi
Variables
totalSupply: Tracks the total supply of the token.
Functions
1. Minting Function
function mint(address _address, uint _value) public
Mints new tokens and assigns them to the specified address.

2. Burning Function

solidity
function burn(address _address, uint256 _value) public
Burns a specified amount of tokens from the given address, decreasing the total supply.

License

This smart contract is released under the MIT License. See the LICENSE file for more details.

SPDX-License-Identifier
