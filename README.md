# Mirror Mischief

Configurable MagicMirror² modules by [FoggEyez](https://github.com/FoggEyez), designed to work with the Mirror Mischief companion and ordinary MagicMirror² configuration.

The goal is simple installation, understandable settings and useful displays that adapt to your mirror. Each module has its own repository: clone only the modules you want.

| Module | What it does | Network/account requirements |
| --- | --- | --- |
| [Hora · Observatory clock](https://github.com/FoggEyez/MMM-MCHF-Hora) | Clear round dial, Gothic Flip digits, date placement and optional daylight | Offline, no account |
| [Echo · Music](https://github.com/FoggEyez/MMM-MCHF-Echo) | Artwork, ambient glow and responsive music layouts | Existing OnSpotify, your own Spotify app or local playback notifications |
| [Flow · Adaptive layout](https://github.com/FoggEyez/MMM-MCHF-Flow) | Responsive card sizes, smooth reflow and button-ready expansion | Offline; helper with no screen position |
| [Wit · Funny comments](https://github.com/FoggEyez/MMM-MCHF-Wit) | Original humor and your own phrases | Offline, no account |
| [Luna · Moon](https://github.com/FoggEyez/MMM-MCHF-Luna) | NASA-textured Moon and local phase lighting | Offline, no account |
| [Astra · Star canopy](https://github.com/FoggEyez/MMM-MCHF-Astra) | A dim star canopy for your location | Offline, no account |
| [Rite · Holiday scenes](https://github.com/FoggEyez/MMM-MCHF-Rite) | Seasonal decorations and fitted frost | Offline, no account |
| [Air · Local conditions](https://github.com/FoggEyez/MMM-MCHF-Air) | US regional air quality and NWS alerts | Public feeds, no key |
| [Haven · Home network](https://github.com/FoggEyez/MMM-MCHF-Haven) | Internet response history; optional private telemetry | HTTPS probe, no account by default |
| [Vigil · System health](https://github.com/FoggEyez/MMM-MCHF-Vigil) | Local health and configurable external checks | No external collector required |
| [Tide · Economy](https://github.com/FoggEyez/MMM-MCHF-Tide) | US economic releases and reporting periods | FRED public downloads, Python 3, no key |
| [Atmos · Dynamic weather](https://github.com/FoggEyez/MMM-MCHF-Atmos) | Snow, frost, rain, heat and thunderstorm atmosphere | Native current weather or optional Open-Meteo |


**MCHF = Mischief.** Short names carry the collection’s identity: Hora (hour), Echo (sound that leaves an impression), Flow (making room for change), Rite (tradition), Atmos (atmosphere), Wit (humor), Luna (Moon), Astra (stars), Vigil (watchfulness), Haven (home), Tide (economic currents), and Air (local air conditions).


## The Mirror Mischief companion

Mirror Mischief is the companion being developed alongside these modules: browse repositories, install and configure modules, move them between native mirror regions, save changes and check setup from one desktop interface.

**Public companion installer: not yet released.** This hub does not currently contain a downloadable companion application. The existing development companion supports Install from a link and generated module settings; the modules can be installed manually today. Companion manifests describe each module's settings contract; current settings discovery reads the JavaScript defaults. Packages have automated and isolated browser checks. Rite, Atmos, Wit, Hora and Echo have also been installed and checked on the development Raspberry Pi; broader device coverage is still welcome.

Already using Mirror Mischief? Open Browse modules → Install from a link, paste a module repository URL, then open Module settings, choose a position and save. Run Check setup and inspect the physical display. Legacy local names are separate installations: disable the earlier version before enabling its Mischief replacement.

Every module README includes manual installation, customization, dependencies, data sources, limitations, preview screenshots and a support path. No module requires the companion to run.

## Quality and recognition

We aim to earn trust through working releases, clear screenshots, good bug reports, preserved upstream credit and dependable maintenance. These are early public-preview releases; report reproducible problems in the relevant module repository. Stars are welcome if a module is useful to you, but support and reliability come first.

See [ROADMAP.md](ROADMAP.md) for proposed improvements and [MODULE-LIST.md](MODULE-LIST.md) for the catalog submission process. Future feature names also include Mischief. No popularity or adoption outcome is promised.

## Credits

Built for [MagicMirror²](https://magicmirror.builders/), an independent open-source project. Mischief is not endorsed by MagicMirrorOrg or NASA. Moon/sky modules preserve their NightSky and catalog attribution. See each repository's license and notices.

## Backgrounds and entrances

Information modules include neutral earthy card backgrounds: Moss, Sage, Clay, Sand, Walnut, Slate and Peat, or the original clear style. Set `classes: "mischief-earth-sage"` on the module entry, or use the companion’s Card background selector. Existing custom classes are preserved. Full-screen Rite, Atmos and Astra layers stay transparent. Use `animateIn: "flipInX"`, `fadeInUp`, `zoomIn` or `fadeIn` for native optional entrances. Native numeric data refreshes do not replay the entrance. Reduced-motion preferences are respected by the shared style. Wit separately supports phrase-only fades.

## Updating from the earlier repository names

GitHub redirects the earlier MMM-Mischief repository URLs after the rename, preserving history and issues. MagicMirror needs the folder, main JavaScript filename and `module` name to agree: install the new MMM-MCHF repository in its own folder, transfer the settings you want and disable the earlier entry before enabling its replacement. Keep a copy of your configuration first. Rite has a new scene model; use its Scene Studio or documented defaults rather than assuming every legacy frost option maps directly.

## Latest polish release

Rite 0.2.2, Atmos 0.1.1 and the other seven modules at 0.2.1. This pass improves weather pause/resume, handles missing network and health data explicitly, keeps every economic indicator readable with reduced motion, and adds visible severe-alert guidance. Each repository now includes a troubleshooting guide and current previews. Manual installation and configuration remain first-class paths.

The companion development build adds a curated nine-module gallery, clearer settings progress and recovery, and connection checks before saved preferences change. Its independent public installer remains in development.

## Flow public preview

[MMM-MCHF-Flow](https://github.com/FoggEyez/MMM-MCHF-Flow) adds an optional adaptive board layout. Cards use real widths/heights, move smoothly and can expand through local notifications ready for later buttons. The included interactive preview demonstrates the actual controller. Flow has manual and companion settings, no backend/account/API requirement, and no visible card of its own. It has not migrated the development Pi’s daily layout. Fixed/fullscreen or unusual module layouts need exclusions or specific support; see its guide before enabling.

## Hora and Echo public previews

Hora 0.1.1 floats directly on the mirror, with a round dial or rectangular Gothic Flip digits, a date above or below, and locally bundled blackletter type. Echo 0.1.1 keeps original Spotify artwork and a configurable glow while paused, then fades stale artwork and light over 1.8 seconds. Both provide manual setup, literal settings defaults and optional companion settings. Echo reuses an installed OnSpotify connection without another login, or accepts an independently configured source.
