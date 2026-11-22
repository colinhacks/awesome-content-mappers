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

- [@vue/content-mapper](https://www.npmjs.com/package/@vue/content-mapper) - Types Vue single-file components with `@vue/language-core`.
- [vue-ts-mapper-rs](https://github.com/chatium/vue-ts-mapper-rs) - Types Vue single-file components, written in Rust.
- [tsc-vue-mapper](https://github.com/kjanat/typebridge/tree/master/vue-mapper) - Types Vue single-file components with Vue language-core and Volar's source maps.
- [@astrojs/ts-content-mapper](https://github.com/withastro/astro/tree/main/packages/language-tools/ts-content-mapper) - Types Astro components.
- [ember-content-mapper](https://github.com/NullVoxPopuli/ember-content-mapper) - Types Ember's `.gts` and `.gjs` files.
- [@tsrx/content-mapper](https://github.com/tsrx-org/tsrx/tree/main/packages/content-mapper) - Types TSRX modules.
- [@preact-labs/sfc-content-mapper](https://www.npmjs.com/package/@preact-labs/sfc-content-mapper) - Types Preact single-file components.
- [@usevibejs/language-tools](https://github.com/vibejs/vibejs/tree/main/packages/language-tools) - Types vibe.js single-file components, templates included.
- [@jxsuite/content-mapper](https://github.com/jxsuite/jx/tree/main/packages/content-mapper) - Checks the code inside Jx Notation documents.
- [@causeeffect/jsx-content-mapper](https://github.com/crutchcorn/causeeffect/tree/main/packages/jsx-content-mapper) - Types JSX generator components for Effect, with generator types preserved.
- [@webda/content-mapper](https://github.com/loopingz/webda.io/tree/main/packages/content-mapper) - Runs Webda's compile-time code generation on model and service sources.
- [@lwc-bolts/typescript-content-mapper](https://www.npmjs.com/package/@lwc-bolts/typescript-content-mapper) - Types Salesforce metadata as modules for Lightning Web Components.

## Styles

- [css-modules-content-mapper](https://github.com/remcohaszing/css-modules-content-mapper/tree/main/packages/css-modules-content-mapper) - Types CSS modules.
- [less-content-mapper](https://github.com/remcohaszing/css-modules-content-mapper/tree/main/packages/less-content-mapper) - Types Less CSS modules.
- [sass-content-mapper](https://github.com/remcohaszing/css-modules-content-mapper/tree/main/packages/sass-content-mapper) - Types Sass CSS modules.
- [@css-modules-kit/content-mapper](https://github.com/mizdra/css-modules-kit/tree/main/packages/content-mapper) - Types CSS modules and provides css-modules-kit's editor features.
- [typed-css-modules-mapper](https://github.com/JoviDeCroock/typed-css-modules-mapper) - Types `.module.css` imports from the CSS, with no generated declaration files.
- [typed-css-imports](https://github.com/danfry1/typed-css-imports) - Types CSS and Sass module class names as postcss-modules exports them.
- [css-modules-mapper](https://github.com/baevm/css-modules-mapper) - Checks CSS module imports against the CSS itself.
- [@weswigham/css-content-mapper](https://github.com/weswigham/css-content-mapper) - Types CSS imports from css-loader's output, with optional Sass support.

## Documents and data

- [Motherload](https://github.com/colinhacks/motherload) - Types TOML, YAML, JSONC, JSON5, CSV, TSV, Markdown, text and `.env` files.
- [mdx-content-mapper](https://github.com/remcohaszing/mdx-content-mapper) - Types MDX content.
- [json-schema-content-mapper](https://github.com/nfroidure/json-schema-content-mapper) - Types JSON Schema files with schema2dts.
- [tyfigo](https://github.com/imranbarbhuiya/tyfigo) - Types layered application config in YAML, TOML, JSONC, JSON5, INI, `.properties` and XML.
- [Tottle](https://github.com/dearlordylord/tottle) - Types the class and property IRIs of Turtle RDF files.
- [@contextual-io/typegen](https://www.npmjs.com/package/@contextual-io/typegen) - Types a Contextual application's `contextual.yaml`.
- [prompt-content-mapper](https://github.com/denisshepelin/prompt-mapper) - Types the placeholders of Mustache prompt templates.

## Query languages

- [@gql.tada/content-mapper](https://github.com/0no-co/gql.tada/tree/main/packages/content-mapper) - Types GraphQL files as gql.tada documents.
- [graphql-content-mapper](https://github.com/SoraKumo001/graphql-content-mapper) - Types GraphQL files as typed document nodes and enums, with bundler plugins.
- [@sanity-labs/groq-content-mapper](https://github.com/sanity-labs/groq-content-mapper) - Types GROQ queries from a Sanity schema.
- [Reylo](https://github.com/reylosql/reylo) - Types SQL files against a PostgreSQL, MySQL or SQLite database.
- [sqlsure](https://github.com/AfshinJalili/sqlsure) - Types SQL files against a schema run in an in-process PostgreSQL.
- [ottersql](https://github.com/otterfamily/ottersql) - Types SQL query files from a schema run in PGlite.
- [trisql](https://github.com/hatappo/trisql) - Types 2-way SQL templates against a PostgreSQL schema.
- [Silt](https://github.com/deracs/effect-silt) - Types SQL files as Effect queries on SQLite.

## APIs

- [@sdk-it/content-mapper](https://github.com/JanuaryLabs/sdk-it/tree/main/packages/content-mapper) - Types an OpenAPI document as a client SDK.
- [@dyst-no/typed-api](https://www.npmjs.com/package/@dyst-no/typed-api) - Types an OpenAPI, Swagger or WSDL spec as a client, on Bun.
- [openapi-import](https://github.com/kubb-labs/openapi-import) - Types OpenAPI specs with Kubb.
- [inspex](https://github.com/chenxin-yan/inspex) - Types OpenAPI documents in the shapes openapi-typescript emits.
- [proto-mapper](https://github.com/sulthonuladib/proto-mapper) - Types Protocol Buffers files as gRPC clients, server handlers and messages.

## Other languages

- [interstage](https://github.com/HaukeSchnau/interstage) - Types WGSL shaders as TypeGPU modules.
- [ts-polyglot](https://github.com/mykhailen/ts-polyglot) - Types functions from C, C++ and Rust files and runs them through Node-API.
- [Workman](https://github.com/goodpuppies/workman) - Compiler and tools for the Workman programming language, a content mapper among them.
- [content-mapper-auto](https://github.com/uhyo/content-mapper-auto) - Has Claude implement a module described in plain English.

## Building content mappers

- [ts-content-mapper](https://github.com/sxzz/ts-content-mapper) - SDK with the protocol's types, a mapping builder and a server runner.
- [content-mapper-test-utils](https://github.com/remcohaszing/content-mapper-test-utils) - Test utilities for content mappers.
- [muggle-string](https://github.com/johnsoncodehk/muggle-string) - Source rewriting that maps the result back as spans and source maps.
- [content-mapper-starter](https://github.com/colinhacks/content-mapper-starter) - Starter kit whose one transform types the import and runs in Node.js, Bun, Vite, esbuild and other hosts.
- [content-mapper-sample](https://github.com/DanielRosenwasser/content-mapper-sample) - Sample mapper for script blocks in DHTML files, with an example project and a VS Code extension.

## Resources

- [Announcing TypeScript 7.1 Beta](https://devblogs.microsoft.com/typescript/announcing-typescript-7-1-beta/#content-mappers) - The release post's section on content mappers.
- [Content mappers](https://github.com/microsoft/typescript-go/pull/4712) - The pull request that added content mappers, with an overview of the protocol.
- [Content mappers round 2](https://github.com/microsoft/TypeScript/pull/63936) - The follow-up pull request, with the protocol changes it made.

## Contributing

Contributions are welcome. Read the [contribution guidelines](contributing.md) first.
