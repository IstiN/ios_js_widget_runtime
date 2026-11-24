# ios_js_widget_runtime

iOS renderer for jsr widgets: JavaScriptCore (or embedded QuickJS) + JSON tree to UIKit/SwiftUI.

Part of the jsr family:
- Contract + conformance: [js_widget_runtime](https://github.com/IstiN/js_widget_runtime) (PROTOCOL.md is the binding test spec)
- Runtime core: [js_runtime](https://github.com/IstiN/js_runtime)
- Reference renderer: [flutter_js_widget_runtime](https://github.com/IstiN/flutter_js_widget_runtime)
- Android: [android_js_widget_runtime](https://github.com/IstiN/android_js_widget_runtime)

Engine notes: JavaScriptCore is the natural engine on iOS (system framework, no embedding); embedded QuickJS keeps identical engine semantics with js_runtime — decide in the spike issue.

Status: **planning** — see issues. Conformance must pass per
[js_widget_runtime/docs/conformance/PROTOCOL.md](https://github.com/IstiN/js_widget_runtime/blob/main/docs/conformance/PROTOCOL.md).
