# Test-Dependence

[![CI](https://github.com/Trard/test-dependence/actions/workflows/CI.yml/badge.svg)](https://github.com/Trard/CICD-tests/actions/workflows/CI.yml)
[![CD](https://github.com/Trard/test-dependence/actions/workflows/CD.yml/badge.svg)](https://github.com/Trard/CICD-tests/actions/workflows/CD.yml)

Test package for testing tests.

## Installation

Using npm:

```shell
npm i test-dependence
```

Using yarn:

```shell
yarn add test-dependence
```

## Using example

```js
const test = require('test-dependence');

console.log(test.get_random_size_array(1, 10));
```
