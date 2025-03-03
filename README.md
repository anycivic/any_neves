# any_neves
sistemacassino__any
7.0.2 • Public • Published 3 months ago
/css-has-pseudo/README.md
/
css-has-pseudo
/
README.md


Back
331 LOC
9.76 kB
# PostCSS Has Pseudo [<img src="https://postcss.github.io/postcss/logo.svg" alt="PostCSS Logo" width="90" height="90" align="right">][PostCSS]

`npm install css-has-pseudo --save-dev`

[PostCSS Has Pseudo] lets you style elements relative to other elements in CSS, following the [Selectors Level 4] specification.

To use this feature you need to do two things :
- add the [PostCSS plugin](#usage) that transforms the selector into a class or attribute
- add the [browser polyfill](#browser) that sets the attribute or class on elements in a browser

```css
.title:has(+ p) {
	margin-bottom: 1.5rem;
}

/* becomes */

.js-has-pseudo [csstools-has-1a-38-2x-38-30-2t-1m-2w-2p-37-14-17-w-34-15]:not(does-not-exist) {
	margin-bottom: 1.5rem;
}
.title:has(+ p) {
	margin-bottom: 1.5rem;
}
```

## Usage

Add [PostCSS Has Pseudo] to your project:

```bash
npm install postcss css-has-pseudo --save-dev
```

Use it as a [PostCSS] plugin:

```js
const postcss = require('postcss');
const postcssHasPseudo = require('css-has-pseudo');

postcss([
	postcssHasPseudo(/* pluginOptions */)
]).process(YOUR_CSS /*, processOptions */);
```



## Options

### preserve

The `preserve` option determines whether the original notation
is preserved. By default the original rules are pre


7.0.2 • Public • Published 3 months ago
/css-has-pseudo/README.md
/
css-has-pseudo
/
README.md


Back
331 LOC
9.76 kB
# PostCSS Has Pseudo [<img src="https://postcss.github.io/postcss/logo.svg" alt="PostCSS Logo" width="90" height="90" align="right">][PostCSS]

`npm install css-has-pseudo --save-dev`

[PostCSS Has Pseudo] lets you style elements relative to other elements in CSS, following the [Selectors Level 4] specification.

To use this feature you need to do two things :
- add the [PostCSS plugin](#usage) that transforms the selector into a class or attribute
- add the [browser polyfill](#browser) that sets the attribute or class on elements in a browser

```css
.title:has(+ p) {
	margin-bottom: 1.5rem;
}

/* becomes */

.js-has-pseudo [csstools-has-1a-38-2x-38-30-2t-1m-2w-2p-37-14-17-w-34-15]:not(does-not-exist) {
	margin-bottom: 1.5rem;
}
.title:has(+ p) {
	margin-bottom: 1.5rem;
}
```

## Usage

Add [PostCSS Has Pseudo] to your project:

```bash
npm install postcss css-has-pseudo --save-dev
```

Use it as a [PostCSS] plugin:

```js
const postcss = require('postcss');
const postcssHasPseudo = require('css-has-pseudo');

postcss([
	postcssHasPseudo(/* pluginOptions */)
]).process(YOUR_CSS /*, processOptions */);
```



## Options

### preserve

The `preserve` option determines whether the original notation
is preserved. By default the original rules are pre7.0.2 • Public • Published 3 months ago
/css-has-pseudo/README.md
/
css-has-pseudo
/
README.md


Back
331 LOC
9.76 kB
# PostCSS Has Pseudo [<img src="https://postcss.github.io/postcss/logo.svg" alt="PostCSS Logo" width="90" height="90" align="right">][PostCSS]

`npm install css-has-pseudo --save-dev`

[PostCSS Has Pseudo] lets you style elements relative to other elements in CSS, following the [Selectors Level 4] specification.

To use this feature you need to do two things :
- add the [PostCSS plugin](#usage) that transforms the selector into a class or attribute
- add the [browser polyfill](#browser) that sets the attribute or class on elements in a browser

```css
.title:has(+ p) {
	margin-bottom: 1.5rem;
}

/* becomes */

.js-has-pseudo [csstools-has-1a-38-2x-38-30-2t-1m-2w-2p-37-14-17-w-34-15]:not(does-not-exist) {
	margin-bottom: 1.5rem;
}
.title:has(+ p) {
	margin-bottom: 1.5rem;
}
```

## Usage

Add [PostCSS Has Pseudo] to your project:

```bash
npm install postcss css-has-pseudo --save-dev
```

Use it as a [PostCSS] plugin:

```js
const postcss = require('postcss');
const postcssHasPseudo = require('css-has-pseudo');

postcss([
	postcssHasPseudo(/* pluginOptions */)
]).process(YOUR_CSS /*, processOptions */);
```



## Options

### preserve

The `preserve` option determines whether the original notation
is preserved. By default the original rules are pre7.0.2 • Public • Published 3 months ago
/css-has-pseudo/README.md
/
css-has-pseudo
/
README.md


Back
331 LOC
9.76 kB
# PostCSS Has Pseudo [<img src="https://postcss.github.io/postcss/logo.svg" alt="PostCSS Logo" width="90" height="90" align="right">][PostCSS]

`npm install css-has-pseudo --save-dev`

[PostCSS Has Pseudo] lets you style elements relative to other elements in CSS, following the [Selectors Level 4] specification.

To use this feature you need to do two things :
- add the [PostCSS plugin](#usage) that transforms the selector into a class or attribute
- add the [browser polyfill](#browser) that sets the attribute or class on elements in a browser

```css
.title:has(+ p) {
	margin-bottom: 1.5rem;
}

/* becomes */

.js-has-pseudo [csstools-has-1a-38-2x-38-30-2t-1m-2w-2p-37-14-17-w-34-15]:not(does-not-exist) {
	margin-bottom: 1.5rem;
}
.title:has(+ p) {
	margin-bottom: 1.5rem;
}
```

## Usage

Add [PostCSS Has Pseudo] to your project:

```bash
npm install postcss css-has-pseudo --save-dev
```

Use it as a [PostCSS] plugin:

```js
const postcss = require('postcss');
const postcssHasPseudo = require('css-has-pseudo');

postcss([
	postcssHasPseudo(/* pluginOptions */)
]).process(YOUR_CSS /*, processOptions */);
```



## Options

### preserve

The `preserve` option determines whether the original notation
is preserved. By default the original rules are pre
7.0.2 • Public • Published 3 months ago
/css-has-pseudo/README.md
/
css-has-pseudo
/
README.md


Back
331 LOC
9.76 kB
# PostCSS Has Pseudo [<img src="https://postcss.github.io/postcss/logo.svg" alt="PostCSS Logo" width="90" height="90" align="right">][PostCSS]

`npm install css-has-pseudo --save-dev`

[PostCSS Has Pseudo] lets you style elements relative to other elements in CSS, following the [Selectors Level 4] specification.

To use this feature you need to do two things :
- add the [PostCSS plugin](#usage) that transforms the selector into a class or attribute
- add the [browser polyfill](#browser) that sets the attribute or class on elements in a browser

```css
.title:has(+ p) {
	margin-bottom: 1.5rem;
}

/* becomes */

.js-has-pseudo [csstools-has-1a-38-2x-38-30-2t-1m-2w-2p-37-14-17-w-34-15]:not(does-not-exist) {
	margin-bottom: 1.5rem;
}
.title:has(+ p) {
	margin-bottom: 1.5rem;
}
```

## Usage

Add [PostCSS Has Pseudo] to your project:

```bash
npm install postcss css-has-pseudo --save-dev
```

Use it as a [PostCSS] plugin:

```js
const postcss = require('postcss');
const postcssHasPseudo = require('css-has-pseudo');

postcss([
	postcssHasPseudo(/* pluginOptions */)
]).process(YOUR_CSS /*, processOptions */);
```



## Options

### preserve

The `preserve` option determines whether the original notation
is preserved. By default the original rules are pre
