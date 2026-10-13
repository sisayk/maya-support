# Privacy Policy — Maya Ethiopian Calendar

**Last updated: 13 October 2026**

Maya Ethiopian Calendar ("the app") is made by Sisay Kelka. This policy explains what the
app does with your information. In short: **it collects nothing about you.**

---

## What the app does not do

- It does **not** collect any personal information.
- It does **not** read your location — not your device's, not your network's.
- It does **not** have accounts, sign-in, or user profiles.
- It does **not** use analytics, crash reporting, or advertising SDKs of any kind.
- It does **not** track you across apps or websites.
- It does **not** sell or share anything, because it has nothing to sell or share.

---

## What is stored on your Mac

The app saves your own preferences — interface language, time zone, whether the desktop
widget is on, and where you placed it. These live in the app's standard preferences on your
own Mac. They are never transmitted anywhere, and deleting the app removes them.

---

## The one network request

The desktop widget shows the current weather **in Addis Ababa**. To do that, the app makes
one HTTPS request to [Open-Meteo](https://open-meteo.com), a free public weather service,
roughly every 15 minutes.

That request contains only:

- the coordinates **9.03 N, 38.74 E** — built into the app, not read from your device
- the request for current weather

It does **not** contain your location, your IP-derived location, any device identifier, any
advertising identifier, any account, or any cookie. The app sets no cookies.

If the request fails — no internet, or the service is unreachable — the widget simply shows
no weather. It never invents a value.

You can verify this yourself: the app's network entitlement allows only outgoing
connections, and Open-Meteo is the only host it contacts.

---

## Location

The app has **no location permission** and never asks for one. The Addis Ababa coordinates
are fixed in the app's code, which is why it works without knowing where you are.

---

## Children

The app is suitable for all ages and collects no data from anyone, including children.

---

## Your rights

Because the app collects no personal data, there is nothing to access, correct, export or
delete. If you believe otherwise, please contact me and I will look into it.

---

## Changes

If this policy ever changes, the updated version will be posted at this address with a new
date. The app's behaviour would have to change first, and any change that introduces data
collection would be described here before it shipped.

---

## Contact

Questions about this policy: **sisaykelka@gmail.com**

Or open an issue: https://github.com/sisayk/maya-support/issues
