---
title: Bootstrap
permalink: /bootstrap
layout: post
category: framework
sortReleasesBy: "releaseCycle"
activeSupportColumn: true
changelogTemplate: https://github.com/twbs/bootstrap/releases/tag/v__LATEST__
auto:
-   git: https://github.com/twbs/bootstrap.git
releases:
-   releaseCycle: "5"
    release: 2021-05-05
    eol: false
    support: true
    lts: true
    latest: "5.1.3"
    latestReleaseDate: 2021-10-09
-   releaseCycle: "4"
    release: 2018-01-18
    eol: 2022-11-01
    latest: "4.6.1"
    lts: true
    support: false
    latestReleaseDate: 2021-10-28
-   releaseCycle: "3"
    release: 2013-08-19
    eol: 2019-07-24
    latest: "3.4.1"
    support: false
    latestReleaseDate: 2019-02-13
-   releaseCycle: "2"
    release: 2012-01-31
    eol: 2013-08-19
    latest: "2.3.2"
    support: false
    latestReleaseDate: 2013-07-26
releasePolicyLink: https://github.com/twbs/release
releaseDateColumn: true
eolColumn: Critical Support

---

> [Bootstrap](https://getbootstrap.com/) is the most popular HTML, CSS, and JavaScript framework for developing responsive, mobile first projects on the web.

At times to be determined by the release working group, major versions will be frozen and transitioned to _Long Term Support_ (LTS). After a determined period of time, versions in Long Term Support will be deep-frozen and transition to _Maintenance_.

Versions in _Maintenance_ should not have any changes landed, except for:

- **Critical** bug fixes
- **Critical** security updates
- **Important** documentation updates

Unless a change is urgent, _Maintenance_ releases are likely to be made with minimal frequency. The `v4` branch is currently in Active LTS and will receive bug fixes till 2021-07-01, after which it will only receive critical fixes till its End of Life.
