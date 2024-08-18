# Mini Project 1

## 1. Check valid password
Given that you are developing a signing up feature in a mobile app.

1 part is to write a function to check if the password is valid or not. A password is valid if and only if all of the following conditions are satisfied:

- At least 1 lowercase letter [a-z]
- At least 1 number [0-9]
- At least 1 uppercase letter [A-Z]
- At least 1 symbol in [$ @ #]
- Minimum password length: 6
- Maximum password length: 12

```ruby
password = input('Your password is ')

def valid_pass(password):
  total_lower = 0
  total_upper = 0
  total_number = 0
  total_symbol = 0

  for i in password:
      # write if statement to check if elements in string are lowercase or not, if yes, add 1 point to total_lower


      # write if statement to check if elements in string are uppercase or not, if yes, add 1 point to total_upper


      # write if statement to check if elements in string are number from 0 to 9 or not, if yes, add 1 point to total_number


      # write if statement to check if elements in string are symbols '$','@','#', if yes, add 1 point to total_symbol
      if i in ['$', '@', '#']:
        total_symbol += 1

  # write if statement to check if all criteria listed above are met or not, if yes, print "valid password", else print "invalid password"


valid_pass(password)
```

## 2. Format & remove duplicates in an array

Given that you are developing a program that will be able to remove duplicates from a given array. The output should meet the following requirements:

- Sorted in ascending order
- Leading and trailing spaces removed
- Duplicates removed
- Each element's first character is uppercase.

For instance:
- Input: ["Panasonic ", " pensonic", "panasonic ", " Haier", "electrolux","Electrolux"]
- Output: ['Electrolux', 'Haier', 'Panasonic', 'Pensonic']

```ruby
input_array = ["Panasonic ", " pensonic", "panasonic  ", " Haier", "electrolux","Electrolux"]
# function to format data values
def normalize(array):
    nor_value= []
    for s in array:
         #trim space
         #upercase the first character
         #append s to nor_value list
    return nor_value

# function to remove duplicate
def remove_duplicate(array):
  # for loop to access unique value
  return unique_value

normalized_array = normalize(input_array)
unique_array = remove_duplicate(normalized_array)
unique_array = sorted(unique_array)
print(unique_array)
```

## 3. Calculate tax payable

Given that you are developing a income tax calculation feature which calculates income tax for the given income by adhering to the below rules:

![image](https://github.com/user-attachments/assets/dac564ba-98c9-4dc6-8855-75481b993db3)

For example, suppose the taxable income is 45000 the income tax payable is

10000x0% + 10000x10% + 25000x20% = $6000.



```ruby
income = int(input("Your income is "))
tax_payable = 0

def calculate_tax(income, tax_payable):
  # write if statement to check if income <= 10000

  # write if statement to check if income <= 20000

  print("Total tax to pay is", tax_payable)

calculate_tax(income, tax_payable)
```
