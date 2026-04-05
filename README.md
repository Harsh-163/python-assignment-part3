# 📦 Product Explorer & Error-Resilient Logger (Part 3)

This project is a Python-based application that demonstrates File I/O operations, API integration, exception handling, and logging mechanisms.  
It simulates a real-world system that fetches product data, processes it, handles errors gracefully, and logs failures for debugging.

---

## 📌 Features

### 🔹 Task 1: File Read & Write Basics
- Created and wrote data to `python_notes.txt`
- Appended additional lines without overwriting existing content
- Read file and displayed numbered output
- Counted total lines in the file
- Implemented case-insensitive keyword search
- Tested with different inputs including invalid cases

---

### 🔹 Task 2: API Integration
- Fetched product data from DummyJSON API using GET requests
- Displayed formatted product table (ID, Title, Category, Price, Rating)
- Filtered products with rating ≥ 4.5
- Sorted filtered products by price (descending)
- Retrieved products by category (laptops)
- Simulated POST request to add a new product

---

### 🔹 Task 3: Exception Handling
- Implemented safe division function with error handling
- Created safe file reader using try-except-finally
- Handled API errors (ConnectionError, Timeout, general exceptions)
- Built input validation loop to prevent invalid API calls
- Tested system with invalid inputs to ensure robustness

---

### 🔹 Task 4: Logging to File
- Built a custom error logger using datetime
- Logged timestamped error entries in `error_log.txt`
- Captured both connection errors and HTTP errors
- Verified logs by reading file contents
- Ensured logs persist across multiple runs

---

## 🧠 Key Learnings

- File handling (read, write, append)
- API communication using requests
- Exception handling and defensive programming
- Input validation techniques
- Logging and debugging practices
- Real-world application design concepts

---

## ⚙️ Technologies Used

- Python
- Jupyter Notebook (.ipynb)
- requests library
- datetime module

---


## 🚀 How to Run

1. Open the notebook in Jupyter or VS Code  
2. Run all cells sequentially  
3. Ensure files (`python_notes.txt`, `error_log.txt`) are generated  
4. Verify outputs and logs  

---
