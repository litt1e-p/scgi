# Scgi

browser cache with garbage collection tool

## Installation

```
npm i scgi

```

## Usage

> Notice: cahe will be deleted after expired

```js
import { Scgi } from 'scgi'

let c = new Scgi()

// set value to cache
c.value = { value: 'I am the key', seconds: 10 }

// values of cache
c.values // { value: 'I am the key', seconds: 10 }

```
