# Tectonic outreach leaderboard

Public leaderboard with aggregate outreach counts, identified by Tect email. Source: the private Tectonic 2026 Startup LinkedIn Outreach Log, tab `Outreach log` (gid 1578630869).

The Codex scheduled sync updates `data.json` every 15 minutes from the connected Google Sheets and Slack accounts. Raw recipient details, message bodies and conversation links are never published. Hosting uses GitHub Pages from `main`, repository root. The browser checks for refreshed data every minute.

Count one row for each confirmed send: `Verified sent`, variants starting with `Verified sent`, and `Sent; verified in LinkedIn conversation`. Exclude deleted, skipped, unsent and unverified rows. Normalize sender email with trim + lowercase and combine name variations. Include all Slack members with an `@tectonicconf.eu` email, plus any sender in the sheet. Equal totals receive equal competition ranks. Zero means no confirmed outreach in this particular log.
