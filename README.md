# NetGuard

A personal fork of [M66B/NetGuard](https://github.com/M66B/NetGuard) — a no-root Android firewall — with extra features for fine-grained network control.

## Features

### Per-App Firewall
Block or allow any app's access to mobile data and Wi-Fi independently, with no root required.

### Temporary Allow
Lets you temporarily allow a blocked app through the firewall for a fixed duration without permanently changing its rules.

- A timer icon appears next to any app that is blocked on mobile
- Tap it to pick a duration: 10 min, 30 min, 1 h, 12 h, or 24 h
- While active the icon shows remaining time and turns green
- When the timer expires the app goes back to blocked automatically
- Applies to mobile/other connections only (not Wi-Fi)

### Traffic Log
Displays a detailed log of outgoing IP traffic per app — see exactly what your device is connecting to in real time. Can be exported.

### Network Filter
Block specific addresses per app while leaving the rest of its internet access intact. Useful for stopping apps from phoning home without fully blocking them.

### App Install Notifications
Get a notification whenever a new app is installed, with a direct option to allow or block it immediately.

## Installing

Download the APK from the [Releases](https://github.com/zarurc/NetGuard/releases) page, enable "Install from unknown sources" on your phone, and install.
