# BSA Meritbadge SVG Icons and PDF Workbooks
This is a repository containing SVG files and PDF workbooks for every BSA merit badge (145 badges as of 2026), plus the nine badges currently in the [Scouts BSA Test Lab](https://www.scouting.org/skills/merit-badges/test-lab/).

## Test Lab badges

Test Lab badges are candidate topics a Scout completes for a certificate rather than a blue card. Their artwork is hexagonal where a merit badge is round, and their filenames carry a ` - Test Badge` suffix.

A topic can have artwork in both folders at once, and that is not a duplicate. Competitive Gaming and Wildland Fire Management have graduated to official merit badges, so `CompetitiveGaming.svg` and `WildlandFireManagement.svg` are the merit badges while `Competitive Gaming - Test Badge.svg` and `Wildland Fire Management - Test Badge.svg` remain the Test Lab badges Scouts earned before they graduated. Keep both: retiring the Test Lab artwork would erase what those Scouts completed. Life Skills went the other way, expiring without graduating, so it exists only as a Test Lab badge.

## MeritBadgesList.csv

One row per file in `svg-images/`, with the badge name, the filename, the original scouting.org URL where one exists, a `raw.githubusercontent.com` URL that resolves today, and the inline SVG source. Alongside the merit badges and Test Lab badges it lists the shared award artwork (`fire.svg`, `totin.svg`, `nova.svg`), the generic `bsa.svg` fallback icon, and `DisabilitiesAwarenessOld.svg`, kept for reference.

Renaming or replacing an SVG makes this file stale, since it embeds the artwork inline.

I did not make these images or workbooks, nor do I own them. I simply collected them and placed them in a common repository for easier access and public reference. 

If new badges come out in the future, please feel free to open a PR against this repo to add in the new SVG and PDF file

These images came from:
https://www.scouting.org/programs/scouts-bsa/advancement-and-awards/merit-badges/

This website was replaced with the current merit badge website on October 2021. You can now only find caches of these images here:

https://web.archive.org/web/20221007173835/https://www.scouting.org/programs/scouts-bsa/advancement-and-awards/merit-badges/

For reference, here is the current website which does not include the SVG images: https://www.scouting.org/skills/merit-badges/all/
