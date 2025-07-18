# Awesome Zod [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
## Contents

- [About this List](#about-this-list)
- [Docs](#docs)
- [APIs and Servers](#apis-and-servers)
- [Convertors and Generators](#convertors-and-generators)
- [CLIs](#clis)
- [Other](#other)
- [Projects Using Zod](#projects-using-zod)
- [Tutorials](#tutorials)
    - [Tutorials with tRPC](#tutorials-with-trpc)
- [Contribute](#contribute)

## About this List

This is a collection of **awesome resources** about [Zod](https://github.com/colinhacks/zod 'TypeScript-first schema declaration and validation library')

**Zod is a TypeScript-first schema declaration and validation library**. It is designed to be as developer-friendly as possible. The goal is to eliminate duplicate type declarations. With Zod, you declare a validator once and Zod will automatically infer the static TypeScript type. It's easy to compose simpler types into complex data structures.

## Docs

- [Zod Docs](https://github.com/colinhacks/zod/tree/master/docs)

## APIs and Servers

- [`tRPC`](https://github.com/trpc/trpc) - Build end-to-end type-safe APIs without GraphQL.
- [`express-zod-api`](https://github.com/RobinTail/express-zod-api) - Build Express-based APIs with I/O schema validation and custom middlewares.
- [`zod-endpoints`](https://github.com/flock-community/zod-endpoints) - Contract-first strictly typed endpoints with Zod. OpenAPI compatible.
- [`@anatine/zod-nestjs`](https://github.com/anatine/zod-plugins/tree/main/libs/zod-nestjs) - Helper methods for using Zod in a NestJS project.
- [`fastify-type-provider-zod`](https://github.com/turkerdev/fastify-type-provider-zod) - Create Fastify type providers from Zod schemas.
- [`zod-http-schemas`](https://github.com/Skutopia-org/zod-http-schemas) - Uses zod to define well typed API, generate a router that enforces and validates the api at runtime, & generate a well-typed client.
- [`fastify-zod`](https://github.com/elierotenberg/fastify-zod) - Zod integration with Fastify.
- [`zod-json-rpc`](https://www.npmjs.com/package/zod-json-rpc) - Lets you rapidly build typesafe JSON-RPC servers and clients in TypeScript. Not only that, it is self-describing via its advanced introspection API, which can output JSON Schema or source code in multiple languages.
- [`zod-express-middleware`](https://github.com/Aquila169/zod-express-middleware) - Middleware for express that uses zod to make requests type-safe.
- [`ts-rest`](https://github.com/ts-rest/ts-rest) - RPC-like client, contract, and server implementation for a pure REST API.
- [`zodios`](https://github.com/ecyrbe/zodios) - A typescript api client with auto-completion features backed by axios and zod.
- [`@lambda-func/zod`](https://github.com/connorgiles/lambda-func) - A middleware to use zod for type parsing.
- [`zod-express-guard`](https://github.com/roziscoding/zod-express-guard) - Small package intended to use zod to make express request type-safe.

## Convertors and Generators

- [`prisma-zod-generator`](https://github.com/omar-dulaimi/prisma-zod-generator) - Prisma 2+ generator to emit Zod schemas from your Prisma schema.
- [`ts-to-zod`](https://github.com/fabien0102/ts-to-zod) - Convert TypeScript definitions into Zod schemas.
- [`zod-to-ts`](https://github.com/sachinraja/zod-to-ts) - Generate TypeScript definitions from Zod schemas.
- [`@anatine/zod-mock`](https://github.com/anatine/zod-plugins/tree/main/libs/zod-mock) - Generate mock data from a Zod schema. Powered by [faker.js](https://github.com/Marak/Faker.js).
- [`zod-mocking`](https://github.com/dipasqualew/zod-mocking) - Generate mock data from your Zod schemas.
- [`zod-fast-check`](https://github.com/DavidTimms/zod-fast-check) - Generate `fast-check` arbitraries from Zod schemas.
- [`zod-to-json-schema`](https://github.com/StefanTerdell/zod-to-json-schema) - Convert your Zod schemas into JSON Schemas.
- [`json-schema-to-zod`](https://github.com/StefanTerdell/json-schema-to-zod) - Convert your JSON Schemas into Zod schemas.
- [`json-to-zod`](https://github.com/rsinohara/json-to-zod) - Convert JSON objects into Zod schemas.
- [`zod-prisma`](https://github.com/CarterGrimmeisen/zod-prisma) - Generate Zod schemas from your Prisma schema.
- [`Supervillain`](https://github.com/Southclaws/supervillain) - Generate Zod schemas from your Go structs.
- [`@anatine/zod-openapi`](https://github.com/anatine/zod-plugins/tree/main/libs/zod-openapi) - Converts a Zod schema to an OpenAPI v3.x `SchemaObject`.
- [`zod-dto`](https://github.com/kbkk/abitia/tree/master/packages/zod-dto) - Generate Nest.js DTOs from a Zod schema.
- [`graphql-codegen-typescript-validation-schema`](https://github.com/Code-Hex/graphql-codegen-typescript-validation-schema) - GraphQL Code Generator plugin to generate form validation schema from your GraphQL schema.
- [`graphql-codegen-zod`](https://github.com/withshepherd/graphql-codegen-zoda) - GraphQL codegen schema to Zod schema.
- [`zod-to-openapi`](https://github.com/asteasolutions/zod-to-openapi) - Generate full OpenAPI (Swagger) docs from Zod, including schemas, endpoints & parameters.
- [`pgzod`](https://github.com/owncoral/pgzod) - Transform PostgreSQL schemas into Zod validators and types.
- [`atlas2ts`](https://www.npmjs.com/package/atlas2ts) - Generates typescript interfaces or zod typespecs from atlas DDL specification.
- [`kanel-zod`](https://www.npmjs.com/package/kanel-zod) - Generates Zod schemas from a live Postgres database.

## CLIs

- [`soly`](https://github.com/mdbetancourt/soly) - Create CLI applications with zod.

## Other
- [`zod-match`](https://www.npmjs.com/package/zod-match) - Adds a resultify method to ZodTypes so you can match Without Exceptions™️!.
- [`zod-joda`](https://github.com/dasprid/zod-joda) - JS-Joda integration for Zod validation library.
- [`zod-localstorage`](https://github.com/bigbeno37/zod-localstorage) - A Typescript library to allow typesafe access to localstorage using schema validation from Zod.
- [`zod-formik-adapter`](https://github.com/robertLichtnow/zod-formik-adapter) - Formik adapter for Zod.
- [`@felte/validator-zod`](https://github.com/pablo-abc/felte/tree/main/packages/validator-zod) - Handle validation with Zod in Felte.

## Projects Using Zod
- [`prisma-trpc-generator`](https://github.com/omar-dulaimi/prisma-trpc-generator) - Prisma 2+ generator to emit fully implemented tRPC routers.
- [`@danprince/zhttp`](https://github.com/danprince/zhttp) - A small library that brings zod, express, and static-path together to create type safe HTTP endpoints for clients and servers.
- [`@renke/vod`](https://www.npmjs.com/package/@renke/vod) - Immutable, type-safe, validated, nominal value objects in TypeScript based on @renke/vo and zod.
- [`react-zorm`](https://github.com/esamattis/react-zorm) - Type-safe <form> for React using Zod!.
- [`daruk`](https://github.com/darukjs/daruk) - A Node.js web framework based on typescript.
- [`shrub`](https://github.com/jjvainav/shrub) - A framework for building modular Node.js apps and front-end components.
- [`react-hook-form`](https://github.com/react-hook-form/react-hook-form) - React Hooks for form state management and validation (Web + React Native).
- [`YAMLResume`](https://github.com/yamlresume/yamlresume) - A resume compiler/transpiler that allow people to write resumes in YAML and provide clang-style validations.

## Tutorials

### Tutorials with tRPC
- [`Build a full-stack TypeScript app using tRPC and React`](https://blog.logrocket.com/build-full-stack-typescript-app-trpc-react)


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
