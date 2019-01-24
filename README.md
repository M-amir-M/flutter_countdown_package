# simple_countdown

An easy way to use count down

## How to use simple_countdown

1. Open the `pubspec.yaml` file, and add `simple_countdown: <latest_version>` unde `dependencies`:
```
  dependencies:
    flutter:
      sdk: flutter
    # ...
    # ...
    simple_countdown: ^0.0.1
```

2. install it from terminal: Run `flutter packages get`

## Example

``` dart
import 'package:flutter/material.dart';
import 'package:simple_countdown/simple_countdown.dart';

void main() => runApp(MaterialApp(
      home: Scaffold(
        body: Center(
          child: Countdown(
            seconds: 10,
            onFinish: () {
              print('Finish');
            },
            textStyle: TextStyle(fontSize: 25, color: Colors.white),
          ),
        ),
      ),
    ));

```
