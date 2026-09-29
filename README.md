# Android Menus and WebView - Experiment 8

## Student Details

**Name:** Akriti Shankar  
**USN:** 25MCAR0087  
**Course:** MCA  
**Experiment:** 8

## Aim

To develop an Android application demonstrating different types of menus and WebView.

## Technologies Used

- Android Studio
- Kotlin
- XML
- Android WebView

## Features

The application demonstrates:

1. Options Menu
2. Popup Menu
3. Context Menu
4. Toolbar
5. WebView
6. Toast Messages

## Application Description

The application contains a Student Web Portal interface.

### Options Menu

The toolbar contains an options menu with:

- Home
- WebView
- About

### Popup Menu

The Popup Menu contains:

- Profile
- Settings
- Help

### Context Menu

A long press on the text opens a context menu containing:

- Edit
- Copy
- Delete

### WebView

The application uses Android WebView to display web content inside the application.

The WebView currently loads:

https://example.com/

## Project Structure

```text
app
├── manifests
│   └── AndroidManifest.xml
│
├── java
│   └── com.example.menu_exp8
│       └── MainActivity.kt
│
└── res
    ├── layout
    │   └── activity_main.xml
    │
    └── menu
        ├── menu_options.xml
        ├── menu_popup.xml
        └── menu_context.xml
