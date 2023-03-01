# Solved EVM Puzzles and More EVM Puzzles

A collection of EVM puzzles. Each puzzle consists on sending a successful transaction to a contract. The bytecode of the contract is provided, and you need to fill the transaction data that won't revert the execution.

Total Puzzles Solved: 20

## How to play

1. Clone this repository
2. Delete the solutions folder
3. Install its dependencies (`npm install` or `yarn`).
4. Then run:

```
npx hardhat play
```

And the game will start.

In some puzzles you only need to provide the value that will be sent to the contract, in others the calldata, and in others both values.

You can use [`evm.codes`](https://www.evm.codes/)'s reference and playground to work through this.
