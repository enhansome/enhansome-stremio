# Awesome Stremio with stars

> A curated list of awesome tools and addons for Stremio

## Contents

1. [Stremio official](#stremio-official)
2. [Unofficial communities](#unofficial-communities)
3. [Tools](#tools)
4. [Addons](#addons)
   1. [Movies & TV shows](#Movies--TV-shows)
   2. [Live TV](#Live-TV)
   3. [Podcasts](#Podcasts)
   4. [Subtitles](#subtitles)
   5. [Catalogs](#catalogs)
5. [Tutorials](#tutorials)
6. [Addon Developer Resources](#Addon-Developer-Resources)
7. [Contribute](#contribute)
8. [License](#license)

## Stremio official

Links to official Stremio resources:

* [Bugs](https://github.com/Stremio/stremio-bugs) ⭐ 167 | 🐛 414 | 📅 2026-06-28
* [Feature requests](https://github.com/Stremio/stremio-features) ⭐ 164 | 🐛 596 | 📅 2026-04-22
* [Website](https://www.stremio.com/)
* [Blog](https://blog.strem.io/)
* [Support](https://stremio.zendesk.com/)
* [Community addons collection](https://api.strem.io/addonscollection.json)

Community:

* [Facebook](https://www.facebook.com/stremio/)
* [Twitter](https://twitter.com/stremio)
* [Instagram](https://www.instagram.com/stremioofficial/)
* [Reddit](https://www.reddit.com/r/Stremio/)

Open source code:

* [Stremio Web](https://github.com/stremio/stremio-web) ⭐ 12,662 | 🐛 70 | 🌐 JavaScript | 📅 2026-08-13
* [Stremio Core](https://github.com/Stremio/stremio-core/tree/development) ⭐ 2,269 | 🐛 80 | 🌐 Rust | 📅 2026-08-13
* [Addon SDK](https://github.com/Stremio/stremio-addon-sdk) ⭐ 1,314 | 🐛 79 | 🌐 JavaScript | 📅 2026-04-08
* [Stremio Desktop](https://github.com/stremio/stremio-shell) ⭐ 909 | 🐛 146 | 🌐 C++ | 📅 2026-03-27

## Unofficial communities

* [Stremio addon subreddit](https://www.reddit.com/r/StremioAddons/)
* [Discord chat](https://discord.gg/zNRf6YF)
* [Stremio addon Facebook page](https://www.facebook.com/StremioAddons/)
* [Stremio Facebook group](https://www.facebook.com/groups/stremio/)

## Tools

Official:

* [Addon publishing helper](https://stremio.github.io/stremio-publish-addon/index.html)
* [Catalog builder](https://stremio.github.io/stremio-catalog-builder/)

3rd party:

* [PimpMyStremio (aka "PMS")](https://github.com/sungshon/PimpMyStremio) ⭐ 499 | 🐛 37 | 🌐 JavaScript | 📅 2023-10-25: Local addon manager for Stremio; allows you to run addons that don't work with the regular Stremio
  * [Addon list including links to their GitHub repository](https://github.com/sungshon/PimpMyStremio/blob/master/src/addonsList.json) ⭐ 499 | 🐛 37 | 🌐 JavaScript | 📅 2023-10-25
  * [Reddit post with further info](https://www.reddit.com/r/Stremio/comments/db9qmn/what_is_pimpmystremio_xpost_from_rstremioaddons/)
  * [Tutorial for running PMS on Android](https://gist.github.com/sleeyax/e9635eb352a4fcdf94194f763d743689)
* [Stremio Downloader](https://github.com/BurningSands70/stremio-downloader) ⭐ 418 | 🐛 17 | 🌐 JavaScript | 📅 2023-09-04: Allows you to download streams from Stremio
* [Stremio-RaspberryPi](https://github.com/shivasiddharth/Stremio-RaspberryPi) ⭐ 187 | 🐛 14 | 🌐 Shell | 📅 2026-02-25: Helps you to run Stremio on a Raspberry Pi
* [Stremio Install Scripts](https://github.com/alexandru-balan/Stremio-Install-Scripts) ⭐ 92 | 🐛 11 | 🌐 Shell | 📅 2022-01-31: Scripts that are meant to install Stremio and its dependencies on systems that do not provide an official installation for Stremio
* [Flatpak package](https://github.com/bilelmoussaoui/stremio-flatpak) ⚠️ Archived: Stremio installer for systems with [Flatpak](https://flatpak.org/)
* [Flatpak package](https://github.com/p1u3o/com.stremio.Stremio) ⭐ 4 | 🐛 1 | 📅 2020-01-23: Same

## Addons

This list here focuses on open source addons, linking the source code repositories. For a list of addons that aren't necessarily open source check <https://github.com/danamag/stremio-addons-list> ⚠️ Archived, which is the successor of the addon list that was maintained on the [r/StremioAddons](https://www.reddit.com/r/StremioAddons/) subreddit in the past.

### Movies & TV shows

Torrent and HTTP streams:

* [Torrentio](https://github.com/TheBeastLT/torrentio-scraper) ⭐ 1,280 | 🐛 75 | 🌐 JavaScript | 📅 2026-08-01: Torrent and Debrid addon with multiple sources (YTS, EZTV, RARBG, 1337x, ThePirateBay, KickassTorrents, HorribleSubs) and support for multiple debrid services (RealDebrid, AllDebrid, Premiumize, Put.io, DebridLink)
* [Orion](https://github.com/gorlev/orion-stremio-addon) ⭐ 93 | 🐛 9 | 🌐 JavaScript | 📅 2023-07-04: Torrent and Debrid addon with Orion as source and support for multiple debrid services (via Orion: RealDebrid, Premiumize, Offcloud)

HTTP streams only (no P2P uploading):

* [Deflix](https://github.com/doingodswork/deflix-stremio) ⭐ 189 | 🐛 21 | 🌐 Go | 📅 2023-11-19: Debrid addon with multiple sources (YTS, The Pirate Bay, RARBG, 1337x and ibit) and support for multiple debrid services (RealDebrid, AllDebrid, Premiumize), written in Go
* [Lobo Guara Series](https://github.com/mrcanelas/lobo-guara-addon) ⚠️ Archived: Addon for dubbed TV Shows in brazilian portuguese
* [Animes Brasil](https://github.com/mrcanelas/anime-tv-addon): Anime addon for brazilian portuguese (dubbed and subbed)

Torrent streams:

* [1337x torrents](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/1337x-torrents) ⚠️ Archived: Torrent addon for 1337x
* [HorribleSubs](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/horriblesubs) ⚠️ Archived: Anime torrents
* [RARBG torrents](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/rarbg-torrents) ⚠️ Archived: Torrent addon for RARBG
* [Stream Quality Filter (aka "SQF")](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/stream-quality-filter) ⚠️ Archived: Fetches streams from RARBG, 1337x, YTS and TPB+ addons, removes duplicates and sorts them by quality
* [Juan Carlos 2](https://github.com/JCB9090/juan-carlos-torrents-2) ⭐ 55 | 🐛 11 | 🌐 JavaScript | 📅 2015-12-12: Torrent addon for KAT.cr and torrentz.eu
* [Mico leão dublado](https://github.com/fadoaglauss/stremio-brazilian-addon) ⭐ 47 | 🐛 15 | 🌐 HTML | 📅 2023-01-06: Addon for dubbed movies in brazilian portuguese (PT-BR) with multiple sources
* [Piratebay](https://github.com/ThanosDi/piratebay-stremio-addon) ⭐ 43 | 🐛 2 | 🌐 JavaScript | 📅 2021-02-11: Torrent addon for The Pirate Bay
* [ThePirateBay+](https://github.com/TheBeastLT/stremio-thepiratebay-plus) ⭐ 41 | 🐛 7 | 🌐 JavaScript | 📅 2024-11-16: Torrent addon for The Pirate Bay
* [pct](https://github.com/JCB9090/pct-addon) ⭐ 37 | 🐛 5 | 🌐 JavaScript | 📅 2016-02-12: Torrent addon for EZTV and YTS
* [rarbg](https://github.com/sebastiencs/rarbg-addon) ⭐ 20 | 🐛 4 | 🌐 JavaScript | 📅 2017-03-12: Torrent addon for RARBG

### Live TV

* [dlive.tv](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/dlive) ⚠️ Archived: Live streams from dlive.tv

### Podcasts

* [podcasts](https://github.com/sleeyax/stremio-addons/tree/master/packages/addons/podcasts) ⚠️ Archived
* [podcasts-for-all](https://github.com/NivM1/podcasts-for-all)

### Subtitles

* [OpenSubtitles (*official* addon)](https://github.com/Stremio/stremio-opensubtitles): Adds subtitles from [OpenSubtitles](https://www.opensubtitles.org) to your stream

### Catalogs

* [Kitsu animes](https://github.com/TheBeastLT/stremio-kitsu-anime) ⭐ 34 | 🐛 3 | 🌐 JavaScript | 📅 2026-02-20: Provides several [Kitsu](https://kitsu.io) anime catalogs (All, Top Rated, Most Popular, Trending) and metadata for them
* [Top movies](https://github.com/doingodswork/stremio-top-movies) ⭐ 29 | 🐛 1 | 🌐 Go | 📅 2021-09-04: Contains multiple catalogs of top movies: IMDb Top 250, IMDb Most Popular, Top Box Office, Rotten Tomatoes Certified Fresh Movies, Academy Award for Best Picture, Cannes Film Festival Palme, Venice Film Festival Golden Lion, Berlin International Film Festival Golden Bear
* [IMDb list](https://github.com/jaruba/stremio-imdb-list) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2023-12-22: Allows you to use any IMDb list as catalog
* [IMDb tag](https://github.com/jaruba/stremio-imdb-tag) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2020-04-21: Allows you to dynamically create a catalog from an IMDb tag

## Tutorials

* [How to download movies/series on android](https://www.reddit.com/r/StremioAddons/comments/ekwj5x/how_to_download_moviesseries_on_android/)

## Addon Developer Resources

SDKs:

* [Official addon SDK](https://github.com/Stremio/stremio-addon-sdk) ⭐ 1,314 | 🐛 79 | 🌐 JavaScript | 📅 2026-04-08
* [Addon SDK for Go](https://github.com/Deflix-tv/go-stremio) ⭐ 38 | 🐛 4 | 🌐 Go | 📅 2023-09-12: Stremio addon SDK for Go
* [Addon SDK for Rust](https://github.com/sleeyax/stremio-addon-sdk) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-10: Rust version of the stremio-addon-sdk using stremio-core

Examples using those SDKs:

* Node.js
  * [Hello World Addon](https://github.com/Stremio/addon-helloworld) ⭐ 80 | 🐛 4 | 🌐 JavaScript | 📅 2025-11-27: also includes a step by step tutorial
  * [IGDB Addon](https://github.com/Stremio/stremio-igdb-addon/tree/tutorial) ⭐ 9 | 🐛 0 | 🌐 JavaScript | 📅 2019-03-07
* Rust
  * [Example Addon](https://github.com/sleeyax/stremio-addon-sdk/tree/master/example-addon) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-10
* Go
  * [Examples for a catalog addon and a stream addon](https://github.com/Deflix-tv/go-stremio/tree/master/examples) ⭐ 38 | 🐛 4 | 🌐 Go | 📅 2023-09-12

Examples not using any SDK:

* [Node.js Express Addon Example Using User Data](https://github.com/Stremio/stremio-addon-sdk/blob/master/docs/advanced.md) ⭐ 1,314 | 🐛 79 | 🌐 JavaScript | 📅 2026-04-08
* [Jackett Addon - Node.js Express Addon Using User Data](https://github.com/BoredLama/stremio-jackett-addon) ⭐ 50 | 🐛 2 | 🌐 JavaScript | 📅 2019-05-24
* [Python Addon Example & Tutorial](https://github.com/Stremio/addon-helloworld-python) ⭐ 32 | 🐛 2 | 🌐 Python | 📅 2019-02-22
* [IMDB Watchlist - Node.js Express Addon Using User Data and Proxying Another Stremio Addon](https://github.com/jaruba/stremio-imdb-watchlist) ⭐ 20 | 🐛 3 | 🌐 JavaScript | 📅 2020-04-21
* [IMDB Lists - Node.js Express Addon Using User Data and Ajax Calls](https://github.com/jaruba/stremio-imdb-list) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2023-12-22
* [Go Addon Example](https://github.com/Stremio/addon-helloworld-go) ⭐ 11 | 🐛 2 | 🌐 Go | 📅 2022-11-10
* [PHP Addon Example & Tutorial](https://github.com/Stremio/stremio-php-addon-example) ⭐ 10 | 🐛 1 | 🌐 PHP | 📅 2019-02-18
* [C# Addon Example](https://github.com/Stremio/addon-helloworld-csharp) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2019-02-14
* [Ruby Addon Example & Tutorial](https://github.com/Stremio/addon-helloworld-ruby) ⭐ 5 | 🐛 0 | 🌐 Ruby | 📅 2019-02-15
* [Node.js Express Addon Example & Tutorial](https://github.com/Stremio/addon-helloworld-express) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2019-02-19

Guides:

* [Official SDK guide](https://stremio.github.io/stremio-addon-guide/sdk-guide/prelude)
* [Official generic guide](https://stremio.github.io/stremio-addon-guide/basics)

Video tutorials:

* [Building a Stremio addon](https://www.youtube.com/watch?v=ULLqhPJl2v0)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, doingodswork has waived all copyright and
related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
