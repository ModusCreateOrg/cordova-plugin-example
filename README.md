# Cordova Plugin Example

Example Cordova plugin for iOS and Android to support [this blog post] (http://moduscreate.com/plugin-authoring-cordova-6-ios-android/).

A simple Cordova plugin based on the echo plugin example from the [Cordova documentation](https://cordova.apache.org/docs/en/latest/guide/hybrid/plugins/index.html).

* `echo` method: Extends that example to display a native Toast on Android, and a native dialog like view on iOS.
* `echojs` method: Basic demo showing that plugins can also be used to organize and distribute useful JavaScript, and don't need native implementations necessarily.

iOS doesn't have a Toast type UI component, hat tip to [this Stack Overflow thread](http://stackoverflow.com/questions/18680891/displaying-a-message-in-ios-which-has-the-same-functionality-as-toast-in-android) for providing a simplistic alternative that doesn't introduce any extra dependencies and allows us to demonstrate a native interface without having to get lost in implementing something complex.

Now also supports the browser platform as detailed in [this blog post](http://moduscreate.com/supporting-the-browser-platform-in-a-cordova-plugin/).
