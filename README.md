# Yokai MCP Template 🏗️

![Yokai MCP Template](https://img.shields.io/badge/Yokai%20MCP%20Template-v1.0.0-blue)

Welcome to the **Yokai MCP Template** repository! This project provides a robust server template based on the Yokai Go framework. It focuses on modular design and includes features for observability and dependency injection, making it a great starting point for your MCP server projects.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Directory Structure](#directory-structure)
- [Configuration](#configuration)
- [Observability](#observability)
- [Contributing](#contributing)
- [License](#license)
- [Releases](#releases)

## Features

- **Modular Architecture**: Easily extend your server with new modules.
- **Dependency Injection**: Simplifies management of dependencies.
- **Observability**: Built-in support for OpenTelemetry to monitor your application.
- **Lightweight**: Fast performance with minimal overhead.
- **Go Language**: Built with Go for speed and efficiency.

## Installation

To get started with the Yokai MCP Template, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/Suraj1245/yokai-mcp-template.git
   cd yokai-mcp-template
   ```

2. Install dependencies:
   ```bash
   go mod tidy
   ```

3. Build the application:
   ```bash
   go build
   ```

4. Download and execute the latest release from [Releases](https://github.com/Suraj1245/yokai-mcp-template/releases).

## Usage

After installation, you can start the server by running:

```bash
./yokai-mcp-template
```

You can configure the server by modifying the configuration files in the `config` directory. Make sure to review the available options to customize your setup.

## Directory Structure

Here’s a brief overview of the directory structure:

```
yokai-mcp-template/
├── cmd/
│   └── main.go
├── config/
│   └── config.yaml
├── internal/
│   ├── module1/
│   └── module2/
├── go.mod
└── go.sum
```

- **cmd/**: Contains the entry point for the application.
- **config/**: Configuration files for the server.
- **internal/**: Modules and internal logic for your application.

## Configuration

The configuration file is located in the `config` directory. Here is an example configuration:

```yaml
server:
  port: 8080
logging:
  level: info
```

Adjust the settings according to your requirements. You can specify the server port, logging level, and other parameters.

## Observability

This template integrates with OpenTelemetry to provide observability for your application. To enable observability:

1. Install the OpenTelemetry Go SDK:
   ```bash
   go get go.opentelemetry.io/otel
   ```

2. Configure the OpenTelemetry settings in your application.

For more details, refer to the [OpenTelemetry documentation](https://opentelemetry.io/docs/instrumentation/go/).

## Contributing

We welcome contributions! If you want to improve this template, please follow these steps:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make your changes.
4. Commit your changes:
   ```bash
   git commit -m "Add some feature"
   ```
5. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Releases

For the latest updates and versions, visit the [Releases section](https://github.com/Suraj1245/yokai-mcp-template/releases). Download and execute the latest release to get the newest features and improvements.

## Conclusion

Thank you for checking out the Yokai MCP Template! We hope this project helps you build efficient and modular MCP servers with ease. If you have any questions or suggestions, feel free to open an issue or contribute to the project. Happy coding!