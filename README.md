# Deluxe Mobile SDK

Mobile SDK for iOS and Android integration.

The Deluxe Mobile SDK enables developers to integrate secure payment processing and POS terminal management directly into native and hybrid mobile applications. It provides native frameworks for iOS and Android, allowing you to build fast, reliable, and scalable in-person payment experiences.

The SDK is designed for flexibility and performance, supporting secure transactions, terminal connectivity, and merchant operations within a unified solution. It enables Independent Software Vendors (ISVs) to embed payment capabilities into mobile apps while maintaining full control over user experience and business workflows.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Dependencies](#dependencies)
- [Quickstart](#quickstart)
- [Releases](#releases)
- [Documentation](#documentation)
- [Support](#support)

---

## Overview

The Deluxe Mobile SDK provides a comprehensive set of tools and services to simplify mobile payment integration. It combines payment processing, POS terminal connectivity, and merchant operations into a single platform, reducing development complexity while maintaining high performance and security standards.

---

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

**Best Practices:**
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
- iOS SDK built with Swift
- Android SDK built with Kotlin

---

## Requirements

### iOS
- iOS 13.0 or later
- Xcode 14 or later recommended
- Supported on iPhone 7 and newer

### Android
- Minimum SDK: API 24
- Target SDK: API 36
- Kotlin-based project recommended

---

## Installation

### iOS

1. Download the SDK package
2. Add the following frameworks to your project:
   - `PosSDK.xcframework`
   - `PaymentSDK.xcframework`
   - `ServiceSDK.xcframework`
   - `PaymentHostModule.xcframework`
   - `TapToPaySDK.xcframework`
3. Set deployment target to iOS 13 or later
4. Add frameworks under:
   - **Link Binary With Libraries**
   - **Embed Frameworks**

### Android

1. Copy AAR files into the `libs` directory
2. Configure your project to reference local dependencies
3. Sync your project

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

1. Configure the SDK environment (Validation or Production)
2. Initialize the SDK during application startup
3. Authenticate the merchant using client credentials
4. Connect to a supported POS terminal
5. Execute a transaction

For detailed integration steps, refer to the Implementation Guide.

---

## Releases

New versions of the SDK are distributed through the Deluxe Developer Portal.

Each release includes:
- Feature enhancements
- Bug fixes
- Performance improvements
- Updated documentation

Refer to the Developer Portal for the latest release notes and upgrade instructions.

---

## Documentation

The Deluxe Mobile SDK is fully documented on the Deluxe Developer Portal.

### Get Started
- Deluxe Connect | Developer Portal

### Implementation Guide
- Deluxe Connect | Developer Portal

These guides provide step-by-step instructions for installation, configuration, and integrating SDK capabilities including payments, terminal management, and merchant services.

---

## Support

For questions, onboarding, or technical assistance:

**Email:** isvinquiries@deluxe.com
