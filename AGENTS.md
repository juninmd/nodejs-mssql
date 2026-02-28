```markdown
# AGENTS.md File Guidelines

These guidelines outline the core principles and structure for development of the AGENTS.md repository. Adherence to these principles is crucial for maintaining a robust, maintainable, and scalable codebase.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent module should have a single, well-defined responsibility.
*   **Code Reuse:** Promote the creation of reusable components and functions across multiple agents.
*   **Avoid Redundant Logic:** Eliminate duplicate code patterns and logic.
*   **Standardized Components:** Define and document standardized components to minimize duplication.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimalism:** Strive for the simplest possible solution that meets the current requirements.
*   **Readability:** Write code that is easy to understand and maintain.
*   **Efficiency:**  Prioritize efficiency over excessive complexity.
*   **Clear Intent:** Ensure every line of code has a clear purpose.

## 3. SOLID Principles

*   **Single Responsibility:** Each class/module has a single, clear purpose.
*   **Open/Closed Principle:**  The system should be extensible without modification.
*   **Liskov Substitution Property:** Subclasses should be able to replace any underlying class without altering the correctness of the program.
*   **Interface Segregation Principle:** Each interface should define only the methods that its clients need.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules; they should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Future-Proofing:**  Avoid implementing features that are unlikely to be needed in the future.
*   **Focus on Current Requirements:**  Prioritize implementation based on current needs, not speculative future requirements.

## 5. Code Structure & Formatting

*   **Modular Design:**  The codebase should be organized into logical modules with well-defined interfaces.
*   **Consistent Naming Conventions:** Use consistent naming conventions throughout the repository (e.g., camelCase, snake_case).
*   **Docstrings:**  Provide comprehensive docstrings for all functions, classes, and modules, explaining their purpose, parameters, and return values.  Follow a standard format (e.g., Google Style Docstring).
*   **Error Handling:** Implement robust error handling with appropriate logging and informative error messages.
*   **Configuration:** Utilize a configuration file to easily manage different agent configurations.
*   **Comments:**  Add concise comments where necessary to explain complex logic or design decisions.
*   **Code Formatting:** Use a code formatter (e.g., Black) for consistent code style.
*   **Line Length:** Limit lines to 180 characters.

## 6. Testing - Focus on Unit & Integration Tests

*   **Mocking & Stubbing:** All unit and integration tests *must* utilize mocks or stubs for testing agents. Do not use real implementations.
*   **Comprehensive Test Suite:** Aim for at least 80% code coverage based on unit tests.
*   **Test-Driven Development (TDD) Principles:**  Consider applying TDD principles where possible, with a focus on writing tests before implementation.
*   **Isolation Tests:** Design tests that isolate individual agents and their components.
*   **Negative Test Cases:** Include tests that intentionally fail or produce unexpected results to validate agent behavior.

## 7. File Size Limit: 180 Lines

*   **Code Length Constraints:** All code must remain within 180 lines.

## 8.  Maintainability & Readability

*   **Clear Code Ownership:** Assign ownership for each file and module to a specific individual or team.
*   **Code Reviews:** Encourage thorough code reviews to ensure quality and adherence to guidelines.
*   **Documentation Updates:**  Maintain documentation in accordance with best practices.

## 9.  Dependencies & External Libraries

*   **Explicit Dependencies:** Clearly specify dependencies in the `requirements.txt` file.
*   **Version Control:**  Version control all dependencies with appropriate versions.

## 10.  Future Considerations (Beyond Current Guidelines)

*   **API Documentation:**  Document APIs using a tool like Swagger/OpenAPI.
*   **Data Modeling:** Consider data modeling best practices when designing agent data structures.
*   **Monitoring:** Plan for monitoring agent performance and health.

These guidelines are intended to serve as a framework for developing the AGENTS.md repository.  Continuous refinement and adaptation are encouraged based on ongoing feedback and evolving requirements.
```