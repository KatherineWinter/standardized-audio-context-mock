# standardized-audio-context-mock

**A mocked version of the standardized-audio-context module.**

[![tests](https://img.shields.io/travis/chrisguttandin/standardized-audio-context-mock/master.svg?style=flat-square)](https://travis-ci.org/chrisguttandin/standardized-audio-context-mock)
[![dependencies](https://img.shields.io/david/chrisguttandin/standardized-audio-context-mock.svg?style=flat-square)](https://www.npmjs.com/package/standardized-audio-context-mock)
[![version](https://img.shields.io/npm/v/standardized-audio-context-mock.svg?style=flat-square)](https://www.npmjs.com/package/standardized-audio-context-mock)

## Usage example

Inside of your test file, override the desired global audio modules.

```
const AudioContextMock = require('standardized-audio-context-mock')
global.AudioContext = AudioContextMock.AudioContext
```