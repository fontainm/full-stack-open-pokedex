# Exercise 11.1

For the purpose of this hypothetical scenario, let's consider Java as the language of choice for the application.

## 1) Common tools in the Java ecosystem for CI setups

- Linting: While Java does not have linting in the same sense as dynamically typed languages, static code analysis tools like Checkstyle, PMD, and FindBugs can enforce coding standards and identify potential issues.
- Testing: JUnit is the de facto standard for unit testing in Java. Additionally, tools like TestNG offer alternative testing frameworks. For code coverage, JaCoCo is widely used.
- Building: Apache Maven and Gradle are popular build automation tools for Java projects. They handle dependencies, compile code, run tests, and package the application for deployment.

## 2) Alternatives to Jenkins and GitHub Actions for CI setups in Java

- TeamCity: A CI/CD server by JetBrains, offering powerful features for building, testing, and deploying Java applications with an intuitive user interface.
- Bamboo: Atlassian's CI/CD server, which integrates seamlessly with other Atlassian products like Jira and Bitbucket for end-to-end software development.
- Azure Pipelines: Part of the Azure DevOps suite, offering cloud-based CI/CD pipelines that can build, test, and deploy Java applications with integration options for GitHub, Bitbucket, and Azure Repos.

## 3) Self-hosted vs. cloud-based

The choice between self-hosted and cloud-based CI environments for Java projects depends on similar factors as discussed earlier:

- Control and customization: Self-hosted solutions offer more control over the CI environment, allowing customization to specific requirements, whereas cloud-based solutions provide convenience and scalability.
- Resource availability: Consider factors such as hardware, bandwidth, and personnel for maintaining a self-hosted CI infrastructure versus relying on the resources provided by cloud-based solutions.
- Budget: Cloud-based solutions may incur ongoing costs based on usage, while self-hosted solutions involve upfront hardware and setup costs, along with ongoing maintenance expenses.

Ultimately, the decision should be based on project requirements, team expertise, security considerations, and budget constraints.
