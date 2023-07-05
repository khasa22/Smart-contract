# Smart-contract
This smart contract comprises functions for the exchange of ERC tokens between various accounts.
Token Exchange Overview
1. ERC20
• Functions:
      o Total Supply: Return the total number of tokens from the associated account. Such as the subject who has deployed the account “CryptoPayment” is the owner of account.
      o SetToken: Set the number of tokens and owner account address value probability drop off exponentially with z.
      o transfer: Transfer the given token from the owner's account to the recipient’s account
      o TransferFrom: Transfer the given token from mentioned sender account to the recipient account
      o Allowance: check transfer permission of tokens from one account to another
      o Approve: set the number of tokens allowed for transfer from account A to account B
      o balanceOf: Return balance in the form of token in a given account
Events:
      • Two events Transfer and Approve are declared which get to be triggered upon transfer of 
      token and approval of transaction respectively.
 • SafeMath is used to handle integer-related errors 
3. Library: SafeMath
    Safemath library provides the safe use of signed/unsigned numbers in solidity such as overflow in addition, underflow in subtraction, and multiplication and division.

