# Deluxe Mobile SDK

![Release](https://img.shields.io/badge/release-v1.0.0-blue)
![License](https://img.shields.io/badge/license-Commercial-lightgrey)

Mobile SDK for iOS and Android integration.

The Deluxe Mobile SDK enables developers to integrate secure payment processing and POS terminal management directly into native and hybrid mobile applications. It provides native frameworks for iOS and Android, allowing you to build fast, reliable, and scalable in-person payment experiences.

The SDK is designed for flexibility and performance, supporting secure transactions, terminal connectivity, and merchant operations within a unified solution. It enables Independent Software Vendors (ISVs) to embed payment capabilities into mobile apps while maintaining full control over user experience and business workflows.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Releases](#releases)
- [Getting Started](#documentation)
- [Support](#support)

## Overview

The Deluxe Mobile SDK provides a comprehensive set of tools and services to simplify mobile payment integration. It combines payment processing, POS terminal connectivity, and merchant operations into a single platform, reducing development complexity while maintaining high performance and security standards.

## Features

### Payments
- Accept in-person payments
- Support for sale, refund, and void transactions
- Optimized transaction lifecycle handling

### POS Terminal Integration
- Discover and connect to supported devices
- Bluetooth-based connectivity
- Connection lifecycle management

### Security
- Tokenization and vaulting
- PCI-conscious architecture
- Secure communication with backend services

**Best Practices**
- Do not store sensitive cardholder data
- Always use tokenization
- Protect API credentials and access tokens
- Follow PCI compliance best practices

### Merchant Services
- Merchant authentication and authorization
- Account and terminal management
- Inventory, tax, discount, and reporting services

### Reporting and Receipts
- Transaction history and summaries
- Email and SMS receipt delivery

### Native SDKs
- iOS SDK supports both Objective and Swift
- Android SDK supports both Java and Kotlin

## Requirements

### iOS
- iOS 13.0 or later
- Xcode 14 or later recommended
- Supported on iPhone 7 and newer

### Android
- Minimum SDK: API 24
- Target SDK: API 36
- Kotlin-based project recommended

## Installation

### iOS

1. Download the SDK package
2. Add the all xcframeworks to your project:
3. Set deployment target to iOS 13 or later
4. Add frameworks under **Link Binary With Libraries** and **Embed Frameworks**

### Android

1. Copy AAR files into the `libs` directory
2. Configure your project to reference local dependencies
3. Sync your project


## Releases

The [changelog](https://github.com/Kanagu-durai/MerchantSampleSDK/blob/main/CHANGELOG.md) provides a summary of changes in each release.
The [migration guide](https://github.com/Kanagu-durai/MerchantSampleSDK/blob/main/MIGRATING.md) provides instructions on upgrading from older versions.



## Getting Started

### iOS

Get started with our **[integration guides](https://github.com/Kanagu-durai/MerchantSampleSDK/tree/main/iOSSDK/Docs/ImplementationGuide)** and **[example projects](https://github.com/Kanagu-durai/MerchantSampleSDK/tree/main/iOSSDK/Sample)**, or browse the **[iOS SDK reference](https://github.com/Kanagu-durai/MerchantSampleSDK/blob/main/iOSSDK/Docs/IOSSdkReferenceGuide.pdf)** for detailed documentation.

---

### Android
Get started with our **[integration guides](https://github.com/Kanagu-durai/MerchantSampleSDK/tree/main/AndroidSDK/Docs/ImplementationGuide)** and **[example projects](https://github.com/Kanagu-durai/MerchantSampleSDK/tree/main/AndroidSDK/Sample)**, or browse the **[Android SDK reference](https://github.com/Kanagu-durai/MerchantSampleSDK/blob/main/AndroidSDK/Docs/AndroidSdkReferenceGuide.pdf)** for detailed documentation.
  
## Support

For questions, onboarding, or technical assistance:

**Email:** isvinquiries@deluxe.com

## Licenses
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
