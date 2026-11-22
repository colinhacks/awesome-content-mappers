# Awesome Content Mappers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Packages that give TypeScript the types of a non-TypeScript file when it is imported.

Content mappers arrived in TypeScript 7.1. A project registers one for a set of file extensions in its `tsconfig.json`:

```jsonc
{
  "contentMappers": [
    { "package": "@astrojs/ts-content-mapper", "extensions": [".astro"] }
  ]
}
```

## Contents

- [Frameworks and components](#frameworks-and-components)
- [Styles](#styles)
- [Documents and data](#documents-and-data)
- [Query languages](#query-languages)
- [APIs](#apis)
- [Other languages](#other-languages)
- [Building content mappers](#building-content-mappers)
- [Resources](#resources)

## Frameworks and components

- [@vue/content-mapper](https://www.npmjs.com/package/@vue/content-mapper) ![GitHub stars](https://img.shields.io/github/stars/vuejs/language-tools?style=flat&label=%E2%98%85) - Types Vue single-file components with `@vue/language-core`.
- [vue-ts-mapper-rs](https://github.com/chatium/vue-ts-mapper-rs) ![GitHub stars](https://img.shields.io/github/stars/chatium/vue-ts-mapper-rs?style=flat&label=%E2%98%85) - Types Vue single-file components, written in Rust.
- [tsc-vue-mapper](https://github.com/kjanat/typebridge/tree/master/vue-mapper) ![GitHub stars](https://img.shields.io/github/stars/kjanat/typebridge?style=flat&label=%E2%98%85) - Types Vue single-file components with Vue language-core and Volar's source maps.
- [@astrojs/ts-content-mapper](https://github.com/withastro/astro/tree/main/packages/language-tools/ts-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/withastro/astro?style=flat&label=%E2%98%85) - Types Astro components.
- [ember-content-mapper](https://github.com/NullVoxPopuli/ember-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/NullVoxPopuli/ember-content-mapper?style=flat&label=%E2%98%85) - Types Ember's `.gts` and `.gjs` files.
- [@tsrx/content-mapper](https://github.com/tsrx-org/tsrx/tree/main/packages/content-mapper) ![GitHub stars](https://img.shields.io/github/stars/tsrx-org/tsrx?style=flat&label=%E2%98%85) - Types TSRX modules.
- [@preact-labs/sfc-content-mapper](https://www.npmjs.com/package/@preact-labs/sfc-content-mapper) - Types Preact single-file components.
- [@usevibejs/language-tools](https://github.com/vibejs/vibejs/tree/main/packages/language-tools) ![GitHub stars](https://img.shields.io/github/stars/vibejs/vibejs?style=flat&label=%E2%98%85) - Types vibe.js single-file components, templates included.
- [@jxsuite/content-mapper](https://github.com/jxsuite/jx/tree/main/packages/content-mapper) ![GitHub stars](https://img.shields.io/github/stars/jxsuite/jx?style=flat&label=%E2%98%85) - Checks the code inside Jx Notation documents.
- [@causeeffect/jsx-content-mapper](https://github.com/crutchcorn/causeeffect/tree/main/packages/jsx-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/crutchcorn/causeeffect?style=flat&label=%E2%98%85) - Types JSX generator components for Effect, with generator types preserved.
- [@webda/content-mapper](https://github.com/loopingz/webda.io/tree/main/packages/content-mapper) ![GitHub stars](https://img.shields.io/github/stars/loopingz/webda.io?style=flat&label=%E2%98%85) - Runs Webda's compile-time code generation on model and service sources.
- [@lwc-bolts/typescript-content-mapper](https://www.npmjs.com/package/@lwc-bolts/typescript-content-mapper) - Types Salesforce metadata as modules for Lightning Web Components.

## Styles

- [css-modules-content-mapper](https://github.com/remcohaszing/css-modules-content-mapper/tree/main/packages/css-modules-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/remcohaszing/css-modules-content-mapper?style=flat&label=%E2%98%85) - Types CSS modules.
- [less-content-mapper](https://github.com/remcohaszing/css-modules-content-mapper/tree/main/packages/less-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/remcohaszing/css-modules-content-mapper?style=flat&label=%E2%98%85) - Types Less CSS modules.
- [sass-content-mapper](https://github.com/remcohaszing/css-modules-content-mapper/tree/main/packages/sass-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/remcohaszing/css-modules-content-mapper?style=flat&label=%E2%98%85) - Types Sass CSS modules.
- [@css-modules-kit/content-mapper](https://github.com/mizdra/css-modules-kit/tree/main/packages/content-mapper) ![GitHub stars](https://img.shields.io/github/stars/mizdra/css-modules-kit?style=flat&label=%E2%98%85) - Types CSS modules and provides css-modules-kit's editor features.
- [typed-css-modules-mapper](https://github.com/JoviDeCroock/typed-css-modules-mapper) ![GitHub stars](https://img.shields.io/github/stars/JoviDeCroock/typed-css-modules-mapper?style=flat&label=%E2%98%85) - Types `.module.css` imports from the CSS, with no generated declaration files.
- [typed-css-imports](https://github.com/danfry1/typed-css-imports) ![GitHub stars](https://img.shields.io/github/stars/danfry1/typed-css-imports?style=flat&label=%E2%98%85) - Types CSS and Sass module class names as postcss-modules exports them.
- [css-modules-mapper](https://github.com/baevm/css-modules-mapper) ![GitHub stars](https://img.shields.io/github/stars/baevm/css-modules-mapper?style=flat&label=%E2%98%85) - Checks CSS module imports against the CSS itself.
- [@weswigham/css-content-mapper](https://github.com/weswigham/css-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/weswigham/css-content-mapper?style=flat&label=%E2%98%85) - Types CSS imports from css-loader's output, with optional Sass support.

## Documents and data

- [Motherload](https://github.com/colinhacks/motherload) ![GitHub stars](https://img.shields.io/github/stars/colinhacks/motherload?style=flat&label=%E2%98%85) - Types TOML, YAML, JSONC, JSON5, CSV, TSV, Markdown, text and `.env` files.
- [mdx-content-mapper](https://github.com/remcohaszing/mdx-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/remcohaszing/mdx-content-mapper?style=flat&label=%E2%98%85) - Types MDX content.
- [json-schema-content-mapper](https://github.com/nfroidure/json-schema-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/nfroidure/json-schema-content-mapper?style=flat&label=%E2%98%85) - Types JSON Schema files with schema2dts.
- [tyfigo](https://github.com/imranbarbhuiya/tyfigo) ![GitHub stars](https://img.shields.io/github/stars/imranbarbhuiya/tyfigo?style=flat&label=%E2%98%85) - Types layered application config in YAML, TOML, JSONC, JSON5, INI, `.properties` and XML.
- [Tottle](https://github.com/dearlordylord/tottle) ![GitHub stars](https://img.shields.io/github/stars/dearlordylord/tottle?style=flat&label=%E2%98%85) - Types the class and property IRIs of Turtle RDF files.
- [@contextual-io/typegen](https://www.npmjs.com/package/@contextual-io/typegen) - Types a Contextual application's `contextual.yaml`.
- [prompt-content-mapper](https://github.com/denisshepelin/prompt-mapper) ![GitHub stars](https://img.shields.io/github/stars/denisshepelin/prompt-mapper?style=flat&label=%E2%98%85) - Types the placeholders of Mustache prompt templates.

## Query languages

- [@gql.tada/content-mapper](https://github.com/0no-co/gql.tada/tree/main/packages/content-mapper) ![GitHub stars](https://img.shields.io/github/stars/0no-co/gql.tada?style=flat&label=%E2%98%85) - Types GraphQL files as gql.tada documents.
- [graphql-content-mapper](https://github.com/SoraKumo001/graphql-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/SoraKumo001/graphql-content-mapper?style=flat&label=%E2%98%85) - Types GraphQL files as typed document nodes and enums, with bundler plugins.
- [@sanity-labs/groq-content-mapper](https://github.com/sanity-labs/groq-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/sanity-labs/groq-content-mapper?style=flat&label=%E2%98%85) - Types GROQ queries from a Sanity schema.
- [Reylo](https://github.com/reylosql/reylo) ![GitHub stars](https://img.shields.io/github/stars/reylosql/reylo?style=flat&label=%E2%98%85) - Types SQL files against a PostgreSQL, MySQL or SQLite database.
- [sqlsure](https://github.com/AfshinJalili/sqlsure) ![GitHub stars](https://img.shields.io/github/stars/AfshinJalili/sqlsure?style=flat&label=%E2%98%85) - Types SQL files against a schema run in an in-process PostgreSQL.
- [ottersql](https://github.com/otterfamily/ottersql) ![GitHub stars](https://img.shields.io/github/stars/otterfamily/ottersql?style=flat&label=%E2%98%85) - Types SQL query files from a schema run in PGlite.
- [trisql](https://github.com/hatappo/trisql) ![GitHub stars](https://img.shields.io/github/stars/hatappo/trisql?style=flat&label=%E2%98%85) - Types 2-way SQL templates against a PostgreSQL schema.
- [Silt](https://github.com/deracs/effect-silt) ![GitHub stars](https://img.shields.io/github/stars/deracs/effect-silt?style=flat&label=%E2%98%85) - Types SQL files as Effect queries on SQLite.

## APIs

- [@sdk-it/content-mapper](https://github.com/JanuaryLabs/sdk-it/tree/main/packages/content-mapper) ![GitHub stars](https://img.shields.io/github/stars/JanuaryLabs/sdk-it?style=flat&label=%E2%98%85) - Types an OpenAPI document as a client SDK.
- [@dyst-no/typed-api](https://www.npmjs.com/package/@dyst-no/typed-api) - Types an OpenAPI, Swagger or WSDL spec as a client, on Bun.
- [openapi-import](https://github.com/kubb-labs/openapi-import) ![GitHub stars](https://img.shields.io/github/stars/kubb-labs/openapi-import?style=flat&label=%E2%98%85) - Types OpenAPI specs with Kubb.
- [inspex](https://github.com/chenxin-yan/inspex) ![GitHub stars](https://img.shields.io/github/stars/chenxin-yan/inspex?style=flat&label=%E2%98%85) - Types OpenAPI documents in the shapes openapi-typescript emits.
- [proto-mapper](https://github.com/sulthonuladib/proto-mapper) ![GitHub stars](https://img.shields.io/github/stars/sulthonuladib/proto-mapper?style=flat&label=%E2%98%85) - Types Protocol Buffers files as gRPC clients, server handlers and messages.

## Other languages

- [interstage](https://github.com/HaukeSchnau/interstage) ![GitHub stars](https://img.shields.io/github/stars/HaukeSchnau/interstage?style=flat&label=%E2%98%85) - Types WGSL shaders as TypeGPU modules.
- [ts-polyglot](https://github.com/mykhailen/ts-polyglot) ![GitHub stars](https://img.shields.io/github/stars/mykhailen/ts-polyglot?style=flat&label=%E2%98%85) - Types functions from C, C++ and Rust files and runs them through Node-API.
- [Workman](https://github.com/goodpuppies/workman) ![GitHub stars](https://img.shields.io/github/stars/goodpuppies/workman?style=flat&label=%E2%98%85) - Compiler and tools for the Workman programming language, a content mapper among them.
- [content-mapper-auto](https://github.com/uhyo/content-mapper-auto) ![GitHub stars](https://img.shields.io/github/stars/uhyo/content-mapper-auto?style=flat&label=%E2%98%85) - Has Claude implement a module described in plain English.

## Building content mappers

- [ts-content-mapper](https://github.com/sxzz/ts-content-mapper) ![GitHub stars](https://img.shields.io/github/stars/sxzz/ts-content-mapper?style=flat&label=%E2%98%85) - SDK with the protocol's types, a mapping builder and a server runner.
- [content-mapper-test-utils](https://github.com/remcohaszing/content-mapper-test-utils) ![GitHub stars](https://img.shields.io/github/stars/remcohaszing/content-mapper-test-utils?style=flat&label=%E2%98%85) - Test utilities for content mappers.
- [muggle-string](https://github.com/johnsoncodehk/muggle-string) ![GitHub stars](https://img.shields.io/github/stars/johnsoncodehk/muggle-string?style=flat&label=%E2%98%85) - Source rewriting that maps the result back as spans and source maps.
- [content-mapper-starter](https://github.com/colinhacks/content-mapper-starter) ![GitHub stars](https://img.shields.io/github/stars/colinhacks/content-mapper-starter?style=flat&label=%E2%98%85) - Starter kit whose one transform types the import and runs in Node.js, Bun, Vite, esbuild and other hosts.
- [content-mapper-sample](https://github.com/DanielRosenwasser/content-mapper-sample) ![GitHub stars](https://img.shields.io/github/stars/DanielRosenwasser/content-mapper-sample?style=flat&label=%E2%98%85) - Sample mapper for script blocks in DHTML files, with an example project and a VS Code extension.

## Resources

- [Announcing TypeScript 7.1 Beta](https://devblogs.microsoft.com/typescript/announcing-typescript-7-1-beta/#content-mappers) - The release post's section on content mappers.
- [Content mappers](https://github.com/microsoft/typescript-go/pull/4712) - The pull request that added content mappers, with an overview of the protocol.
- [Content mappers round 2](https://github.com/microsoft/TypeScript/pull/63936) - The follow-up pull request, with the protocol changes it made.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first.
