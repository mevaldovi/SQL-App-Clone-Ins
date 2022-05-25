# SQL-App-Clone-Instructions

## Summary

A step-by-step instruction for any programmer or Trilogy Education Instructor Staff on exactly how to locally test any application that includes a mySQL database.

## Installation

- Go towrads the right side of the main GitHub repo page.
- Click green "Code" button. 
- Copy repo URL || the repo's SSH key.
- Open a new Bash terminal on your desktop.
- Navigate to proper directory which will hold the repo file.
- `ls`
- `git clone xxxxxxxxxxx` where `xxxxxxxxxxx` equals the repo's URL or its SSH key.
-  Enter || Return for Macs
- `ls`
- `cd xxxxxxxxxxx` where `xxxxxxxxxxx` equals the name of repo directory just created.
- `code .`
- Delete node modules and package-lock.json files.
- Right click on package.json file
- Select ``"open in integrated terminal"``
- `npm i`
- `touch .env`
- Create the following variables in .env file:

  `DB_NAME`= name-of-database_db *
  
  `DB_USER`= your-mysql-username-here (most common = root)
  
  `DB_PW`= your-mysql-password-here
