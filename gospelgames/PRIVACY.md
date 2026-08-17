# Privacy Policy for Gospel Games

**Effective Date: May 14, 2026**  
**Last Updated: August 17, 2026**

This policy outlines data practices for Gospel Games across mobile platforms.

## 1. Zero Personal Data Collection
Gospel Games does not collect Personally Identifiable Information (PII). Players can join multiplayer rooms anonymously without creating an account, linking social media profiles, or providing an email address.

## 2. Multiplayer Rooms & Ephemeral State
- **Game Rooms**: When you host or join a room, temporary game state (scores, player nicknames, selected answers) is synchronized across participants via Firebase Realtime Database and Firestore.
- **Session Cleanup**: Multiplayer room sessions and ephemeral presence data are automatically deleted after games conclude or become inactive.

## 3. Local Storage & Audio Caching
Game assets, customized player avatars, and neural audio pronunciation files are cached locally on your device via secure native storage (`MMKV` / local cache) to reduce network usage and enable offline play.

## 4. Third-Party Services
- **Firebase (Google Cloud)**: Provides anonymous authentication, real-time database synchronization, and cloud storage for game media assets.
- **Supabase**: Handles anonymous error telemetry and user-submitted bug reports.
- **No Advertising Trackers**: We do not include third-party advertising SDKs, behavioral analytics scripts, or commercial data brokers.

## 5. Children's Privacy
Gospel Games is intended for general audiences, families, and youth groups. We do not knowingly collect personal information from children under 13.

## 6. Contact
For questions regarding this policy, visit [hansoncreations.com](https://hansoncreations.com).


