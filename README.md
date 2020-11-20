# `@reason-react-native/fetch-blob`

[![Build Status](https://github.com/reason-react-native/fetch-blob/workflows/Build/badge.svg)](https://github.com/reason-react-native/fetch-blob/actions)
[![Version](https://img.shields.io/npm/v/@reason-react-native/fetch-blob.svg)](https://www.npmjs.com/@reason-react-native/fetch-blob)
[![Chat](https://img.shields.io/discord/235176658175262720.svg?logo=discord&colorb=blue)](https://reasonml-community.github.io/reason-react-native/discord/)

[ReScript](https://rescript-lang.org) / [Reason](https://reasonml.github.io) bindings for
[`rn-fetch-blob`](https://github.com/joltup/rn-fetch-blob).

Exposed as `ReactNativeFetchBlob` module.

**⚠️ Incomplete bindings!**

`@reason-react-native/fetch-blob` X.y.\* means it's compatible with
`rn-fetch-blob` X.y.\*

## Installation

When [`rn-fetch-blob`](https://github.com/joltup/rn-fetch-blob) is properly
installed & configured by following their installation instructions, you can
install the bindings:

```console
npm install @reason-react-native/fetch-blob
# or
yarn add @reason-react-native/fetch-blob
```

`@reason-react-native/fetch-blob` should be added to `bs-dependencies` in your
`bsconfig.json`:

```diff
{
  //...
  "bs-dependencies": [
    "reason-react",
    "reason-react-native",
    // ...
+    "@reason-react-native/fetch-blob"
  ],
  //...
}
```

## Usage

@todo

---

## Changelog

Check the [changelog](./CHANGELOG.md) for more informations about recent
releases.

## Contribute

Read the [contribution guidelines](https://github.com/reason-react-native/.github/blob/master/CONTRIBUTING.md) before contributing.

## Code of Conduct

We want this community to be friendly and respectful to each other. Please read
[our full code of conduct](https://github.com/reason-react-native/.github/blob/master/CODE_OF_CONDUCT.md) so that you can understand what
actions will and will not be tolerated.
