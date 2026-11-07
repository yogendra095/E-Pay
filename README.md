# E-Pay 💳

### A Console-Based Digital Wallet Application Using C

E-Pay is a C programming project inspired by digital payment platforms like eSewa. It provides a simple console-based environment where users can create accounts, manage their balances, transfer money to other registered users, and pay college fees.

The project demonstrates fundamental C programming concepts, including structures, file handling, functions, pointers, and basic data management.

## Features

- **User Registration:** Create an account with username, email, phone number, and password.
- **User Authentication:** Log in using registered account credentials.
- **Password Masking:** Hides password characters during input.
- **Account Management:** View personal account details and current balance.
- **Money Transfer:** Transfer funds between registered users.
- **College Fee Payment:** Pay predefined fees for supported colleges.
- **Transaction History:** View transaction logs, including sent and received transactions.
- **File-Based Storage:** Store user information and transaction records using files.
- **Console Interface:** Interactive menu with ASCII-based visual elements.

## Tech Stack

| Technology | Purpose |
|---|---|
| C | Core programming language |
| Standard C Libraries | Input/output, strings, file handling |
| Windows API | Console screen management |
| File Handling | Persistent user and transaction data |

## Project Structure

```text
E-Pay/
│
├── ascii_display.c    # ASCII interface and display functions
├── testtest.c         # Main application and program logic
├── README.md          # Project documentation
└── testtest.exe       # Compiled executable
```

## Getting Started

### Prerequisites

- Windows operating system
- GCC compiler (MinGW recommended)
- Terminal or command prompt

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/yogendra095/E-Pay.git
```

**2. Navigate to the project directory**

```bash
cd E-Pay
```

**3. Update the source file include path**

In `testtest.c`, make sure the ASCII display file is included using a relative path:

```c
#include "ascii_display.c"
```

**4. Compile the program**

```bash
gcc testtest.c -o epay.exe
```

**5. Run the application**

```bash
epay.exe
```

## How to Use

After launching the application, you will be presented with the main menu.

### 1. Register or Login

- Create a new account using the Sign Up option.
- Enter your registered credentials to log in.
- New accounts receive an initial balance of Rs. 8,000.

### 2. Account Dashboard

After successful login, the application provides the following options:

| Option | Description |
|---|---|
| 1 | Check Balance and Details |
| 2 | Send Money |
| 3 | College Fee Payment |
| 4 | View Transaction Logs |
| 5 | Logout |
| 6 | Exit |

### 3. Send Money

- View the list of registered users.
- Enter the recipient's username and phone number.
- Specify the amount to transfer.
- Complete the transaction if the required conditions are satisfied.

### 4. College Fee Payment

Choose from the predefined institutions and pay the corresponding fee.

| Institution | Fee |
|---|---:|
| IOE Pulchowk | Rs. 1,000 |
| IOE WRC | Rs. 1,500 |
| Thapathali | Rs. 1,500 |
| IOE ERC | Rs. 1,500 |
| Advanced College | Rs. 3,000 |

### 5. Transaction History

View recorded transactions associated with your account, including sent and received amounts.

## Concepts Implemented

This project provided practical experience with several fundamental C programming concepts:

- Structures for organizing user information.
- File handling using `fopen()`, `fread()`, `fwrite()`, and `fclose()`.
- Functions and modular programming.
- String manipulation using the C string library.
- Conditional statements and loops.
- Pointers and file pointers.
- Basic password input masking.
- Persistent data storage.

## Limitations

- This is an academic prototype, not a real payment gateway.
- Transactions are simulated within the application.
- Data is stored locally using files.
- Password handling uses basic character transformation and is not suitable for real-world security.
- The application currently relies on Windows-specific console functionality.

**Note:** Do not use real passwords or financial information with this application.

## Contributors

- **Yogendra Sharma Upadhyaya**
- **Saurav Gaudel**

## Project Purpose

Developed as a college-level C programming project to explore practical applications of procedural programming, file handling, structures, and data management through a simplified digital wallet system.

---

<p align="center">
  Made with C ❤️
</p>
