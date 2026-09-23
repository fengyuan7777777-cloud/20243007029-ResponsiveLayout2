# 20243007029-ResponsiveLayout2

Practical 2 for Mobile Computing and Network Architecture. This project builds on the ConstraintLayout implementation from Practical 1 and adds alternative layouts for different device configurations.

## Current baseline

- The original Practical 1 layout is located at `app/src/main/res/layout/activity_main.xml`.
- The interface is written manually in XML.
- Responsive dimensions use constraints, `0dp`, `dp`, and `sp` rather than pixel dimensions.

Alternative landscape and tablet layouts will be added in subsequent development stages.

## Build

Open the repository root in Android Studio, allow Gradle sync to finish, and run the `app` configuration.

From PowerShell, a debug build can also be produced with:

```text
.\gradlew.bat :app:assembleDebug
```
