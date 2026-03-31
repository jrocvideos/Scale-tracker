# Scale Tracker

A web-based inventory management system for tracking fishing scales lent to the companies that calibrate the scales as well as commercial fishing vessels

Built to replace manual Excel logs at a commercial fishing operation. Office and or Dock staff check scales out to vessels at ice-up, track return dates, and get flagged on overdue equipment.

**Live app:** https://scale-tracker-alpha.vercel.app

---

## What it does

- Check scales in and out to specific vessels by serial number
- Tracks which vessel has which scale and when it's due back
- Flags overdue returns on the dashboard
- Supports multiple scale models (Porta Weigh, Ocean King D6, Island Scales)
- Vessel registry with ice and scale requirements per boat
- Export data as JSON backup
- Mobile-first — designed for iPad/tablet use on the dock

## Stack

- **Frontend:** React, TypeScript, Tailwind CSS
- **Hosting:** Vercel
- **Storage:** Local storage (no login required, export/import for backup)

## Screenshots

<img width="228" height="66" alt="Screen Shot 2026-03-30 at 4 55 07 PM" src="https://github.com/user-attachments/assets/0c9cbb4a-bf18-4944-b6f5-76955ed5b743" />
<img width="1440" height="813" alt="Screen Shot 2026-03-30 at 4 55 14 PM" src="https://github.com/user-attachments/assets/e8c39351-19b2-4c67-aefc-e0eae1189484" />
<img width="1440" height="791" alt="Screen Shot 2026-03-30 at 4 55 31 PM" src="https://github.com/user-attachments/assets/79df2849-e24e-4153-8378-e3529a58758c" />
<img width="1440" height="701" alt="Screen Shot 2026-03-30 at 4 55 43 PM" src="https://github.com/user-attachments/assets/cc2e8932-9ee1-49f7-b07a-1d8760bf80f8" />

## Background

This was built for a real dock operation where scales worth thousands of dollars per unit were being lost or forgotten on Scale companies that were calibrating them or servicing them and vessels after fishing season. The previous system was a shared Excel file that was updated manually. Took a while to do and the labour rate was high on that.

The app is used by the office or dock personnel during vessel ice-up — when boats come in to load ice before heading out to fish herring. Each scale gets checked out to a vessel with a return date, and the dashboard shows at a glance what's overdue.

## Running locally

```bash
git clone https://github.com/jrocvideos/Scale-tracker
cd Scale-tracker
npm install
npm run dev
```

## Author

Built by J Y — self-taught full-stack developer
GitHub: https://github.com/jrocvideos
