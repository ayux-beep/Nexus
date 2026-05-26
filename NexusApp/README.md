# Nexus Chat App — Android APK

A modern chat app built with WebView + HTML/CSS/JS.

## 🚀 How to Get Your APK via GitHub Actions

### Step 1 — Upload to GitHub

1. Go to [github.com](https://github.com) → Sign in or create account
2. Click **"New Repository"**
3. Name it: `NexusApp`
4. Set to **Public**
5. Click **"Create repository"**
6. Upload ALL files from this zip — keep the folder structure exactly as is

### Step 2 — Trigger the Build

1. After uploading, go to your repo → click **"Actions"** tab
2. You'll see **"Build Nexus APK"** workflow
3. Click it → click **"Run workflow"** → click green **"Run workflow"** button
4. Wait ~3-5 minutes for it to complete ✅

### Step 3 — Download Your APK

1. Once the workflow shows ✅ green
2. Click on the workflow run
3. Scroll down to **"Artifacts"**
4. Download **NexusApp-debug** → extract → install the `.apk` on your phone!

## 📱 Installing on Android

1. On your phone go to **Settings → Security → Unknown Sources → Enable**
2. Transfer the APK to your phone
3. Tap the APK file → Install
4. Open **Nexus** 🎉

## 📁 Project Structure

```
NexusApp/
├── .github/
│   └── workflows/
│       └── build-apk.yml       ← GitHub Actions build script
├── app/
│   ├── build.gradle            ← App dependencies
│   └── src/main/
│       ├── AndroidManifest.xml
│       ├── assets/
│       │   └── index.html      ← YOUR NEXUS APP (the HTML file)
│       ├── java/com/nexus/app/
│       │   └── MainActivity.java
│       └── res/
│           ├── mipmap-*/       ← App icons
│           ├── values/
│           │   ├── strings.xml
│           │   └── styles.xml
│           └── xml/
│               └── file_paths.xml
├── gradle/wrapper/
│   └── gradle-wrapper.properties
├── build.gradle
├── settings.gradle
├── gradle.properties
└── gradlew
```

## ⚙️ Admin Panel

- Sign up with username: `admin`
- Tap the shield icon on Profile tab
- Password: `nexus2025`
