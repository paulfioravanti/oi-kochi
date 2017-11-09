# Oi! Kochi

When I was on the [JET Programme](http://jetprogramme.org/en/) in
[Kochi Prefecture](https://en.wikipedia.org/wiki/K%C5%8Dchi_Prefecture), I was
in charge of an English/Japanese bilingual newsletter called _Oi! Kochi_. 
I wanted to create online versions of the newsletter accessible by both the web
and mobile phones, so this repo contains my attempts at that.

In the early 2000s, Japan was using clamshell-style
[feature phones](https://en.wikipedia.org/wiki/Feature_phone#Japan), and sites
developed for them used [C-HTML](https://en.wikipedia.org/wiki/C-HTML), so
that's what I used for the mobile pages.

The code in this repo is terrible, since I had no idea what I was really doing
at the time, but I've left it pretty much as it was written, except for any
changes that needed to be peformed to allow the pages to be deployed to
[Heroku](https://www.heroku.com) and work as expected.
So, it simply stands as a historical record.

## Web Pages

The web pages can be viewed at the following URL:

https://oi-kochi-web.herokuapp.com

## Mobile Pages

The mobile pages can be viewed at the following URL:

https://oi-kochi-mobile.herokuapp.com

For the most period-accurate browsing experience, I'd recommend using an
emulator that replicates the the old Japanese feature phones.
The closest I've come to this is viewing the pages using the
[Firefox](https://www.mozilla.org/en-US/firefox/new/) browser, along with the
[FireMobileSimulator](https://addons.mozilla.org/en-US/firefox/addon/firemobilesimulator/)
add-on.  This will, at the very least, display the pages close to how I tested
them at the time on my
[AU by KDDI](https://en.wikipedia.org/wiki/Au_(mobile_phone_company)) phone,
and enable use of the keyboard to trigger `accesskey` attributes in links
(ie for a link with text "1. English", you can press the "1" number key to
"click" on that link).

## Newsletters

Under the `newsletters` directory, you'll find PDFs of the paper versions
of the 2002 Oi! Kochi newsletters for reference.
I don't recall if paper versions were made for the 2003 newsletters, but if they
were, then I must have lost the copies.

## Deployment

Since I don't plan on developing these pages any further, and wanted to have both
the web and mobile pages in the same repo, I used `git subtree` to deploy the
different page subdirectories to their respective Heroku repos:

Web: `$ git subtree push --prefix web heroku-oi-kochi-web master`<br />
Mobile: `$ git subtree push --prefix mobile heroku-oi-kochi-mobile master`

## Development Notes

- The pages themselves are simply static HTML since I didn't know any better at
  the time
- The additions of PHP `index.php` files were done to give Heroku a project type
  it could recognise in order to enable deployment.
  Use of the
  [PHP Heroku buildpack](https://elements.heroku.com/buildpacks/heroku/heroku-buildpack-php)
  was the path of least resistance for this.

## License

All content in articles (including HTML and PDF files) is licensed
under the [Creative Commons Attribution 4.0 license](LICENSE-CC-BY-4.0.txt),
and all source code is licensed under the [MIT license](LICENSE-MIT.txt).

## Social

[![Contact](https://img.shields.io/badge/contact-%40paulfioravanti-blue.svg)](https://twitter.com/paulfioravanti)

<a href="http://stackoverflow.com/users/567863/paul-fioravanti">
  <img src="http://stackoverflow.com/users/flair/567863.png" width="208" height="58" alt="profile for Paul Fioravanti at Stack Overflow, Q&amp;A for professional and enthusiast programmers" title="profile for Paul Fioravanti at Stack Overflow, Q&amp;A for professional and enthusiast programmers">
</a>
