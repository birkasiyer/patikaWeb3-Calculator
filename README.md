# Simple Calculator - Motoko

This project is a simple calculator implemented in **Motoko**, designed as part of the Web3 internship application for Patika.dev. The calculator leverages Internet Computer (IC) canisters to demonstrate basic arithmetic operations within a smart contract.

## Features

- **Addition**: Adds a given number to the current value.
- **Subtraction**: Subtracts a given number from the current value.
- **Multiplication**: Multiplies the current value by a given number.
- **Division**: Divides the current value by a given number. Handles division by zero by returning `null`.
- **Reset**: Resets the stored value to `0`.

## Code Overview

The main actor is `hesap_makinesi` (calculator), which includes:
1. A variable `hucre` to store the current value.
2. Methods for basic arithmetic operations:
   - `toplama`: Addition
   - `cikarma`: Subtraction
   - `carpma`: Multiplication
   - `bolme`: Division
3. A method to reset the value: `temizle`.

## Usage

This project can be run on the **Motoko Playground**:
1. Open the [Motoko Playground](https://m7sm4-2iaaa-aaaab-qabra-cai.ic0.app/).
2. Copy the code from the repository into the playground.
3. Deploy the canister and test the methods.

## Example

### Addition:
```motoko
await hesap_makinesi.toplama(10); // Adds 10 to the current value.

Notes

This project showcases:
	•	The use of Motoko for developing smart contracts.
	•	Application of asynchronous programming (async) and conditionals (if statements).
	•	Basic understanding of the Internet Computer ecosystem.

Author

Developed by Doğukan Aydın as part of Patika.dev’s Web3 internship application.
