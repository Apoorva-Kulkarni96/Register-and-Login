
## Registration and Login system with Python, file handling

### Problem Statement :
#### To create a registration and Login system using Python

### Steps Involved:
### A) Basic Operation
#### 1) def begin function was created to ask the user whether he/she want to login or register.
#### 2) Depending on the option chosed, def access(option) was created and option was passed
#### 3) Depending on the option chosed, email_id and password are entered
#### 4) If login is chosed then it enter def login(email_id,password) else def register(email_id,password)

### B) Registration : When the user chooses to Register

#### To check the entered email id is valid or not
#### 1) An email is a string (a subset of ASCII characters) separated into two parts by @ symbol, a “personal_info” and a domain, that is personal_info@domain. 
#### 2) The re module is imported and to check the email pattern and entered email id is matched, re.fullmatch(pattern,string) is used.
#### 3) The re.compile() method compiles a regex pattern into a regex object,  when we plan on matching the pattern more than once.
#### 4) If entered email id is valid it checks for password. For that certain criteria should be matched such as length of passwoard must fall between 5- 16, must contain a upper letter, a lower letter, atleast 1 digit and special character.
#### 5) First the len of the password is checked, later no. of upper case, lower case, digit and special character present in the password are counted. If all the criteria as no. of upper case, lower case, digit and special character are greater than zero and total count is equal to length of password then the entered password is valid. 
#### 6) If Entered email id and password are valid, a text file is opened in append mode and both email id and password are written in that particular text file separated by "," and file is closed.
#### 7) def grant() is created to show that after successfully registering it takes to next page (here virtually)
#### 8) If email Id or password is not valid then grant() is not called

### C) Log In : When the user chooses to login

#### 1) file is opened in read mode and each line in the file splitted by "," and stored in 2 variables a and b.
#### 2) if passed email id and password matches the 2 variable then Loggin is successful.
#### 3) If login is not successful , to ask for forgot password option, in which password corresponding to email is retrieved.


### Tools Used
Jupyter Notebook

Text file

### Python Concepts Used

Functions

File Handling

Loops

Conditional Statements

Regular Expression

Control flow


