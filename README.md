# NetGuard (fork)

This is a personal fork of [M66B/NetGuard](https://github.com/M66B/NetGuard), a no-root Android firewall.

## What's different

### Temporary Allow

Adds the ability to temporarily allow an app through the firewall for a fixed duration without permanently changing its rules.

- A timer icon appears next to any app that is currently blocked on mobile
- Tap it to open a dialog and pick a duration: 10 min, 30 min, 1 h, 12 h, or 24 h
- While the timer is active, the icon shows the remaining time and turns green
- When the timer expires the app goes back to being blocked automatically
- Applies to mobile/other connections only (not Wi-Fi)

## Installing

Download the APK from the [Releases](https://github.com/zarurc/NetGuard/releases) page, enable "Install from unknown sources" on your phone, and install.
