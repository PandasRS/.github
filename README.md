![PandaAPI](panda.png)

# Pandas on Rust

## Introduction

PandasRS is an initiative to create an efficient, scalable Rust framework tailored for building server-side applications. Inspired by the ease of use found in Node.js frameworks like NestJS, PandasRS aims to bridge the gap for developers transitioning from JavaScript to Rust. This framework combines elements of Object-Oriented Programming (OOP) and Functional Programming (FP) to offer a robust development experience.

PandasRS utilizes Rocket for HTTP server functionality and integrates seamlessly with MongoDB, making it familiar and easy to adopt for developers accustomed to JavaScript and NoSQL databases.

## Philosophy

In recent years, thanks to Node.js, JavaScript has become the “lingua franca” of the web for both front and backend applications. This has given rise to awesome projects like Angular, React, and Vue, which improve developer productivity and enable the creation of fast, testable, and extensible frontend applications. However, while plenty of superb libraries, helpers, and tools exist for Node (and server-side JavaScript), none of them effectively solve the main problem of - Architecture.

PandasRS provides an out-of-the-box application architecture which allows developers and teams to create highly testable, scalable, loosely coupled, and easily maintainable applications. The architecture is heavily inspired by Angular.

## Features

- Create new PandasAPI projects
- Generate modules with controllers, services, DTOs, schemas, and repositories
- Automatically set up project structure and dependencies
- Easy integration with MongoDB
- Pre-configured Swagger UI for API documentation

## Installation

### Install Rust

Ensure you have Rust and Cargo installed on your system:

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

### Install PandasCLI

To install PandasCLI, run:

```
cargo install pandas-cli
```

## Usage

### Create a New Project

To create a new PandasAPI project, run:

```
pandas-cli new project-name
```

This command sets up a new project with the specified name, including all necessary directories and files.

### Generate a New Module

To generate a new module within your PandasAPI project, run:

```
pandas-cli generate module module-name
```

This command creates a new module with the specified name, including controller, service, DTO, schema, and repository files. During the process, you will be prompted to enter parameters for the module.

## Example

Here's how you can use PandasCLI to create a new project and generate a module:

```
# Create a new project
pandas-cli new my-awesome-api

# Navigate to the project directory
cd my-awesome-api

# Generate a new module
pandas-cli generate module users
```

## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue or submit a pull request on the [GitHub repository](https://github.com/yourusername/pandas-cli).

## Contact

For any inquiries, please reach out to Marcus Gomes at viniciusllgomes@gmail.com.
