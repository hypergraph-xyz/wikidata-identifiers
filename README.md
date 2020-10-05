# wikidata-identifiers ![ci](https://github.com/hypergraph-xyz/wikidata-identifiers/workflows/ci/badge.svg)

[WikiData Identifiers](https://www.wikidata.org/wiki/Wikidata:Identifiers) for Hypergraph applications.

## Usage

```js
const identifiers = require('@hypergraph-xyz/wikidata-identifiers')

identifiers.Q17737 === 'Theory'
```

## Installation

```bash
$ npm install @hypergraph-xyz/wikidata-identifiers
```

## API

### identifiers

An object of identifier -> name mappings. Check out [index.json](index.json) for a full list.

## Releasing

```bash
$ npm run release
```
