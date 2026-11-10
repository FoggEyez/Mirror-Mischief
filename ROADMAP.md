# Mischief roadmap

## Current release work

- Publish the eight standalone 0.1.0 repositories with literal settings defaults, examples, tests, real-render previews and upstream credits.
- Verify clean installation on an independent MagicMirror² device and record exact tested versions before describing the releases as broadly compatible.
- Submit individual modules to the community module list after public links and installation checks are verified. List inclusion is maintained by the community and is not guaranteed.
- Package the companion itself for public installation: portable host setup, private connection onboarding, recovery documentation and independent restore validation. A public installer is not released yet.

## Candidates for the next improvements

The public catalog shows substantial interest in remote control, calendars, Spotify, backgrounds and financial tickers. Popularity is a starting point, not evidence that an existing module needs replacing. Review current issues and setup friction before selecting each next implementation.

| Proposed Mischief module | User benefit to investigate | Release gate |
| --- | --- | --- |
| MMM-MischiefWeather | Guided location/units/provider setup, clear current versus forecast information | Accurate data, time zones and provider failure tests |
| MMM-MischiefCalendar | Easier feed onboarding, multiple calendars, understandable event/time-zone controls | Private-feed handling, recurrence and DST tests |
| MMM-MischiefSpotify | Clear authorization/reconnection and settings guidance | Complete implementation, provider terms, preserved upstream attribution |
| MMM-MischiefControl | Safer understandable local controls and setup checks | Explicit local authorization and connection/recovery tests |

These are proposed modules, not existing releases. The private MMM-OnSpotify helper repair is incomplete as a standalone module and must not be represented as an original Mischief product. Contribute focused fixes upstream where that is more useful than maintaining a fork.

## Contribution standard

Start from a concrete user problem and a measurable improvement. Prefer useful presets and readable options to more switches. Keep external accounts optional where practical. Document geography, device, provider and single-instance limits. New modules must work manually and through Mirror Mischief. Keep private data out of examples, screenshots and repositories.

References: [official development guidance](https://docs.magicmirror.builders/module-development/introduction.html), [community catalog](https://modules.magicmirror.builders/), [catalog source and publishing guidance](https://github.com/MagicMirrorOrg/MagicMirror-3rd-Party-Modules).
