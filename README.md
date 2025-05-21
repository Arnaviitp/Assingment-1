# Assingment-1
# Tax Deduction Calculator - Old vs New Regime

## Assignment Overview

This is a **console-based Python application** to calculate tax deductions using both Old and New Regime methods based on user input for CTC and Bonus.

---

## Features

- **Input:**  
  - Total CTC (Cost to Company)  
  - Total Bonus Amount

- **Output:**  
  - Total Income (CTC + Bonus)  
  - Tax deduction as per Old Regime (with standard deduction and 80C)  
  - Tax deduction as per New Regime (as per latest slabs, no exemptions)  
  - Summary showing which regime saves more tax

- **User Experience:**  
  - Clean, readable output matching assignment example  
  - Menu-driven (if required)  
  - Follows PEP8 and is well-commented

---

## How to Run

1. **Requirements**
    - Python 3.x

2. **Steps**
    - Download or clone this repository.
    - Open a terminal/command prompt in the project directory.
    - Run the script:
      ```
      python tax_calculator.py
      ```
    - Enter your CTC and Bonus as prompted.

---

## Example Output

```
Enter your CTC:  20,00,000
Enter your Bonus: 95,000

Total Income: Rs.20,95,000

Old Regime Tax Deduction: Rs.3,96,240
New Regime Tax Deduction: Rs.3,41,640

You Save Rs.54,600 more using the Old Regime.
```

---

## Logic Used

- **Old Regime:**
    - Standard Deduction: Rs.50,000
    - 80C Deduction: Rs.1,50,000
    - Tax calculated as per FY 2024-25 slabs
    - 4% Health & Education Cess applied
    - Section 87A rebate for income up to Rs.5 lakh

- **New Regime:**
    - No deductions
    - Tax calculated as per FY 2024-25 slabs
    - 4% Health & Education Cess applied
    - Section 87A rebate for income up to Rs.7 lakh

---

## File Structure

- `tax_calculator.py` : Main Python script  
- `README.md` : This file

---

## Submission Checklist

- [x] Console Python script working correctly
- [x] Code commented and clean
- [x] README file included
- [x] Code pushed to GitHub


