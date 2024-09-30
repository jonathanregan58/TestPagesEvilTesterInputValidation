# TestPagesEvilTesterInputValidationByInosoft

Testing https://testpages.eviltester.com/styled/validation/input-validation.html

# Process of creating test cases
Conducted exploratory testing first where I found out the characteristic of the input in each field

First Name:

- Mandatory

- Can be filled with non-alphabetic characters

- The minimum character is 5(it can be 3, but "Firstname too short" will appear after the information submitted to the server)

- It has no limit in terms of maximum characters

- It will accept input that has spaces(Example: Jonathan Jonathan)

Last Name:

- Mandatory

- Can be filled with numbers

- The minimum character is 10

- It has no limit in terms of maximum characters

- It will accept input that has spaces(Example: Jonathan Jonathan)

Age:

- It can only accept number

- It can only accept number between 18 to 80

Country:

- Default value is  "Afghanistan" and cannot be emptied

Notes:

- Non-Mandatory

- Has no maximum value 

- It has no limit in terms of maximum characters
