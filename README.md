# Python Banking System

A simple banking system implementation with unit testing examples demonstrating various Python testing approaches.

## Purpose of the project

The purpose of this project is to demonstrate the use of unittest and pytest frameworks for testing Python applications.

## Project Overview

This project implements a basic banking system with the following core features:
- Bank account management
- User management with multiple accounts
- Transaction logging
- Business hours restrictions for withdrawals
- API integration for location services

## Core Components

### Bank Account
The BankAccount class (`src/bank_account.py`) provides:
- Deposit functionality
- Withdrawal with time restrictions (8am-5pm only)
- Balance checking
- Transaction logging
- Custom exception handling

### User Management
The User class (`src/user.py`) supports:
- Multiple account management
- Total balance calculation across accounts
- Basic user information storage

### API Integration
Location services (`src/api_client.py`) featuring:
- IP-based location lookup
- Country, region, and city information retrieval

## Testing Suite

The project includes comprehensive testing examples using:
- unittest
- pytest
- Mock objects
- Parameterized testing
- Test fixtures
- Various assertion types

### Test Categories
1. Bank Account Tests
   - Transaction validation
   - Balance management
   - Time restriction enforcement
   - Error handling

2. User Tests
   - Account management
   - Balance calculations
   - Data generation using Faker

3. API Tests
   - Mock responses
   - Error handling
   - Request validation

4. Calculator Tests
   - Basic arithmetic operations
   - Error handling

5. Error Handling Tests
   - Custom exception handling
   - Error handling

6. Utility Tests
   - IP geolocation lookup
   - Error handling

7. API Tests
   - Mock responses
   - Error handling

8. Calculator Tests
   - Basic arithmetic operations
   - Error handling

# Running the tests and coverage

## Run unittest tests

```bash
python -m unittest discover -s tests
```

## Run pytest tests

```bash
pytest tests/test_pytest.py
```

## Run pytest tests with coverage

```bash
pytest --cov=src tests/
```

## Run pytest tests with coverage and generate HTML report

```bash
pytest --cov=src tests/ --cov-report html
```

# Disclaimer
- The project is a simple example and is not meant to be a full application.
- The current README was generated using AI and is not meant to be a good example of how to write a README.
