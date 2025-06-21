# Perch: A Command-Line Tool for MCP HexLayer Architecture Projects 🐦

![Perch Logo](https://img.shields.io/badge/Perch-CLI-blue.svg)  
[![Latest Release](https://img.shields.io/github/v/release/lexis010/perch-py)](https://github.com/lexis010/perch-py/releases)

Welcome to the **Perch** repository! Perch is a developer-friendly command-line tool designed for scaffolding and managing MCP HexLayer Architecture server projects. This tool streamlines your workflow and enhances your development experience.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Command Reference](#command-reference)
- [Contributing](#contributing)
- [License](#license)
- [Support](#support)

## Features 🌟

- **Developer-Friendly**: Designed with developers in mind, Perch simplifies the setup of your projects.
- **MCP HexLayer Architecture**: Built specifically for the HexLayer Architecture, it supports modular design and separation of concerns.
- **Fast Setup**: Quickly scaffold new projects and get started without unnecessary delays.
- **Streamable HTTP**: Easily manage HTTP requests and responses in a clean and efficient manner.
- **Modular Design**: Leverage the power of modular programming to create maintainable and scalable applications.
- **Python-Based**: Built using Python, ensuring compatibility and ease of use for Python developers.

## Installation 🛠️

To install Perch, you can download the latest release from the [Releases](https://github.com/lexis010/perch-py/releases) section. Make sure to download the appropriate file for your system, then execute it to set up Perch on your machine.

```bash
# Example command to install Perch
pip install perch-py
```

## Usage 🚀

Using Perch is straightforward. Once installed, you can access the command line interface to start creating and managing your projects. 

### Basic Commands

Here are some basic commands to get you started:

```bash
perch create <project-name>
perch manage <project-name>
```

### Project Structure

When you create a new project, Perch will scaffold a clean architecture for you. This includes directories for models, views, and controllers, making it easy to organize your code.

```plaintext
<project-name>/
│
├── models/
│   └── __init__.py
├── views/
│   └── __init__.py
├── controllers/
│   └── __init__.py
└── main.py
```

## Command Reference 📜

Perch offers a variety of commands to help you manage your projects effectively. Here are some of the key commands:

### Create Command

```bash
perch create <project-name>
```
This command creates a new project with the specified name.

### Manage Command

```bash
perch manage <project-name>
```
Use this command to manage an existing project. This includes running the server, updating dependencies, and more.

### Additional Commands

For a full list of commands and options, please refer to the documentation or use the help command:

```bash
perch --help
```

## Contributing 🤝

We welcome contributions to Perch! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with clear messages.
4. Push your changes to your forked repository.
5. Submit a pull request.

Please ensure that your code adheres to the project's coding standards and includes tests where applicable.

## License 📄

Perch is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Support 💬

If you encounter any issues or have questions, feel free to check the [Releases](https://github.com/lexis010/perch-py/releases) section for updates or reach out through the repository's issues page.

Thank you for using Perch! We hope it makes your development process smoother and more efficient.