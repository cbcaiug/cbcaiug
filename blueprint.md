# Project Blueprint

## Overview

This project converts an existing React-based web application into a native Android app using Flutter. The core of the application is a WebView component that loads and displays the web app, with additional native features to enhance the user experience and meet Google Play Store guidelines.

## Features

*   **WebView Integration:** The app uses `webview_flutter` to display the web content.
*   **Native Android App:** The final output is an APK file, installable on Android devices.
*   **Loading Indicator:** A progress indicator is shown while the web page is loading.
*   **Native UI Integration:** A native refresh button is included in the app bar, providing a tangible native feature for users.
*   **Platform-Specific Code:** The app now correctly handles platform differences, preventing crashes on the web and showing a user-friendly message.

## Current Plan

1.  **Add Dependencies:** Add the `webview_flutter` package to `pubspec.yaml`.
2.  **Configure Android:**
    *   Set the minimum SDK version to 21 in `android/app/build.gradle.kts`.
    *   Add the `INTERNET` permission to `android/app/src/main/AndroidManifest.xml`.
3.  **Implement WebView:**
    *   Replace the default code in `lib/main.dart`.
    *   Create a `WebView` widget that points to `https://teachwithai.vercel.app/app.html`.
    *   Conditionally initialize the `WebViewController` only on mobile platforms to prevent web-based errors.
    *   Add a native refresh button to the app bar.
4.  **Build and Deploy:** Guide the user on how to build the APK.
