# Degen Token 

This repository contains the source code for a Solidity smart contract named `degen_Token`, which implements functionalities for managing a custom ERC20 token, allowing users to redeem tickets for sneakers and earn rewards.

## Contract Overview

### ERC20 Compliance

The `degen_Token` contract extends the ERC20 standard, allowing it to be compatible with Ethereum's token ecosystem. It inherits basic token functionalities such as transfer, balance check, and allowance management.

### Ownable

The contract also inherits from the `Ownable` contract from OpenZeppelin, which provides basic authorization control functions, simplifying the implementation of access control mechanisms.

### Ticket Redemption

Users can redeem tickets for three types of sneakers: Puma, Adidas, and Nike. Each sneaker has a predefined cost associated with it (`Puma_Cost`, `Adidas_Cost`, `Nike_Cost`). Upon redemption, the user's tokens are burned, and the selected sneaker is recorded along with the amount spent.

### Reward System

The contract includes a reward system where the contract owner can add rewards to specific addresses. Users can check their reward balance and claim rewards accordingly.

### Exchange Rate Management

The contract includes functionality to manage the exchange rate of the token against a specified currency. The owner can set and retrieve the exchange rate.


## License

This code is released under the MIT License. See the `LICENSE` file for more information.

## Author

Monu360v@gmail.com
