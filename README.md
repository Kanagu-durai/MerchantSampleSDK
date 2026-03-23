# Deluxe Mobile SDK

Mobile SDK for iOS and Android integration that enables secure payment processing and POS terminal management in native and hybrid mobile applications.

## Overview

The Deluxe Mobile SDK simplifies mobile payment integration by combining payment processing, POS terminal connectivity, and merchant operations into a single platform.

## Features

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
- Authentication and authorization
- Account and terminal management
- Inventory, tax, discount, and reporting

### Reporting and Receipts
- Transaction history
- Email and SMS receipts

### Native SDKs
- Swift (iOS)
- Kotlin (Android)

## Requirements

### iOS
- iOS 13+
- Xcode 14+
- iPhone 7 or later

### Android
- Minimum SDK: API 24
- Target SDK: API 36
- Kotlin recommended

## Installation

### iOS

Add the following frameworks to your project:

- PosSDK.xcframework
- PaymentSDK.xcframework
- ServiceSDK.xcframework
- PaymentHostModule.xcframework
- TapToPaySDK.xcframework

Steps:

1. Download the SDK
2. Add frameworks to the project
3. Set deployment target to iOS 13 or later
4. Link and embed frameworks

### Android

Place AAR files in the libs directory.

Steps:

1. Copy AAR files to /libs
2. Configure dependencies in Gradle
3. Sync the project

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

## Quickstart

1. Configure environment
2. Initialize SDK
3. Authenticate merchant
4. Connect terminal
5. Execute transaction

## Releases

SDK is distributed via the Developer Portal and includes:

- Enhancements
- Bug fixes
- Performance improvements

## Documentation

- Get Started: https://developer.deluxe.com/docs-content/payments/merchant-services/integration/online-payment-integrations/mobile-sdk/get-started
- Implementation Guide: https://developer.deluxe.com/docs-content/payments/merchant-services/integration/online-payment-integrations/mobile-sdk/mobile-sdk-implementation-guide

## Support

For support, contact:

isvinquiries@deluxe.com
