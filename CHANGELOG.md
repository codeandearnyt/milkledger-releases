# Changelog

Installable MilkLedger builds. Each entry links to the release that carries the APKs.

## v1.1.2 — 14 November 2026

Reports moves into More, and first-run setup now lands on Home.

**Navigation**
- Bottom bar is `Home · Ledger | + | Bill · More`, with the centre Add-milk button unchanged
- **Reports** is no longer a tab — open it from **More → Reports**
- Bill keeps its old slot, so nothing moves under your thumb

**First run**
- **Start** now saves the seller, phone number and today's rate, then goes straight to Home on the first tap
- Before, it saved but left you on the setup form until you reopened the app
- Start shows a spinner and *Setting up…*, then a check and *You're all set*

**Speed**
- The app asks Android for the fastest display mode the screen supports, so 90 Hz and 120 Hz phones run above 60 fps
- Tab and screen transitions are unchanged and stay at 60 fps or better

**Files in this release**

| File | Size | For |
| :-- | --: | :-- |
| `MilkLedger-1.1.2.apk` | 83.8 MB | Any phone (universal) |
| `MilkLedger-1.1.2-arm64-v8a.apk` | 39.8 MB | 64-bit phones |
| `MilkLedger-1.1.2-armeabi-v7a.apk` | 38.3 MB | 32-bit phones |
| `MilkLedger-1.1.2-x86_64.apk` | 41.4 MB | Emulators |

## v1.1.1 — 13 November 2026

Bill PDFs can now be saved or shared.

**PDF actions**
- **Generate PDF** builds the bill, then shows two buttons: **Download** and **Share**
- **Download** saves to `Download/MilkLedger/` with no dialog and no storage permission on Android 10+
- **Share** opens the normal Android share sheet
- Readable file names, e.g. `MilkLedger_ML-202611-001.pdf`

**Files in this release**

| File | Size | For |
| :-- | --: | :-- |
| `MilkLedger-1.1.1.apk` | 83.8 MB | Any phone (universal) |
| `MilkLedger-1.1.1-arm64-v8a.apk` | 39.8 MB | 64-bit phones |
| `MilkLedger-1.1.1-armeabi-v7a.apk` | 38.3 MB | 32-bit phones |
| `MilkLedger-1.1.1-x86_64.apk` | 41.4 MB | Emulators |

## v1.1.0 — 13 November 2026

Bill screen and read-only Reports.

**Bills**
- New **Bill** tab: `Home · Ledger · Bill | + | Reports · More`, with the centre Add-milk button unchanged
- **Sellers** pricing uses the rate saved with each entry, so old entries and bills never change
- **Manual** pricing recalculates the bill at one price (₹50–₹200 in ₹5 steps, or any typed amount)
- Period presets: This month, Last month, Custom
- Saved bills are frozen snapshots, included in backup, restore and wipe

**Reports**
- Read-only Bills and Entries previews, with the daily spend chart
- The Create PDF, WhatsApp summary and helper paragraph are gone

**Motion**
- Tabs slide horizontally and pushed screens slide in from the right, with reduced-motion support

**Files in this release**

| File | Size | For |
| :-- | --: | :-- |
| `MilkLedger-1.1.0.apk` | 83.8 MB | Any phone (universal) |
| `MilkLedger-1.1.0-arm64-v8a.apk` | 39.8 MB | 64-bit phones |
| `MilkLedger-1.1.0-armeabi-v7a.apk` | 38.3 MB | 32-bit phones |
| `MilkLedger-1.1.0-x86_64.apk` | 41.4 MB | Emulators |

## v1.0.0 — 10 November 2026

First public build.

**Daily work**
- Morning and evening milk entries in two taps, with quick-pick litre chips
- Rate per litre or per ½ litre, with a rate history that keeps past dates intact
- Multiple sellers with a single combined bill
- Month calendar, day ledger and month summary

**Reports and plans**
- PDF report for one seller or all sellers
- WhatsApp summary with the PDF attached
- Plus plans: monthly, quarterly, half-yearly, yearly — paid by UPI with proof upload
- Manual verification, usually within 4 hours
- Optional ads-free experience; launch popup on the 1st, 10th and 30th open
- Light and dark themes, daily reminder

**Fixed before this build**
- Corrupted characters (`—`, `₹`, `·`, `→`, `½`, `…`) on every screen
- Buttons no longer shrink to their label — primary actions are full width
- 60 fps scrolling on low-end phones: no backdrop blur, no double card shadows, no per-frame fade layers

**Files in this release**

| File | Size | For |
| :-- | --: | :-- |
| `MilkLedger.apk` | 83.7 MB | Any phone (universal) |
| `MilkLedger-arm64-v8a.apk` | 39.8 MB | 64-bit phones |
| `MilkLedger-armeabi-v7a.apk` | 38.2 MB | 32-bit phones |
| `MilkLedger-x86_64.apk` | 41.3 MB | Emulators |

SHA-256 for every file is listed in the release notes and in the README.
