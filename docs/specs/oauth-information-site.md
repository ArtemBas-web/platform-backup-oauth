# OAuth information site

Status: Implemented
Last updated: 2026-11-16

## Goal and scope

Visitors to the consent screen can identify Platform Backup and read its privacy policy. The site describes a private operator integration and provides a public contact route. The backup process, Google authorization, credentials and recovery operations belong to the separate integration.

## Requirements

- The [home page](../../index.html) explains the integration's purpose, the `drive.file` scope and that backups are encrypted before upload.
- The [privacy policy](../../privacy.html) owns the public disclosure of data access, storage, use, retention, deletion and contact. Keep the consent-screen links usable without a GitHub sign-in.
- The site is static HTML and CSS. It does not request Google consent, accept uploads, offer registration or access Drive. No site-owned administrative interface, API or database is required.
- Public content contains no credentials, server addresses, backup data or private operating procedures.

## Acceptance and rollout

- From the project root, open `index.html` in a browser and follow the Privacy and Home links both ways. Both pages render with the local stylesheet. Confirm the text makes no claim of public service availability.
- Check the public disclosure and contact route by reading both pages. A local review uses the checked-out files and does not authenticate to Google or touch backups.
- GitHub Pages publishes from `main`. After a separately authorized publication, check the deployed home and privacy URLs available to consent-screen visitors. Local file checks establish no deployment status.
