# generator-hubot-script-gulp
[![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage Status][coveralls-image]][coveralls-url]

This repository forked from: [desmondmorris/generator-hubot-script](https://github.com/desmondmorris/generator-hubot-script)

This generator provides:
  - hubot-script based on [standard example](https://github.com/hubot-scripts/hubot-example)
  - coffeescript
  - gulp
  - coffeelint
  - code coverage (istanbul)
  - travis-ci ready
  - coveralls ready
  - mocha
  - sinon
  - power-assert

```
$ tree -I 'node_modules|.idea' -a
.
├── .editorconfig
├── .gitattributes
├── .gitignore
├── .travis.yml
├── LICENSE
├── README.md
├── coffeelint.json
├── gulpfile.coffee
├── index.coffee
├── package.json
├── src
│   └── you-want-to-generate.coffee
└── test
    └── you-want-to-generate-test.coffee
```

## Install
```
npm install generator-hubot-script-gulp -g
mkdir hubot-you-want-to-generate && cd $_
yo hubot-script-gulp
```
done!

## License
### generator-hubot-script-gulp
Copyright (c) 2014 sanemat. [Licensed under the MIT license](./LICENSE)

### original generator-hubot-script
Copyright 2013 Desmond Morris. [Licensed under the MIT license](./generator-hubot-script/LICENSE)

[npm-url]: https://npmjs.org/package/generator-hubot-script-gulp
[npm-image]: http://img.shields.io/npm/v/generator-hubot-script-gulp.svg?style=flat
[travis-url]: https://travis-ci.org/sanemat/generator-hubot-script-gulp
[travis-image]: http://img.shields.io/travis/sanemat/generator-hubot-script-gulp/master.svg?style=flat
[daviddm-url]: https://david-dm.org/sanemat/generator-hubot-script-gulp.svg?theme=shields.io
[daviddm-image]: http://img.shields.io/david/sanemat/generator-hubot-script-gulp.svg?style=flat
[coveralls-url]: https://coveralls.io/r/sanemat/generator-hubot-script-gulp
[coveralls-image]: http://img.shields.io/coveralls/sanemat/generator-hubot-script-gulp/master.svg?style=flat
