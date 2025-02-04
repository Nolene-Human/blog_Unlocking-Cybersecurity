# Unlocking-Cybersecurity

In application development, the login page is often the first point of interaction between users and your application. It’s more than just a gateway; it’s a component that ensures security, user experience, and accessibility. This repository takes you through the fascinating, ❗yes fascinating❗ journey of developing and testing a login page.

Working with the principle of starting simple, we will gradually improve the security of the login page using what I learned from CompTIA Security+ following the steps throughout the Application Development Life Cycle.

[Link to Testing Acceptance Criteria](https://smart-chip-653.notion.site/Testing-157bb1e8b94d80b881c9e0a8f032596d?pvs=4)

## MVP 1: LOGIN
I started by building a simple Python terminal login page. The goal is to get the logic right based on the acceptance criteria set out in my user stories and pass the testing before scaling it up to Flask.

| AC1 | AC2 | AC3 | AC5 | AC6 | 
|-----|-----|-----|-----|-----|
| The Login page should request the user to enter   |All fields must be compulsory |When the incorrect username or password has been entered then the system should notify the user to retry.|If a user enters an incorrect username or password more than three times consecutively, the system must:| If the incorrect verification code has been entered more than 3 times then the system will display an error message indicating exceeded failed attempt limit and the user should be blocked and asked to be verified differently.
|• Username                                         |and not allow the user to log in if one or more fields are missing|RISK: Username Enumeration|Display an error message indicating that the failed attempt limit has been exceeded.|
|• Password                                         |||Block the user's account to prevent further login attempts.|  
|• Authentication code                              |||Provide options for the user to either register a new account or reset their password.|     









## MVP 2: 
### Python MVP Login Page transferred to Flask

