# esbuild-plugin-scss

Esbuild plugin for compiling SASS / SCSS

## Usage

Install the package using
**npm**
`npm i esbuild-plugin-scss`
or
**yarn**
`yarn add esbuild-plugin-scss`

import the package to esbuild bundle.js and use as plugin

```javascript
const esbuildSCSS = require("esbuild-plugin-scss");
require("esbuild")
.build({
	...
	plugins: [esbuildSCSS],
	...
})
.catch(() =>  process.exit(1));
```

### import `SCSS` files

Simply add SCSS files using import:

```javascript
import  "./style.scss";
....
```
