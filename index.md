---
title: Pawprint Privacy Policy
---

# Pawprint — Privacy Policy

**Effective date:** 10 November 2026
**Last updated:** 10 November 2026

Pawprint ("the app") is a pet-walking app that turns your walks into territory on a
personal map. This policy explains what the app does with your information.

The short version: **your walks stay on your phone.** Pawprint has no account
system, no server of its own, and no cloud sync. Your GPS route, your claimed
territory, your pet's name, and your streak are stored only in the app's local
database on your device. They are never uploaded to us, because there is nowhere
to upload them to.

---

## 1. Who is responsible

Pawprint is published by Canberk Özcelik, an independent developer based in
Türkiye.

Contact for any privacy question or request: **app.pawprint@yahoo.com**

## 2. What the app collects, and where it goes

### 2.1 Location data — stays on your device

While a walk is running, the app records your device's GPS position (latitude,
longitude, accuracy, speed, timestamp) roughly every few seconds. This is what
draws your route and works out which area you enclosed.

- Location is recorded **only during a walk you started yourself.** There is no
  background or always-on tracking. The app never records your location when no
  walk is active.
- Pawprint requests **"While Using the App"** location permission only. It never
  requests "Always" permission. On iOS the background-location capability is used
  solely to keep an already-running walk recording when your screen locks.
- Recorded positions, the resulting claimed map areas, and your walk history are
  written to a database stored **on your device only.**
- **Your location is never transmitted to us or to any third party.** No route,
  no coordinate, and no map area ever leaves your phone.

### 2.2 Information you enter

- **Pet name** — optional, used only to personalise text in the app. Stored on
  your device.
- **Settings** — daily-reminder on/off and time, your analytics choice, and your
  age-gate confirmation. Stored on your device.
- **Streak and walk statistics** — calculated on your device from your own walks.

### 2.3 Optional analytics and crash reports — off by default

During first-run setup the app asks whether you want to share anonymous usage and
crash data. **The answer is "no" unless you actively turn it on**, and you can
change it at any time in Settings → "Anonymous analytics & crashes".

If — and only if — you turn this on, the app enables Google Firebase Analytics and
Firebase Crashlytics. Until then their data collection stays switched off entirely,
so nothing is gathered in the background while you are undecided. Turning the
setting back off stops collection again.

When enabled, the app sends aggregate product events. The complete list is:

| Event | What it contains |
|---|---|
| `onboarding_completed` | whether you consented to analytics; whether you set a pet name |
| `walk_started` | no parameters |
| `walk_completed` | walk duration in seconds, distance in metres, number of map cells claimed, whether the app was backgrounded |
| `walk_abandoned` | no parameters |
| `gps_warning` | the reason GPS points were rejected, and for how many seconds |
| `streak_changed` | your streak count, and whether it rose or reset |
| `reminder_toggled` | whether the reminder is on or off |
| `consent_changed` | whether analytics is on or off |
| `data_deleted` | no parameters |

**No coordinates, routes, map areas, or pet names are included in any event.**
Distance and duration are totals only — they cannot be used to reconstruct where
you walked.

Crash reports, when enabled, contain technical diagnostics about a failure:
the error and stack trace, device model, OS version, and app version.

Firebase also assigns a random app-instance identifier and collects standard
device/session technical data while collection is enabled. Google acts as our
processor for this. See Google's privacy information at
<https://firebase.google.com/support/privacy>.

### 2.4 Map tiles

Map imagery is served by **MapTiler** (MapTiler AG, Switzerland; tiles served from
EU infrastructure). To draw the map, your device requests the map squares it needs
directly from MapTiler. Those requests necessarily include the **map tile
coordinates being viewed** and, as with any internet request, your device's **IP
address**.

This means MapTiler can infer the general area of the map you are looking at. It
does **not** receive your GPS position, your recorded route, or your claimed
territory — only which part of the world map your screen is showing. Requests
carry no identifier for you, and previously fetched tiles are cached on your device
so repeat views often need no request at all.

MapTiler's privacy policy: <https://www.maptiler.com/privacy-policy/>
Underlying map data © OpenStreetMap contributors.

### 2.5 Notifications

The app can show a persistent notification during a walk and, if you enable it, a
daily walk reminder. These are **local notifications generated on your device.**
No push service is used and no notification content leaves your phone.

## 3. What Pawprint does not do

- No account, sign-up, login, or email collection.
- No cloud sync or remote backup of your walks.
- No advertising, ad networks, or ad identifiers.
- No selling or sharing of personal information with anyone.
- No social, multiplayer, or shared-territory features — your map is yours alone
  and is not visible to any other person.
- No tracking across other apps or websites.

## 4. How long data is kept

Walk data stays on your device until you delete it. Because it is stored in the
app's own local storage, **deleting the app removes it entirely.**

You can also erase everything from inside the app at any time:
**Settings → Delete all data**, which permanently wipes your walks, claimed areas,
and preferences from the device. This cannot be undone.

If you enabled analytics, event and crash data already sent to Firebase is retained
by Google under their standard retention settings. Turning the setting off stops
any further collection; to request deletion of data already sent, contact us at the
address in section 1.

## 5. Your rights

Depending on where you live, you may have rights over your personal data — for
example under the EU/UK **GDPR**, Türkiye's **KVKK**, or the **CCPA** in
California. These typically include the right to access, correct, delete, or export
your data, to object to or restrict processing, and to withdraw consent.

In practice, Pawprint gives you direct control over almost all of this without
needing to ask us:

- **Access and export** — your data is on your device.
- **Deletion** — Settings → Delete all data, or delete the app.
- **Withdraw consent** — Settings → turn off "Anonymous analytics & crashes".
- **Location** — revoke the app's location permission in your device settings at
  any time. Walks simply stop recording.

For anything the app cannot do for you — such as a request concerning analytics
data already sent to Firebase — contact us at the address in section 1. We will
respond within 30 days. You also have the right to complain to your local data
protection authority.

The legal basis for processing, where GDPR applies, is: **consent** for analytics
and crash reporting, and **performance of the service you requested** (drawing your
route and map) for on-device location processing.

## 6. Children

Pawprint is not intended for children under 13, and the app asks you to confirm you
are 13 or older before it can be used. We do not knowingly collect personal
information from children under 13. If you believe a child has provided
information, contact us and we will address it.

## 7. Security

Your walk data is held in your device's app-private storage, protected by your
device's own operating-system sandboxing and encryption. Network requests the app
makes (map tiles, and analytics if enabled) use HTTPS.

No system is perfectly secure, but because Pawprint stores nothing on a server,
there is no central database of user routes that could be breached.

## 8. Changes to this policy

If this policy changes materially, we will update the "Last updated" date above and
publish the revised policy at this address. Continued use of the app after a change
means you accept the updated policy.
