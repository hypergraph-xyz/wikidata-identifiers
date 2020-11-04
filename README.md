# wikidata-identifiers <img src="https://raw.githubusercontent.com/hypergraph-xyz/design/main/hypergraph-logomark-1024-square.png" align="right" height="64" />
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

![ci](https://github.com/hypergraph-xyz/wikidata-identifiers/workflows/ci/badge.svg)

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

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/juliangruber"><img src="https://avatars2.githubusercontent.com/u/10247?v=4" width="100px;" alt=""/><br /><sub><b>Julian Gruber</b></sub></a><br /><a href="https://github.com/hypergraph-xyz/wikidata-identifiers/commits?author=juliangruber" title="Code">💻</a> <a href="#infra-juliangruber" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a> <a href="https://github.com/hypergraph-xyz/wikidata-identifiers/commits?author=juliangruber" title="Tests">⚠️</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!