# Tern for Android — releases

Public on purpose: the Tern app on the phone reads `latest.json` here
(`https://raw.githubusercontent.com/RCDOK/tern-android/main/latest.json`) to update itself (OTA), then downloads the
APK next to it and checks its SHA-256. Only built files live here; the source is in the Tern project.

Install the first time: download the newest `tern-android-<version>.apk` on the phone and open it (allow
"Install unknown apps" for the browser or Files). After that, Tern shows **Install** when a newer version is here.
