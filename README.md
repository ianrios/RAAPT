<!-- ![Logo of the project](https://raw.githubusercontent.com/jehna/readme-best-practices/master/sample-logo.png) -->

# RAAPT

> Rhythmic Automated Audio Processing Templater

The RAAPT project generates rhythmic musical structures by assigning pre-made templates to ecological soundscapes. By applying structural templates to audio clips, RAAPT creates an automated and generative music system capable of transforming any sonic material into rhythmic, musical instruments.

#### 2016/2017 winner of RPI Undergraduate Research Program

## Installing / Getting started

To spin up project, you will need Max MSP 7 installed on your computer.

Double click on `patches/MainRAAPT.maxpat` to start

## Developing

In order to continue work in this project, you need to own a copy of Max MSP 7 or newer

## Features

By choosing start and end points within an audio file and selecting frequency ranges to pre-existing instrument frequencies, the program identifies which sounds are the best matches for predefined patterns.

Drum samples and lead sounds are extracted from the source audio by matching regions to a specified amplitude and frequency range. By shaping the sound to match different waveforms, such as a kick drum or hi-hat, a bank of drum samples is automatically generated. A granular synthesizer processes the same audio file and creates a bank of lead samples that are used as melodic elements within a piece of music.

All samples are then run through effects and stored in a post-processed sample bank.
Finally, a sequencer organizes all the drum and lead sounds and maps them to MIDI presets chosen from a bank of MIDI loops.

The RAAPT project can generate multiple versions of the same piece of music from any raw audio file due to non-deterministic properties of selecting sample length, location, and effects. This approach decouples the composition of musical structure from the traditional orchestration of voices and instruments. Composers using RAAPT can approach creating new material in exciting and experimental ways.

## Contributing

If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome.

## Links

- Project homepage: http://ianrios.me/RAAPT.html
- Repository: https://github.com/ianrios/RAAPT
- Issue tracker: https://github.com/ianrios/RAAPT/issues
  - In case of sensitive bugs like security vulnerabilities, please contact
    ian.rios@email.com directly instead of using issue tracker. We value your effort
    to improve the security and privacy of this project!
- Related projects:
  - [Grandulator](https://github.com/ianrios/Grandulator)
  - [My other Projects:](http://ianrios.me/projects.html)

## Licensing

The code in this project is licensed under MIT license.

Copyright 2016 Ian Rios

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
