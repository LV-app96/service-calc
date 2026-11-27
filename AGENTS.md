# Development rules

- Keep public names and examples generic. Never commit personal, location-specific, financial, client or confidential contract data, including in comments, tests and commit messages.
- Store individual titles and settings locally only. No tracking, external fonts, analytics or unnecessary network requests. Public code is not anonymous by guarantee.
- Preserve existing local storage keys and records; never clear user storage during updates.
- Preserve the exact existing 28-field semicolon-delimited export order, formats and both shortcut destinations. Do not change the external table or CSV import contract without explicit approval.
- Default test mode to off at startup and reset; separate test and real records.
- Do not change remuneration rules without explicit approval and verification of the applicable legal basis. Test ordinary, overnight, Sunday, NRW holiday, midnight and year transitions, overlapping surcharge reasons, separate time rounding, mixed services and multiple persons; verify the 80% rule only for eligible flat fees.
- Preserve offline behavior. Update displayed version and service worker cache version consistently. Never delete local storage when refreshing app assets.
- Keep user input minimal and calculations traceable. Do not imply an external save succeeded without confirmation.
- Before release, inspect changes for private data, run syntax and regression tests, and report actual results and untested cases. Test export and iPhone offline/update behavior when available.
- Work on a separate branch and request review before merging into main. No secrets or personal data in PR descriptions.
