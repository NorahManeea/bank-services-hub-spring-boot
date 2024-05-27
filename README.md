# Bank Services Hub - Spring Boot
A modular Spring Boot project for managing banking operations, including accounts, cards, and loans, using H2 for in-memory database storage.

## Features
* Account Management: Manage customer accounts, balances, and transactions.
* Card Services: Handle credit/debit card issuance, transactions, and management.
* Loan Processing: Manage loan applications, approvals, and repayments.


## Technologies Used
* Spring Boot
* Spring Data JPA
* H2 Database

## Usage
API Endpoints: 

#### Accounts Service:

```GET /accounts: Retrieve all accounts```

```POST /accounts: Create a new account```

```GET /accounts/{id}: Retrieve account details by ID```

```PUT /accounts/{id}: Update account details```

```DELETE /accounts/{id}: Delete an account```


#### Cards Service:

```GET /cards: Retrieve all cards```

```POST /cards: Issue a new card```

```GET /cards/{id}: Retrieve card details by ID```

```PUT /cards/{id}: Update card details```

```DELETE /cards/{id}: Deactivate a card```

#### Loans Service:

```GET /loans: Retrieve all loans```

```POST /loans: Apply for a new loan```

```GET /loans/{id}: Retrieve loan details by ID```

```PUT /loans/{id}: Update loan details```

```DELETE /loans/{id}: Close a loan```


