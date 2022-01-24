# esbuild-plugin-mxn-scss

Esbuild plugin for compiling SASS / SCSS

## Usage

Install the package using
**npm**
`npm i esbuild-plugin-mxn-scss`
or
**yarn**
`yarn add esbuild-plugin-mxn-scss`

import the package to esbuild bundle.js and use as plugin

```javascript
const esbuildSass = require("esbuild-plugin-mxn-scss");
require("esbuild")
.build({
	...
	plugins: [esbuildSass],
	...
})
.catch(() =>  process.exit(1));
```

### import `sass` files

simply add sass files using import

```javascript
import  "./style.scss";
....
```
