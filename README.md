# Privacy Policy for DotX : AZ Earbuds Control

**Effective Date:** November 19, 2026  
**Application ID:** `com.dotx.azcontrol`  
**Developer Contact:** lazyapp.support@gmail.com  

DotX : AZ Earbuds Control ("DotX", "the application", "we", "us") is an independent third-party companion utility designed for paired Bluetooth wireless earbuds.

---

## 1. 100% Offline & Local Architecture
- **Zero Internet Access:** DotX does not request, declare, or use the Android `INTERNET` permission (`android.permission.INTERNET`).
- **No Remote Sockets or Telemetry:** The application is architecturally incapable of opening HTTP/HTTPS connections, connecting to remote servers, or transmitting data over any computer network.
- **Zero Tracking SDKs:** DotX contains no third-party tracking, analytics, crash-reporting, or advertising software development kits (such as Firebase, Google Analytics, Adjust, AppsFlyer, or Sentry).

---

## 2. Zero Data Collection & Sharing
- **No Personal Data Collected:** We do not collect, process, log, or store your name, email, phone number, contacts, location, IP address, browsing activity, or device identifiers.
- **No Data Shared with Third Parties:** Because no data is collected or transmitted from the application, no user information is ever shared with, sold to, or accessible by third parties.

---

## 3. Bluetooth Permissions Usage
DotX requests the following Bluetooth permissions solely to discover and communicate with your hardware:
- `android.permission.BLUETOOTH_CONNECT` (Android 12+ / API 31+): Required to connect to paired earbuds over standard RFCOMM/SPP channels.
- `android.permission.BLUETOOTH_SCAN` (Android 12+ / API 31+): Configured strictly with `android:usesPermissionFlags="neverForLocation"`. DotX never uses Bluetooth scanning to derive, infer, or track your physical geographic location.
- Legacy Bluetooth Permissions (`BLUETOOTH`, `BLUETOOTH_ADMIN`, `ACCESS_FINE_LOCATION` with `maxSdkVersion="30"`): Used exclusively on Android 10 and 11 to establish local Bluetooth connections in compliance with legacy Android OS requirements. Location information is never read, recorded, or transmitted.

---

## 4. Local Preferences Storage
All application preferences (such as custom 8-band Equalizer curves, Active Noise Cancellation levels, and visual Glyph themes) are stored exclusively on your device within private, sandbox-protected Android storage (`SharedPreferences`). This data never leaves your device and is automatically removed if you uninstall the application.

---

## 5. Google Play Data Safety Compliance
In accordance with Google Play's Data Safety standards, DotX certifies:
- **Data Collected:** None.
- **Data Shared:** None.
- **Data Encryption in Transit:** Not applicable (no network traffic occurs).
- **Data Deletion Mechanism:** All data is local; clearing app storage or uninstalling the app deletes all local preferences immediately.

---

## 6. Trademarks & Legal Disclaimer
DotX : AZ Earbuds Control is an independent third-party companion utility. It is not affiliated with, endorsed by, or sponsored by Panasonic Holdings Corporation, Technics, or Nothing Technology Limited. All product names, trademarks, and registered trademarks belong to their respective owners.

---

## 7. Contact & Support
For any technical inquiries, feedback, or privacy-related questions regarding DotX : AZ Earbuds Control, please contact us directly by email:  
**lazyapp.support@gmail.com**
