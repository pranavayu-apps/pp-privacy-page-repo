# Privacy Policy — PoornaPrana

**Effective Date:** November 4, 2025

This Privacy Policy describes how PoornaPrana ("we," "us," or "our") collects, uses, and discloses information when you use our mobile application (the "App").

## 1. Information We Collect

We collect certain usage data to understand how our App is used and to improve your experience. This data is collected through PostHog, our analytics provider. The types of usage data we collect include:

- **App Interactions:** Information about how you interact with the App, such as when the app is opened, screens viewed, exercises started, completed, or created, and attempts to generate exercises using AI.
- **Anonymized Identifiers:** We generate an anonymized Universally Unique Identifier (UUID) for each user. This `userId` is used as a `distinct_id` for analytics events and is sent to our backend API via an `x-user-id` header. This identifier is not linked to any Personally Identifiable Information (PII).

**We do NOT collect any Personally Identifiable Information (PII)** such as your name, email address, phone number, or precise location data.

## 2. How We Use Your Information

We use the information we collect for the following purposes:

- **App Improvement:** To analyze user behavior and preferences to enhance the functionality, features, and overall user experience of the App.
- **Performance Monitoring:** To monitor the performance and stability of the App and identify areas for optimization.
- **Internal Analytics:** For internal research and development to better understand our user base and improve our services.

## 3. Disclosure of Your Information

We do not sell, trade, or otherwise transfer your anonymized usage data to outside parties, except as described below:

- **Third-Party Service Providers:** We use PostHog as our analytics service provider. Your anonymized usage data is shared with PostHog to facilitate our analytics activities. PostHog events are tagged with `platform: 'backend'` and `user_id` for consistent tracking.
- **Legal Requirements:** We may disclose your information if required to do so by law or in response to valid requests by public authorities (e.g., a court order or government agency).

## 4. Your Choices and Opt-Out

The App includes an opt-out toggle that allows you to disable the collection of analytics data. If you choose to opt-out, no usage data will be collected from your device. This setting persists across app sessions.

## 5. Data Security

We implement reasonable security measures to protect the anonymized usage data we collect. These measures include:

- **Anonymization:** All user identifiers are anonymized UUIDs and are not linked to PII.
- **Production Environment Settings:** In the production environment, session recording is disabled, and PostHog events are explicitly tagged with `environment = production` to ensure data consistency and privacy.

## 6. Permissions

The App does not request or use sensitive permissions such as `android.permission.RECORD_AUDIO`. We have verified that our audio engine does not require this permission, and it has been removed from the application's manifest.

## 7. Changes to This Privacy Policy

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy on this page and updating the "Effective Date" at the top. You are advised to review this Privacy Policy periodically for any changes.

## 8. Contact Us

If you have any questions or concerns about this Privacy Policy or our data practices, please contact us via following options:

- Email (alias): pp@poornaprana.anonaddy.com  

Please note that when you contact us for support or inquiries, any personal information you voluntarily provide (such as your email address) will be used solely for the purpose of responding to your request and providing assistance. This information will not be used for marketing purposes or shared with third parties, except as necessary to resolve your inquiry or as required by law.