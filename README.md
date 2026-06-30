# 🗳️ Voting Management System

This is a structural C programming project developed as part of my college curriculum. The main objective of this project is to implement robust data management using arrays, handle input validation, track state across multiple user sessions, and apply conditional tie-breaking logic.  

---

## About the Program

**Voting Management System** is a console-based utility built in C designed to manage college student council or gym elections seamlessly. The program validates student credentials, prevents duplicate voting, records choices in real time, and dynamically calculates election outcomes directly in the terminal.  

---

 ## Features

- SAP ID Validation: Restricts voting strictly to eligible college student SAP ID ranges (590000000 to 600000000).  
- Duplication Prevention: Uses internal tracking arrays to ensure each student can cast only one vote.  
- Visual Candidate Directory: Displays a pre-configured roster of candidates running for the college elections.
- Dynamic Live Tracker: Supports continuous multi-voter participation within a single execution cycle.  
-Comprehensive Results Engine: Automatically handles edge cases such as single winners, multi-candidate ties, and zero-vote scenarios.  

---

## Tech Stack 

- **Language:** C (C99 standard or higher)
- **Paradigm:** Procedural/Structural Programming  
- **Interface:** Command Line Interface (CLI)

---

 ## How to Run

 ```bash
# Compile the code using a C compiler (like GCC)
gcc Voting_Management_System.c -o VotingSystem

# Run the compiled executable
./VotingSystem
```

> Note: Make sure you have a C compiler installed (such as GCC, Clang, or MinGW) on your local environment before running the compilation commands.
