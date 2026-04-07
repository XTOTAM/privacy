# Privacy Policy — GetOut

**Last updated:** April 7, 2026

This Privacy Policy describes how the mobile application **GetOut** (“App”, “we”) processes information on iOS devices. The data controller is the owner of the App and the corresponding legal entity listed in the App Store (the “Operator”). For data-related inquiries, please use the contact information provided at the end of this document.

---

## 1. General Provisions

By using the App, you agree to this Privacy Policy. If you do not agree, please do not use the App or restrict the relevant permissions in your iOS settings.

The App is designed to provide a gaming experience involving movement, maps, and QR code scanning (as described in the App Store).

---

## 2. Data We May Process

### 2.1. Location and Movement

- **Location data** (coordinates, accuracy, and potentially background location) when you grant “While Using” and/or “Always” permissions.
- Purpose: map display, gameplay mechanics (e.g., zones, scans, “fog of war”), and saving progress locally on the device.

Background location tracking is enabled only with appropriate system permissions and App logic.

---

### 2.2. Camera

- **Camera images** are used for **QR code scanning** within the App when you grant camera access.
- Typically, images are not transmitted to our servers unless explicitly stated in App updates.

---

### 2.3. Photo Library

- Access may be used to **save game-related images or QR codes** to your photo library when you grant permission and use the relevant feature.

---

### 2.4. Account and Game Progress Data (Local)

- User profile data (e.g., **nickname**, **character gender** selected by you), game metrics, activity history, and map/scan data may be stored **locally** on your device (including via the **Realm** local database).
- Some features may be prepared for backend synchronization in the future; at the time of this document, core game profile data may be created and stored **locally**. Please refer to the App Store and updates for the latest information.

---

### 2.5. Device Identifiers and Advertising

- **Google Mobile Ads (AdMob)** may collect and use identifiers (such as **IDFA**, depending on your Apple tracking settings), ad impressions, and interaction data in accordance with Google policies.
- The App may display **App Open ads** and other formats supported by the integrated SDK.

---

### 2.6. Maps and Places Search

- **Google Maps SDK**: map rendering and related requests may be sent to Google infrastructure in accordance with Google Maps Platform Terms and Google Privacy Policy.
- **Apple MapKit**: location and search requests may be processed by Apple in accordance with Apple’s privacy policies.

---

### 2.7. Notifications

- If you enable notifications, the App may use **local/scheduled notifications** (e.g., gameplay reminders), without necessarily transmitting content to the Operator’s servers.

---

### 2.8. Technical Data and Logs

- **Technical logs** may be generated on the device (e.g., via logging subsystems) for debugging during development/testing.
- Some legacy keys may remain in **Info.plist**; actual SDK usage is determined by the Xcode build configuration and dependency managers (Podfile / Swift Package Manager).
- Third-party libraries may include: **Google Maps**, **Google Mobile Ads SDK**, **Realm**, **MBProgressHUD**, **CocoaLumberjack**.

---

### 2.9. Third-Party Links

- The App may open **external links** in browsers or other apps (e.g., social media profiles). These services operate under their own privacy policies.

---

## 3. Purpose of Processing

- Providing core gameplay features (maps, location, QR scanning, progress tracking)
- Displaying personalized or non-personalized advertising (depending on user settings and region)
- Improving App stability and security
- Complying with legal obligations

---

## 4. Legal Basis (EEA/UK Users)

Where applicable, processing is based on:
- Performance of a contract (providing the App)
- Consent (iOS permissions, advertising/tracking where required)
- Legitimate interests (security, limited analytics)
- Legal obligations

---

## 5. Sharing with Third Parties

Data may be processed by integrated service providers, including:

| Category         | Provider / Service     | Notes                                      |
|------------------|----------------------|--------------------------------------------|
| Maps             | Google (Maps)        | Governed by Google policies                |
| Advertising      | Google (AdMob)       | Governed by Google and partners            |
| Map Search       | Apple (MapKit)       | Governed by Apple policies                 |
| Local Storage    | Realm (on device)    | Data stored locally                        |

The Operator does **not sell personal data** in the sense of selling contact lists or personal datasets.

---

## 6. Data Retention

- Game data is primarily stored **on the device** until you delete the App or manually remove data.
- Data processed by **Google** or **Apple** is retained according to their policies.
- When you delete the App, local data is typically removed, unless included in backups (e.g., iCloud backups depending on your settings).

---

## 7. Security

The Operator applies reasonable technical and organizational measures to protect data. However, no mobile application can guarantee absolute security. Users are responsible for securing their devices (e.g., passcode, Face ID, OS updates).

---

## 8. Your Rights

Depending on your jurisdiction, you may have the right to:

- Access, correct, or delete data
- Restrict or object to processing
- Data portability (where applicable)
- Withdraw consent (without affecting prior lawful processing)
- Lodge a complaint with a supervisory authority

Some rights can be exercised via iOS settings:  
**Settings → Privacy** (Location, Camera, Photos, Tracking) or by deleting the App.

---

## 9. Children

The App is not intended to knowingly collect data from children under 13 (or other age as defined by local law). If you believe a child has provided data, please contact the Operator for removal.

---

## 10. International Transfers

Use of Google and other providers may involve processing data outside your country of residence, subject to applicable safeguards (e.g., Standard Contractual Clauses or adequacy decisions, depending on regulations and provider practices).

---

## 11. Changes to This Policy

The Operator may update this Privacy Policy. The “Last updated” date will be revised accordingly. Significant changes may also be communicated via App Store updates or within the App.

---

## 12. Contact

**Operator (based on project metadata):** Andrii Rohalia, © 2023  

**Privacy contact email:** _[please insert your contact email]_  

**Public Privacy Policy URL (required for App Store):** _[insert URL where this policy is hosted]_  

---

### Note for App Store Submission

Apple typically requires a **publicly accessible Privacy Policy URL**. You can host this document on your website or GitHub Pages and provide the link in App Store Connect. It is recommended to have the policy reviewed for compliance with your jurisdiction and actual data practices.

---

*This document is based on the GetOut iOS app structure. Update relevant sections if backend services or new SDKs are introduced.*
