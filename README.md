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

- The minimum character is 11

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

Using boundary value analysis, the valid input from each field is:

First Name:
Has minimum 5(or 3 where it will be submitted but the message "Firstname too short" will appear at the end page) characters; it can use non-alphabetic characters and/or space

Example:

Jonathan

Jonathan Jonathan

123

12345

12345.com 12345.com

Last Name:

Has minimum 11 characters; it can use non-alphabetic characters and/or space

Example:

ABCDEFGHIJK

ABCDEFGHIJK ABCDEFGHIJK

12345678912

12345678912 12345678912

Age:

It should be numerical where the minimum is 18 and the maximum is 80

Example:

18

80

79

19
