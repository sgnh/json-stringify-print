# json-stringify-print
Print an object to the console as formatted JSON.

## Install

```sh
npm install --save json-stringify-print
```

## Usage

```js
const jsonStringifyPrint = require('json-stringify-print'); 
const printMe = {
  hello: 'World!',
};

jsonStringifyPrint(printMe);
```

Outputs:

```json
{
  "hello": "World!"
}
```

## License
MIT © Steffen Hansen