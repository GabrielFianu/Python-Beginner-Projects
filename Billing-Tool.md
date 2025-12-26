# SIMPLE HOTEL BILLING TOOL


## Introduction
This tool is used to calculate the total bill for hotel occupancy per day.


---

### 1. Create a script for the following:

a. Print welcome message

```
print("Welcome Actionman Resort")
```

b. Create input function for the user, assign them variables and normalize to uppercase consistency.

```
room_type = input("Which room do you want? S for Standard, D for Deluxe and C for Chalet\n").upper()
sea_front = input("Do you want seafront room? Y for Yes and N for No.\n").upper()
buffet = input("Would prefer buffet for Lunch and dinner? N for No, L for Lunch, D for dinner and B for both Lunch and dinner.\n").upper()
room_service = input("Would prefer exclusive room service? Type Y for Yes and N for No\n").upper()
```


c. Ask for number of days to stay

```
days = int(input("How many days will you stay in the hotel?\n"))
```


d. Initial bill

```
bill = 0
```

e. Initialize bill

```
if room_type == "S":
   bill += 500
elif room_type == "D":
   bill += 1000
elif room_type == "C":
   bill += 2500
else:
    print("You have entered a wrong input")
```

f. Seafront option billing

```
if sea_front == "Y":
   bill += 200
else:
   bill += 0
```

e. Buffet option billing

```
if buffet == "N":
   bill += 0
elif buffet == "L":
   bill += 200
elif buffet == "D":
   bill += 200
elif buffet == "B":
   bill += 300
else:
   print("You have entered the wrong input")
```

f. Room service billing

```
if room_service == "Y":
   bill += 200
else:
    bill += 0
```


g. Multiply by number of days

```
final_bill = bill * days
```

h. Final bill

```
print(f"Your final bill for {days} day(s) is: GH₵{final_bill}")
```

---


### 2. Run code

a. Click the **Run** button to see how the program works.

b. Proof:
Below are the screenshots of editor where the codes are ran. 

<img width="1218" height="582" alt="Image" src="https://github.com/user-attachments/assets/e78800db-37ce-4a65-9af0-2a55447981c0" />

<img width="1209" height="601" alt="Image" src="https://github.com/user-attachments/assets/bfae552e-a366-4214-a679-0aae12e8ce4d" />

<img width="1210" height="550" alt="Image" src="https://github.com/user-attachments/assets/93a66b36-0f6f-47cf-bdfe-d82ff10dab6a" />

<img width="1248" height="378" alt="Image" src="https://github.com/user-attachments/assets/49743cf8-a625-4383-bc3c-70bbfba50ec2" />
