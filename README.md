<img src="web/Common/RyomaReadingOi.gif" height="150" /><img src="web/Common/Oi!Kochibannerlogosmall.gif" height="120" /><img src="web/Common/Kochimap.gif" height="130" />

# Oi! Kochi

When I was on the [JET Programme][] in [Kochi Prefecture][], I was in charge of
an English/Japanese bilingual newsletter called _Oi! Kochi_.  I wanted to create
online versions of the newsletter accessible by both the web and mobile phones,
so this repo contains my attempts at that.

In the early 2000s, Japan was using clamshell-style [feature phones][], and
sites developed for them used [C-HTML][], so that's what I used for the mobile
pages.

The code in this repo is terrible, since I had no idea what I was really doing
at the time, but I've left it pretty much as it was written, except for any
changes that needed to be performed to allow the pages to be deployed to
[Github Pages][] and work as expected.

So, it simply stands as a historical record.

## Web Pages

The web pages can be viewed at the following URL:

<https://www.paulfioravanti.com/oi-kochi/web/>

## Mobile Pages

The mobile pages can be viewed at the following URL:

<https://www.paulfioravanti.com/oi-kochi/mobile>

For the most period-accurate browsing experience, I'd recommend using an
emulator that replicates the old Japanese feature phones.
The closest I've come to this is viewing the pages using the
[Firefox][] browser, along with the [FireMobileSimulator][] add-on. This will,
at the very least, display the pages close to how I tested them at the time on
my [AU by KDDI][] phone, and enable use of the keyboard to trigger
[`accesskey` attributes][] in links (ie for a link with text "1. English", you
can press the :one: number key on the phone to "click" on that link).

## Newsletters

Under the [`newsletters`][] directory, you'll find PDFs of the paper versions of
the 2002 Oi! Kochi newsletters for reference. Due to budget cuts, only online
versions of Oi! Kochi were published from 2003.

## License

| Category |                         License                           |
|----------|-----------------------------------------------------------|
| Content  | [![License: CC BY 4.0][license-cc-badge]][license-cc-url] |
| Code     | [![License: MIT][license-mit-badge]][license-mit-url]     |

All content in articles (including HTML and PDF files) is licensed
under the [Creative Commons Attribution 4.0 license][license-cc],
and all source code is licensed under the [MIT license][license-mit].

SPDX-License-Identifier: (MIT AND CC-BY-4.0)

## Social

[![Contact][twitter-badge]][twitter-url]<br />
[![Stack Overflow][stackoverflow-badge]][stackoverflow-url]

[`accesskey` attributes]: https://en.wikipedia.org/wiki/Access_key
[AU by KDDI]: https://en.wikipedia.org/wiki/Au_(mobile_phone_company)
[C-HTML]: https://en.wikipedia.org/wiki/C-HTML
[feature phones]: https://en.wikipedia.org/wiki/Feature_phone#Japan
[Firefox]: https://www.mozilla.org/en-US/firefox/new/
[FireMobileSimulator]: https://addons.mozilla.org/en-US/firefox/addon/firemobilesimulator/
[Github Pages]: https://pages.github.com/
[JET Programme]: http://jetprogramme.org/en/
[Kochi Prefecture]: https://en.wikipedia.org/wiki/K%C5%8Dchi_Prefecture
[license-cc]: LICENSE-CC-BY-4.0.txt
[license-cc-badge]: https://licensebuttons.net/l/by/4.0/80x15.png
[license-cc-url]: https://creativecommons.org/licenses/by/4.0/
[license-mit]: LICENSE-MIT.txt
[license-mit-badge]: https://img.shields.io/badge/License-MIT-lightgrey.svg
[license-mit-url]: https://opensource.org/licenses/MIT
[`newsletters`]: https://github.com/paulfioravanti/oi-kochi/tree/master/newsletters
[stackoverflow-badge]: http://stackoverflow.com/users/flair/567863.png
[stackoverflow-url]: http://stackoverflow.com/users/567863/paul-fioravanti
[twitter-badge]: https://img.shields.io/badge/contact-%40paulfioravanti-blue.svg
[twitter-url]: https://twitter.com/paulfioravanti
