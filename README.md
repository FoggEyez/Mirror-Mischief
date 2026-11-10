# Mirror Mischief

Configurable MagicMirror² modules by [FoggEyez](https://github.com/FoggEyez), designed to work with the Mirror Mischief companion and ordinary MagicMirror² configuration.

The goal is simple installation, understandable settings and useful displays that adapt to your mirror. Each module has its own repository: clone only the modules you want.

| Module | What it does | Network/account requirements |
| --- | --- | --- |
| [Mischief Quotes](https://github.com/FoggEyez/MMM-MischiefQuotes) | Original humor and your own phrases | Offline, no account |
| [Mischief Moon](https://github.com/FoggEyez/MMM-MischiefMoon) | NASA-textured Moon and local phase lighting | Offline, no account |
| [Mischief Quiet Sky](https://github.com/FoggEyez/MMM-MischiefQuietSky) | A dim star canopy for your location | Offline, no account |
| [Mischief Holiday Accents](https://github.com/FoggEyez/MMM-MischiefHolidayAccents) | Seasonal decorations and fitted frost | Offline, no account |
| [Mischief Local Conditions](https://github.com/FoggEyez/MMM-MischiefLocalConditions) | US regional air quality and NWS alerts | Public feeds, no key |
| [Mischief Home Check](https://github.com/FoggEyez/MMM-MischiefHomeCheck) | Internet response history; optional private telemetry | HTTPS probe, no account by default |
| [Mischief System Watch](https://github.com/FoggEyez/MMM-MischiefSystemWatch) | Local health and configurable external checks | No external collector required |
| [Mischief Economy Ticker](https://github.com/FoggEyez/MMM-MischiefEconomyTicker) | US economic releases and reporting periods | FRED public downloads, Python 3, no key |

## The Mirror Mischief companion

Mirror Mischief is the companion being developed alongside these modules: browse repositories, install and configure modules, move them between native mirror regions, save changes and check setup from one desktop interface.

**Public companion installer: not yet released.** This hub does not currently contain a downloadable companion application. The existing development companion supports Install from a link and generated module settings; the modules can be installed manually today. Companion manifests describe each module's settings contract; current settings discovery reads the JavaScript defaults. Standalone packages have automated and isolated browser verification; independent physical-mirror installation remains to be verified.

Already using Mirror Mischief? Open Browse modules → Install from a link, paste a module repository URL, then open Module settings, choose a position and save. Run Check setup and inspect the physical display. Legacy local names are separate installations: disable the earlier version before enabling its Mischief replacement.

Every module README includes manual installation, customization, dependencies, data sources, limitations, preview screenshots and a support path. No module requires the companion to run.

## Quality and recognition

We aim to earn trust through working releases, clear screenshots, good bug reports, preserved upstream credit and dependable maintenance. These are early 0.1.0 releases; report reproducible problems in the relevant module repository. Stars are welcome if a module is useful to you, but support and reliability come first.

See [ROADMAP.md](ROADMAP.md) for proposed improvements and [MODULE-LIST.md](MODULE-LIST.md) for the catalog submission process. Future feature names also include Mischief. No popularity or adoption outcome is promised.

## Credits

Built for [MagicMirror²](https://magicmirror.builders/), an independent open-source project. Mischief is not endorsed by MagicMirrorOrg or NASA. Moon/sky modules preserve their NightSky and catalog attribution. See each repository's license and notices.
