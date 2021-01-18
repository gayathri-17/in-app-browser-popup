This is a fork of cordova-plugin-inappbrowser which adds support for Braintree's PopupBridge libraries for Android and iOS to support PayPal payments within the context of the InappBrowser element of a Cordova-based app.

The purpose of PopupBridge is to allow Webviews to open emulated popup windows in a browser and send data back to the parent page in the Webview. This is essential for Web-based PayPal checkout flows which use the Braintree JS SDK which supports popup emulation via PopupBridge.

See the example app project which demonstrates usage of cordova-plugin-inappbrowser-popup-bridge.

Installation
cordova plugin add cordova-plugin-inappbrowser-popup-bridge