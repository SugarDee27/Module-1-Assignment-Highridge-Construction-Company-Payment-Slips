# Worker Payment Slip Program

## Description
This project contains two programs — one in Python and one in R — that generate payment slips for 400 dynamically created workers.  
The scripts assign employee levels based on the following rules:

1. If the salary is greater than $10,000 and less than $20,000 → Employee Level = "A1".
2. If the salary is greater than $7,500 and less than $30,000 **and** the employee is female → Employee Level = "A5-F".

## Files
- worker_payment.py  → Python implementation
- worker_payment.R   → R implementation
- README.md          → Instructions for running the code

---

## Requirements

### For Python:
- Python 3.x installed
- Any IDE (VS Code, PyCharm, etc.) or terminal

### For R:
- R 4.x installed
- RStudio (optional, but recommended)

---

## Instructions

### **Running the Python Program**
1. Open a terminal or your IDE.
2. Navigate to the folder containing `worker_payment.py`.
3. Run:
   ```bash
   python payment_slips.py
