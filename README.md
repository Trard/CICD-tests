# Test-Dependence

Test [Dependence](https://github.com/Trard/test-dependence) for [Dependent](https://github.com/Trard/test-dependent).

[![CI](https://github.com/Trard/test-dependence/actions/workflows/CI.yml/badge.svg)](https://github.com/Trard/CICD-tests/actions/workflows/CI.yml)
[![CD](https://github.com/Trard/test-dependence/actions/workflows/CD.yml/badge.svg)](https://github.com/Trard/CICD-tests/actions/workflows/CD.yml)

## Contents

1. [Installation](https://github.com/trard/test-dependence/blob/master/README.md#installation)
    - [NPM](https://github.com/trard/test-dependence/blob/master/README.md#npm)
    - [Yarn](https://github.com/trard/test-dependence/blob/master/README.md#yarn)
2. [Example](https://github.com/trard/test-dependence/blob/master/README.md#example)

## Installation

### NPM

```shell
npm i test-dependence
```

### Yarn

```shell
yarn add test-dependence
```

## Example

```js
const test = require('test-dependence');

console.log(test.get_random_size_array(1, 10));
```
