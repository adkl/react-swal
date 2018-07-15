# react-swal

A React wrapper for [SweetAlert](http://t4t5.github.io/sweetalert/)

## Installation

```
npm install --save react-swal
```

## Usage

##### In your `index.html`:

```html
<link rel="stylesheet" href="../node_modules/sweetalert/dist/sweetalert.css">
```

##### In your React component:

```js
const SweetAlert = require('react-swal');

<SweetAlert isOpen={true}
            type="warning"
            confirmButtonText="Yup"
            cancelButtonText="Nope"
            callback={this.callback} />
```

## Properties

`react-swal` supports all configuration properties supported by SweetAlert. For more info,
see the "Configuration" section of the [SweetAlert docs](http://t4t5.github.io/sweetalert/).

## License

[MIT License](http://opensource.org/licenses/mit-license.html).
