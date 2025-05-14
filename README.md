<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/tools/pub/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/to/develop-packages).
-->

# Solarium

A modern Flutter package implementing the next generation iOS design language, bringing Apple's latest design principles to Flutter applications.

## Features

- 🎨 Modern iOS-inspired design components
- 📱 Native-feeling animations and transitions
- 🎯 High-performance, customizable widgets
- 🌙 Dark mode support
- 📐 Responsive layouts
- ♿ Accessibility support

## Getting Started

### Prerequisites

- Flutter SDK (>=1.17.0)
- Dart SDK (^3.7.2)

### Installation

Add Solarium to your `pubspec.yaml`:

```yaml
dependencies:
  solarium: ^0.0.0-dev.1
```

Then run:

```bash
flutter pub get
```

## Usage

Import the package in your Dart code:

```dart
import 'package:solarium/solarium.dart';
```

### Basic Example

```dart
import 'package:flutter/material.dart';
import 'package:solarium/solarium.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      theme: SolariumTheme.light(),
      darkTheme: SolariumTheme.dark(),
      home: const HomeScreen(),
    );
  }
}
```

## Additional Information

### Documentation

For detailed documentation and API reference, visit our [documentation site](https://pub.dev/documentation/solarium/latest/).

<!-- ### Contributing

We welcome contributions! Please see our [contributing guidelines](https://github.com/glemartret/solarium/CONTRIBUTING.md) for details. -->

### Issues and Feedback

Please file issues and feature requests on the [GitHub repository](https://github.com/glemartret/solarium/issues).

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Roadmap

- [ ] Core UI components
- [ ] Navigation patterns
- [ ] Form elements
- [ ] Animation system
- [ ] Theme customization
- [ ] Documentation
- [ ] Example app

## Support

If you find this package helpful, please consider giving it a star on [GitHub](https://github.com/glemartret/solarium)!
