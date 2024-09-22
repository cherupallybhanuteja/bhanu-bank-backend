# The Bhanu's Bank - Backend

This is the backend part of **The Bhanu's Bank** project. This project handles the server-side operations, including account management, transaction processing, and authentication.

For the frontend part of this project, visit the GitHub repository:
[Bhanu's Bank - Frontend](https://github.com/cherupallybhanuteja/bhanu-bank-frontend)

## Features:
- **User Authentication**: Secured login and authentication using JWT.
- **Account Management**: Users can view their account details, create or update PINs, and manage their profile.
- **Fund Transactions**: Support for deposits, withdrawals, and fund transfers.
- **Transaction History**: Record of all transactions that users can view.

## Setup Instructions:
1. Clone the repository:
   ```bash
   git clone https://github.com/cherupallybhanuteja/bhanu-bank-backend.git
2. Navigate to the project directory:
cd bhanu-bank-backend

3. Install dependencies:
mvn install

4. Setup your MySQL database:

Create a database called bank_db.
Update the application.properties file with your MySQL username and password.

5. Run the application:
mvn spring-boot:run

6. The backend API will be available at:
http://localhost:8180

API Endpoints:

Account Endpoints:

/api/account/details: Retrieves user account details.

/api/account/transactions: Retrieves transaction history.

/api/account/deposit: Deposits money into an account.

/api/account/withdraw: Withdraws money from an account.

/api/account/fund-transfer: Transfers money to another account.

User Endpoints:

/api/users/login: User login and JWT generation.

/api/users/register: User registration.

/api/users/update: Update user details.

PIN Management:

/api/account/pin/create: Create a new account PIN.

/api/account/pin/update: Update existing account PIN.

Technologies Used:

Spring Boot: Backend framework.

MySQL: Database management.

JWT: Authentication mechanism.