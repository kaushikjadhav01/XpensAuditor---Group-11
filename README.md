# XpensAuditor : a smart way to track your expenses

![App Logo](https://github.com/NCSU-Fall-2022-SE-Project-Team-11/XpensAuditor---Group-11/blob/main/docs/demo/ic_account-playstore.png)

[![Code Coverage](https://codecov.io/gh/SaiPavanYalla/XpensAuditor/branch/main/graphs/badge.svg)](https://codecov.io/gh/SaiPavanYalla/XpensAuditor/branch/main)
[![DOI](https://zenodo.org/badge/566109274.svg)](https://zenodo.org/badge/latestdoi/566109274)
[![Collaborators](https://img.shields.io/badge/Collaborators-5-orange.svg?style=flat)](https://github.com/NCSU-Fall-2022-SE-Project-Team-11/XpensAuditor---Group-11/graphs/contributors)
[![License](https://img.shields.io/badge/License-MIT-purple.svg?style=flat)](https://github.com/NCSU-Fall-2022-SE-Project-Team-11/XpensAuditor---Group-11/blob/main/LICENSE)
[![Language](https://img.shields.io/badge/Language-Java-blue.svg?style=flat)](https://github.com/SaiPavanYalla/XpensAuditor/search?l=java)
[![Documentation Status](https://readthedocs.org/projects/ansicolortags/badge/?version=latest)](https://github.com/NCSU-Fall-2022-SE-Project-Team-11/XpensAuditor---Group-11/blob/main/README.md)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/NCSU-Fall-2022-SE-Project-Team-11/XpensAuditor---Group-11?display_name=tag)
![GitHub issues](https://img.shields.io/github/issues/NCSU-Fall-2022-SE-Project-Team-11/XpensAuditor---Group-11)
[![Build & Test](https://github.com/NCSU-Fall-2022-SE-Project-Team-11/XpensAuditor---Group-11/actions/workflows/android.yml/badge.svg)](https://github.com/NCSU-Fall-2022-SE-Project-Team-11/XpensAuditor---Group-11/actions/workflows/android.yml)
[![GitHub Repo Size](https://img.shields.io/github/repo-size/NCSU-Fall-2022-SE-Project-Team-11/XpensAuditor---Group-11.svg)](https://img.shields.io/github/repo-size/NCSU-Fall-2022-SE-Project-Team-11/XpensAuditor---Group-11.svg)

#

 ## Summary
 
 - This mobile application allows customers to add their expenses and keep track of them. 
 - Takes required minimal amount of data like date of transaction, product name and value
 - Each user needs to create/sign up to access the application, Firebase is used to achieve authorization, authentication and accounting
 - The application keeps track of user data and stores it in the Firebase realtime database
 - The app supports multiple interesting features like Rating, Customer Service Feedback, Contact Us
 - The Mailing and SMS services have been configured for the app for ease of sending customer updates, password reset requests and reading personal expenses 
 - Profile set up module is where user can update their details 
 - Account Settings are available to change password, send password reset email

## Demo

https://user-images.githubusercontent.com/112219214/194787499-0125447e-f68d-444b-9a86-559b14adf898.mp4


## Roadmap

 - Issues encountered and solved so far - [ISSUES](https://github.com/SaiPavanYalla/XpensAuditor/issues?q=is%3Aissue+is%3Aclosed)
 - Scope of Improvement :
 
   - Analysis on detected expenses - Category wise expenses and expenditure graphs
   - Detect transaction alerts from notifications and emails as well
   - Add custom categories & Auto detect category by vendor
   - Change password feature is implemented. Likewise, change email also needs to be implemented
 

## License

 This project is licensed under the MIT License. See the [LICENSE](https://github.com/SaiPavanYalla/XpensAuditor/blob/main/LICENSE) file for details
 
## Tools used

- Android Studio
- Embedded Emulator/ USB debugging on android device

## Run the application
### Android Mobile
 - Download the apk from the latest [release](https://github.com/SaiPavanYalla/XpensAuditor/releases/tag/v1.0.0) 
### Android Studio
 - Must have android studio installed
 - Clone the github repo
   git clone https://github.com/SaiPavanYalla/XpensAuditor.git
 - Open the cloned repo using android studio
 - Build the application for any dependency inconsistencies and proper functioning of app
 - Expand the file structure and run the app using "Run" option
 
## Test the application

 - Application has an existing test suite
 - Navigate to the folder of Android Test and right click and select "Run tests in ...."
 - It runs all the test cases in the package and provides the result and code coverage
 
## Team Members:

This repository is made for CSC 510 Software Engineering Course:

Members
 - Sahithi Ammana
 - Mithila Reddy Tatigotla
 - Sunandini Medisetti
 - Sai Pavan Yalla
 - Vineeth Dasi

