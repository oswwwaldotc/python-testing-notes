# Source Code Overview

This directory contains the core implementation of a banking system with additional utility features.

## Core Components

### Banking System
- `bank_account.py` - Implements the `BankAccount` class with:
  - Balance management
  - Transaction logging
  - Time-restricted withdrawals (8am-5pm)
  - Deposit and withdrawal operations
  
- `user.py` - Implements the `User` class for:
  - Managing multiple bank accounts
  - Basic user information (name, email)
  - Total balance calculation across accounts

- `exceptions.py` - Custom exceptions:
  - `InsufficientFundsError`
  - `WithdrawalTimeRestrictionError`

### Utility Modules
- `calculator.py` - Basic arithmetic operations:
  - Addition (sum)
  - Subtraction
  - Multiplication
  - Division (with zero division protection)
  - Includes doctest examples

- `api_client.py` - External API integration:
  - IP geolocation lookup using freeipapi.com
  - Returns country, region, and city information

## Error Handling
The system includes robust error handling for common scenarios:
- Insufficient funds for withdrawals
- Time-restricted withdrawals
- Division by zero protection
- API request error handling

## Dependencies
- `requests` - For API calls
- Python's standard library (`datetime`)

# Disclaimer
- The project is a simple example and is not meant to be a full application.
- The current README was generated using AI and is not meant to be a good example of how to write a README.
