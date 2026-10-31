# SMT Medical Delivery for Android

**Latest version: 1.1.6 (build 13).**

[Download the public SMT Android APK](https://github.com/Mafuleka-Khethelo/smt-medical-delivery-downloads/releases/latest/download/SMT-Medical-Delivery.apk)

Driver applications enter Admin review only after every required field and all three document photos are submitted. Interrupted uploads remain retryable and never receive a false success confirmation. Driver registration is open. Deliveries have not launched. Drivers can register, upload or replace documents, receive review updates and contact support. Approved drivers wait for launch before receiving delivery jobs. Driver wallets remain under maintenance.

Open the download on your Android phone and open the APK to install. If Android asks, allow installation from your browser. Keep your existing SMT app installed and choose Update. Expo Go and a development server are not required. Android 7.0 or newer is supported. The universal APK is approximately 108 MB and supports multiple Android processor types.

## Public sites

- [Patient and driver app](https://app.smtmedtech.co.za)
- [Clinic portal](https://clinic.smtmedtech.co.za/login)
- [Admin portal](https://admin.smtmedtech.co.za/login)

## Separate delivery testing

[Download SMT Test APK](https://github.com/Mafuleka-Khethelo/smt-medical-delivery-downloads/releases/download/v1.1.6-build13/SMT-Test.apk)

SMT Test is for designated testers. It installs beside the public app with a different Android ID and uses separate accounts, database and storage. Test deliveries do not reach public drivers or change their registrations. Use fictional details and document photos. Test accounts and passwords are provided privately, never in this repository.

- [Testing app](https://smt-app-testing.vercel.app)
- [Testing Clinic portal](https://smt-clinic-testing.vercel.app/login)
- [Testing Admin portal](https://smt-admin-testing.vercel.app/login)

The testing checkout includes an explicit no-payment delivery option. It does not charge money or post earnings. Provider payment tests require sandbox credentials. Testing emails are labelled and limited to designated addresses; test SMS is disabled until testing numbers are configured.

## Release verification

[Release details and checksums](https://github.com/Mafuleka-Khethelo/smt-medical-delivery-downloads/releases/tag/v1.1.6-build13)

Both APKs use the SMT release signing certificate and were checked on an Android emulator. Their full public downloads were verified against the local signed files.

Public APK SHA-256: `6dfbe88878f252e2e56f10609612e6784378725aa457e4690734dcedcdf8be5c`

SMT Test APK SHA-256: `534b843e37b7264b0e224204f411a8dc3dd1a88104cf59943e94a68d5a7092d0`

Application IDs: public `za.co.smtmedical.delivery`; testing `za.co.smtmedical.delivery.test`.

Application source is maintained separately. This repository publishes only Android releases and download instructions.
