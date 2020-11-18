# scss-lit

Watch a folder for .scss changes and transform in .css.js that you can import in your litElement.

Why? Tools for .scss to .css on the fly in html exist. e.g. parcel, webpack, but tools .scss to .js on the fly are less. One is in react create nodejs bootstraping app but doesn't work for lit-element.

## Usage

$ ./bin/scss-lit --help

Usage:
scss-lit <file|folder>

## Import

```
import {style} from './css/app.css';
...
static get styles() {
	return style;
}
```
## Start

$ ./bin/scss-lit src/

render:  /Users/.../src/css/app.css.js
result:  107547
wrote : /Users/.../src/css/app.css.js

## License

MIT
