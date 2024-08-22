# flutter_sparkly

Made with ❤️ by [TzviPM](https://www.tzvipm.dev/)

> Make your Flutter app more ✨sparkly✨

Inspired by [`react-sparkle`](https://www.npmjs.com/package/react-sparkle) and built to enable "sparkles mode" in a game I built for my son.

You are free to copy, modify, and distribute `flutter_sparkly` with attribution under the terms of the MIT license. See the LICENSE file for details.

## Features



## Getting started

Simply set up your flutter project, then add `flutter_sparkly` using [this guide](https://pub.dev/packages/flutter_sparkly/install).

## Usage

Simply surround any component with `Sparkly` to make it shine ✨

```dart
class SparklyText extends StatelessWidget {
  final String text;

  const SparklyText({super.key, required this.text});

  @override
  Widget build(BuildContext context) {
    return Sparkly(
      child: Text(text),
    );
  }
}
```
