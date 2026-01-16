# Ad-Bs-Converter (Android Library For Nepali Date Conversion)

A lightweight Android library to convert and handle ad / bs data efficiently, designed for easy integration and minimal setup.

[![](https://jitpack.io/v/MENT0Z/Ad-Bs-Converter.svg)](https://jitpack.io/#MENT0Z/Ad-Bs-Converter)
![Android](https://img.shields.io/badge/Android-21%2B-green)
![Kotlin](https://img.shields.io/badge/Kotlin-Yes-blue)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## ✨ Features
- Simple, plug-and-play Android library
- Lightweight and fast
- No UI dependency
- Works with both local AAR and JitPack
- Kotlin-first API

---

## 📦 Installation


Add JitPack repository in your **`settings.gradle.kts`**:

```kotlin
dependencyResolutionManagement {
    repositories {
        google()
        mavenCentral()
        maven(url = "https://jitpack.io")
    }
}
```
Add the dependency:
```
dependencies {
    implementation("com.github.MENT0Z:Ad-Bs-Converter:v1.0.0")
}
```

## 🚀 Sample Usage
```kotlin
import com.mruraza.adbsconverter.adToBs
import com.mruraza.adbsconverter.bsToAd

// here date is YYYY-MM--DD or YYYY/MM/DD in BS
bsToAd(date)

// Converts an AD timestamp, provided as a Long in milliseconds, to BS format and returns Object (day: Int, month: String, year: Int)
adToBs(timeMillis)
```

## 🛠 Requirements
- Android SDK 21+
- Kotlin
- Android Gradle Plugin 8.5+
- compileSdk = 36
- minSdk = 28
- agp >= 8.9.1

