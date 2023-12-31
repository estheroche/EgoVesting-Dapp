Vesting Contract Dapp

This Solidity software is a full stack "Vesting contract" application with a frontend that is completely integrated with smart contracts. It uses the factory contract paradigm to enable anyone to develop vesting contracts.
An explanation

Written in Solidity, a programming language used to create smart contracts on the Ethereum blockchain, this program is a straightforward contract. The contract incorporates a time lock mechanism that forbids users from withdrawing vested tokens prior to the designated unlock time. It is a factory contract that launches new instances of a child contract that anyone can use to create vesting plans on behalf of employees or stakeholders of their company.

Functionalities Implemented

The contract implements the following features:

    Function that allows an organization to register themselves and their token
    Function that allows an Organization to be able to mention the type of stakeholder and their vesting period.
    Function that Organization should be able to whitelist addresses for certain stakeholders (founders, investors etc.).
    Whitelisted addresses should be able to claim their tokens after the vesting period.

Live Url:

https://ego-vesting-dapp-wja5.vercel.app/


Contract Addresses

TokenContract: https://sepolia.etherscan.io/address/0x99b3bca6b5d13464c2c986f220d7f962a5fce7bb

OrganizationFactory Contract: https://sepolia.etherscan.io/address/0x5d7005b3a59c991454aa4889c6e6780283e17ec2

Organization Contract: https://sepolia.etherscan.io/address/0x93136f5b0c6948716d6a4d8decd0bc1f8db585b9
Authors

Esther Oche @metacraftersio   
https://twitter.com/Estheroche1

License
This project is licensed under the MIT License - see the LICENSE.md file for details