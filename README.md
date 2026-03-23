# Deluxe Mobile SDK

![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-blue)
![iOS](https://img.shields.io/badge/iOS-13%2B-black)
![Android](https://img.shields.io/badge/Android-API%2024%2B-green)
![Language](https://img.shields.io/badge/language-Swift%20%7C%20Kotlin-orange)
![Status](https://img.shields.io/badge/status-Active-success)

Mobile SDK for iOS and Android integration.

The Deluxe Mobile SDK enables developers to integrate secure payment processing and POS terminal management directly into native and hybrid mobile applications.

---

## 📚 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Requirements](#-requirements)
- [Installation](#-installation)
- [Dependencies](#-dependencies)
- [Quickstart](#-quickstart)
- [Releases](#-releases)
- [Documentation](#-documentation)
- [Support](#-support)

---

## Overview
The Deluxe Mobile SDK simplifies mobile payment integration by combining payment processing, POS terminal connectivity, and merchant operations into a single platform.

---

## ✨ Features

### Payments
- Accept in-person payments
- Sale, refund, and void transactions
- Optimized transaction lifecycle

### POS Terminal Integration
- Device discovery and connection
- Bluetooth connectivity
- Lifecycle management

### Security
- Tokenization and vaulting
- PCI-conscious architecture
- Secure backend communication

**Best Practices**
- Do not store sensitive cardholder data
- Always use tokenization
- Protect API credentials
- Follow PCI compliance

### Merchant Services
- Authentication & authorization
- Account & terminal management
- Inventory, tax, discount, reporting

### Reporting & Receipts
- Transaction history
- Email & SMS receipts

### Native SDKs
- Swift (iOS)
- Kotlin (Android)

---

## Requirements

### iOS
- iOS 13+
- Xcode 14+
- iPhone 7+

### Android
- Min SDK: API 24
- Target SDK: API 36
- Kotlin recommended

---

## Installation

### iOS
```bash
Add frameworks:
- PosSDK.xcframework
- PaymentSDK.xcframework
- ServiceSDK.xcframework
- PaymentHostModule.xcframework
- TapToPaySDK.xcframework
```

Steps:
1. Download SDK
2. Add frameworks
3. Set deployment target (iOS 13+)
4. Link & embed frameworks

### Android
```gradle
Place AAR files in /libs
```

Steps:
1. Copy AARs
2. Configure dependencies
3. Sync project

---

## Dependencies

### Android
- possdk-release
- payment-release
- servicesdk-release
- payment-hostmodule-release
- roamreaderunifiedapi

### iOS
- PosSDK
- PaymentSDK
- ServiceSDK
- PaymentHostModule
- TapToPaySDK

---

## Quickstart
```text
1. Configure environment
2. Initialize SDK
3. Authenticate merchant
4. Connect terminal
5. Execute transaction
```

---

## Releases
Distributed via Developer Portal:
- Enhancements
- Bug fixes
- Performance improvements

---

## 📖 Documentation
- [Get Started](https://developer.deluxe.com/docs-content/payments/merchant-services/integration/online-payment-integrations/mobile-sdk/get-started)
- [Implementation Guide](https://developer.deluxe.com/docs-content/payments/merchant-services/integration/online-payment-integrations/mobile-sdk/mobile-sdk-implementation-guide)

---

## 🤝 Support
📧 isvinquiries@deluxe.com
