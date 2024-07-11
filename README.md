# Clean Code Rules
- [Clean Code Rules](#clean-code-rules)
   * [Poster](#poster)
   * [Detailed Notes](#detailed-notes)
      + [Naming Conventions](#naming-conventions)
      + [Functions](#functions)
      + [Comments](#comments)
      + [Formatting](#formatting)
      + [Error Handling](#error-handling)
      + [Classes](#classes)
      + [General Principles](#general-principles)
      + [Testing](#testing)

## Poster
![CleanCodePoster_ShyamPatel](https://github.com/patelshyam/Clean-code-notes./assets/26683455/bc72e5a4-ea20-40c8-bbe7-46551c5174ab)
## Detailed Notes
### Naming Conventions
1. **Use Meaningful Names:** Names should reveal intent. Choose names that describe the purpose or role of the variable, method, or class.
2. **Avoid Encodings:** Do not include type or scope information in the name (e.g., Hungarian notation (public static int publicStaticIntPrice=10)).
3. **Use Pronounceable Names:** This makes it easier to discuss the code.
4. **Use Searchable Names:** Avoid using single letters or overly short names, except for temporary variables.
5. **Consistency:** Use a consistent naming convention throughout the codebase (e.g., camelCase for variables and methods, PascalCase for classes).

### Functions
1. **Small Functions:** Functions should be small and do one and only one thing.
2. **Single Responsibility Principle:** Each function should have only one responsiblity.
3. **Descriptive Names:** Function names should clearly describe what they do.
4. **Avoid Side Effects:** Functions should avoid altering the state of the system or causing unexpected behavior.
5. **Limit the Number of Arguments:** Prefer fewer arguments; consider using objects if more than three arguments are needed.

### Comments
1. **Self-Explanatory Code:** Write code that is self-explanatory so that comments are not needed.
2. **Useful Comments:** Use comments to explain why something is done, not what is done.
3. **Avoid Redundant Comments:** Avoid comments that restate the obvious or duplicate the code.
4. **Update Comments:** Ensure comments are updated when the code changes.

### Formatting
1. **Consistent Indentation:** Use consistent indentation to improve readability.
2. **Line Length:** Limit line length to a reasonable amount (typically 80-120 characters).
3. **Whitespace:** Use whitespace to separate logical sections of code and improve readability.
4. **Blocks:** Use curly braces for blocks, even if optional, to avoid errors and improve readability.

### Error Handling
1. **Use Exceptions:** Prefer exceptions over error codes for error handling.
2. **Catch Specific Exceptions:** Catch specific exceptions rather than using a general catch-all.
3. **Fail Fast:** Detect errors early and handle them as close to the source as possible.
4. **Provide Context:** Include meaningful messages and context with exceptions to aid debugging.

### Classes
1. **Small Classes:** Classes should be small and focused on a single responsibility.
2. **Encapsulation:** Keep internal details private and expose only what is necessary.
3. **Cohesion:** Ensure that class members are related and work together towards a common goal.
4. **Dependency Injection:** Use dependency injection to decouple classes and make them more testable.

### General Principles
1. **DRY (Don't Repeat Yourself):** Avoid code duplication by abstracting common functionality.
2. **KISS (Keep It Simple, Stupid):** Keep the code as simple as possible.
3. **YAGNI (You Aren't Gonna Need It):** Don't add functionality until it is necessary.
4. **SOLID Principles:** Follow SOLID principles for object-oriented design:
   - **S:** Single Responsibility Principle
   - **O:** Open/Closed Principle
   - **L:** Liskov Substitution Principle
   - **I:** Interface Segregation Principle
   - **D:** Dependency Inversion Principle

### Testing
1. **Write Tests:** Ensure code is covered by automated tests.
2. **Test Coverage:** Aim for high test coverage but prioritize meaningful tests over coverage percentage.
3. **Isolate Tests:** Tests should be isolated and independent of each other.
4. **Readable Tests:** Write tests that are easy to read and understand.

---

## Inspiration
- Special thanks to Robert C. Martin (Uncle Bob) for introduction of Clean Code in very easy way. 
    - [YouTube Video Playlist](https://www.youtube.com/watch?v=7EmboKQH8lM&list=PLmmYSbUCWJ4x1GO839azG_BBw8rkh-zOj).