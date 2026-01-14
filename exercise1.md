# 11.1 Warming up

In this hypothetical situation, a team of 6 people is developing an application, using Java. The application is soon to be released.

The CI setup for this project includes three main steps: linting, testing, and building.

Linting is important for maintaining code quality, preventing errors, and ensuring consistent code style. Common linting tools in the Java ecosystem include Checkstyle and SpotBugs.

Testing makes sure that the code works as expected and doesn’t break the main branch. There are several testing frameworks for Java. JUnit is a popular, open-source framework mainly for unit testing, but it can be used for integration tests as well. TestNG is another popular testing framework that can be used to perform unit, integration, functional, as well as end-to-end tests.

Building the application makes sure that the code compiles and produces deployable packages. In the Java world, tools like Maven and Gradle can be used to handle dependencies, compilation, and packaging.

There are several alternatives to GitHub Actions and Jenkins. For example, CircleCI can run in the cloud or on self-hosted servers, and GitLab CI/CD could be a good cloud-based option if Gitlab is in use.

Deciding between self-hosted or cloud-based CI depends on factors like resources, security and scalability. Self-hosted setups offer more control but can be harder to configure, whereas cloud-based setups are easier to start with and to maintain, but offer less options for very specific needs. With this in mind, information on the project scope and size, security needs, and skills within the team are needed to choose between the two options. Considering team size (6 people), we could assume that the application isn't very large and that a cloud-based solution would be a safe choice.
