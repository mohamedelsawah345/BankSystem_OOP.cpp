🏦 Bank Management System (C++ OOP)
A robust, terminal-based Bank Management System architected using Object-Oriented Programming (OOP) principles in C++. This project serves as a comprehensive demonstration of low-level system design, custom library development, and efficient memory management without relying on heavy external frameworks.
🚀 Key Technical Highlights
1. Advanced OOP Architecture
The system is built on a solid foundation of OOP pillars to ensure scalability and maintainability:
Inheritance: Utilized a base clsPerson class inherited by clsClient and clsUser to minimize code duplication.
Encapsulation: Strict use of private/protected members with public getters/setters (Properties) to protect data integrity.
Abstraction: Abstracted complex UI logic into dedicated "Screen" classes (e.g., clsMainScreen, clsTransactionScreen) to separate concerns.
Static Methods: Extensively used static methods for utility functions and data access to optimize memory usage and performance.
2. Custom Library Development
To master the internals of C++, I developed several custom utility libraries instead of relying solely on standard shortcuts:
clsString: A custom string manipulation library handling parsing, splitting (Join/Split), and encryption/decryption.
clsDate: A comprehensive date arithmetic library for handling system timestamps and validation.
clsInputValidate: A robust validation layer to ensure data type safety and range checking for all user inputs.
3. Memory & Data Management
Pointer Arithmetic: Managed data structures and object relations using efficient pointer operations.
File Persistence: Implemented a flat-file database system with custom parsing logic to handle CRUD operations (Create, Read, Update, Delete).
Vector Optimization: Used std::vector with efficient capacity management to handle dynamic lists of clients and users in memory.
🛠️ Tech Stack
Language: C++ (Standard 17/20)
Paradigm: Object-Oriented Programming
Environment: Cross-platform Terminal/Console
📂 Project Structure
text
├── Core/
│   ├── clsClient.h       # Business logic for bank clients
│   ├── clsUser.h         # Administrative user management
│   └── clsPerson.h       # Base class for all entities
├── Lib/
│   ├── clsString.h       # Custom string utilities
│   ├── clsDate.h         # Date & Time logic
│   └── clsInputValidate.h# Input sanitization
└── Screens/
    ├── clsMainScreen.h   # Root navigation logic
    └── clsLoginScreen.h  # Security & Authentication layer
⚙️ How to Run
Clone the repository: git clone https://github.com/mohamedelsawah345/Bank-Broject-Using-OOP.git
Compile using any C++ compiler (GCC/Clang/MSVC ):
Bash
g++ -o BankSystem main.cpp
Run the executable:
Bash
./BankSystem
