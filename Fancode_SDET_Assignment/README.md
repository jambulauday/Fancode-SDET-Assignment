# 🚀 FanCode SDET Assignment Solution

Welcome to the automation solution for the FanCode SDET Assignment! This project focuses on verifying that users in FanCode city have completed more than half of their todo tasks.

## 📋 Scenario

We're testing the following scenario:

> All users of City `FanCode` should have more than half of their todos tasks completed.

- Given: User has todo tasks
- And: User belongs to the city FanCode
- Then: User's completed task percentage should be greater than 50%

## 🗺️ FanCode City Criteria

FanCode City is identified by the following geographical coordinates:
- Latitude: Between -40 to 5
- Longitude: Between 5 to 100

## 🛠️ Prerequisites

Before you begin, ensure you have the following installed:

* Java Development Kit (JDK) ☕
* Maven
* An Integrated Development Environment (IDE) like Eclipse or IntelliJ 💻

## 🏁 Getting Started

1. Clone the repository:
   ```console
   git clone https://github.com/FancodeAssignmentTest.git
   ```
2. Open the project in your preferred IDE
3. Build the project using Maven to resolve dependencies

## 🏃‍♂️ Running Tests

To run the automated tests:

1. Right-click on the `testng.xml` file and select "Run as TestNG suite"
   OR
   Navigate to `src/test/java/com.assignment.fancode > FancodeTest.java`, right-click, and select "Run as TestNG test"

2. Test results will be displayed in the console, showing passes, fails, and skips.

3. An ExtentReport will be generated in the `Reports` folder as `TestResults.html`, providing detailed test results and logs.

## 🧠 Project Structure

- `com.assignment.constants`: Configuration files, constants, and status code enums
- `com.assignment.core`: HTTP client setup and test base
- `com.assignment.endpoints`: API endpoint definitions
- `com.assignment.model`: Data models for User and TodoResponse
- `com.assignment.utils`: Utility methods for data processing and calculations
- `com.assignment.fancode`: Test implementation in `FanCodeCityTodoTest.java`

## 🔗 API Resources

We're using the following endpoints from http://jsonplaceholder.typicode.com/:
- /todos
- /users

## 💻 Technologies Used

- Rest Assured
- TestNG
- Maven
- Extent Reports
- Jackson API
- Java

## 🎯 Assessment Criteria

This project aims to demonstrate:
- Coding skills
- Logical approach to problem-solving
- Code reusability
- Project structuring

## 🙏 Acknowledgements

Thanks to [JSONPlaceholder](https://jsonplaceholder.typicode.com/) for providing the API endpoints for this assignment.

---

Happy testing! May all your assertions pass! 🎉

