# Z-Anatomy (Android Edition)

Open-source 3D human anatomy atlas optimized for Android.

## 📱 Download Android APK

You can directly download and install the latest compiled APK on your Android device:

👉 **[Download ZAnatomy.apk (v1.0.0)](https://github.com/MAROON7doc/Z-Anatomy-BEDA-version/releases/download/v1.0.0-android/ZAnatomy.apk)** (166.5 MB)

Or view the [v1.0.0-android Release Page](https://github.com/MAROON7doc/Z-Anatomy-BEDA-version/releases/tag/v1.0.0-android).

---

## 🚀 One-Click Build & Install

If you are cloning this repository to build from source:

### 1. Build APK
```powershell
.\build_android.ps1
```

### 2. Install to Connected Android Device
```powershell
.\install_to_device.ps1
```

---

## ✨ Features & Fixes in this Release
- **Full 3D Anatomy Models**: Restored all high-resolution FBX models (~120 MB) across skeletal, muscular, vascular, nervous, and organ systems.
- **TextMeshPro Mobile Optimization**: Fixed distorted text and triangle artifacts (`▲▲▲▲`) by migrating to `TMP_SDF-Mobile` shaders and setting dynamic Canvas shader channels (`UV1`, `Normal`, `Tangent`).
- **Camera Auto-Focus & Scaling**: Auto-centers and scales the camera directly onto the 3D model upon app launch.
- **Instant Model Visibility**: Ensures 3D anatomy is visible on startup.
- **Smooth Touch Navigation**: Touch orbit, two-finger pan, and pinch zoom.

