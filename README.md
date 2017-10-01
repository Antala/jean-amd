## Description

Provides a minimal AMD loader for use when all modules are build with r.js into one file. Much shorter than almond.

## Restrictions
- All modules must be located into one file
- All modules must have ids and dependency arrays
- No loading of modules, which have undefined dependencies
- No circular dependency support
- No dynamic code loading
- almond.js restrictions


## Installation

`npm install jean-amd --save --legacy-bundling`

## Tests

- Open spec/spec-runner.html in browser to see the test cases.

## License

MIT