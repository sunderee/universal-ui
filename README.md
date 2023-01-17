# Universal UI

Temporary fix of dart:ui. 

## Usage

Import the package.

```dart
import 'package:universal_ui/universal_ui.dart' as ui;
```

Then, use the `ui` object as usual. You don't need to create an alias and
add ignore:

```dart
ui.platformViewRegistry.registerViewFactory(
    'iframeElement',
    (int viewId) => _iframeElement,
);
```