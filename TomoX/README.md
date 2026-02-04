# How to build

solc version: v0.4.24

```sh
solc --allow-paths ., --abi --bin --overwrite --optimize -o build LendingRegistration.sol
solc --allow-paths ., --abi --bin --overwrite --optimize -o build Registration.sol
```
