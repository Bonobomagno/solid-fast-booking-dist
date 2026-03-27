---
layout: default
---

<p align="center">
  <img src="logo.png" alt="Agora Fast Booking" width="200">
</p>

# BOOXX

Tampermonkey userscript for bulk desk booking on [Agora](https://agora.fastweb.it/).

**Current version:** v4.6.3

---

## Supported Browsers

- Google Chrome
- Microsoft Edge
- Mozilla Firefox

## Installation

1. **Install Tampermonkey** for your browser:
   - [Chrome](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
   - [Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)
   - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
2. **Install the userscript** — [click here to install](https://raw.githubusercontent.com/Bonobomagno/solid-fast-booking-dist/main/solid-fast-booking.user.js)
3. **Enable user scripts** (Chrome/Edge only):
   - Go to the extensions page: paste `chrome://extensions` (or `edge://extensions`) in the address bar
   - Find **Tampermonkey** → click **Details**
   - Enable **"Consenti script utente"** (or **"Allow user scripts"** in English)
4. **Refresh** the browser tab (F5) or close and reopen it
5. Navigate to **[agora.fastweb.it](https://agora.fastweb.it/)** — the "Fast Booking" tab appears on the right

---

## How to Use

1. **Pick a floor** from the dropdown, or type a **seat** (e.g. `2-41-001`)
2. **Select days** on the calendar (click to toggle, shift-click for range)
3. Hit **Scan** — checks all floors for available seats
4. **Review the plan** — each row shows the best available seat:
   - Green: your preferred seat is free
   - Yellow: different seat, same area
   - Blue: you already have a booking
   - Red: no seats available
5. Use row buttons: **Skip**, **Rebook**, or **Cancel** individual days
6. Hit **Book All** to execute

---

## Updating

Updates are **automatic** — Tampermonkey checks for new versions periodically.

To force an update: Tampermonkey Dashboard → Agora Fast Booking → check for update.
