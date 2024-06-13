
# Vesting-Smart-Contract

## Description
This project involves building a token vesting smart contract on the blockchain, managing vesting for three distinct roles: User, Partners, and Team. The contract handles token vesting according to specific schedules for each role. The following document provides a detailed overview of the project, including the Solidity smart contract code, deployment instructions, and usage guide.


## Overview

 * Roles and Vesting Schedules
     1. User
        - Allocation: 50% of total allocated tokens
        - Cliff Period: 10 months
        - Vesting Duration: 2 years
   
     2. Partners
        - Allocation: 25% of total allocated tokens
        - Cliff Period: 2 months
        - Vesting Duration: 1 year
   
     3. Team
        - Allocation: 25% of total allocated tokens
        - Cliff Period: 2 months
        - Vesting Duration: 1 year

##Features
      - Owner can start vesting.
      - Beneficiaries can be added for each role before vesting starts.
      - Beneficiaries can claim their vested tokens according to the schedule.
      - Events are emitted for vesting start, beneficiary addition, and token withdrawal.
  
 ##Deployment and Usage
      - Install Dependencies: Ensure you have Node.js and npm installed. Install the necessary dependencies:

## bash
    npm install @openzeppelin/contracts

Compile the Contract: Use a Solidity compiler (like Remix) to compile the contract.

 * Deploy the Contract: 
    - Deploy the compiled contract on your preferred Ethereum network (testnet or mainnet). Ensure you provide the correct token address and total allocated tokens during deployment.



