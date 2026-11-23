# FF ESPORTS ARENA — Android starter project

This is a **starter UI prototype** for an admin-controlled Free Fire tournament manager.

## Included
- Dark esports admin dashboard
- Tournament list and create dialog (Solo/Duo/Squad)
- Player list
- UPI payment review screen with manual demo approval
- Default settings: ₹50 entry, ₹25 per kill, ₹150 Booyah

## Important limitations
This starter uses in-memory demo data. It does **not** yet include:
- Real admin authentication or secure admin-only authorization
- Cloud database / player registration API
- Uploading and viewing actual payment screenshots
- A configured UPI QR code or live payment verification
- Play Store signing / publishing

Do not collect real player payments or run a paid tournament using this demo until secure backend, privacy controls, payment reconciliation and applicable game/platform/legal requirements are implemented.

## Open and run
1. Install Android Studio (current stable) and Android SDK 35.
2. Open this folder in Android Studio.
3. Let Gradle sync complete.
4. Run on an Android device or emulator.

## Before real release
1. Add your UPI ID and QR image (never hard-code secret keys).
2. Add Firebase Authentication with a single authorized admin account and server-side role checks.
3. Add Firestore collections for tournaments, players, registrations and payment reviews.
4. Store payment screenshots in private Cloud Storage with access rules.
5. Verify payment references against your bank/UPI statement; a screenshot alone is not proof of payment.
6. Add audit logs, backups, privacy policy, support contact and secure release signing.

Package: `com.ffesports.arena`
