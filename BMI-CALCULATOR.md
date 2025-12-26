# BMI CALCULATOR

## INTRODUCTION 
A BMI (Body Mass Index) calculator estimates mass based on height and weight. 
BMI categorizes you as underweight, normal weight, overweight.
BMI = weight(Kg) / height (m)2.

This project utilizes:
- conditional statements
- logical operators
- code blocks
- scope

### 1. Create a script for the following:

**Option One**

a. Print welcome message.

```
print("Welcome to the BMI CALCULATOR")
```

b. Create input function for the needed user data, specify the data type for each input and assign them variables.

```
weight = float(input("What was your weight in kg?\n"))
height = float(input("What was height in meters?\n"))
```

c. Calculate the bmi

```
bmi = weight / (height ** 2)
```

d. Print the bmi to two decimal points.

```
print(f"Your bmi is: {bmi:.2f}")
```

e. Interpret bmi using control flow

```
if bmi >= 25:
    print("Your bmi is overweight")
elif bmi >= 18.5:
    print("You bmi is bmi normal weight")
else:
    print("You bmi is underweight")
```


---


**Option Two**

a. Print welcome message

```
print("Welcome to the BMI CALCULATOR")
```

b. Create input function for the needed data, specify the data type for each input and them variables.

```
weight = float(input("What was your weight in kg?\n"))
height = float(input("What was height in meters?\n"))
```

c. Calculate the bmi

```
bmi = weight / (height ** 2)
```

d. Print and interpret bmi results using control flow

```
if bmi >= 25:
    print(f"Your bmi is: {bmi:.2f} " + "-" " overweight")
elif bmi >= 18.5:
    print(f"Your bmi is: {bmi:.2f} " + "-" " normal weight")
else:
    print(f"Your bmi is: {bmi:.2f} " + "-" " underweight")
```


---


### 2. Run code

a. Click the **Run** button to see how the program works.

b. Proof:
Below are the screenshots of editor where the codes are ran. 

**Option One**

<img width="991" height="229" alt="Image" src="https://github.com/user-attachments/assets/390e4654-c410-4b8d-9053-7fb6d950f09a" />

<img width="991" height="255" alt="Image" src="https://github.com/user-attachments/assets/97eaeef4-d6c8-4c10-acc7-90ef17d16fa9" />


**Option Two**

<img width="986" height="233" alt="Image" src="https://github.com/user-attachments/assets/87dd98cf-3e9f-41c7-bdb6-3573e4c5b231" />


**Output**

<img width="1243" height="222" alt="Image" src="https://github.com/user-attachments/assets/713786f9-ee8c-4377-abbe-8a1127536ae8" />

<img width="1247" height="176" alt="Image" src="https://github.com/user-attachments/assets/b690d41e-3e22-4f2e-9439-044123ca16c2" />

<img width="1251" height="213" alt="Image" src="https://github.com/user-attachments/assets/f0e13040-6e18-4bd4-a658-f340a7ab97bb" />
