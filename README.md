# Tectonic outreach leaderboard

The website reads aggregate outreach totals directly from Google Sheets every 30 seconds through Google Visualization. No Codex automation, credentials or build is needed for outreach count changes. Google may briefly cache responses; the page shows the latest successful read and reports connection failures.

Source: https://docs.google.com/spreadsheets/d/16BelYduZSjXx8Ng0HS3Pmr11pYQ_c2LpXJ1CWCJJ3QI/edit?gid=1578630869

The source must remain viewable by anyone with its link for this direct connection. Requests select only sender email and confirmed-send counts, grouped in Google Sheets. Include Verified sent status variants and Sent; verified in LinkedIn conversation; exclude deleted, skipped and unsent messages. Sender emails are normalized in the browser.

The 29-member Slack roster in data.json provides names and zero-count members. Count fields in that file are unused: live counts always come from the sheet. New sender emails in the sheet appear automatically; Slack roster changes can be made in data.json.

Design follows tectonicconf.eu: Anybody type, navy background, blue and aqua accents, official logo. The viewport is fixed; only the member list scrolls. Hosting: GitHub Pages, main branch, root directory.
