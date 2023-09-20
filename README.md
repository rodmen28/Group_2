# Group_5

Software Requirement Specification (SRS) for Mobile Banking App
1. Introduction
  -1.1 Purpose
    -The purpose of this document is to define the requirements for the development of a mobile banking application, referred to as "MobileBank,".

-1.2 Scope
  -The MobileBank app will offer a range of banking services, including balance checking, fund transfers, bill payments, ATM location services, and      account management. It will be available on iOS and Android.

-1.3 Document Organization
  -This document is organized into sections that go over user requirements, functional requirements, non-functional requirements, and additional         information.

2. User Requirements

-2.1 User Types
  The MobileBank app will cater to the following user types:
    -Registered Users: Customers who have registered and verified their accounts.
    -Guest Users: Users who can access limited features without registration.

-2.2 User Authentication
 	-2.2.1 Registration
    -Description: Users can register by providing personal information, verifying their identity, and creating a secure login.
    -Functional Requirements: User data collection, identity verification process, password creation.
  -2.2.2 Login
    -Description: Registered users can log in using a username and password or biometric authentication (fingerprint or facial recognition).
    -Functional Requirements: Secure authentication mechanisms, and password reset functionality.

-2.3 Account Management
  -2.3.1 View Account Balance
    -Description: Users can view their account balances, including checking, savings, and credit card accounts.
    -Functional Requirements: Real-time balance updates, transaction history.
  -2.3.2 Fund Transfers
    -Description: Users can transfer funds between their own accounts or to other bank accounts.
    -Functional Requirements: Secure transfer protocols, recipient verification, and transaction history.

3. Functional Requirements

-3.1 Transaction Processing
  -3.1.1 Bill Payments
    -Description: Users can pay bills for utilities, credit cards, loans, and other services.
    -Functional Requirements: Integration with biller systems, payment scheduling, payment history.
  -3.1.2 Mobile Check Deposit
    -Description: Users can deposit checks by capturing images of the checks using their mobile device's camera.
    -Functional Requirements: Check image processing, and deposit confirmation.

-3.2 Alerts and Notifications
  -3.2.1 Account Alerts
    -Description: Users can set up account alerts for low balances, large transactions, or specific account activities.
    -Functional Requirements: Alert configuration, delivery via push notifications or email.
	
4. Non-functional Requirements

-4.1 Security
  -4.1.1 Data Encryption
    -Description: All sensitive user data, including transactions and personal information, must be encrypted during transmission and storage.
    -Requirements: Use of SSL/TLS for data in transit, encryption at rest.
  -4.1.2 Authentication and Authorization
    -Description: The app must implement strong user authentication and authorization mechanisms to prevent unauthorized access.
    -Requirements: Multi-factor authentication, role-based access control.

-4.2 Performance
  -4.2.1 Response Time
    -Description: The app should respond to user actions (e.g., balance inquiries, fund transfers) within 2 seconds.
    -Requirements: Load testing to ensure responsiveness.




5. Other

-5.1 Expected Changes
  -The app should support future changes and updates to banking regulations and security standards.

-5.2 Glossary
  -Mobile Check Deposit: A feature allowing users to deposit checks by capturing check images using their mobile device.
  -Bill Payments: The ability to pay bills for various services and utilities through the app.

-5.3 Potential Risks
  -Data breaches and security vulnerabilities.
  -Compatibility issues with different mobile devices and OS versions.

-5.4 Timeline
  -The development timeline is expected to span 12 months, including testing and deployment.
