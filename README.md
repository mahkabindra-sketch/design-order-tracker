# Design Order Tracker

A simple web app to manage design client orders — order entry, status pipeline, advance & balance tracking, and payment records.

**Live app (GitHub Pages):** https://mahkabindra-sketch.github.io/design-order-tracker/

## Features
- Add orders: client name, phone, service, total price (Rs.), advance paid, deadline, notes
- Status pipeline: New → In Progress → Revision → Delivered → Completed (+ Cancelled)
- Record payments anytime — remaining balance and % paid update automatically
- Totals at a glance: collected vs. still to collect, active orders, overdue warnings
- Search by client / phone / service, filter by status, "Unpaid only" view
- Backup & restore: download your data as a JSON file and restore it on any device

## How it works
Open `index.html` in a browser (or use the live link above). No server, no sign-up — all data is saved in your own browser (localStorage), so use the **Backup** buttons to keep a copy of your orders.

## Note
This is the standalone GitHub version of the Design Order Tracker. Orders saved here stay in the browser you used; they do not sync with the Muse app version.
