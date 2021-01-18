---
title: Inappbrowser
description: Open an in-app browser popup window.
---
This is a fork of cordova-plugin-inappbrowser which adds support for PopupBridge libraries for Android and iOS to support payments within the context of the InappBrowser element of a Cordova-based app.



Installation
cordova plugin add cordova-plugin-inappbrowser-popup-bridge

## Installation

    cordova plugin add cordova-plugin-inappbrowser

If you want all page loads in your app to go through the InAppBrowser, you can
simply hook `window.open` during initialization.  For example:

    document.addEventListener("deviceready", onDeviceReady, false);
    function onDeviceReady() {
        window.open = cordova.InAppBrowser.open;
    }

