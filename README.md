# Maya Keyboard

An open-source Bangla language keyboard for Android. Currently in development.


## Feature roadmap

### Basics
* [ ] Implementation of the keyboard core (InputMethodService)
* [ ] Caps + Caps Lock
* [ ] Key popups
* [ ] Extended key popups (e.g. a -> á, à, ä, ...) (needs tweaks for
      emojis)
* [ ] Key press sound/vibration
* [ ] Portrait orientation support
* [ ] Landscape orientation support (needs tweaks)
* [ ] Tablet screen support

### Layouts
* [ ] Latin character layout (QWERTY)
* [ ] Adapt to situation in app (password, url, text, etc. )
* [ ] Special character layout(s)
* [ ] Numeric layout
* [ ] Numeric layout (advanced)
* [ ] Phone number layout
* [ ] Emoji layout (popups buggy atm)
* [ ] Emoticon layout

### Preferences
* [ ] Setup wizard
* [ ] Preferences screen
* [ ] Customize look and behaviour of keyboard (currently only
      light/dark theme)
* [ ] Theme customization
* [ ] Theme import/export (?)
* [ ] Subtype selection (language/layout)
* [ ] Keyboard behaviour preferences
* [ ] Text suggestion / Auto correct preferences
* [ ] Gesture preferences

### Composing suggestions
* [ ] Auto suggest words from precompiled dictionary
* [ ] Auto suggest words from user dictionary
* [ ] Auto suggest contacts
* [ ] Multilingual typing

### Other useful features
* [ ] One-handed mode
* [ ] Clipboard manager (?)
* [ ] Floating keyboard
* [ ] Gesture support
* [ ] Glide typing (?)
* [ ] Full integration in IME service list of Android (xml/method)
      (integration is internal-only, because Android's default subtype
      implementation not really allows for dynamic language/layout
      pairs, only compile-time defined ones)
* [ ] (dev only) Generate well-structured documentation of code
* [ ] ...

Note: (?) = not sure if it will be implemented

## Used libraries and icons
* [Google Flexbox Layout for Android](https://github.com/google/flexbox-layout)
  by [google](https://github.com/google)
* [Google Material icons](https://github.com/google/material-design-icons) by
  [google](https://github.com/google)
* [Moshi JSON library](https://github.com/square/moshi) by
  [square](https://github.com/square)

## License
```
MIT License

Copyright (c) 2020 Tarek Al Zihad

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
