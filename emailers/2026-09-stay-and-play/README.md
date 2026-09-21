# Dwight School Dubai – Stay & Play / Whole School Open Morning emailer (Sept 2026)

HTML build of the "WSA Emailer Sept26" design (600 W x ~1800 H).

## Files

| File | Purpose |
|------|---------|
| `index.html` | The emailer. Table-based layout, inline CSS, 600px container, 100% background, mobile stacking below 600px. |
| `images/` | Sliced assets (2x for retina). Referenced as `images/...` – see "Before sending". |
| `preview-desktop.png` / `preview-mobile.png` | Rendered previews for QA. |

## Links (from the Trello card)

| Element | URL |
|---------|-----|
| Top menu: Book a tour | https://dwight.ae/visit/ |
| Top menu: Inquire | https://dwight.ae/inquiry/ |
| Top menu: Apply | https://dwight.ae/admissions/apply-now/ |
| Top menu: Academics | https://dwight.ae/academics/overview/ |
| Logo | https://dwight.ae/ |
| Main image (hero) | https://dwight.ae/event-calendar/stayplay-october2026/ |
| REGISTER 1 (Stay & Play) | https://dwight.ae/event-calendar/stayplay-october2026/ |
| REGISTER 2 (Open Morning) | **TEMPORARY:** https://dwight.ae/inquiry/ until the client provides the real URL (Monday). Search for `TODO` in `index.html`. |
| Early Years image | https://dwight.ae/academics/early-years-programme/ |
| Primary Years image | https://dwight.ae/academics/primary-years-programme/ |
| Middle Years image | https://dwight.ae/academics/middle-years-programme/ |
| Senior Years image | https://dwight.ae/academics/upper-school/ |
| Facebook | https://www.facebook.com/DwightSchoolDXB/ |
| Instagram | https://www.instagram.com/dwightschooldxb/ |
| LinkedIn | https://www.linkedin.com/company/dwightschooldxb/ |

## Before sending

1. Replace the temporary REGISTER 2 link (`https://dwight.ae/inquiry/`, marked `TODO`) with the Whole School Open Morning registration URL.
2. Upload the `images/` folder to the mailing platform / web host and replace every `images/` path in `index.html` with the absolute hosted URL (e.g. `https://dwight.ae/emailers/sept26/`). Email clients cannot load relative paths.
3. Send a test to Outlook, Gmail and iPhone Mail.

## Notes

- Brand colours: red `#cf202f`, navy `#13234b`, blue `#325590`, mid-blue `#33a3dc`, light-blue `#78c4f5`.
- Body copy uses live text (Brandon Grotesque with Arial fallback). Display headings (Farmhand Sans) are images, as email clients cannot load custom fonts reliably.
