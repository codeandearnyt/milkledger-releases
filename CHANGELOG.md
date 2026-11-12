# Changelog

All installable builds of MilkLedger. Each entry links to the release that carries the APKs.

## v1.0.0 — 10 November 2026

First public build.

**User app**
- Morning and evening milk entries with quick-pick litre chips
- Rate per litre or per ½ litre, with a rate history that keeps past dates intact
- Multiple sellers with a single combined bill
- Month calendar, day ledger and month summary
- PDF report for one seller or all sellers
- WhatsApp summary with the PDF attached
- Plus plans: monthly, quarterly, half-yearly, yearly — paid by UPI with proof upload
- Optional ads-free experience; launch popup on the 1st, 10th and 30th open
- Light and dark themes, notification reminder

**Admin app**
- Overview with users, active Plus, pending requests and revenue
- Payment queue with proof preview, approve and reject
- User detail with plan, expiry, last seen, app version, device and ad control
- Activity log for every admin action
- Config for pricing, ads and the launch popup

**Fixed before this build**
- Corrupted characters (`—`, `₹`, `·`, `→`, `½`, `…`) on all screens
- Buttons no longer shrink to their label — every primary action is full width
- Scrolling kept at 60 fps on low-end phones: no backdrop blur, no double card shadows, no per-frame fade layers
- Admin stat labels no longer truncate; payment filters wrap on narrow screens

**Downloads in this release**
- `MilkLedger.apk` — 83.7 MB — SHA-256 `9FDB0736FFE779CB4470E691E00C256D43060C54A5BE8D97D49BA6D413DB8EF2`
- `MilkLedger-Admin.apk` — 56.6 MB — SHA-256 `562C7F43664E0A9EE358873A0635E52F833F061623E4039A1E622C56EBDB9240`
