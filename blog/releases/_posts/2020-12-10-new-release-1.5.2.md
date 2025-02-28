---

layout: post-bugfix
title: 'New release: 1.5.2'
author: foosel
date: 2020-12-10 13:40:00 +0100
card: /assets/img/blog/2020-12/2020-12-10-octoprint-1.5.2-card.png
featuredimage: /assets/img/blog/2020-12/2020-12-10-octoprint-1.5.2-card.png
poster: /assets/img/blog/2020-12/2020-12-10-octoprint-1.5.2-poster.png
excerpt: "This is a hotfix release to fix one bug and add a workaround for a third party dependency issue."

bugfix: 1.5.2
release:
  tag: 1.5.0
  link: /blog/2020/11/30/new-release-1.5.0/
  headsups: true

---

I wish it hadn't be necessary to push yet another release out within this short amount of
time, but sadly a recent third party dependency update that introduced a critical backwards
incompatibility on a patch release forced my hand here. On the upside, you also
get a bugfix included that was originally only scheduled to go out with 1.6.0.

Due to this being a hotfix release the [changelog](https://github.com/OctoPrint/OctoPrint/releases/tag/1.5.2) is very short and only consists
of these entries:

>  * [#3855](https://github.com/OctoPrint/OctoPrint/issues/3855) & [#3867](https://github.com/OctoPrint/OctoPrint/issues/3867) - Fix settings merging on the frontend causing issues with array values.
>  * Pin `watchdog` dependency to 0.10.4 to work around backwards incompatibility with the just release 0.10.5 under Python 3.

Like every single release (and release candidate) of OctoPrint ever since early 2016 this release was made possible only
through your continued **[support of my work](/support-octoprint/)** 💕
