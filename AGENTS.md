```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure consistent, maintainable, and high-quality code for our AI coding agents. Adherence to these principles is crucial for a successful development process.

**1. DRY (Don't Repeat Yourself)**

*   Each function, class, and module should have a single, well-defined purpose.
*   Avoid duplicating code. When a similar functionality is needed, create a reusable component.
*   Favor composition over inheritance whenever possible.

**2. KISS (Keep It Simple, Stupid)**

*   Prioritize readability and simplicity.  Code should be easy to understand and maintain.
*   Use concise and clear variable names.
*   Avoid overly complex logic.  Break down complex tasks into smaller, manageable steps.
*   Strive for minimal code, focusing on essential functionality.

**3. SOLID Principles**

*   **Single Responsibility Principle:** Each class or module should have one, and only one, reason to change.
*   **Open/Closed Principle:**  Systems should be open for extension but closed for modification.  This is achieved through interfaces and abstraction.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to rely on abstractions they do not need.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.  They should depend on abstractions.

**4. YAGNI (You Aren't Gonna Need It)**

*   Implement only the functionalities required *at this point in time*.
*   Defer adding features or complexity until they are absolutely necessary.
*   Avoid premature optimization. Focus on delivering working code first.

**5. Code Length & Structure**

*   Code length: Maximum 180 lines of code per file.
*   File Structure:
    *   Modular Design:  Break down the codebase into logical modules.
    *   Clear Directory Structure: Organize files by function, component, or task.
    *   Comments:  Provide clear and concise comments explaining complex logic, assumptions, and design decisions.
*   Naming Conventions:
    *   Follow a consistent naming convention (e.g., snake_case).
    *   Use descriptive names for functions, classes, and variables.

**6. Testing & Verification**

*   All development must be productive.
*   Automated Testing:  A minimum of 80% of the code should be covered by unit tests.
*   Test-Driven Development:  Write tests *before* writing code.
*   Test Coverage Reports:  Generate automated test coverage reports to identify areas needing improvement.

**7.  AI Specific Considerations**

*   Focus on creating modular and reusable components.
*   Documentation:  Provide sufficient documentation for all functions, classes, and modules.  Include clear explanations of their purpose, inputs, and outputs.
*   Error Handling:  Implement robust error handling to prevent crashes and provide informative error messages.
*   Data Handling: Clearly define data types and validation rules for input data.

**8.  Project-Specific Rules**

*   [Specify any AI-specific rules here - e.g., constraints on data formats, model interaction protocols]

**9.  Tools & Technologies**

*   Use [Specific Libraries/Frameworks] as defined in the README.
*   Document dependencies using [Dependency Management Tool].

**10.  Documentation**

*   Create a README file with a clear overview of the project and its key components.
*   Include a comprehensive documentation section detailing API usage and expected behavior.

**11.  Code Quality:**

*   Follow PEP 8 coding style guidelines.
*   Use static analysis tools (e.g., pylint, flake8) to identify potential issues.

**12.  Version Control:**

*   Use Git for version control.
*   Follow a consistent branching strategy (e.g., Gitflow).

These guidelines are intended as a starting point; adapt and refine them as the project evolves.  Regular review and updates are crucial for maintaining a high-quality codebase.
```