# nikku

Web-based BRSTM player

Just open [the demo](https://kenrick95.github.io/nikku/) in modern browser, select .brstm file, and enjoy!

## What Is BRSTM?

BRSTM is a file format that contains [lossless](https://sound.stackexchange.com/a/40879) audio data that's being used for some Nintendo consoles. One of the differences with the usual audio format (MP3, etc) is that this format can contain a loop point, making it suitable for usage in games.

`.brstm` file is not included in the repository.

Some places to look for BRSTM files:

- ~~[Smash Custom Music](http://smashcustommusic.com/)~~<sup>[_dead link_]</sup>
- [Smash Custom Music Archive](https://smashcustommusic.net/) (the audio player in this site is using the ["brstm" package](https://github.com/kenrick95/nikku/tree/master/src/brstm) from this repo!)
- [Reddit](https://www.reddit.com/r/BRSTM/)

## Browser Requirements

There are no polyfill included in [the demo](https://kenrick95.github.io/nikku/).

Browser needs to support the following features without any vendor prefix:

- [Audio Worklet API](https://caniuse.com/mdn-api_audioworklet)
- [Web Audio API](https://caniuse.com/#feat=audio-api)
- [`<script type="module"> `](https://caniuse.com/#feat=es6-module)
- [ES2016 class](https://caniuse.com/#feat=es6-class)
- [ES2015 in general](https://caniuse.com/#feat=es6)
- [`<template>`](https://caniuse.com/#feat=template)

Developed and tested in Firefox 66

## References

- [WiiBrew](https://wiibrew.org/wiki/BRSTM_file), for BRSTM file description.
- [BrawlLib](https://github.com/libertyernie/brawltools) codes, on how to decode BRSTM.

## See Also

- [My journey of building this](https://blog.kenrick95.org/2019/04/nikku/) (April 2019)
- [My talk in Geekcamp Singapore 2019](https://github.com/kenrick95/nikku-talk) (October 2019)
