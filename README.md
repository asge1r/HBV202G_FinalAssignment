# HBV202G Final Project

#### Ásgeir Snær Magnússon

I decided to move on with assignment 8 since I built a good structure for that specific project.
However, since I had to add more features to the project I had to rebuild my structure quite a lot.
It went great since I have learned a lot about Java and I have used the Maven build tool to build projects in this course.

Maven:

- `mvn compile` compiles all implementation classes
- `mvn compile exec:java` compiles all implementation classes and runs main
- `mvn exec:java` runs main
- `mvn test` runs all test cases
- `mvn package` creates executable jar file
- `mvn site` creates site from files in /site folder

To run the executable jar file run the runjar.cmd file.

Design Pattern:

I used the Composite pattern to create Lendables that can be used to store different types of things in the library, e.g. Books and Book Collections.

##Here are the class diagram and license file.

[Class Diagram](/src/site/markdown/design.md)

[License file](/LICENSE)

##Problems
The main problems I ran into and did not solve completely are:

- The lender counter is always 0.
- So returning a book returns the oldest lending.
- Lending.getDueDate() returns null.
