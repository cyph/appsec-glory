![](http://i.imgur.com/V2QIMNS.png)

To see the techniques discussed (including in-browser code signing) implemented in production, check out [Cyph](https://www.cyph.com).

Slides: [us-16-Zadegan-Abusing-Bleeding-Edge-Web-Standards-For-AppSec-Glory.pdf](https://www.dropbox.com/s/63zlhsuhwtwfd12/us-16-Zadegan-Abusing-Bleeding-Edge-Web-Standards-For-AppSec-Glory.pdf?dl=1)

Demo links:

* [heisenberg.co/srifallbackdemo](https://heisenberg.co/srifallbackdemo)

* [heisenberg.co/sridemo/sameorigin](https://heisenberg.co/sridemo/sameorigin)

* [heisenberg.co/metacspdemo](https://heisenberg.co/metacspdemo)

* [redskins.io](https://redskins.io)

* cyph.wang (more specifically, `*.cyph.wang` as a demo HPKP-Supercookie server)

* [isis.io](https://isis.io)

Source code links:

* [github.com/cyph/sri-fallback](https://github.com/cyph/sri-fallback)

* [github.com/cyph/hpkp-supercookie](https://github.com/cyph/hpkp-supercookie)

* [github.com/cyph/ransompkp](https://github.com/cyph/ransompkp)

---

**Edit:** After the Black Hat version of our talk on 2016-08-03, it was conveyed to us by Blue Coat that their cert has a path length of 0, thus preventing its use in any sort of wide-ranged HPKP Suicide attack as we'd suggested on stage. We haven't yet thoroughly investigated the implications of path length 0, so feel free to investigate on your own and pass on any findings.
