# Thinreports Editor

[Thinreports](http://www.thinreports.org/) is an open source report generation tool for Ruby.

  * Thinreports Editor (GUI Designer)
  * Thinreports Generator (Report Generator for Ruby)

## Features

Features of Generator is [here](http://www.thinreports.org/features/generator/).

### Easy to use

Less special training, possible to create by drag&drop.

### Multi-platform

Currently supported platforms are Windows, Mac and Linux.

### I18n Support

Currently supported locales are Japanese and English.
Please [contribute to translate](https://github.com/thinreports/thinreports-editor/blob/master/TRANSLATION.md)!

## Supported Platforms

We tested the following platform:

 * macOS 10.12
 * Windows 10
 * Ubuntu 16.04

## Supported Layout versions

Support a layout file that created/modified with 0.9.0+ Editor.

## Getting Started

  * [Installation Guide](http://www.thinreports.org/documentation/getting-started/installation.html)
  * [Quick Start Guide](http://www.thinreports.org/documentation/getting-started/quickstart.html)
  * [Examples](https://github.com/thinreports/thinreports-examples)
  * [Discussion Group](https://groups.google.com/forum/#!forum/thinreports)

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/thinreports/thinreports-editor.

### Translating for your language

See [TRANSLATION.md](https://github.com/thinreports/thinreports-editor/blob/master/TRANSLATION.md).

## Development

### Requirements

  * JDK 6+
  * Python 2.7
  * Node.js
  * [yarn](https://yarnpkg.com/en/)

### Getting Started

Install dependencies:
```
$ yarn install
```

Compile javascript, css and templates:
```
$ yarn run compile
```

Launch Editor on development:
```
$ yarn start
```

### Other Tasks

Watch and compile:
```
$ yarn run watch
```

Build package for macOS, Windows, Ubuntu(linux):
```
$ yarn run build
```

Run compilation and building on production:
```
$ yarn run release
```

## License

Thinreports Editor is licensed under the [GPLv3](https://github.com/thinreports/thinreports-editor/blob/master/GPLv3).
Please see [LICENSE](https://github.com/thinreports/thinreports-editor/blob/master/LICENSE) for further details.

## Copyright

&copy; 2010-2015 [Matsukei Co.,Ltd](http://www.matsukei.co.jp).
