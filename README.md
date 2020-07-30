# QR scanner task

Trafi decided to make it easier for the users to rent a micromobility vehicles (such as bikes and kick-scooters). Our users should not be bothered with picking the right vehicle provider upfront and then using the camera to scan the QR. To make it easier we need you to implement a universal scanner feature.

## Goal

Write the logic for the QR scanner flow for an iOS app using Trafi's [state pattern](https://github.com/trafi/states).

Your goal is to write correct and robust logic that correctly handles both the happy case and any errors. We will not be evaluating your UI or design chops.

Our designer has provided the following designs.

| QR code scanner | Manual code entry |
|:--:|:--:|
![](sample/scanner.png)    |  ![](sample/entry.png)

- We don't expect you to write UI code;
- We don't expect you to write networking code;
- We don't expect you to create VC transitions;

## Requirements

- Be sure to send scanned data and handle happy/unhappy paths' responses;
- The application should direct user to vehicle if code is recognized by the backend;
- If the user scans unknown vehicle we should show the error about unrecognized vehicle provider (alert is fine) and offer user to perform manual entry and provider selection;
- QR content can contain plain numbers/characters and complete URLs;
- Swift 5+
- iOS 12+ support
- iPhone
