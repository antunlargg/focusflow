# FocusFlow

FocusFlow is a privacy-focused, offline-first Android application designed to eliminate distractions and help you maintain deep focus. By automatically toggling system states and managing app activity based on your active usage, FocusFlow provides a seamless way to regain control over your attention.

## Key Features

- **Automatic Do Not Disturb**: FocusFlow automatically activates Do Not Disturb (DND) mode when you open any of your configured, protected applications.
- **Distraction Suspension via Shizuku**: Integrates with Shizuku to force-stop background apps, preventing background syncs and notifications from interrupting your focus.
- **100% Private and Local**: All app configurations and monitored data remain strictly on your device. FocusFlow does not transmit any personal data or usage metrics.
- **Multi-language Support**: Includes localization for English, Czech, Spanish, German, and Portuguese, selectable via an adaptive picker on first launch.
- **Modern Jetpack Compose UI**: Features a beautiful, responsive, and accessible Material Design 3 interface styled with proper contrast and spacing guidelines.

## Requirements

- **Android 7.0 (API level 24) or higher**
- **Accessibility Service Permission**: Required to detect when a protected foreground application is opened.
- **Do Not Disturb Access**: Required to automatically toggle notification filters.
- **Shizuku (Optional)**: Required for advanced background application force-stopping capabilities.