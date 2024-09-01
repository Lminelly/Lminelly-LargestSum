# Largest Sum

## Description
The `LargestSum` project is a Java application designed to find the largest possible sum that can be obtained from a pair of values in a list of integers. A number cannot be added to itself unless there are duplicates present in the list.

## Technologies Used
- **Java**: The programming language used for this project.
- **JUnit**: Testing framework for unit tests.
- **Maven**: Build automation tool and dependency management.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/LargestSum.git
Navigate to the project directory:
bash
Copy code
cd LargestSum
Build the project using Maven:
bash
Copy code
mvn clean install
Usage
Compile and Run: You can compile and run the application using Maven:
bash
Copy code
mvn compile
mvn exec:java -Dexec.mainClass="LargestSum"
Run Tests: To run the tests and verify functionality:
bash
Copy code
mvn test
Features
bigSum Method: Computes the largest sum of two distinct numbers in a list. Handles duplicates appropriately.
JUnit Tests: Includes tests to verify functionality with various input cases.
Contributions
Implemented the bigSum method to calculate the largest sum.
Developed and wrote unit tests to ensure the correctness of the bigSum method.
Future Improvements
Add additional functionality to handle more complex input scenarios.
Enhance the performance of the bigSum method for very large lists.
License
This project is licensed under the MIT License. See the LICENSE file for details.
