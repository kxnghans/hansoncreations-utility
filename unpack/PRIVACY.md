# Privacy Policy for Unpack

**Effective Date: May 14, 2026**  
**Last Updated: August 17, 2026**

This policy explains how Unpack protects your personal data, travel itineraries, and sensitive documents.

## 1. Tiered Zero-Knowledge Document Architecture
Unpack separates your data into strict security tiers:
- **Tier 1 — Sensitive Identification (Local-Only)**: Passports, visas, driver's licenses, and health records are encrypted (AES-256) and saved exclusively in local hardware-backed device storage (`expo-file-system` / `expo-secure-store`). **Tier 1 documents never leave your device and are never uploaded to our servers.**
- **Tier 2 — Travel Bookings & Tickets (Optional Cloud Sync)**: Flight boarding passes, hotel reservations, and activity tickets are synced to a private, encrypted storage bucket on Supabase only for authenticated Pro accounts requesting multi-device backup. These files are protected with Row Level Security (RLS) accessible only by your user account.

## 2. On-Device Packing & Financial Storage
Your packing inventories, custom item weights, credit card benefit tracking configurations, and personal expense logs are processed and stored locally on your device in SQLite.

## 3. Cloud Services & Third Parties
- **Supabase**: Powers user authentication, trip sync for Pro subscribers, community itinerary discovery, and user-submitted bug telemetry.
- **No Third-Party Ad Trackers**: We do not sell your personal data, nor do we embed commercial ad networks or third-party behavioral trackers.

## 4. AI Travel Concierge
When you use AI prompts or voice inputs to build itineraries, only trip context (destination, dates, interests) is sent to our inference functions to generate recommendations. Sensitive IDs, passports, and credit card numbers are never sent to AI models.

## 5. Security & Biometrics
You can enable biometric protection (Face ID / Touch ID) in the app settings to lock access to your document vault and financial cards.

## 6. Contact
For questions regarding this privacy policy, contact us at [hansoncreations.com](https://hansoncreations.com).


