# input-time-polyfill
Polyfill for time input.
Use this for IE and Safari support or for standardize UI behaviour.

Support dynamically created inputs, so can be used in single page applications.

Forked from [date-input-polyfill](https://github.com/jcgertig/date-input-polyfill). Continuing and fixed as a separate project.

**Demo available here**: https://codepen.io/epavanello/pen/RwoqVvx

## Install
`npm install --save input-time-polyfill`

Add to your project:

* **Webpack/Browserify:** `require('input-time-polyfill');`

    or alongside **Babel:** `import 'input-time-polyfill';`

* **Script Tag:** Copy `input-time-polyfill.dist.js` from `node_modules` and
include it anywhere in your HTML.

* This package also supports **AMD**.

## Features

* **Keyboard Shortcuts:** `Esc` will hide the timepicker. `Up/Down` will
increment/decrement the hours/minutes by one.

### Local Development
Run `npm start`

### Build
Run `npm run build`
