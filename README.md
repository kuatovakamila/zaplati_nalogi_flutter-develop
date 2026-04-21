# Zaplati Nalogi (QPay) — FinTech Tax Payment Application

> A cross-platform mobile application that simplifies tax payment and document management for citizens.

📂 **Repository:** [github.com/kuatovakamila/zaplati_nalogi_flutter-develop](https://github.com/kuatovakamila/zaplati_nalogi_flutter-develop)

---

## Overview

Zaplati Nalogi ("Pay Taxes" in Russian) is a Flutter-based FinTech mobile application designed to make navigating tax obligations straightforward. The app provides a secure, unified interface for authentication, tax payment flows, and PDF document handling — all from a single mobile experience on iOS and Android.

---

## Features

### 🔐 Secure OAuth2 Authentication
Implements the OAuth2 protocol with JWT token handling via the `jose` library, ensuring secure and standards-compliant user authorization.

### 💳 In-App Payment Flow
Integrated WebView-based payment interface allowing users to complete tax payments without leaving the app, using `flutter_inappwebview` for a seamless browsing experience.

### 📄 PDF Document Viewer
Built-in PDF rendering and viewing capabilities for tax documents, receipts, and official forms — powered by `flutter_pdfview` and `pdf_render`.

### 💾 Persistent Session Management
User sessions and preferences are stored locally with `shared_preferences`, enabling a smooth login experience across app restarts.

### ⚡ Reactive State Management
Application state is managed with `flutter_riverpod`, ensuring a scalable, testable, and maintainable architecture.

---

## Tech Stack

| Layer | Technology |
|-------|------------|
| Mobile Framework | Flutter (Dart) |
| State Management | Riverpod |
| Authentication | OAuth2, JOSE (JWT) |
| In-App Browser | flutter\_inappwebview |
| PDF Viewing | flutter\_pdfview, pdf\_render |
| Local Storage | shared\_preferences |
| Platform | iOS & Android |

---

## Screenshots

| | | |
|---|---|---|
| ![Screen 1](flutter_01.png) | ![Screen 2](flutter_02.png) | ![Screen 3](flutter_03.png) |
| ![Screen 4](flutter_04.png) | ![Screen 5](flutter_05.png) | ![Screen 6](flutter_06.png) |

---

## Getting Started

```bash
# Clone the repository
git clone https://github.com/kuatovakamila/zaplati_nalogi_flutter-develop.git
cd zaplati_nalogi_flutter-develop

# Install dependencies
flutter pub get

# Run the application
flutter run
```

**Requirements:** Flutter SDK `>=2.17.3 <3.0.0`

---

## License

This is a private project. All rights reserved.
