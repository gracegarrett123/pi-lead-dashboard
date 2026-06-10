# P&I Lead Gen Tracker

Self-serve dashboard of Pensions & Investments lead-gen programs currently in market.
One open-anytime view for AEs, Julie, and the team: program, client, launch date,
leads/registrations, promo window, and live link.

**Live page:** https://gracegarrett123.github.io/pi-lead-dashboard/

## Data
Real launched P&I programs from the **Pensions & Investments Task Tracker** (Smartsheet):
Crain Brand = P&I, Status = Launched.

- Webinar **registrations are live** (pulled from the sheet).
- White-paper **lead counts show "Pending"** — those live in the P&I Jotform workspace and
  are not yet flowing into the sheet. They fill in automatically once the Jotform feed is
  connected (or counts are logged in the sheet).
- **Lead source (UTM)** also pulls from Jotform in phase 2.

## Refresh
Currently a static snapshot. Can be set to refresh from Smartsheet on a cadence
(e.g., each morning) so it stays current with no manual updates.

## Files
- `index.html` — the dashboard (self-contained; open in any browser).
