# Maya Ethiopian Calendar — Support

Maya shows the Ethiopian (Geʽez) calendar alongside the Gregorian one, with holidays,
fasting seasons and the Ethiopian 12-hour clock. It runs in a window, in the menu bar, and
as a widget on the desktop.

**[Download on the Mac App Store](#)** <!-- replace # with the App Store link once live -->

---

## Getting help

Found a bug, or something not working as you expect? Please
[open an issue](https://github.com/sisayk/maya-support/issues) and include:

- what you did
- what you expected
- what happened instead
- your macOS version (Apple menu → About This Mac)

I read every report. For anything you would rather not post publicly, email
**sisaykelka@gmail.com**.

---

## Common questions

### The desktop widget isn't showing

Open the app, then **Settings → Widget** and switch it on. The widget is off by default.

Drag it anywhere on the desktop to move it; the position is remembered. If it ends up
somewhere awkward, use **Reset Widget Position** in the menu bar menu.

### The widget shows no weather

The widget shows the **real weather in Addis Ababa**, so it stays blank when the reading
can't be fetched — no internet, or Open-Meteo unreachable. It deliberately never invents a
condition. It also shows nothing if you haven't enabled the widget.

### The weather is wrong for where I live

That is intentional. The widget is fixed to Addis Ababa, so the app never needs to know
your location and never asks for permission.

### A holiday or fasting date looks wrong

Ethiopian holidays that follow the lunar calendar — ʿĪd al-Fiṭr, ʿĪd al-Aḍḥā — are
calculated, and can differ by a day from local announcements. Moveable feasts such as
Timkat and Fasika are derived from the Orthodox computus.

If a fixed date (Genna, Timkat, Adwa, Enkutatash) is wrong, please
[report it](https://github.com/sisayk/maya-support/issues) — those are exact and a mistake
there is a real bug.

### Does the app need my location?

No. Nothing is ever read from your device's location.

### What does the app send over the internet?

One request, roughly every 15 minutes: an HTTPS call to
[Open-Meteo](https://open-meteo.com) for the current Addis Ababa weather, so the widget can
show the real condition. The coordinates are built into the app.

No identifiers, no accounts, no cookies, no analytics, no advertising. Nothing about you is
sent or stored.

---

## Languages

English · አማርኛ · ትግርኛ · Afaan Oromoo, with optional Geʽez numerals.

---

## Privacy

Maya collects nothing. See the privacy section above.

---

## Credits

Calendar arithmetic follows the Ethiopian (Amete Mihret) reckoning, computed locally from
Julian Day Numbers. Weather data by [Open-Meteo](https://open-meteo.com).

---

*Maya Ethiopian Calendar is made by Sisay Kelka.*
