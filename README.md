
# luv2code-unit-test-mvc-web-app

Welcome to the GitHub repository dedicated to your learning journey in Java testing, inspired by the Udemy course "Spring Boot Unit Testing with JUnit, Mockito, and MockMvc."


## Course Goals

- **JUnit Mastery** : Build a solid foundation in JUnit with an in-depth review. Learn to write comprehensive unit tests that validate your Java code's functionality.

- **Test Driven Development (TDD)**: Embrace the principles of TDD and discover how to write tests before implementing your code. This practice ensures code correctness from the outset.

- **Spring Boot Testing Support**: Explore Spring Boot's native testing support, allowing you to create a robust testing environment for your Spring applications.

- **Unit Testing with Mockito**: Dive into Mockito for efficient mocking of dependencies in your unit tests. Simulate and isolate complex components for effective testing.

- **Reflection Test Utils**: Uncover the power of Reflection Test Utils for testing private methods and fields within your Java classes.

- **Database Integration Testing**: Learn to test Spring Boot MVC web applications with a focus on database integration. Validate your database operations and ensure data integrity.

- **MVC Controller Testing**: Master the art of testing Spring Boot MVC controllers, ensuring the correctness of your web application's controller logic.

- **GradeBook App - Student Grades**: Apply your learning to a practical example with the GradeBook App, testing student grade management in a Spring Boot MVC web application.

- **SQL Scripts in Properties File**: Set up SQL scripts in a properties file for streamlined database testing, making it easier to manage and apply data changes.

## Docummentation

- [Java](https://docs.oracle.com/en/java/)
- [Official Spring Boot](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/)
- [JUnit 5](https://junit.org/junit5/docs/current/user-guide/)
- [Mockito](https://javadoc.io/doc/org.mockito/mockito-core/latest/index.html)
- [MockMvc](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#spring-web)
## Installation

1. **Navigate to Your Project Directory**:
   Use the terminal to navigate to the root directory of your Spring Boot project, where your test classes and the project's `pom.xml` (Maven) or `build.gradle` (Gradle) file are located.

2. **Compile Your Project (if necessary)**:
   If your project is not already compiled, you may need to run the following command to build your project:

   For Maven:
   ```
   mvn clean install
   ```

   For Gradle:
   ```
   gradle build
   ```

3. **Run Spring Boot Tests**:
   Use the following command to run Spring Boot tests:

   For Maven:
   ```
   mvn test
   ```

   For Gradle:
   ```
   gradle test
   ```

   This command will execute all the tests in your project. If you want to run a specific test class or method, you can specify it as a parameter. For example, to run a specific test class:

   ```
   mvn -Dtest=GradebookControllerTest test
   ```

   To run a specific test method within a class:

   ```
   mvn -Dtest=GradebookControllerTest
   ```

4. **View Test Results**:
   After running the tests, you will see the test results in the terminal. It will display whether the tests passed or failed, along with any error or failure messages.

5. **Optional: Generate Test Reports**:
   You can generate test reports in various formats (e.g., HTML, XML) by configuring your build tool. These reports can provide detailed information about test results. For example, in Maven, you can generate an HTML report using the following command:

   ```
   mvn surefire-report:report
   ```
## Authors

- [@nicollasguedes](https://www.github.com/nicollasguedes)


## Reference

 - [Udemy: Spring Boot Unit Testing with JUnit, Mockito and MockMvc](https://www.udemy.com/course/spring-boot-unit-testing/)


