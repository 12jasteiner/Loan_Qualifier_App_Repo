# Loan_Qualifier_App

This app is designed to take user input of credit score, monthly debt, desired loan amount, and house price to determine which loans the user qualifies for.

---

## Technologies

This app runs using python version 3.7.13. Windows 10 OS. The app uses the pathlib, questionary, sys, and fire libraries

---

## Installation Guide

1) Ensure you are running Python version 3.7.13+

2) Install the following libraries:
    * Fire
    * Sys
    * Questionary
    * Pathlib 

---

## Usage

Run app using:
```
> python app.py
```
The following would be example input:

```
? Enter a file path to a rate-sheet (.csv): ./data/da 
ily_rate_sheet.csv
? What's your credit score? 750
? What's your current amount of monthly debt? 2000    
? What's your total monthly income? 7000
? What's your desired loan amount? 15000
? What's your home value? 240000
The monthly debt to income ratio is 0.29
The loan to value ratio is 0.06.
Found 15 qualifying loans
? Would you like to save your qualifying loans? No    
Thank you for using our service!
```

---

## Contributors

Jason Steiner
email: jrs2276@caa.columbia.edu


---

## License

[See MIT license](https://github.com/12jasteiner/Loan_Qualifier_App_Repo/blob/main/LICENSE.md)

