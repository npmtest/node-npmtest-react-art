# npmtest-react-art

#### basic test coverage for  react-art (v0.15.1)  [![npm package](https://img.shields.io/npm/v/npmtest-react-art.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-art) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-art.svg)](https://travis-ci.org/npmtest/node-npmtest-react-art)

#### React ART is a JavaScript library for drawing vector graphics using React. It provides declarative and reactive bindings to the ART library. Using the same declarative API you can render the output to either Canvas, SVG or VML (IE8).

[![NPM](https://nodei.co/npm/react-art.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-art)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-art/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-art/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-art/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-art/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-art/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-art/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-art/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-art/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-art/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-art/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-art/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-art/build/test-report.html](https://npmtest.github.io/node-npmtest-react-art/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-art/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-art/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-art/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-art/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-art/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-art/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-art/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-art/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "react-art",
    "description": "React ART is a JavaScript library for drawing vector graphics using React. It provides declarative and reactive bindings to the ART library. Using the same declarative API you can render the output to either Canvas, SVG or VML (IE8).",
    "version": "0.15.1",
    "keywords": [
        "react",
        "art",
        "svg",
        "vml",
        "canvas",
        "jsx"
    ],
    "bugs": "https://github.com/reactjs/react-art/issues",
    "license": "BSD-3-Clause",
    "main": "lib/ReactART.js",
    "repository": {
        "type": "git",
        "url": "https://github.com/reactjs/react-art.git"
    },
    "dependencies": {
        "art": "^0.10.1",
        "fbjs": "^0.8.1",
        "object-assign": "^4.0.1"
    },
    "peerDependencies": {
        "react": "^15.0.0"
    },
    "devDependencies": {
        "babel-jest": "^12.0.2",
        "babel-preset-es2015": "^6.6.0",
        "babel-preset-react": "^6.5.0",
        "del": "^2.2.0",
        "gulp": "^3.9.1",
        "gulp-babel": "^6.1.2",
        "gulp-shell": "^0.5.2",
        "jest-cli": "^12.0.2",
        "react": "^15.0.2",
        "react-addons-test-utils": "^15.0.2",
        "react-dom": "^15.0.2"
    },
    "scripts": {
        "prepublish": "gulp",
        "test": "jest"
    },
    "jest": {
        "rootDir": "src",
        "scriptPreprocessor": "../node_modules/babel-jest",
        "setupEnvScriptFile": "../jest/environment.js",
        "unmockedModulePathPatterns": [
            ""
        ]
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
