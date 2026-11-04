# Project provenance and credits

This is Iliass Benkirane's portfolio edition of the AdSpy team project, based on the supplied `adspy-main.zip`. It adds personal documentation of the scraping contribution and historical sample outputs.

The full application is collaborative work. Inclusion here does not claim sole authorship of the dashboard, AWS orchestration, n8n workflows, report generation, or every line of the integrated scraper.

## Sources

- Project source: the user-supplied archive of [thomaschuckle/adspy](https://github.com/thomaschuckle/adspy).
- Three reused application screenshots: [thomaschuckle/adspy_intelligence](https://github.com/thomaschuckle/adspy_intelligence), revision `0e6977922d3a59765a20b3a6d6af65e90b73209b`, under `docs/screenshots/`. They illustrate the team's application.
- Scraping samples: `linkedin_sample.txt`, `google_sample.txt`, and `meta_sample.txt`, supplied by Iliass Benkirane. Referenced advertising text and assets belong to their respective advertisers and platforms.

The original package metadata has an MIT license field, but the supplied archive contains no standalone license. This edition does not add a new license or claim additional rights over team code or third-party assets.

## Portfolio preparation

- Replaced the README with a project overview, four-person team acknowledgment, and setup guide.
- Added a scraping walkthrough, three original sample files, and first-record JSON excerpts.
- Reused three application screenshots with source attribution.
- Replaced deployment-specific AWS URLs, S3 bucket names, and n8n host names with placeholders.
- Removed saved n8n execution data, instance metadata, and credential references. Reconnect credentials after importing workflows.
- Added `.env.example` and ignore exceptions for documentation screenshots and configuration templates.

No feature changes were intended. This source portfolio is not a hosted production deployment.
