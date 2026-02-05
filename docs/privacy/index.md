# Privacy Policy for Mogu Exercise

**Last Updated: February 5, 2026**

## 1. Information We Collect

### 1.1 Camera Data
Mogu Exercise uses the device camera exclusively for Apple's ARKit face tracking technology. The camera captures real-time facial movements to detect chewing motions.

### 1.2 Health Data
The app collects and stores the following health-related data locally on your device:
- Chewing count per bite
- Meal session timing and duration
- Statistical data about your eating habits

### 1.3 In-App Purchase Data
The app offers in-app purchases and subscriptions through Apple's StoreKit 2:
- **Purchase Status**: Premium subscription status and entitlement are stored locally on your device as a boolean flag
- **Transaction Verification**: Purchase receipts are verified using Apple's StoreKit 2 framework (cryptographic verification on-device)
- **No Payment Information**: We do NOT collect, store, or have access to your credit card numbers, payment details, or purchase history
- **Apple's Role**: All payment processing is handled exclusively by Apple. We only receive a verification result that a purchase was successful

### 1.4 No Personal Information
We do NOT collect:
- Names, email addresses, or other personally identifiable information
- Account credentials or login information
- Location data
- Contacts or social media information
- Payment information (credit card numbers, billing details, etc.)

## 2. How We Use Information

### 2.1 Primary Purpose
All collected data is used exclusively for:
- Real-time chewing detection and counting
- Displaying statistics and graphs
- Tracking meal sessions
- Providing visual feedback during meals
- Unlocking premium features for subscribers

### 2.2 In-App Purchase Usage
Purchase data is used solely to:
- Verify your premium subscription status
- Unlock premium features within the app
- Restore previous purchases on the same device or re-installation
- Process subscription renewals

### 2.3 No Analytics or Advertising
- We do NOT use your data for analytics
- We do NOT use your data for advertising purposes
- We do NOT sell or share your data with third parties
- No third-party analytics or advertising SDKs are integrated

## 3. Data Storage & Security

### 3.1 Local Storage Only
- **All health data is stored locally on your device** using Apple's SwiftData framework
- Face mesh data is processed in real-time and is NOT saved
- Camera footage is never recorded or stored
- No health data is transmitted to external servers

### 3.1.1 In-App Purchase Data Storage
- Purchase status (premium/free) is stored locally on your device using UserDefaults
- Transaction verification is performed on-device using Apple's StoreKit 2 cryptographic receipts
- We do NOT store or process payment information on our servers
- All payment processing is handled by Apple's secure payment systems

### 3.2 Cloud Sync
The app does NOT currently support cloud synchronization or backup. All data remains on your device.

### 3.3 Data Security
- Data is protected by iOS device-level security
- No internet connection required for core functionality
- Face tracking data never leaves your device
- Payment transactions are secured by Apple's StoreKit 2 framework

## 4. Permissions

### 4.1 Camera Permission
**Required**: The app requires camera access to use ARKit for face tracking.

**Purpose**: To detect facial movements associated with chewing.

**What we DON'T do**:
- We do NOT record photos or videos
- We do NOT access your photo library
- We do NOT transmit camera feed to any server

### 4.2 Biometric Data
**Not Used**: The app does NOT use Face ID, Touch ID, or any biometric authentication.

### 4.3 Other Permissions
The app does NOT require access to:
- Location services
- Contacts
- Microphone
- Photo library
- Social media accounts

## 5. Data Retention & Deletion

### 5.1 Data Retention
- Chewing and meal session data is retained indefinitely on your device until you delete it
- Purchase status is retained until you uninstall the app or cancel your subscription
- No automatic data deletion or expiration

### 5.2 User Control
You have complete control over your data:
- Delete individual meal sessions within the app
- Delete all data through app settings
- Uninstalling the app completely removes all data
- Manage subscriptions through your Apple ID settings

### 5.3 Data Deletion Instructions
To delete all your data:
1. Open Mogu Exercise
2. Go to Settings
3. Select "Delete All Data"
4. Confirm deletion

Alternatively, uninstalling the app will permanently remove all stored data.

**Note**: Deleting the app does not cancel your subscription. You must cancel subscriptions through your Apple ID settings.

## 6. Children's Privacy

### 6.1 Age Appropriateness
- Mogu Exercise is suitable for users of all ages
- The app does NOT target children under 13 specifically
- No account registration or personal information is required

### 6.2 No Collection from Children
We do NOT knowingly collect personal information from children under 13. Since the app does not collect personal information and all data is stored locally, this is not applicable.

## 7. Third-Party Services

### 7.1 Apple Frameworks and Services
The app uses the following Apple frameworks:
- **ARKit**: For face tracking (all processing on-device)
- **SwiftData**: For local data storage
- **SwiftUI**: For user interface
- **Combine**: For reactive programming
- **StoreKit 2**: For in-app purchases and subscriptions

### 7.2 Apple's Payment Processing
- All purchases are processed through Apple's App Store payment system
- Apple handles payment collection, transaction security, and receipt verification
- We do NOT collect, store, or have access to your payment information
- Purchase receipts and transaction data are managed by Apple
- Subscription billing and renewals are managed by Apple

### 7.3 No Other Third-Party Services
We do NOT use:
- Third-party analytics services (e.g., Google Analytics, Firebase Analytics)
- Third-party advertising networks
- Third-party crash reporting services
- Third-party payment processors
- Social media integrations

## 8. Changes to Privacy Policy

### 8.1 Updates
We may update this privacy policy from time to time to reflect:
- Changes in our app functionality
- Changes in legal requirements
- Clarifications of our practices

### 8.2 Notification
Significant changes will be:
- Posted in the app
- Updated on this page with a new "Last Updated" date

### 8.3 Your Responsibility
We encourage you to review this privacy policy periodically. Continued use of the app after changes indicates acceptance of the new policy.

## 9. Data Export & Portability

### 9.1 Data Export
Currently, the app does NOT support data export functionality. All data is stored in Apple's SwiftData format and is accessible only within the app.

### 9.2 Future Enhancements
We may consider adding data export features in future updates, which would allow you to:
- Export your chewing statistics
- Backup your meal session data
- Transfer data to a new device

## 10. Legal Compliance

### 10.1 GDPR (Europe)
Under GDPR, you have the right to:
- Access your data (all data is in the app)
- Delete your data (through app settings or uninstallation)
- Data portability (not currently supported)
- Object to processing (you can stop using the app at any time)

### 10.2 CCPA (California)
Under CCPA:
- We do NOT sell personal information
- All data is stored locally on your device
- You can delete all data by uninstalling the app

### 10.3 Other Jurisdictions
We comply with applicable data protection laws in all jurisdictions where the app is available.

## 11. Security Measures

### 11.1 Technical Safeguards
- Data is protected by iOS sandbox security
- No network transmission of health or facial data
- No server-side storage vulnerability
- All payment processing uses Apple's encrypted payment systems

### 11.2 Purchase Security
- Payment transactions are secured by Apple's StoreKit 2 framework
- Transaction verification uses Apple's cryptographic receipt validation
- We do not store or process payment information on our servers

### 11.3 Best Practices
We follow iOS development best practices:
- Use of secure storage frameworks
- No hardcoded sensitive data
- Regular security reviews

## 12. Subscription Management

### 12.1 Managing Your Subscription
Subscriptions are managed through your Apple ID:
1. Open Settings on your iOS device
2. Tap your Apple ID at the top
3. Tap "Subscriptions"
4. Select "Mogu Exercise"
5. Cancel or modify your subscription

### 12.2 Auto-Renewal
- Subscriptions auto-renew unless cancelled at least 24 hours before the end of the current period
- Your account will be charged for renewal within 24 hours prior to the end of the current period
- You can manage or cancel auto-renewal at any time through your Apple ID settings

### 12.3 Refund Policy
All purchases and subscriptions are processed through Apple's App Store. Refund requests must be submitted to Apple Support:
- Report a Problem: https://reportaproblem.apple.com
- Apple Support: https://support.apple.com

## 13. Contact Information

### 13.1 Questions & Concerns
If you have questions, concerns, or requests regarding this privacy policy or our data practices:

**Email**: xiaotiantakumi@gmail.com

**App Name**: Mogu Exercise
**Developer**: Takumi Oda

### 13.2 Complaints
If you believe we have violated applicable privacy laws:
- Contact us directly at the email above
- You may also file a complaint with:
  - Your local data protection authority (EU)
  - The Federal Trade Commission (USA)
  - Appropriate regulatory body in your jurisdiction

## 14. Transparency & Accountability

### 14.1 Our Commitment
We are committed to:
- Transparency about our data practices
- Protecting your privacy
- Providing you control over your data
- Complying with applicable privacy laws

### 14.2 Privacy by Design
Mogu Exercise is built with privacy as a core principle:
- All health data processing happens on your device
- No account or personal information required
- No data sharing with third parties
- No advertising or analytics
- Payment processing handled exclusively by Apple

---

**Summary**: Mogu Exercise respects your privacy. All face tracking and health data is processed locally on your device. We never transmit or store your facial data on external servers. No personal information is collected. In-app purchases are processed securely through Apple's payment systems, and we do not have access to your payment information.

**Download Source**: This privacy policy is also available within the app in the Settings section.

---

© 2026 Takumi Oda. All rights reserved.
