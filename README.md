# Student_Details_API_Testing_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run Student_Details_API_Testing.postman_collection.json -e Student_Details_API_Testing.postman_environment.json
```
- Run Command for Report: 
```console 
newman run Student_Details_API_Testing.postman_collection.json -e Student_Details_API_Testing.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/31261931/2s9YsQ79pL

## Test case list:
1. ### Create Student
	> Create Data Sets Using the Dynamic Random Variables.

2. ### Crated Student Details
	> In the test case you need to validate the following field values:
 	1. > First Name
 	2. > Middle Name
 	3. > Last Name
 	4. > Date of Birth

3. ### Update Student
	> In the test case you need to validate the following field values:
 	1. > Only Message
4. ### Updated Student Details
	> In the test case you need to validate the following field values:
	1. > First Name
 	2. > Middle Name
	3. > Last Name
 	4. > Date of Birth

5. ### Create Technical skills 
	> In the test case you need to validate the following field values:
	1. > Only Message

6. ### Create a Student Address
	> In the test case you need to validate the following field values:
	1. > Only Message

7. ### Get the Student's Full Details
	> In the test case you need to validate the following field values:
	1. > First Name
	2. > Middle Name
	3. > Last Name
	4. > Date of Birth
	5. > Language
	6. > Year Of Experience
	7. > Last Used Date
	8. > House Number
	9. > City
	10. > State
	11. > Country
	12. > Std Code
	13. > Home Address
	14. > Mobile

## Newman Report Summary:
![Newman Report Summary](https://github.com/momtazshanta/API-Testing-Project/assets/41441256/caf40bca-a946-4930-92fb-4c005d3e0b12)


![Newman Report Summary](https://github.com/momtazshanta/API-Testing-Project/assets/41441256/a83e7dfe-d829-4e12-be5f-8b77b90a5047)

