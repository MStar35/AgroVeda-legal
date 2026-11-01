# Privacy Policy for AgroVeda 

**Last Updated:** November 1, 2026  
**Governing Regulation:** Indian Digital Personal Data Protection Act (DPDP Act, 2023) & Google Play Developer Policy  
**Live Legal Hub:** [https://mstar35.github.io/AgroVeda-legal/](https://mstar35.github.io/AgroVeda-legal/)  

---

## 1. Introduction

Welcome to **AgroVeda** (referred to as "we", "us", or "our"). We are dedicated to empowering Indian farmers with smart farming technology, real-time APMC mandi prices, hyper-local weather alerts, AI-driven crop disease diagnostics, and farmer-to-farmer community networking while honoring and safeguarding user privacy.

This Privacy Policy explains how we collect, use, store, process, and safeguard your personal and agricultural data when you install and use the AgroVeda mobile application.

> **Farmer Privacy Promise:** We do not sell, rent, monetize, or trade your personal or agricultural data to any commercial advertisers, third-party brokers, or marketing entities.

---

## 2. Information We Collect

To deliver relevant agricultural advisory services, we collect the following types of information:

### A. Account & Profile Data
- **Mobile Phone Number:** Used for secure login and account recovery via SMS One-Time Password (OTP) powered by Firebase Phone Authentication.
- **Farmer Name & Location:** Name, village name, district, and state to personalize advisories and fetch local mandi market prices.
- **Farm Profile:** Total landholding in acres/vigha, primary irrigation method (drip, sprinkler, flood, borewell, canal, rain-fed), and crop list.

### B. Crop Records & Farm Notebook
- **Active Crops:** Crop names, variety, sowing dates, and growth stages entered to receive timely spray and fertilizer recommendations.
- **Crop Health Photos:** Photos of plants, leaves, and crops submitted for automated pest and disease diagnosis.

### C. Voice & Microphone Audio
- **Voice Inquiries:** Temporary audio recordings captured when you use speech-to-text queries in Gujarati, Hindi, or English to consult the AI farm assistant. Audio files are not permanently stored or shared.

### D. Device Location Data
- **GPS Coordinates (Coarse & Fine Location):** Collected only when you grant permission to provide accurate, hyper-local weather forecasts (rain timing, temperature, wind) and show nearby APMC mandi commodity prices and farm service providers. Background location is not tracked.

### E. Technical & Diagnostic Information
- Mobile device model, operating system version, anonymous app installation IDs, network status, and crash logs collected via Google Firebase to troubleshoot errors and enhance stability.

---

## 3. Permissions Requested and Purpose

| Permission | Android Identifier | Purpose |
| :--- | :--- | :--- |
| **Internet Access** | `INTERNET`, `ACCESS_NETWORK_STATE` | Fetch live mandi prices, satellite weather, and synchronize records. |
| **Location** | `ACCESS_COARSE_LOCATION`, `ACCESS_FINE_LOCATION` | Deliver local weather warnings and display nearest mandi prices. |
| **Camera & Photos** | `CAMERA`, `READ_MEDIA_IMAGES` | Capture leaf/crop photos for AI disease detection & profile picture. |
| **Microphone** | `RECORD_AUDIO` | Hands-free regional voice queries to the AI agricultural advisor. |
| **Notifications** | `POST_NOTIFICATIONS` | Send severe weather alerts, irrigation reminders, and community replies. |
| **Boot Completed** | `RECEIVE_BOOT_COMPLETED` | Restore scheduled crop care and vaccine reminders after device reboot. |

---

## 4. How We Use Collected Information

- Delivering personalized crop lifecycle guidance, fertilizer bag calculations, and spray dosages.
- Running computer vision machine learning models to detect agricultural pests and plant pathologies.
- Displaying real-time market rates from nearby APMC mandis.
- Sending proactive notifications regarding impending rainfall, temperature fluctuations, or pest outbreaks.
- Enabling farmer interactions in the community forum.
- Detecting bugs and crash diagnostics to maintain high app performance.

---

## 5. Third-Party Service Providers & SDKs

We work with trusted industry SDK providers adhering to strict security protocols:

1. **Google Firebase Authentication:** SMS OTP generation and secure farmer sign-in.
2. **Google Cloud Firestore & Realtime Database:** Encrypted cloud storage for community posts and news articles.
3. **Firebase Crashlytics & Analytics:** Real-time crash diagnostics and aggregate anonymous usage metrics.
4. **Google AdMob:** Displaying family-friendly advertisements to keep the app free for farmers.
5. **Open-Meteo API:** Satellite and weather model forecasts (coordinates sent without personal identifying details).

---

## 6. Data Storage & Security Measures

- **Encryption in Transit:** All network communication is strictly encrypted via HTTPS / TLS 1.3.
- **Cloud Security:** Backend records are hosted on ISO 27001 and SOC 2 certified Google Cloud data centers.
- **Local Storage:** Farm notes, crop calendars, and calculators are stored securely on your device using a local SQLite database (Drift).

---

## 7. Data Retention & Account Deletion (Google Play Compliance)

You maintain full control over your data:

- **Profile Modification:** Update your name, village, land size, and crop choices in the app at any time under `Profile > Edit Profile`.
- **Permanent Account Deletion:** You have the right to request permanent deletion of your account and all associated data.
  - To request account and data deletion, email **lbyello35@gmail.com** with the subject:  
    `"Account Deletion Request - [Your Registered Phone Number]"`.
  - All personal profile information, crop entries, and forum posts will be purged permanently from our active production systems within 7 business days.

---

## 8. Children's Privacy

AgroVeda is designed for adult farmers and agricultural workers. We do not knowingly solicit or collect data from individuals under 13 years of age (or under 18 years in India). If we learn that personal data of a minor has been collected without parental consent, we will promptly delete it.

---

## 9. Agricultural Advisory Disclaimer

- All AI disease detection results, pesticide dose calculations, and crop recommendations are provided on an **advisory basis**.
- Natural agricultural outcomes depend on variable local field conditions (soil moisture, seed vitality, pest mutations, weather swings).
- Always cross-verify chemical recommendations with certified local agronomists, Krishi Vigyan Kendras (KVK), or government agricultural extension officers.

---

## 10. Grievance Officer & Contact Details

For inquiries, privacy complaints, or data deletion requests under the Indian Information Technology Act, 2000 and DPDP Act, 2023, please reach out to:

- **Support & Grievance Desk:** AgroVeda Support Team
- **Email:** [lbyello35@gmail.com](mailto:lbyello35@gmail.com)
- **Application:** AgroVeda
- **Jurisdiction:** Gujarat, India
