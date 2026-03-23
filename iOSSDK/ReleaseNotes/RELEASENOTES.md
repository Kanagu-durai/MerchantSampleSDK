# SDK Release Notes

## Version 2.1.0 – July 11, 2025

#### New Features
- **Apple Tap to Pay License Support**  
    
    Added support to check the Tap to Pay merchant license status. The SDK now returns whether the merchant has already accepted the license agreement or not. 
    

## Version 2.2.0 – July 21, 2025

#### Enhancement
**Introduced a new terminal status indicating that the terminal is busy** when a TaptoPay initialization is already in progress.  


## Version 3.0.0 – August 07, 2025

#### Logger
**This release introduces a new logging mechanism to the SDK, enabling improved log handling and better visibility into SDK operations.**



#### Cancel Transaction Enhancement
**Added support for cancelling transactions at more stages.**



#### Bug Fix
**Resolved minor issues in taptopay transactions to improve stability and reliability.**



## Version 3.0.1 – November 28, 2025

#### New Feature
- **Apple Tap to Pay – Relink Support**  
Added support for Apple TaptoPay Relink, enabling a seamless reconnection flow when a device needs to be re-authenticated.



## Version 3.0.2 – December 03, 2025

####  Bug Fix
**Resolved minor issue in Ingenico device disconnect**


## Version 3.0.3 – December 16, 2025

#### Bug Fix
**Additional fields have been added to the transaction response**


## Version 3.0.4 – February 17, 2026

#### Enhancement
**Introduced a new terminal status to indicate that the Tap to Pay terms and conditions were declined when the user disagree or dismisses the Tap to Pay terms and conditions sheet.**


## Version 3.0.5 – February 25, 2026

#### Enhancement
**Introduces a built-in TaptoPay tutorial to guide merchants on accepting contactless payments using iPhone.**


## Version 4.0.0 – September 09, 2025

#### Transaction History Enhancement
**This release introduces performance improvements to the Transaction History, enabling faster loading when accessing past transactions.**


#### New UAT Environment Added
**A new UAT environment has been introduced to support end-to-end testing.**


## Version 4.1.0 – September 19, 2025

#### Surcharge Support
**This release adds support for applying surcharges during transactions.**


## Version 4.2.0 – September 24, 2025

#### Enhanced Transaction Details
**Transaction Details now returns additional EMV field values in the response.**


## Version 4.2.1 – October 24, 2025

#### Enhanced TaptoPay Logger
**Enhanced logging during Tap to Pay initialization**


## Version 4.2.2 – October 31, 2025

#### Introduced configurable logging levels for improved debugging.
   Added a new LoggerLevel with two modes:  
      .minimal – Logs only key events and high-level details.
      .detailed – Logs complete request and response data for in-depth debugging.



