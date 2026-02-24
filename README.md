# Coink

A concise, well-structured README for the Coink Android project. This document provides an overview, quick build/run instructions, and embedded screenshots from the `Images_App` folder showing the app in action.

---

## Table of contents

- Overview
- Screenshots
- Requirements
- Build & Run
- Project structure
- Contributing
- Troubleshooting
- Acknowledgements

---

## Overview

`Coink` is an Android project maintained in this repository. The README focuses on how to open, build, and run the project locally and includes screenshots demonstrating the app UI.

## Screenshots

Below are a few screenshots of the app running. Images are embedded from the `Images_App` folder in the repository root.

<p align="center">
  <img src="Images_App/Captura%20de%20pantalla%202026-02-23%20225514.png" alt="Screenshot 1" width="320" />
</p>

<p align="center">
  <em>Screenshot: app screen 1</em>
</p>

<p align="center">
  <img src="Images_App/Captura%20de%20pantalla%202026-02-23%20225539.png" alt="Screenshot 2" width="320" />
</p>

<p align="center">
  <em>Screenshot: app screen 2</em>
</p>

<p align="center">
  <img src="Images_App/Captura%20de%20pantalla%202026-02-23%20225607.png" alt="Screenshot 3" width="320" />
</p>

<p align="center">
  <em>Screenshot: app screen 3</em>
</p>

---

## Requirements

- Java Development Kit (JDK) 11 or later
- Android Studio (recommended) or Gradle wrapper
- Android SDK (installed via Android Studio)

## Build & Run

Recommended (Android Studio):

1. Open Android Studio.
2. Choose "Open an existing Android Studio project" and select this repository root.
3. Let Android Studio sync Gradle and download dependencies.
4. Connect an Android device or start an emulator and run the `app` module.

Command line (using the Gradle wrapper):

- To build a debug APK:

```
# On Windows PowerShell in the project root
./gradlew assembleDebug
```

- To install and run on a connected device (debug):

```
./gradlew installDebug
```

Note: If you encounter SDK or build errors, open the project in Android Studio for guided fixes.

## Project structure (high level)

- `app/` — main Android application module
- `build.gradle`, `settings.gradle` — top-level Gradle files
- `Images_App/` — screenshots used in this README

## Contributing

If you plan to contribute, please follow these steps:

1. Create an issue describing the change or bug.
2. Open a branch for your work.
3. Submit a pull request with a clear description and screenshots if UI-related.

## Troubleshooting

- Gradle sync failures: open the project in Android Studio and follow the prompts to install missing SDK components.
- JDK errors: ensure `JAVA_HOME` points to a JDK 11+ installation.

## Acknowledgements

This README was added to provide quick onboarding and documentation for the project. If you want more detailed documentation (API, architecture diagrams, tests), I can add those next.
