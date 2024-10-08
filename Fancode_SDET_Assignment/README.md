# Fancode SDET Assignment Solution 📒
This is a small automation framework for ensuring that the users in Fancode city 🏙 have completed more than 50% of their tasks📜 based on their ToDos.

## Prerequisites
Before using this framework, ensure that you have following installed on you machine:
* Java Development Kit (JDK) ☕
* Maven Build tool
* Eclipse or IntelliJ any Integrated Development Environment (IDE) 💻

## Getting Started ▶
1. Clone the repository on local machine
```console
git clone https://github.com/FancodeAssignmentTest.git
```
2. Open the project in your preferred IDE
3. Build the project using Maven to resolve the dependencies

## Running Test 🏃
To run the automated test, follow these steps:
1. Right click on the testng.xml file and Click Run as TestNG suite or
Navigate to src/test/java/com.assignment.fancode > FancodeTest.java > Right Click on the file and Click run as TestNG test.
2. Test results will be displayed in the console, including Passes, Fail and Skips and any assertions.
3. ExtentReport will be generated for the result with logs 

## About the framework
### Test Data 🗃
  com.assignment.constants :
  * Config file in framework contains the Base URI
  * Constants has the constants for Longitude and Latitude
  * StatusCodeEnum stores the API status codes for now, later it may be implemented to add messages as well
 
### Test Configurations 🛠
 com.assignment.core :
  * Client file contains the Response get method, we can implement more methods further
  * TestBase contains the setUp method to set the BASE_URI

### Test API Endpoints 🔗
 com.assignment.endpoints: This contains all the Endpoints mentioned

#### Get all users
https://jsonplaceholder.typicode.com
  GET /users
| Description                |
| :------------------------- |
| *This endpoint fetches the users present in the system*.  |

#### Get todo
https://jsonplaceholder.typicode.com
  GET /todos
| Description                       |
| :-------------------------------- |
| *This endpoint fetches all the todos in the system* |

### Test Models 🧪
com.assignment.model : This contains the models for User and TodoResponse

### Test Utility Methods ⚙
com.assignment.utils : stores all the utility and Reusable methods
* ResponseArrayUtils: converts the response to array.
* TestHelper : Two methods present, LatituteLongitudeCheckerForUser and CalculateTaskCompletedPercentage

### Test Implementation ✍🏻
Test case is implemented in the FanCodeCityTodoTest.java file in the com.assignment.fancode package. You can modify this file to add more test cases or customize the existing ones.

### Test Results 🚀
Test results will be displayed in the console as well as Extent Report will be generated in Reports folder by the name 'TestResults.html'

## Tools and Technologies used 💻
* Rest Assured
* TestNG
* Maven
* Extent Reports
* Eclipse
* Jackson API
* Java

## Acknowledgements 🤝🏻
- Thanks to [JSONPlaceHolder](https://jsonplaceholder.typicode.com/) for providing the API for Testing
