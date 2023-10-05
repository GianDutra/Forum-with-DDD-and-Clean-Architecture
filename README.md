# Clean Architecture Project

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/GianDutra/Forum-with-DDD-and-Clean-Architecture?color=%2304D361">

   <a href="https://github.com/seu-usuario/seu-projeto/commits/master">
    <img alt="GitHub último commit" src="https://img.shields.io/github/last-commit/GianDutra/Forum-with-DDD-and-Clean-Architecture">
  </a>
  
</p>

## Table of Contents

- [Overview](#overview)
- [Project Structure](#project-structure)
- [Tests](#tests)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project embraces the principles of Clean Architecture, focusing on entities and use cases. It is designed with modularity and maintainability in mind, making it easy to extend and adapt to changing requirements.

## Project Structure

The project is organized according to the principles of Clean Architecture, separating concerns into layers:

- **Core**: Contains the fundamental building blocks of the application.
  - **Entities**: Define the core data structures of the application.
  - **Errors**: Houses custom error types for the application.
  - **Events**: Manages domain events and event handling.
  - **Repositories**: Specifies interfaces for data access.
  - **Types**: Provides utility types.
- **Domain**: Contains the application-specific logic.
  - **Forum**: Handles forum-related functionality.
    - **Application**: Contains use cases.
    - **Entities**: Define entities specific to the forum.
- **Enterprise**: Contains business-specific logic.
  - **Entities**: Define entities specific to the business domain.
  - **Value Objects**: Define value objects used in the business logic.


## Tests

This project includes a comprehensive suite of unit tests to ensure the correctness and reliability of the codebase. Tests are located in the `test` directory.

## Getting Started

<!-- Provide instructions for setting up the project locally, including any dependencies, database setup, etc. -->

## Contributing

<!-- Provide guidelines for contributing to the project, including coding standards, issue reporting, and pull request process. -->

## License

[MIT License](LICENSE)
