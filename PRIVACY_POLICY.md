# Privacy Policy for Snakes & Wildlife - Rescue BD (সাপ ও বন্যপ্রাণী - রেসকিউ বিডি)

**Effective Date:** May 25, 2026  
**Last Updated:** September 3, 2026  

The **"Snakes & Wildlife - Rescue BD"** (সাপ ও বন্যপ্রাণী - রেসকিউ বিডি) mobile application (hereafter referred to as the "App") is developed and maintained by the **Snakes & Wildlife - Rescue BD Team** (hereafter referred to as "we", "us", "our", or "Developer"). We are deeply committed to protecting your privacy and ensuring the security of the personal information of our general users, community members, volunteers, and registered rescuers.

This Privacy Policy explains how we collect, use, store, process, share, and protect your information when you download, install, access, or use our App, and outlines your rights in relation to your data in strict compliance with Google Play Developer Policies and global privacy regulations (GDPR / CCPA).

---

## 1. About the App & Services

The App serves as Bangladesh's foremost digital emergency response and educational platform for snakebite mitigation, wildlife conservation, and emergency rescue assistance:
1. **Emergency Medical & Rescue:** Comprehensive snakebite first-aid guides, verified antivenom hospital directory with 530+ government facilities, emergency forest department directory, and verified 64-district wildlife rescuer contacts.
2. **Community & Discussion Hub:** Interactive social network allowing users to share snake/wildlife sightings, ask for species identification from verified rescuers, exchange wildlife knowledge, and comment/like posts.
3. **AI Species Recognition & Scanner:** Instant snake species and toxicity recognition powered by AI camera analysis.
4. **Rescuer Emergency Network & SOS:** Area-wise emergency SOS alerts connecting victims and callers directly to nearby verified rescuers.
5. **Snakebite Death Registry (জাতীয় মৃত্যু নিবন্ধন):** Reliable national memorial database documenting field-level snakebite mortality for policy advocacy and antivenom distribution.
6. **Educational Reward Hub & Quiz:** Interactive learning modules and quizzes rewarding users with Snake Coins for wildlife awareness and knowledge building.

---

## 2. Information We Collect and Process

### A. General App Users (Anonymous Browsing)
If you use the App solely to read educational guides, lookup first aid, check hospital antivenom directories, or search snake species:
* **No Mandatory Sign-Up:** You do not need to register or provide any personal information.
* **Anonymous Browsing:** All offline lookups and guide browsing are 100% anonymous.
* **AI Image Scanner:** When using the AI Snake Scanner, images captured or selected from your gallery are sent securely in real-time to AI servers for herpetological classification. This process is stateless, contains no personal identifiers, and images are not permanently retained.

### B. Community Members & Registered Users (Google Sign-In)
When you log in to participate in the community, share posts, comment, or earn reward coins:
1. **Profile Data:**
   * **Display Name:** Used to identify your posts, comments, and leaderboard ranking.
   * **Unique Username (`@username`):** A customized public handle of your choice.
   * **District Location:** Used to contextualize rescue/sighting reports and filter local emergency alerts.
   * **Profile Avatar:** Google profile photo URL or default avatar.
2. **Email Privacy Protection (Gmail Hidden):**
   * Your raw Gmail/email address is used **strictly for secure Firebase Authentication and account recovery**.
   * **Your email address is NEVER displayed, shared, or made visible to any other community user, in posts, comments, or public profile cards.**
3. **User-Generated Content (UGC):**
   * Captions, photos of snakes/wildlife, location tags, comments, likes, and species identification tags. Photos are securely stored on Cloudflare R2 / Firebase Storage.
4. **Push Notification Tokens (FCM):**
   * Secure, system-generated Firebase Cloud Messaging (FCM) device tokens are stored to deliver post replies, likes, species identification notifications, and critical emergency SOS broadcasts.
5. **Snake Coins & Reward Hub Activity:**
   * Quiz participation, educational booster streaks, points earned, and reward history are securely tracked in our Cloudflare database.

### C. Registered Rescuers (Volunteers)
* **Public Rescuer Profile:** Full Name, District/Upazila, and Mobile Phone Number are displayed in the verified Rescuer Directory so citizens in distress can initiate direct phone calls for rapid emergency snake removal.
* **Rescue Logs:** Date, location, species, rescue status (released, treatment, etc.), and verification photos.

### D. Snakebite Death Registry (Memorial Data)
* To ensure transparent statistics for national healthcare advocacy, verified rescuers report deceased victim records (name, age, gender, district, incident date, and snake species).
* **Family Phone Numbers and Sensitive Death Certificates are strictly encrypted and NEVER displayed publicly.**

### E. Direct Admin Feedback & Bug Reports
* When submitting feedback or reporting issues directly to the administration, your verified Google account email, message, and category are securely recorded in our private administration database to enable direct developer follow-up. Phone numbers are purely optional. Feedback messages remain strictly private and are never shared publicly or displayed to other community members.

---

## 3. Device Permissions We Request

We request only the minimum runtime permissions necessary to deliver core features:
1. **Internet Access (`android.permission.INTERNET`):** Required for cloud synchronization, community feed, AI scanner, push alerts, and map assets.
2. **Phone Call Permission (`android.permission.CALL_PHONE`):** Allows users to directly dial verified rescuers or hospital emergency numbers with a single tap during emergencies.
3. **Camera & Photo Storage (`CAMERA`, `READ_MEDIA_IMAGES`):** Required only when you choose to take a photo for AI snake scanning, upload community posts, or add rescue documentation.
4. **Notifications (`POST_NOTIFICATIONS`):** Required on Android 13+ to receive critical emergency SOS alerts, rescuer responses, and community interactions. Permissions can be revoked anytime in your device settings.
5. **Location (Coarse/Fine):** Optional; used exclusively to locate nearest antivenom hospitals, calculate distance, and route local emergency rescue alerts. We do NOT track background location.

---

## 4. Third-Party Services & SDKs

We partner exclusively with trusted, industry-standard infrastructure providers:
* **Google Firebase (Auth, Firestore, Cloud Messaging, Analytics):** Secure user authentication, real-time sync, push notifications, and crash diagnostics.
* **Cloudflare (Workers, D1, R2):** Fast, global edge computing, community database, and secure media storage.
* **Google Gemini AI:** Herpetological image classification.
* **Google Mobile Ads (AdMob):** Displays banner, interstitial, and native ads to support free public safety operations. AdMob may process anonymous device identifiers (AAID) in accordance with Google's Privacy Policy.
* **Meta Audience Network:** Backup advertising network adhering to Meta privacy standards.

---

## 5. Data Sharing & Disclosure

* **No Sale of Data:** We **NEVER** sell, rent, monetize, or trade your personal data to any data brokers or commercial third parties.
* **Public Information:** Only your chosen display name, `@username`, district, and your public posts/comments are visible to other community members.
* **Legal Compliance:** We may disclose data only if legally required by law enforcement or competent judicial authorities in Bangladesh to protect human life.

---

## 6. User Data Rights & Account Deletion (Google Play Compliance)

We provide full transparency and control over your personal data in strict compliance with Google Play Store User Data & Account Deletion policies:

### In-App Instant Self-Service Deletion:
1. **Direct In-App Deletion:** Go to **Profile Menu ➔ Settings (প্রোফাইল মেনু ও সেটিংস) ➔ অ্যাকাউন্ট স্থায়ীভাবে অপসারণ (Delete Account)**.
2. **Security Verification Guard:** Type the word **`DELETE`** in uppercase inside the confirmation prompt to eliminate accidental triggers.
3. **Immediate Permanent Erasure:** All personal profile records, login mappings, community posts, comments, likes, earned Snake Coins, and FCM push tokens are instantaneously and irreversibly deleted from Cloudflare D1 and Firebase Authentication.

### Assisted / Web Deletion Request:
If you no longer have the app installed or require manual deletion, you can request immediate manual account deletion by emailing **snakeappbd@gmail.com** or messaging developer support on WhatsApp at **+8801560017292**. Requests are fulfilled within 24 to 48 hours.

---

## 7. Children’s Privacy

Our App is intended for a general audience. The educational and safety material is appropriate for all ages, including children under the age of 13.
* **No Child Data Collection:** We do not knowingly collect personal information from children under the age of 13. Since general users are not required to log in or register, no PII is requested from children browsing the guides.
* **Rescuer Registrations:** Only verified, trained adult volunteers are authorized to be registered as rescuers. We do not permit registration or login accounts for anyone under the age of 18.

---

## 8. Policy Updates

We may update our Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy inside this App and updating the "Last Updated" date at the top of this document. You are advised to review this Privacy Policy periodically for any changes.

---

## 9. Contact Us

If you have any questions, feedback, concerns, or requests regarding this Privacy Policy or your personal data, please contact us directly:
* **Developer Support:** Arefin Nabil / Snakes & Wildlife - Rescue BD Team
* **WhatsApp Contact:** **+8801560017292** (https://wa.me/8801560017292)
* **Support Email:** **snakeappbd@gmail.com** (or direct WhatsApp contact for immediate assistance)
