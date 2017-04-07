# api documentation for  [react-tooltip (v3.2.10)](https://github.com/wwayne/react-tooltip)  [![npm package](https://img.shields.io/npm/v/npmdoc-react-tooltip.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-react-tooltip) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-react-tooltip.svg)](https://travis-ci.org/npmdoc/node-npmdoc-react-tooltip)
#### react tooltip component

[![NPM](https://nodei.co/npm/react-tooltip.png?downloads=true)](https://www.npmjs.com/package/react-tooltip)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-tooltip/build/screenCapture.buildNpmdoc.browser.%2Fhome%2Ftravis%2Fbuild%2Fnpmdoc%2Fnode-npmdoc-react-tooltip%2Ftmp%2Fbuild%2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-tooltip/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-react-tooltip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-react-tooltip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "wwayne"
    },
    "browserify-shim": {
        "react": "global:React",
        "react-dom": "global:ReactDOM"
    },
    "bugs": {
        "url": "https://github.com/wwayne/react-tooltip/issues"
    },
    "dependencies": {
        "classnames": "^2.2.0"
    },
    "description": "react tooltip component",
    "devDependencies": {
        "babel-cli": "^6.5.1",
        "babel-core": "^6.9.1",
        "babel-eslint": "^4.1.1",
        "babel-plugin-transform-decorators-legacy": "^1.3.4",
        "babel-plugin-transform-runtime": "^6.5.0",
        "babel-preset-es2015": "^6.5.0",
        "babel-preset-react": "^6.5.0",
        "babel-preset-stage-0": "^6.5.0",
        "babelify": "^7.2.0",
        "browserify": "^13.0.0",
        "browserify-shim": "^3.8.12",
        "chai": "^3.5.0",
        "chai-enzyme": "^0.5.0",
        "concurrently": "^2.1.0",
        "enzyme": "^2.3.0",
        "http-server": "^0.8.0",
        "jsdom": "^9.2.1",
        "mocha": "^2.5.3",
        "node-sass": "^3.7.0",
        "react-addons-test-utils": "^15.1.0",
        "sinon": "^1.17.4",
        "snazzy": "^2.0.1",
        "standard": "^5.2.2",
        "uglifyjs": "^2.4.10",
        "watchify": "^3.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "484a5c8c0709701e89db9e0281ec32a50a0925ea",
        "tarball": "https://registry.npmjs.org/react-tooltip/-/react-tooltip-3.2.10.tgz"
    },
    "engines": {
        "node": ">=4.2.1"
    },
    "gitHead": "987f463e93167355811706cba1666e144157cc99",
    "homepage": "https://github.com/wwayne/react-tooltip",
    "keywords": [
        "react",
        "react-component",
        "tooltip",
        "react-tooltip"
    ],
    "license": "MIT",
    "main": "dist/index.js",
    "maintainers": [
        {
            "name": "hmnid",
            "email": "huumanoid@hotmail.com"
        },
        {
            "name": "wwayne",
            "email": "wayne.wang0821@gmail.com"
        }
    ],
    "name": "react-tooltip",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0",
        "react-dom": "^0.14.0 || ^15.0.0"
    },
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/wwayne/react-tooltip.git"
    },
    "scripts": {
        "deploy": "make deploy",
        "start": "make dev",
        "test": "make test"
    },
    "standard": {
        "parser": "babel-eslint",
        "ignore": [
            "dist/",
            "standalone/",
            "src/style.js",
            "src/style.css",
            "example/"
        ]
    },
    "version": "3.2.10"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module react-tooltip](#apidoc.module.react-tooltip)
1.  [function <span class="apidocSignatureSpan">react-tooltip.</span>hide (target)](#apidoc.element.react-tooltip.hide)
1.  [function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.afterShow ()](#apidoc.element.react-tooltip.propTypes.afterShow)
1.  [function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.children ()](#apidoc.element.react-tooltip.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.delayHide ()](#apidoc.element.react-tooltip.propTypes.delayHide)
1.  [function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.multiline ()](#apidoc.element.react-tooltip.propTypes.multiline)
1.  [function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.offset ()](#apidoc.element.react-tooltip.propTypes.offset)
1.  [function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.place ()](#apidoc.element.react-tooltip.propTypes.place)
1.  [function <span class="apidocSignatureSpan">react-tooltip.</span>rebuild ()](#apidoc.element.react-tooltip.rebuild)
1.  [function <span class="apidocSignatureSpan">react-tooltip.</span>show (target)](#apidoc.element.react-tooltip.show)
1.  object <span class="apidocSignatureSpan">react-tooltip.</span>defaultProps
1.  object <span class="apidocSignatureSpan">react-tooltip.</span>propTypes
1.  object <span class="apidocSignatureSpan">react-tooltip.</span>supportedWrappers

#### [module react-tooltip.propTypes](#apidoc.module.react-tooltip.propTypes)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>afterHide ()](#apidoc.element.react-tooltip.propTypes.afterHide)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>afterShow ()](#apidoc.element.react-tooltip.propTypes.afterShow)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>border ()](#apidoc.element.react-tooltip.propTypes.border)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>children ()](#apidoc.element.react-tooltip.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>class ()](#apidoc.element.react-tooltip.propTypes.class)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>className ()](#apidoc.element.react-tooltip.propTypes.className)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>delayHide ()](#apidoc.element.react-tooltip.propTypes.delayHide)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>delayShow ()](#apidoc.element.react-tooltip.propTypes.delayShow)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>disable ()](#apidoc.element.react-tooltip.propTypes.disable)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>effect ()](#apidoc.element.react-tooltip.propTypes.effect)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>event ()](#apidoc.element.react-tooltip.propTypes.event)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>eventOff ()](#apidoc.element.react-tooltip.propTypes.eventOff)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>getContent ()](#apidoc.element.react-tooltip.propTypes.getContent)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>globalEventOff ()](#apidoc.element.react-tooltip.propTypes.globalEventOff)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>html ()](#apidoc.element.react-tooltip.propTypes.html)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>id ()](#apidoc.element.react-tooltip.propTypes.id)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>insecure ()](#apidoc.element.react-tooltip.propTypes.insecure)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>isCapture ()](#apidoc.element.react-tooltip.propTypes.isCapture)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>multiline ()](#apidoc.element.react-tooltip.propTypes.multiline)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>offset ()](#apidoc.element.react-tooltip.propTypes.offset)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>place ()](#apidoc.element.react-tooltip.propTypes.place)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>resizeHide ()](#apidoc.element.react-tooltip.propTypes.resizeHide)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>scrollHide ()](#apidoc.element.react-tooltip.propTypes.scrollHide)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>type ()](#apidoc.element.react-tooltip.propTypes.type)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>watchWindow ()](#apidoc.element.react-tooltip.propTypes.watchWindow)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>wrapper ()](#apidoc.element.react-tooltip.propTypes.wrapper)

#### [module react-tooltip.propTypes.afterShow](#apidoc.module.react-tooltip.propTypes.afterShow)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>afterShow ()](#apidoc.element.react-tooltip.propTypes.afterShow.afterShow)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.afterShow.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.afterShow.isRequired)

#### [module react-tooltip.propTypes.children](#apidoc.module.react-tooltip.propTypes.children)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>children ()](#apidoc.element.react-tooltip.propTypes.children.children)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.children.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.children.isRequired)

#### [module react-tooltip.propTypes.delayHide](#apidoc.module.react-tooltip.propTypes.delayHide)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>delayHide ()](#apidoc.element.react-tooltip.propTypes.delayHide.delayHide)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.delayHide.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.delayHide.isRequired)

#### [module react-tooltip.propTypes.multiline](#apidoc.module.react-tooltip.propTypes.multiline)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>multiline ()](#apidoc.element.react-tooltip.propTypes.multiline.multiline)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.multiline.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.multiline.isRequired)

#### [module react-tooltip.propTypes.offset](#apidoc.module.react-tooltip.propTypes.offset)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>offset ()](#apidoc.element.react-tooltip.propTypes.offset.offset)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.offset.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.offset.isRequired)

#### [module react-tooltip.propTypes.place](#apidoc.module.react-tooltip.propTypes.place)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>place ()](#apidoc.element.react-tooltip.propTypes.place.place)
1.  [function <span class="apidocSignatureSpan">react-tooltip.propTypes.place.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.place.isRequired)



# <a name="apidoc.module.react-tooltip"></a>[module react-tooltip](#apidoc.module.react-tooltip)

#### <a name="apidoc.element.react-tooltip.hide"></a>[function <span class="apidocSignatureSpan">react-tooltip.</span>hide (target)](#apidoc.element.react-tooltip.hide)
- description and source-code
```javascript
hide = function (target) {
  dispatchGlobalEvent(_constant2.default.GLOBAL.HIDE, { target: target });
}
```
- example usage
```shell
...

##### Note:
1. **data-tip** is necessary, because '<ReactTooltip />' finds the tooltip via this attribute
2. **data-for** corresponds to the **id** of '<ReactTooltip />'
3. When using react component as tooltip, you can have many '<ReactTooltip />' in a page but they should have different **id**s

## Static Methods
### ReactTooltip.hide(target)

> Hide the tooltip manually, the target is optional, if no target passed in, all existing tooltips will be hidden

'''js
import {findDOMNode} from 'react-dom'
import ReactTooltip from 'react-tooltip'
...
```

#### <a name="apidoc.element.react-tooltip.propTypes.afterShow"></a>[function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.afterShow ()](#apidoc.element.react-tooltip.propTypes.afterShow)
- description and source-code
```javascript
propTypes.afterShow = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.children ()](#apidoc.element.react-tooltip.propTypes.children)
- description and source-code
```javascript
propTypes.children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.delayHide"></a>[function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.delayHide ()](#apidoc.element.react-tooltip.propTypes.delayHide)
- description and source-code
```javascript
propTypes.delayHide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.multiline"></a>[function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.multiline ()](#apidoc.element.react-tooltip.propTypes.multiline)
- description and source-code
```javascript
propTypes.multiline = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.offset"></a>[function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.offset ()](#apidoc.element.react-tooltip.propTypes.offset)
- description and source-code
```javascript
propTypes.offset = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.place"></a>[function <span class="apidocSignatureSpan">react-tooltip.</span>propTypes.place ()](#apidoc.element.react-tooltip.propTypes.place)
- description and source-code
```javascript
propTypes.place = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.rebuild"></a>[function <span class="apidocSignatureSpan">react-tooltip.</span>rebuild ()](#apidoc.element.react-tooltip.rebuild)
- description and source-code
```javascript
rebuild = function () {
  dispatchGlobalEvent(_constant2.default.GLOBAL.REBUILD);
}
```
- example usage
```shell
...
import ReactTooltip from 'react-tooltip'

<p ref='foo' data-tip='tooltip'></p>
<button onClick={() => { ReactTooltip.hide(findDOMNode(this.refs.foo)) }}></button>
<ReactTooltip />
'''

### ReactTooltip.rebuild()

> Rebinding all tooltips

### ReactTooltip.show(target)

> Show specific tooltip manually, for example:
...
```

#### <a name="apidoc.element.react-tooltip.show"></a>[function <span class="apidocSignatureSpan">react-tooltip.</span>show (target)](#apidoc.element.react-tooltip.show)
- description and source-code
```javascript
show = function (target) {
  dispatchGlobalEvent(_constant2.default.GLOBAL.SHOW, { target: target });
}
```
- example usage
```shell
...
<ReactTooltip />
'''

### ReactTooltip.rebuild()

> Rebinding all tooltips

### ReactTooltip.show(target)

> Show specific tooltip manually, for example:

'''js
import {findDOMNode} from 'react-dom'
import ReactTooltip from 'react-tooltip'
...
```



# <a name="apidoc.module.react-tooltip.propTypes"></a>[module react-tooltip.propTypes](#apidoc.module.react-tooltip.propTypes)

#### <a name="apidoc.element.react-tooltip.propTypes.afterHide"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>afterHide ()](#apidoc.element.react-tooltip.propTypes.afterHide)
- description and source-code
```javascript
afterHide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.afterShow"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>afterShow ()](#apidoc.element.react-tooltip.propTypes.afterShow)
- description and source-code
```javascript
afterShow = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.border"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>border ()](#apidoc.element.react-tooltip.propTypes.border)
- description and source-code
```javascript
border = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.children"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>children ()](#apidoc.element.react-tooltip.propTypes.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.class"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>class ()](#apidoc.element.react-tooltip.propTypes.class)
- description and source-code
```javascript
class = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.className"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>className ()](#apidoc.element.react-tooltip.propTypes.className)
- description and source-code
```javascript
className = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.delayHide"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>delayHide ()](#apidoc.element.react-tooltip.propTypes.delayHide)
- description and source-code
```javascript
delayHide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.delayShow"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>delayShow ()](#apidoc.element.react-tooltip.propTypes.delayShow)
- description and source-code
```javascript
delayShow = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.disable"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>disable ()](#apidoc.element.react-tooltip.propTypes.disable)
- description and source-code
```javascript
disable = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.effect"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>effect ()](#apidoc.element.react-tooltip.propTypes.effect)
- description and source-code
```javascript
effect = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.event"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>event ()](#apidoc.element.react-tooltip.propTypes.event)
- description and source-code
```javascript
event = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.eventOff"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>eventOff ()](#apidoc.element.react-tooltip.propTypes.eventOff)
- description and source-code
```javascript
eventOff = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.getContent"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>getContent ()](#apidoc.element.react-tooltip.propTypes.getContent)
- description and source-code
```javascript
getContent = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.globalEventOff"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>globalEventOff ()](#apidoc.element.react-tooltip.propTypes.globalEventOff)
- description and source-code
```javascript
globalEventOff = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.html"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>html ()](#apidoc.element.react-tooltip.propTypes.html)
- description and source-code
```javascript
html = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.id"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>id ()](#apidoc.element.react-tooltip.propTypes.id)
- description and source-code
```javascript
id = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.insecure"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>insecure ()](#apidoc.element.react-tooltip.propTypes.insecure)
- description and source-code
```javascript
insecure = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.isCapture"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>isCapture ()](#apidoc.element.react-tooltip.propTypes.isCapture)
- description and source-code
```javascript
isCapture = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.multiline"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>multiline ()](#apidoc.element.react-tooltip.propTypes.multiline)
- description and source-code
```javascript
multiline = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.offset"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>offset ()](#apidoc.element.react-tooltip.propTypes.offset)
- description and source-code
```javascript
offset = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.place"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>place ()](#apidoc.element.react-tooltip.propTypes.place)
- description and source-code
```javascript
place = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.resizeHide"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>resizeHide ()](#apidoc.element.react-tooltip.propTypes.resizeHide)
- description and source-code
```javascript
resizeHide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.scrollHide"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>scrollHide ()](#apidoc.element.react-tooltip.propTypes.scrollHide)
- description and source-code
```javascript
scrollHide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.type"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>type ()](#apidoc.element.react-tooltip.propTypes.type)
- description and source-code
```javascript
type = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.watchWindow"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>watchWindow ()](#apidoc.element.react-tooltip.propTypes.watchWindow)
- description and source-code
```javascript
watchWindow = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.wrapper"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>wrapper ()](#apidoc.element.react-tooltip.propTypes.wrapper)
- description and source-code
```javascript
wrapper = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-tooltip.propTypes.afterShow"></a>[module react-tooltip.propTypes.afterShow](#apidoc.module.react-tooltip.propTypes.afterShow)

#### <a name="apidoc.element.react-tooltip.propTypes.afterShow.afterShow"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>afterShow ()](#apidoc.element.react-tooltip.propTypes.afterShow.afterShow)
- description and source-code
```javascript
afterShow = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.afterShow.isRequired"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.afterShow.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.afterShow.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-tooltip.propTypes.children"></a>[module react-tooltip.propTypes.children](#apidoc.module.react-tooltip.propTypes.children)

#### <a name="apidoc.element.react-tooltip.propTypes.children.children"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>children ()](#apidoc.element.react-tooltip.propTypes.children.children)
- description and source-code
```javascript
children = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.children.isRequired"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.children.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.children.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-tooltip.propTypes.delayHide"></a>[module react-tooltip.propTypes.delayHide](#apidoc.module.react-tooltip.propTypes.delayHide)

#### <a name="apidoc.element.react-tooltip.propTypes.delayHide.delayHide"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>delayHide ()](#apidoc.element.react-tooltip.propTypes.delayHide.delayHide)
- description and source-code
```javascript
delayHide = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.delayHide.isRequired"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.delayHide.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.delayHide.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-tooltip.propTypes.multiline"></a>[module react-tooltip.propTypes.multiline](#apidoc.module.react-tooltip.propTypes.multiline)

#### <a name="apidoc.element.react-tooltip.propTypes.multiline.multiline"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>multiline ()](#apidoc.element.react-tooltip.propTypes.multiline.multiline)
- description and source-code
```javascript
multiline = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.multiline.isRequired"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.multiline.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.multiline.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-tooltip.propTypes.offset"></a>[module react-tooltip.propTypes.offset](#apidoc.module.react-tooltip.propTypes.offset)

#### <a name="apidoc.element.react-tooltip.propTypes.offset.offset"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>offset ()](#apidoc.element.react-tooltip.propTypes.offset.offset)
- description and source-code
```javascript
offset = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.offset.isRequired"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.offset.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.offset.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.react-tooltip.propTypes.place"></a>[module react-tooltip.propTypes.place](#apidoc.module.react-tooltip.propTypes.place)

#### <a name="apidoc.element.react-tooltip.propTypes.place.place"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.</span>place ()](#apidoc.element.react-tooltip.propTypes.place.place)
- description and source-code
```javascript
place = function () { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.react-tooltip.propTypes.place.isRequired"></a>[function <span class="apidocSignatureSpan">react-tooltip.propTypes.place.</span>isRequired ()](#apidoc.element.react-tooltip.propTypes.place.isRequired)
- description and source-code
```javascript
isRequired = function () { [native code] }
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
