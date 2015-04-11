# Bap

> Beatmaking and sequence composition toolkit, using Javascript and Web Audio

Made by [Adam Renklint](http://adamrenklint.com)

**BEWARE, THIS IS ALPHA SOFTWARE. NOT READY YET.**

[![Travis branch](https://img.shields.io/travis/adamrenklint/bap/dev.svg?style=flat-square)](https://travis-ci.org/adamrenklint/bap)

[![npm](https://img.shields.io/npm/dm/bap.svg?style=flat-square)](https://www.npmjs.com/package/bap)

[![npm](https://img.shields.io/npm/v/bap.svg?style=flat-square)](https://www.npmjs.com/package/bap)

[![Code Climate](https://img.shields.io/codeclimate/github/adamrenklint/bap.svg?style=flat-square)](https://codeclimate.com/github/adamrenklint/bap)

[![Code Climate](https://img.shields.io/codeclimate/coverage/github/adamrenklint/bap.svg?style=flat-square)](https://codeclimate.com/github/adamrenklint/bap)

[![David dependencies](https://img.shields.io/david/adamrenklint/bap.svg?style=flat-square)](https://david-dm.org/adamrenklint/bap)

[![David devDependencies](https://img.shields.io/david/dev/adamrenklint/bap.svg?style=flat-square)](https://david-dm.org/adamrenklint/bap#info=devDependencies)

[![GitHub issues](https://img.shields.io/github/issues-raw/adamrenklint/bap.svg?style=flat-square)](https://github.com/adamrenklint/bap)

[![GitHub forks](https://img.shields.io/github/forks/adamrenklint/bap.svg?style=flat-square)](https://github.com/adamrenklint/bap)

[![GitHub stars](https://img.shields.io/github/stars/adamrenklint/bap.svg?style=flat-square)](https://github.com/adamrenklint/bap)

## Summary

> Public demos, examples

## Install

## Usage

### Example: metronome

## API

### bap

- ```bap.kit(params)``` returns a new [kit](#kit)
- ```bap.slot()``` returns a new [slot](#slot)
- ```bap.layer()``` returns a new [layer](#layer)
- ```bap.pattern()``` returns a new [pattern](#pattern)
- ```bap.sequence()``` returns a new [sequence](#sequence)
- ```bap.channel()``` returns a new [channel](#channel)
- ```bap.note()``` returns a new [note](#note)

### kit

- ```kit.slot()``` returns blank [slot](#slot) assigned to next index
- ```kit.slot(index)``` returns existing or blank slot with index
- ```kit.slot(index, slot)``` set slot instance at index

### slot

- ```slot.layer()``` returns a blank [layer](#layer) assigned to next index
- ```slot.layer(index)``` returns existing or blank layer with index
- ```slot.layer(index, layer)``` set layer instance at index

### layer

### pattern

- is [playable](#playable) and automatically looped

### sequence

### channel

### note

### playable

## Develop

## Contribute

## License
