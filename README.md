# markdown-it-center-text



> Center text plugin for [markdown-it](https://github.com/markdown-it/markdown-it) markdown parser.

`->Centered Text<-` => `<p class="text-align-center">Centered Text</p>`


## Install

node.js, browser:

```bash
npm install markdown-it-center-text --save
bower install markdown-it-center-text --save
```

## Use

```js
var md = require('markdown-it')()
            .use(require('markdown-it-center-text'));

md.render('->Centered Text<-') // => '<div class="text-align-center">Centered Text</div>'

```

The widgetparams can be used to determine what kind of html widget should be rendered in the output container.

_Differences in browser._ If you load script directly into the page, without
package system, module will add itself globally as `window.markdownitCentertext`.


## License
[MIT](https://github.com/jay-hodgson/markdown-it-center-text/blob/master/LICENSE)
