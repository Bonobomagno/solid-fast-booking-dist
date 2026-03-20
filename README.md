# Agora Fast Booking

Tampermonkey userscript for bulk desk booking on [Agora](https://agora.fastweb.it/).

**Current version:** v4.3.3

## Install

1. Install [Tampermonkey](https://www.tampermonkey.net/) in your browser
2. [Click here to install the userscript](https://raw.githubusercontent.com/Bonobomagno/solid-fast-booking-dist/main/solid-fast-booking.user.js) — Tampermonkey will prompt automatically
3. Navigate to https://agora.fastweb.it/ — the "Fast Booking" tab appears on the right

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

## Updating

Updates are **automatic** — Tampermonkey checks for new versions periodically.
To force an update: Tampermonkey Dashboard → Agora Fast Booking → check for update.
