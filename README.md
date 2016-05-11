# numeric-http-status

HTTP status code constants with their numeric value in the key.

Based on https://github.com/wdavidw/node-http-status

## Usage

```js
const numericHttpStatus = require('numeric-http-status');

console.log(numericHttpStatus._100_CONTINUE);
// 100

console.log(numericHttpStatus[numericHttpStatus._100_CONTINUE]);
// 'Continue'
```

Available codes:
```
_100_CONTINUE
_101_SWITCHING_PROTOCOLS
_200_OK
_201_CREATED
_202_ACCEPTED
_203_NON_AUTHORITATIVE_INFORMATION
_204_NO_CONTENT
_205_RESET_CONTENT
_206_PARTIAL_CONTENT
_300_MULTIPLE_CHOICES
_301_MOVED_PERMANENTLY
_302_FOUND
_303_SEE_OTHER
_304_NOT_MODIFIED
_305_USE_PROXY
_307_TEMPORARY_REDIRECT
_400_BAD_REQUEST
_401_UNAUTHORIZED
_402_PAYMENT_REQUIRED
_403_FORBIDDEN
_404_NOT_FOUND
_405_METHOD_NOT_ALLOWED
_406_NOT_ACCEPTABLE
_407_PROXY_AUTHENTICATION_REQUIRED
_408_REQUEST_TIMEOUT
_409_CONFLICT
_410_GONE
_411_LENGTH_REQUIRED
_412_PRECONDITION_FAILED
_413_REQUEST_ENTITY_TOO_LARGE
_414_REQUEST_URI_TOO_LONG
_415_UNSUPPORTED_MEDIA_TYPE
_416_REQUESTED_RANGE_NOT_SATISFIABLE
_417_EXPECTATION_FAILED
_422_UNPROCESSABLE_ENTITY
_429_TOO_MANY_REQUESTS
_451_UNAVAILABLE_FOR_LEGAL_REASONS
_500_INTERNAL_SERVER_ERROR
_501_NOT_IMPLEMENTED
_502_BAD_GATEWAY
_503_SERVICE_UNAVAILABLE
_504_GATEWAY_TIMEOUT
_505_HTTP_VERSION_NOT_SUPPORTED
_507_INSUFFICIENT_STORAGE
```


## Contributing

1. **Fork** the repository. Committing directly against this
repository is highly discouraged.

2. Make your modifications in a branch, updating and writing new unit tests
   as necessary in the `spec` directory.

3. `rebase` your changes against master. *Do not merge*.

4. Submit a pull request to this repository. Wait for tests to run
and someone to chime in.

## Code Style
This repository is configured with [EditorConfig][EditorConfig],
and [eslint][eslint] rules.

[EditorConfig]: http://editorconfig.org/
[eslint]: http://eslint.org/
