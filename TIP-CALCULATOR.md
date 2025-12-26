# THE  TIP CALCULATOR 

## Introduction
The tip calculator is a tool that helps users to calculate the total amount for services like restaurants. 
As an input, it takes the total bill and the tip as percent to calculate and displays the tip amount and total amount to pay.
It's also capable of splitting the total bill among friends or families.

This project utilizes the following to create the Tip Calculator:
- Data Types
- Numbers
- Mathmatical Operations
- Data Type Conversion
- f-strings


### 1. Create scripts for the following:
a. Print welcome message

```
print("Welcome to the Tip Calculator")
```

a. Create input function for the needed data, specify the data type for each input and assign them variables.

```
bill = float(input("What was your total bill?\nGH₵"))
tip = int(input("What percent tip would like to give? 5 10 15\n"))
people = int(input("How may people are splitting the bill ?\n"))
```

b. Calculate the Total Bill

```
tip_as_percent = tip / 100
total_tip_amount = bill + tip_as_percent
total_bill = bill + total_tip_amount
```

# Calculate Bill split per person

```
bill_per_person = total_bill / people
final_amount = round(bill_per_person, 2)
```

# Print final bill to the user

```
print(f"Each person should pay: GH₵{final_amount}")
```
 
---

2. Run code
a. Click the **Run** button to see how the program works.

b. Proof:
Below are the screenshots of editor where the codes are ran. 

<img width="1198" height="463" alt="Image" src="https://github.com/user-attachments/assets/22de8ccc-c784-446e-95a0-434c3f725882" />

<img width="1240" height="222" alt="Image" src="https://github.com/user-attachments/assets/ebd5ea3d-db0c-4b6a-a226-a72122865278" />
