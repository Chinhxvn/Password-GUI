# Password-GUI 

This repository is the final assignment of the HCI/Usable Security class from the Cyber Security course at Johnson and Wales University. 

## Description 

Creating a website(non-live) that contains a GUI that allows the user to create an account, stores the account information in a database, and add password requirements to strengthen the password. 

## Requirements 

- Must be a functional GUI
- Must have a written password policy 
- Password must comply with the policy and vice versa 

## Building on Visual Studio Code

For this project I used version 1.73.1

## Building

The main foundation of the website and database structure came from the github link listed below. What I actually implemented that differs from code to code is listed below:

#### sign_up.html

- Added more information required before signing up. eg. First Name, Last Name, Confirm Password
- Added a checkbox of the password requirements that updated after every input of a key 
- Added the feature reCAPTCHA 

#### login.html

- Added the feature reCAPTCHA

#### auth.py

- Added a password character limit
- Added the feature where the password must contain at least one uppercase, lowercase, number and a special character
- Added the feature where the password cannot contain sequential/repeated characters 
- Added the feature where if the reCAPTCHA was not completed it would not let the user login 

## Sources

https://github.com/techwithtim/Flask-Web-App-Tutorial

