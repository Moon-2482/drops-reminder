# Drops Reminder 💧

An **offline-first Android medicine-drops reminder app** — built for people who must never miss a dose.

## Features

- ⏰ Reliable dose reminders that work fully offline
- 📞 **Call-aware alarms** — no alarm ever rings during a phone call; the full reminder fires after the call ends, after your chosen gap
- ✅ A dose stays **pending** until you confirm it — nothing silently disappears
- 🔕 No extra permissions beyond what a reminder app genuinely needs
- 🔄 **Self-updating** — the app checks `version.json` in this repo on startup and offers one-tap updates

## Install

Download the latest APK from the [**Releases**](https://github.com/Moon-2482/drops-reminder/releases) page and install it on any Android phone. No account, no internet required.

## Tech

Kotlin · Android · MVVM · fully offline (no backend, no tracking)

## Update channel

- `version.json` — latest `versionCode`, APK URL and changelog, checked by the app on startup
- Tagged releases carry the signed APKs

## License

MIT — see [LICENSE](LICENSE).
