# Flutter Core

[![Pub Version](https://img.shields.io/pub/v/flutter_core)](https://pub.dev/packages/flutter_core)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A comprehensive Flutter package that provides essential core functionality for building robust Flutter applications. This package implements clean architecture principles and includes tools for secure storage, state management, error handling, and more.

## Features

- 🏗️ **Clean Architecture Support**: Base classes and utilities for implementing clean architecture
- 🔒 **Secure Storage**: Type-safe secure storage implementation with JSON object support
- 🎯 **State Management**: Integrated BLoC pattern support with proper exports
- 🎭 **Error Handling**: Robust error handling with Result type implementation
- 💉 **Dependency Injection**: GetIt service locator integration
- 🆔 **UUID Generation**: Utilities for unique identifier generation
- 🔐 **Encryption**: Built-in encryption capabilities

## Installation

Add this to your package's `pubspec.yaml` file:

```yaml
dependencies:
  flutter_core: ^0.0.1
```

## Architecture

```
lib/
  ├── src/
  │   ├── entity/          # Base entity classes
  │   ├── error/           # Error handling
  │   ├── extension/       # Extension methods
  │   ├── local_storage/   # Secure storage implementation
  │   ├── use_case/        # Base use case definitions
  │   └── utils/           # Utility classes
  └── flutter_core.dart    # Main export file
```

## Dependencies

- flutter_bloc: ^9.1.1 - State management
- encrypt: ^5.0.3 - Data encryption
- flutter_secure_storage: ^9.2.4 - Secure storage
- get_it: ^8.0.3 - Dependency injection
- uuid: ^4.5.1 - UUID generation

## Requirements

- Dart SDK: ">=2.18.4 <3.0.0"
- Flutter: ">=1.17.0"

## Contributing

We welcome contributions! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
