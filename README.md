# SMT Medical Delivery for Android

**Latest version: 1.1.9 (build 16).**

[Download SMT Medical Delivery APK](https://github.com/Mafuleka-Khethelo/smt-medical-delivery-downloads/releases/latest/download/SMT-Medical-Delivery.apk)

One email and password can hold Patient, Driver and authorised staff roles. Existing patients can apply as drivers using their current SMT password. People with both mobile profiles can switch from Profile or their driver review screen. Adding a role preserves the existing account and history. Staff access requires an Admin invitation; clinic access requires a clinic invitation.

Public signup remains for drivers only. New patient registration opens at delivery launch. Drivers must complete every required field and upload all three document photos before Admin review. Independent document acceptance and application approval are required. Public deliveries have not launched and public wallets remain under maintenance.

Download on your Android phone and open the APK. Allow installation from your browser if Android asks. Keep the existing app installed and choose **Update**. Expo Go and a development server are not required. Supports Android 7.0 or newer. The universal APK is approximately 108 MB.

## Public sites

- [Patient and driver app](https://app.smtmedtech.co.za)
- [Clinic portal](https://clinic.smtmedtech.co.za/login)
- [Admin portal](https://admin.smtmedtech.co.za/login)

## Separate delivery testing

[Download SMT Test 1.1.9 (build 16)](https://github.com/Mafuleka-Khethelo/smt-medical-delivery-downloads/releases/download/v1.1.9-build16/SMT-Test.apk)

For designated testers only. Includes shared-email profiles and the compact wallet showing actual testing ledger balances and history. Payouts remain paused. Installs alongside the public app using separate accounts, database and storage. Test deliveries do not reach public drivers. Use fictional details and document photos. Testing credentials are shared privately.

- [Testing app](https://smt-app-testing.vercel.app)
- [Testing Clinic portal](https://smt-clinic-testing.vercel.app/login)
- [Testing Admin portal](https://smt-admin-testing.vercel.app/login)

Testing checkout includes a no-payment delivery option that does not charge money or post earnings. Provider tests require sandbox credentials. Testing email recipients are restricted; test SMS remains disabled.

## Release verification

[Release details and checksums](https://github.com/Mafuleka-Khethelo/smt-medical-delivery-downloads/releases/tag/v1.1.9-build16)

Both APKs use the existing SMT signing certificate and passed emulator checks. Anonymous downloads were verified against the complete signed files.

Public APK SHA-256: `efd2501514dea34c673f98ba9189d4c8629860a71942fc37329e806ddd1bfa10`

SMT Test APK SHA-256: `651c6c18c1ef929e068cdaf0318f98ee236e04b10924e2dfd818c8f7f8d18a5d`

Application IDs: public `za.co.smtmedical.delivery`; testing `za.co.smtmedical.delivery.test`.

Application source remains in its separate private repository. This repository publishes only APKs, checksums and download instructions.
