---
layout: splash
title: "QR Scanner"
permalink: /qr-scanner/
---

QR Scanner is currently in beta testing but will be available through the Play Store soon.

QR Scanner is simply a QR scanning app for Android. It was created to offer a full
featured QR scanner app that requires the absolute minimum required device permissions.
Below is a summary of the implemented features along with the version in which they
were added.

# Application Features

| Feature | Implemented | Added In Version |
|:-------:|:-----------:|:----------------:|
| QR Scanning | &#10003; | v0.1.0 |

## Supported QR Code Types

| QR Code Type | Supported | Added In Version |
|:------------:|:---------:|:----------------:|
| URL Bookmark | &#10003; | v0.1.0 |
| WiFi | &#10003; | v0.1.0 |
| Address | &#10007; | |
| Calendar Date/Time | &#10007; | |
| Calendar Event | &#10007; | |
| Contact Info | &#10007; | |
| Driver License | &#10007; | |
| Email | &#10007; | |
| GeoPoint | &#10007; | |
| Person Name | &#10007; | |
| Phone Number | &#10007; | |
| SMS | &#10007; | |

# Required Device Access

The application requires access to the Camera and the WiFi state.

## Camera

Camera access is required so that the application can scan QR codes. The camera is only
used when you press the "Scan" button on the application's main screen.

## WiFi State

WiFi state access is required for attaching a mobile device to a WiFi network. This is
done only when a user explicitly presses the "Connect" button on the app's WiFi screen.

In Android version 10 or greater, the network name and password scanned from a QR code
can be added as a suggested WiFi network to the user. A notification will ask the user
if they want to join the network. 

Prior to Android version 10, an application can add a WiFi network and attach to it.
For users whose device runs Android 9 or lower, the application will automatically
attach to the network - after they have pressed the "Connect" button.

# Privacy Policy

See QR Scanner's [privacy policy](/qr-scanner/privacy-policy).
