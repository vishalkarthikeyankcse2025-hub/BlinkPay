# BlinkPay

**BlinkPay** is a Java-based Android application that combines digital payments and communication into a unified platform. Its key feature is an offline NFC-based payment workflow that enables payment communication between compatible Android devices without requiring an active internet connection.

The project was developed as part of the Project-Based Learning (PBL) component of the Java Programming course at Chennai Institute of Technology.

## Features

- Offline NFC-based payment communication
- Digital wallet and balance management
- Send and receive payments
- Transaction history
- Google Sign-In
- Four-digit Blink PIN authentication
- Biometric authentication
- Online payment processing
- Cloud synchronization
- Real-time text messaging
- Voice messages
- File sharing
- Push notifications
- User profile and account management

## How BlinkPay Works

### Offline Payment

The offline payment workflow uses NFC communication between two compatible Android devices.

```text
Sender
   |
   v
Enter Payment Amount
   |
   v
Validate Amount & Wallet Balance
   |
   v
PIN / Biometric Authentication
   |
   v
NFC Communication
   |
   v
Receiver
   |
   v
Transaction Completed
