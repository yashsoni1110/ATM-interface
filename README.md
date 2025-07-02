# ATM Interface
 ATM Interface

Overview
The ATM Interface is a web-based application that simulates the functionality of an Automated Teller Machine (ATM). It allows users to perform basic banking operations such as checking their balance, withdrawing and depositing money, changing their PIN, and viewing transaction history. The application provides a user-friendly interface with secure PIN authentication and responsive design.

Features
PIN Authentication: Securely authenticates users with a 4-digit PIN, allowing three attempts before locking the account.
Balance Inquiry: Displays the current account balance.
Withdrawals: Enables users to withdraw funds, with validation for sufficient balance and valid input.
Deposits: Allows users to deposit funds, ensuring positive and valid input amounts.
PIN Change: Permits users to update their PIN, requiring the current PIN and a new 4-digit numeric PIN.
Transaction History: Maintains and displays a log of all transactions with timestamps.
Responsive Design: Built with Tailwind CSS for a clean, modern, and mobile-friendly interface.
Error Handling: Provides clear feedback for invalid inputs or failed operations (e.g., insufficient funds, incorrect PIN).

Technologies Used
HTML: Structures the web interface.
JavaScript: Handles the application logic, including account management and user interactions.
Tailwind CSS: Provides styling for a responsive and visually appealing design.
