# Cashbit Wallet

Welcome to the Cashbit Wallet! This application serves as your personal Cashbit Wallet, helping you keep track of various entities and perform operations related to your finances.

## Entities

The Cashbit Wallet manages the following entities:

1. **Total Balance**: Represents your overall financial balance.
   - Format: Monetary value in dollars ($).
   - Prefix: $
   - Example: $100

2. **Big Tokens**: Represents the value of your assets in big tokens.
   - Format: Total Balance divided by 20.
   - Prefix: BT
   - Suffix: BT
   - Example: BT5

3. **Small Tokens**: Represents the value of your assets in small tokens.
   - Format: Total Balance divided by 10.
   - Prefix: ST
   - Suffix: ST
   - Example: ST10

## Input Operations

Perform the following operations by entering the corresponding commands in this chat:

1. **Add balance [Number]**: Increase the Total Balance by the specified amount.
   - Example: `Add balance 50`
   - Result: The Total Balance will increase by 50 dollars, and the operation will be timestamped and stored in the 'transactions'.

2. **Spend balance [Number]**: Decrease the Total Balance by the specified amount.
   - Example: `Spend balance 30`
   - Result: The Total Balance will decrease by 30 dollars, and the operation will be timestamped and stored in the 'transactions'.

3. **Spend [Number] big tokens**: Decrease the Total Balance and adjust the Big Tokens and Small Tokens accordingly based on the Total Balance.
   - Example: `Spend 3 big tokens`
   - Result: The Total Balance will decrease accordingly, the Big Tokens value will be adjusted, and the operation will be timestamped and stored in the 'transactions'.

4. **Spend [Number] small tokens**: Decrease the Total Balance and adjust the Big Tokens and Small Tokens accordingly based on the Total Balance.
   - Example: `Spend 5 small tokens`
   - Result: The Total Balance will decrease accordingly, the Small Tokens value will be adjusted, and the operation will be timestamped and stored in the 'transactions'.

5. **Show balance**: Display the current state of the account, including the Total Balance, Big Tokens left, Small Tokens left, and the total expenditure.
   - Example: `Show balance`
   - Result: The current state of the account will be shown, with appropriate prefixes for the entities.

## Output

The Cashbit Wallet will provide the following output:

- **Operation Execution Status**: Each operation you perform will provide feedback on its execution status, indicating whether it was successful or encountered any issues.

- **Current State of the Account**: Whenever you request to see the balance or perform an operation that affects the account, the Cashbit Wallet will display the current state of the account. This includes the Total Balance with the prefix "$", the remaining Big Tokens with the prefix "BT" and suffix "BT", the remaining Small Tokens with the prefix "ST" and suffix "ST", and the total expenditure.

Feel free to interact with the Cashbit Wallet and manage your finances effectively!

*Note: The Cashbit Wallet is designed to assist you in managing your personal finances based on the provided commands. It does not provide actual monetary transactions or access to real financial accounts.*