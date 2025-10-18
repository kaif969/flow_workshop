### 🧮 Storage Smart Contract

A simple Solidity project demonstrating how to store and retrieve a value on the Ethereum blockchain — implemented and deployed using Hardhat.
---

## 📜 Description

The Counter contract maintains a single state variable, count, which is a signed 256-bit integer (int256). The value of this counter can be modified through increment and decrement functions, and its value can be read at any time.
### Contract Address : 0xd9145CCE52D386f254917e481eB44e9943F39138
---

## ✨ Features

- *Initial Value:* Set an initial value for the counter during contract deployment.
- *Increment:* Increase the counter's value by 1.
- *Decrement:* Decrease the counter's value by 1.
- *View Count:* Retrieve the current value of the counter without consuming gas (in a local call).

---

## 🔧 Contract Details

### State Variables

- int256 public count: Stores the current value of the counter. The public visibility keyword automatically creates a getter function to read its value.

### Functions

#### Constructor
