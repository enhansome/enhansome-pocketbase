# Awesome PocketBase with stars

![GitHub forks](https://img.shields.io/github/stars/benallfree/awesome-pocketbase?style=flat) ![GitHub forks](https://img.shields.io/github/forks/benallfree/awesome-pocketbase?style=flat) ![GitHub forks](https://img.shields.io/github/contributors/benallfree/awesome-pocketbase?style=flat)

> Curated list of awesome [PocketBase](https://pocketbase.io) resources.

PocketBase is an open source backend consisting of embedded database (SQLite) with realtime subscriptions, built-in auth management, convenient dashboard UI and simple REST-ish API.

## Contents

* [Official Packages](#official-packages)
* [Forks](#forks)
* [Top PocketBase-specific Projects (>100 stars)](#top-pocketbase-specific-projects-100-stars)
* [Major Community Projects](#major-community-projects)
* [JSVM Plugins](#jsvm-plugins)
* [Go Plugins](#go-plugins)
* [React](#react)
* [Svelte](#svelte)
* [Dart/Flutter](#dartflutter)
* [C#](#c)
* [Unofficial PocketBase Clients (SDKs)](#unofficial-pocketbase-clients-sdks)
* [Self Hosting](#self-hosting)
* [TypeScript tools](#typescript-tools)
* [SQLite tools](#sqlite-tools)
* [Other tools](#other-tools)
* [Showcases](#showcases)
* [Unmaintained](#unmaintained)

## Official Packages

PocketBase moved its repositories from GitHub to [ganigeorgiev.com](https://ganigeorgiev.com/pocketbase); the GitHub repositories are archived. Star counts below are from the archived GitHub repositories.

* [Golang Server](https://ganigeorgiev.com/pocketbase/pocketbase/releases) - The main PocketBase server. ![GitHub Repo stars](https://img.shields.io/github/stars/pocketbase/pocketbase)

* [JavaScript SDK](https://ganigeorgiev.com/pocketbase/js-sdk) - Browser and Node.js for interacting with the PocketBase API. ![GitHub Repo stars](https://img.shields.io/github/stars/pocketbase/js-sdk)

* [Dart SDK](https://ganigeorgiev.com/pocketbase/dart-sdk) - Multi-platform SDK for interacting with the PocketBase Web API. ![GitHub Repo stars](https://img.shields.io/github/stars/pocketbase/dart-sdk)

## Forks

* [PostgreBase](https://github.com/zhenruyan/postgrebase) ⭐ 101 | 🐛 1 | 🌐 Go | 📅 2026-10-14 - A PocketBase fork with PostgreSQL and MySQL support alongside SQLite, a built-in MCP server and Redis or in-memory caching, keeping the PocketBase API. ![GitHub Repo stars](https://img.shields.io/github/stars/zhenruyan/postgrebase)
* [PocketOne](https://pocketone.dev) - An open, community-driven fork of PocketBase. Features live in Go extensions that connect only through versioned contracts, so anyone can contribute (PITR, bulk mail, WASM, an updated JSVM, and more) without touching core. Not affiliated with PocketBase. ![GitHub Repo stars](https://img.shields.io/github/stars/pocketonehq/pocketone)

## Top PocketBase-specific Projects (>100 stars)

* [PocketBase Typegen](https://github.com/patmood/pocketbase-typegen) ⭐ 832 | 🐛 7 | 🌐 TypeScript | 📅 2026-10-30 - Generate TypeScript types from the SQLite db file. ![GitHub Repo stars](https://img.shields.io/github/stars/patmood/pocketbase-typegen)
* [PocketBase Docker](https://github.com/muchobien/pocketbase-docker) ⭐ 574 | 🐛 1 | 🌐 Shell | 📅 2026-11-16 - Docker setup supporting multiple architectures and automatically updated with PocketBase releases. ![GitHub Repo stars](https://img.shields.io/github/stars/muchobien/pocketbase-docker)
* [Python SDK](https://github.com/vaphes/pocketbase) ⭐ 548 | 🐛 16 | 🌐 Python | 📅 2026-05-20 - PocketBase client in Python. ![GitHub Repo stars](https://img.shields.io/github/stars/vaphes/pocketbase)
* [SvelteKit Starter](https://github.com/spinspire/pocketbase-sveltekit-starter) ⭐ 510 | 🐛 3 | 🌐 Svelte | 📅 2026-08-22 - A starter-kit showing how to use customized PocketBase as a backend to SvelteKit frontend. ![GitHub Repo stars](https://img.shields.io/github/stars/spinspire/pocketbase-sveltekit-starter)
* [SvelteKit PocketBase Auth](https://github.com/jianyuan/pocketbase-sveltekit-auth) ⭐ 234 | 🐛 16 | 🌐 Svelte | 📅 2026-11-26 - Demo login and registration pages with examples. ![GitHub Repo stars](https://img.shields.io/github/stars/jianyuan/pocketbase-sveltekit-auth)
* [PocketBase+Stripe](https://github.com/mrwyndham/pocketbase-stripe) ⭐ 226 | 🐛 1 | 🌐 Go | 📅 2026-10-20 - Go extended PocketBase for Stripe subscription integration. ![GitHub Repo stars](https://img.shields.io/github/stars/mrwyndham/pocketbase-stripe)
* [pocketbase-mcp](https://github.com/mrwyndham/pocketbase-mcp) ⭐ 156 | 🐛 2 | 🌐 TypeScript | 📅 2026-10-20 - MCP server for building PocketBase apps with AI assistants. ![GitHub Repo stars](https://img.shields.io/github/stars/mrwyndham/pocketbase-mcp)
* [pb-ext](https://github.com/magooney-loon/pb-ext) ⭐ 118 | 🐛 0 | 🌐 Go | 📅 2026-07-27 - Enhanced PocketBase server with monitoring, logging & API docs. ![GitHub Repo stars](https://img.shields.io/github/stars/magooney-loon/pb-ext)
* [refine-pocketbase](https://github.com/kruschid/refine-pocketbase) ⭐ 106 | 🐛 2 | 🌐 TypeScript | 📅 2026-04-07 - Data, auth and live providers for building refine apps on PocketBase. ![GitHub Repo stars](https://img.shields.io/github/stars/kruschid/refine-pocketbase)
* [PocketBlocks](https://github.com/pedrozadotdev/pocketblocks) ⭐ 106 | 🐛 0 | 🌐 TypeScript | 📅 2025-11-26 - Openblocks low-code app builder integrated with PocketBase. ![GitHub Repo stars](https://img.shields.io/github/stars/pedrozadotdev/pocketblocks)
* [pockethost.io](https://pockethost.io) - Pro PocketBase hosting. ![GitHub Repo stars](https://img.shields.io/github/stars/pockethost/pockethost)
* [PocketBaseUML](https://pocketbase-uml.github.io/) - Generate UML diagrams from PocketBase databases. ![GitHub Repo stars](https://img.shields.io/github/stars/pocketbase-uml/pocketbase-uml.github.io)

## Major Community Projects

* [PocketPages](https://pocketone.dev/docs/extensions/pages) - Server-side JS pages for PocketBase, built into PocketOne.
* [PocketCon 2027](https://pocketcon.dev) - A free online PocketBase conference on Saturday, February 6, 2027.

## JSVM Plugins

* [pocketbase-presigned-urls](https://github.com/benallfree/pocketbase-presigned-urls) ⭐ 15 | 🐛 0 | 🌐 JavaScript | 📅 2024-12-03 - Serve file uploads from presigned S3 URLs. ![GitHub Repo stars](https://img.shields.io/github/stars/benallfree/pocketbase-presigned-urls)

## Go Plugins

* [pocketbase-ha](https://github.com/litesql/pocketbase-ha) ⭐ 94 | 🐛 2 | 🌐 Go | 📅 2026-11-22 - Highly available leader or leaderless PocketBase cluster built on the go-ha database/sql driver. ![GitHub Repo stars](https://img.shields.io/github/stars/litesql/pocketbase-ha)
* [Telegram auth](https://github.com/iamelevich/pocketbase-plugin-telegram-auth) ⭐ 51 | 🐛 5 | 🌐 Go | 📅 2026-11-10 - Add Telegram auth (Widget button and WebApp). ![GitHub Repo stars](https://img.shields.io/github/stars/iamelevich/pocketbase-plugin-telegram-auth)
* [pocketbase-gogen](https://github.com/Snonky/pocketbase-gogen) ⭐ 43 | 🐛 1 | 🌐 Go | 📅 2025-10-25 - Generate data model structs from a PocketBase schema. ![GitHub Repo stars](https://img.shields.io/github/stars/Snonky/pocketbase-gogen)
* [TypeScript Generator](https://github.com/Vogeslu/pocketbase-ts-generator) ⭐ 37 | 🐛 0 | 🌐 Go | 📅 2025-08-17 - Standalone tool or library that generates TypeScript types, with auto-generation hook or command. ![GitHub Repo stars](https://img.shields.io/github/stars/Vogeslu/pocketbase-ts-generator)
* [Proxy](https://github.com/iamelevich/pocketbase-plugin-proxy) ⭐ 23 | 🐛 1 | 🌐 Go | 📅 2026-11-11 - Forward requests to another host. Can be useful when you want to use separate server as frontend (like Next.js), but serve everything with same port. ![GitHub Repo stars](https://img.shields.io/github/stars/iamelevich/pocketbase-plugin-proxy)
* [Ngrok](https://github.com/iamelevich/pocketbase-plugin-ngrok) ⭐ 11 | 🐛 2 | 🌐 Go | 📅 2026-11-17 - Expose local PocketBase to the internet with ngrok. ![GitHub Repo stars](https://img.shields.io/github/stars/iamelevich/pocketbase-plugin-ngrok)
* [Webhooks](https://gist.github.com/cugu/9e74f75dcad3df74370c71ff3c02085a) - Add webhook support in the admin UI to send `create`, `update` and `delete` events on selected collections via POST request to other systems.

## React

* [PocketBase React](https://github.com/tobicrain/pocketbase-react) ⭐ 86 | 🐛 3 | 🌐 TypeScript | 📅 2025-02-24 - Unofficial React SDK (React, React Native, Expo) for interacting with the PocketBase JavaScript SDK. ![GitHub Repo stars](https://img.shields.io/github/stars/tobicrain/pocketbase-react)
* [pbtsdb](https://github.com/nathanstitt/pbtsdb) ⭐ 26 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-20 - A type-safe TanStack DB adapter to easily create LiveQueries with real-time subscriptions. ![GitHub Repo stars](https://img.shields.io/github/stars/nathanstitt/pbtsdb)
* [Next.js PocketBase Auth](https://github.com/jianyuan/pocketbase-nextjs-auth) ⭐ 24 | 🐛 11 | 🌐 TypeScript | 📅 2026-11-27 - Sample Next.js 15 application with PocketBase integration, a typed client, server-side and client-side rendering techniques, and server actions. ![GitHub Repo stars](https://img.shields.io/github/stars/jianyuan/pocketbase-nextjs-auth)
* [next-pocketbase-auth](https://github.com/g12i/next-pocketbase-auth) ⭐ 10 | 🐛 0 | 🌐 TypeScript | 📅 2025-01-30 - A lightweight authentication wrapper for Next.js applications, providing easy-to-use utilities for handling user session in both client and server components. ![GitHub Repo stars](https://img.shields.io/github/stars/g12i/next-pocketbase-auth)

## Svelte

* [pocketbase-sveltekit-static](https://github.com/Egor-S/pocketbase-sveltekit-static) ⭐ 49 | 🐛 0 | 🌐 Svelte | 📅 2026-11-21 - A minimalist template with configured authorization featuring a single Docker image (from 55 MB) for deploying. ![GitHub Repo stars](https://img.shields.io/github/stars/Egor-S/pocketbase-sveltekit-static)

## Dart/Flutter

* [PocketBase Server Flutter](https://github.com/rohitsangwan01/pocketbase_server_flutter) ⭐ 52 | 🐛 5 | 🌐 Kotlin | 📅 2025-02-14 - A Flutter plugin to run PocketBase server directly from Android/iOS. ![GitHub Repo stars](https://img.shields.io/github/stars/rohitsangwan01/pocketbase_server_flutter)

## C\#

* [PocketBaseSharp](https://github.com/PSCourtney/PocketBaseSharp) ⭐ 45 | 🐛 0 | 🌐 C# | 📅 2026-11-11 - C# SDK for PocketBase and demo Blazor WebAssembly webapp. ![GitHub Repo stars](https://img.shields.io/github/stars/PSCourtney/PocketBaseSharp)

## Unofficial PocketBase Clients (SDKs)

* [Go](https://github.com/pluja/pocketbase) ⭐ 81 | 🐛 4 | 🌐 Go | 📅 2025-01-22 - PocketBase Client in Golang. ![GitHub Repo stars](https://img.shields.io/github/stars/pluja/pocketbase)
* [Swift](https://github.com/briannadoubt/PocketBase) ⭐ 75 | 🐛 2 | 🌐 Swift | 📅 2026-05-11 - PocketBase client for iOS, macOS, watchOS, tvOS and visionOS. ![GitHub Repo stars](https://img.shields.io/github/stars/briannadoubt/PocketBase)
* [Python (Async)](https://github.com/thijsmie/pocketbase) ⭐ 74 | 🐛 2 | 🌐 Python | 📅 2026-10-12 - PocketBase Client in Python. ![GitHub Repo stars](https://img.shields.io/github/stars/thijsmie/pocketbase)
* [Rust](https://github.com/sreedevk/pocketbase-sdk-rust) ⭐ 73 | 🐛 2 | 🌐 Rust | 📅 2026-07-26 - PocketBase Client in Rust. ![GitHub Repo stars](https://img.shields.io/github/stars/sreedevk/pocketbase-sdk-rust)
* [Kotlin](https://github.com/agrevster/pocketbase-kotlin) ⭐ 67 | 🐛 1 | 🌐 Kotlin | 📅 2026-04-09 - PocketBase Client in Kotlin. ![GitHub Repo stars](https://img.shields.io/github/stars/agrevster/pocketbase-kotlin)
* [Unity (Multiplatform)](https://github.com/Sov3rain/pocketbase-unity) ⭐ 22 | 🐛 1 | 🌐 C# | 📅 2026-03-30 - PocketBase client for Unity 3D game engine. ![GitHub Repo stars](https://img.shields.io/github/stars/Sov3rain/pocketbase-unity)
* [Kotlin (Multiplatform)](https://github.com/IdanAizikNissim/pocketbase-kt) ⭐ 11 | 🐛 2 | 🌐 Kotlin | 📅 2026-02-12 - PocketBase Client in Kotlin. ![GitHub Repo stars](https://img.shields.io/github/stars/IdanAizikNissim/pocketbase-kt)
* [Ruby](https://github.com/azmi2409/pocketbase-ruby) ⭐ 0 | 🐛 0 | 🌐 Ruby | 📅 2026-10-17 - PocketBase Client in Ruby. ![GitHub Repo stars](https://img.shields.io/github/stars/azmi2409/pocketbase-ruby)

## Self Hosting

* [DigitalOcean](https://github.com/pocketbase/pocketbase/discussions/512) ⚠️ Archived - Guide to deploy in a Droplet.
* [Fly.io](https://github.com/pocketbase/pocketbase/discussions/537) ⚠️ Archived - Guide to deploy for free in Fly.io.
* [Coolify PocketBase images](https://github.com/coollabsio/pocketbase) ⭐ 89 | 🐛 0 | 🌐 Dockerfile | 📅 2026-11-09 - Unofficial Docker images for ARM and AMD. ![GitHub Repo stars](https://img.shields.io/github/stars/coollabsio/pocketbase)
* [pb-deployer](https://github.com/magooney-loon/pb-deployer) ⭐ 51 | 🐛 0 | 🌐 Svelte | 📅 2026-06-20 - Automates the lifecycle of deploying PocketBase apps to production ![GitHub Repo stars](https://img.shields.io/github/stars/magooney-loon/pb-deployer)
* [PBLauncher](https://github.com/user0608/pb_launcher) ⭐ 35 | 🐛 3 | 🌐 Go | 📅 2026-10-23 - Manage PocketBase instances — fast, lightweight, open source. ![GitHub Repo stars](https://img.shields.io/github/stars/user0608/pb_launcher)
* [PocketBase on Dokku](https://github.com/blockshiftnetwork/dokku-pocketbase) ⭐ 25 | 🐛 1 | 🌐 Dockerfile | 📅 2025-06-05 - Deploy PocketBase instances on Dokku effortlessly. ![GitHub Repo stars](https://img.shields.io/github/stars/blockshiftnetwork/dokku-pocketbase)
* [PocketBase Docker](https://github.com/kdpuvvadi/pocketbase) ⭐ 13 | 🐛 0 | 🌐 Dockerfile | 📅 2026-11-17 - Docker images supporting multiple architectures and updated with latest PocketBase releases. ![GitHub Repo stars](https://img.shields.io/github/stars/kdpuvvadi/pocketbase)
* [AWS Lightsail](https://github.com/boustanihani/pocketbase-lightsail-hosting) ⭐ 3 | 🐛 0 | 🌐 Shell | 📅 2026-11-25 - Guide to deploy to AWS Lightsail.
* [Railway](https://github.com/metruzanca/pocketbase_railway) ⭐ 0 | 🐛 0 | 🌐 Dockerfile | 📅 2025-11-23 - Guide to deploy on Railway.
* [LocalXpose](https://localxpose.io/docs/tutorials/expose-pocketbase-backend) - Allow public access to a localhost instance.

## TypeScript tools

* [astro-loader-pocketbase](https://github.com/pawcoding/astro-loader-pocketbase) ⭐ 63 | 🐛 12 | 🌐 TypeScript | 📅 2026-11-14 - Astro content loader that reads collections from the PocketBase API. ![GitHub Repo stars](https://img.shields.io/github/stars/pawcoding/astro-loader-pocketbase)
* [pocketbase-query](https://github.com/emresandikci/pocketbase-query) ⭐ 61 | 🐛 0 | 🌐 TypeScript | 📅 2026-11-01 - A TypeScript-based query builder designed to generate complex filter queries for PocketBase. It allows for easy construction of queries using various operators while maintaining a fluent and chainable API. ![GitHub Repo stars](https://img.shields.io/github/stars/emresandikci/pocketbase-query)
* [pocketbase-schema-generator](https://github.com/satohshi/pocketbase-schema-generator) ⭐ 41 | 🐛 0 | 🌐 TypeScript | 📅 2025-12-29 - JS hook for automatically generating schema files. (Zod/TS interfaces) ![GitHub Repo stars](https://img.shields.io/github/stars/satohshi/pocketbase-schema-generator)
* [pb-query](https://github.com/sergio9929/pb-query) ⭐ 40 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-14 - A flexible, strongly-typed query builder with useful helpers to simplify the querying process, featuring examples, documentation, and full autocompletion based on your schema, directly in the IDE. ![GitHub Repo stars](https://img.shields.io/github/stars/sergio9929/pb-query)
* [pocketbase-ts](https://github.com/satohshi/pocketbase-ts) ⭐ 37 | 🐛 2 | 🌐 TypeScript | 📅 2026-06-04 - SDK wrapper with more readable `options` syntax and full type-safety. ![GitHub Repo stars](https://img.shields.io/github/stars/satohshi/pocketbase-ts)
* [pocketbase-jsvm](https://github.com/benallfree/pocketbase-jsvm) ⭐ 14 | 🐛 0 | 🌐 JavaScript | 📅 2026-11-08 - JSVM typings. ![GitHub Repo stars](https://img.shields.io/github/stars/benallfree/pocketbase-jsvm)
* [pbkit](https://github.com/Karnak19/pbkit) ⭐ 13 | 🐛 7 | 🌐 TypeScript | 📅 2026-10-11 - PocketBase code generation toolkit. Introspect your collections and generate fully typed TypeScript SDKs, with plugins for TanStack Query, Zod, and realtime. ![GitHub Repo stars](https://img.shields.io/github/stars/Karnak19/pbkit)

## SQLite tools

* [Marmot](https://github.com/maxpert/marmot) ⭐ 2,832 | 🐛 39 | 🌐 Go | 📅 2026-09-30 - A distributed SQLite replicator. ![GitHub Repo stars](https://img.shields.io/github/stars/maxpert/marmot)
* [pocketbase-import](https://github.com/michal-kapala/pocketbase-import) ⭐ 68 | 🐛 0 | 🌐 TypeScript | 📅 2026-10-27 - Import CSV and JSON data into PocketBase collections. ![GitHub Repo stars](https://img.shields.io/github/stars/michal-kapala/pocketbase-import)
* [Litestream](https://litestream.io/) - Streaming SQLite replication. ![GitHub Repo stars](https://img.shields.io/github/stars/benbjohnson/litestream)

## Other tools

* [pb-hooks-dash](https://github.com/deselected/pb-hooks-dash) ⭐ 67 | 🐛 0 | 🌐 JavaScript | 📅 2025-03-30 - Drop-in web dashboard to view and edit PocketBase hooks in the browser. ![GitHub Repo stars](https://img.shields.io/github/stars/deselected/pb-hooks-dash)
* [PocketBaseMobile](https://github.com/rohitsangwan01/pocketbase_mobile) ⭐ 47 | 🐛 2 | 🌐 Go | 📅 2025-01-26 - Android and iOS frameworks for running PocketBase from mobile. ![GitHub Repo stars](https://img.shields.io/github/stars/rohitsangwan01/pocketbase_mobile)
* [pbf](https://github.com/nedpals/pbf) ⭐ 28 | 🐛 0 | 🌐 TypeScript | 📅 2025-01-13 - Library for serializing and deserializing PocketBase filter syntax. ![GitHub Repo stars](https://img.shields.io/github/stars/nedpals/pbf)
* [pb-llm](https://github.com/magooney-loon/pb-llm) ⭐ 16 | 🐛 0 | 🌐 Go | 📅 2025-10-15 - Pocketbase LLM docs scraper ![GitHub Repo stars](https://img.shields.io/github/stars/magooney-loon/pb-llm)
* [pocketbase-security-skill](https://github.com/Perufitlife/pocketbase-security-skill) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-21 - Open-source MIT auditor that probes anonymously to confirm permissive default-rule wildcards, anonymous record listing exposure, and admin-API misconfigurations. Outputs an HTML report with copy-paste fix snippets. ![GitHub Repo stars](https://img.shields.io/github/stars/Perufitlife/pocketbase-security-skill)
* [PocketBase API Rule Builder](https://pocketbase-api-rule-builder.vercel.app) - A free, open-source web application that makes it easy to generate API rules for PocketBase collections visually. ![GitHub Repo stars](https://img.shields.io/github/stars/kerimovok/pocketbase-api-rule-builder)
* [PocketBase GPT](https://chatgpt.com/g/g-Owo2FBp4K-pocketbase-gpt) - A GPT that has all of PocketBase's documentation uploaded to it, to give more accurate and up-to-date answers.

## Showcases

* [UpSnap](https://github.com/seriousm4x/UpSnap) ⭐ 6,463 | 🐛 3 | 🌐 Go | 📅 2026-11-06 - A simple Wake-on-LAN web app written with SvelteKit, Go and PocketBase. ![GitHub Repo stars](https://img.shields.io/github/stars/seriousm4x/UpSnap)
* [CheckCle](https://github.com/operacle/checkcle) ⭐ 3,331 | 🐛 91 | 🌐 Go | 📅 2026-07-17 - Self-hosted monitoring platform with uptime checks, distributed checks, incident tracking and alerts. ![GitHub Repo stars](https://img.shields.io/github/stars/operacle/checkcle)
* [Dashwise](https://github.com/andreasmolnardev/dashwise) ⭐ 469 | 🐛 39 | 🌐 TypeScript | 📅 2026-11-04 - All-in-one homelab dashboard. ![GitHub Repo stars](https://img.shields.io/github/stars/andreasmolnardev/dashwise)
* [Cially](https://github.com/cially/cially) ⭐ 217 | 🐛 15 | 🌐 TypeScript | 📅 2026-11-27 - Analytics dashboard for Discord servers: member activity, engagement trends and statistics. ![GitHub Repo stars](https://img.shields.io/github/stars/cially/cially)
* [OpenSOHO](https://github.com/rubenbe/opensoho) ⭐ 205 | 🐛 18 | 🌐 Go | 📅 2026-11-23 - OpenWISP alternative for managing a small number of OpenWrt network devices. ![GitHub Repo stars](https://img.shields.io/github/stars/rubenbe/opensoho)
* [Realtime Blog](https://github.com/rajesh6161/pbRealtimeBlog) ⭐ 31 | 🐛 3 | 🌐 TypeScript | 📅 2025-05-05 - A React-based realtime blog demo. ![GitHub Repo stars](https://img.shields.io/github/stars/rajesh6161/pbRealtimeBlog)
* [Adnexos](https://github.com/tametsi/adnexos) ⭐ 29 | 🐛 3 | 🌐 Go | 📅 2026-05-31 - Self-hostable expense-splitter on the web. ![GitHub Repo stars](https://img.shields.io/github/stars/tametsi/adnexos)
* [PocketChat](https://github.com/PocketTogether/pocket-chat) ⭐ 27 | 🐛 0 | 🌐 TypeScript | 📅 2026-09-20 - A real-time chat platform built with PocketBase and Vue3, supporting OAuth, notifications, PWA, file/image sharing, permissions, and more. ![GitHub Repo stars](https://img.shields.io/github/stars/PocketTogether/pocket-chat)
* [Facet](https://github.com/jesposito/Facet) ⭐ 22 | 🐛 0 | 🌐 Svelte | 📅 2026-11-16 - Self-hostable personal profile and portfolio platform built on PocketBase and Svelte, and the open-source core of the [Facet Cloud](https://get-facet.com) creator platform. ![GitHub Repo stars](https://img.shields.io/github/stars/jesposito/Facet)
* [pocketbase-libsql](https://github.com/cobeo2004/pocketbase-libsql) ⭐ 18 | 🐛 0 | 🌐 HTML | 📅 2025-07-25 - Scaling Pocketbase with LibSQL and sqld - a Proof Of Concept ![GitHub Repo stars](https://img.shields.io/github/stars/cobeo2004/pocketbase-libsql)
* [JustJot](https://justjot.app) - A keyboard-first note-taking full-featured Progressive Web App. [frontend repo](https://github.com/JunoNgx/justjot-frontend) ⭐ 15 | 🐛 2 | 🌐 TypeScript | 📅 2026-03-27 / [backend repo](https://github.com/JunoNgx/justjot-backend) ⭐ 12 | 🐛 0 | 🌐 JavaScript | 📅 2026-03-27 ![GitHub Repo stars](https://img.shields.io/github/stars/JunoNgx/justjot-backend)
* [Chirkle](https://github.com/border-radius/chirkle) ⭐ 14 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-25 - Ultra-light, self-hosted messenger on a PocketBase server, with federation between instances and lightweight web and Android clients. ![GitHub Repo stars](https://img.shields.io/github/stars/border-radius/chirkle)
* [STJÓRNA](https://github.com/secanis/stjorna) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2026-11-24 - Multi-tenant product and catalogue management built on PocketBase, with roles, SSO, an S3-backed media library and a read-only REST API for storefronts. ![GitHub Repo stars](https://img.shields.io/github/stars/secanis/stjorna)
* [Beszel](https://beszel.dev) - Lightweight server monitoring with historical data, Docker stats and alerts; its hub is built on PocketBase. ![GitHub Repo stars](https://img.shields.io/github/stars/henrygd/beszel)
* [wanderer](https://wanderer.to) - Self-hosted trail database for saving and planning hikes. ![GitHub Repo stars](https://img.shields.io/github/stars/open-wanderer/wanderer)
* [Primo](https://primo.build) - Builder for client-editable websites, with a PocketBase backend. ![GitHub Repo stars](https://img.shields.io/github/stars/primocms/primo)
* [tinykit](https://tinykit.studio) - Self-hosted AI app builder with a PocketBase realtime database and storage. ![GitHub Repo stars](https://img.shields.io/github/stars/tinykit-studio/tinykit)
* [Long Habit](https://longhabit.com) - Tracker for long-term habits and recurring tasks, built with PocketBase and React. ![GitHub Repo stars](https://img.shields.io/github/stars/s-petr/longhabit)
* [Canutin](https://canutin.com) - Self-hosted personal finance platform. ![GitHub Repo stars](https://img.shields.io/github/stars/fmaclen/canutin)
* [TinyCld](https://github.com/tinycld) - A full featured workspace with mail/calendar/drive/text/calc package, uses Pocketbase with React Native for realtime db and file storage.  Extends Pocketbase server with golang services for imap/smtp/caldav/webdav.

## Unmaintained

Archived, or no commits in the last two years. They may not work with current PocketBase (v0.23 changed the API).

* [pocketpages 0.x](https://github.com/benallfree/pocketpages) ⚠️ Archived - Server-side EJS pages for PocketBase, npm-based. Archived; v1 is built into PocketOne. ![GitHub Repo stars](https://img.shields.io/github/stars/benallfree/pocketpages)
* [Vimsnake](https://github.com/patmood/vim_snake) ⭐ 149 | 🐛 6 | 🌐 JavaScript | 📅 2023-08-13 - A realtime WebAssembly game where Vim commands are used as controller inputs. Last commit Aug 2023. ![GitHub Repo stars](https://img.shields.io/github/stars/patmood/vim_snake)
* [SvelteKit Auth](https://github.com/danawoodman/sveltekit-auth-example) ⭐ 119 | 🐛 5 | 🌐 TypeScript | 📅 2022-12-06 - This project is designed as a sample implementation reference for getting authentication setup using SvelteKit. Last commit Dec 2022. ![GitHub Repo stars](https://img.shields.io/github/stars/danawoodman/sveltekit-auth-example)
* [typed-pocketbase](https://github.com/david-plugge/typed-pocketbase) ⭐ 110 | 🐛 6 | 🌐 TypeScript | 📅 2024-07-04 - Generate types from your PocketBase instance and enjoy fully type-safe queries. Last commit Jul 2024. ![GitHub Repo stars](https://img.shields.io/github/stars/david-plugge/typed-pocketbase)
* [PocketNuxt](https://github.com/j-wil/pocket-nuxt) ⭐ 108 | 🐛 5 | 🌐 Vue | 📅 2023-07-12 - A Nuxt3 PocketBase starter that builds into a single binary. Last commit Jul 2023. ![GitHub Repo stars](https://img.shields.io/github/stars/j-wil/pocket-nuxt)
* [PocketBase+Litestream example](https://github.com/TylerSustare/pocketbase-framework-litestream) ⭐ 84 | 🐛 0 | 🌐 Dockerfile | 📅 2022-09-25 - Template showing Litestream running with PocketBase. Last commit Sep 2022. ![GitHub Repo stars](https://img.shields.io/github/stars/TylerSustare/pocketbase-framework-litestream)
* [PocketBase with Litestream](https://github.com/bscott/pocketbase-litestream/) ⭐ 82 | 🐛 2 | 🌐 Dockerfile | 📅 2023-09-21 - Docker example of PocketBase saving/restoring from Litestream. Last commit Sep 2023. ![GitHub Repo stars](https://img.shields.io/github/stars/bscott/pocketbase-litestream)
* [Flutter Chat App](https://github.com/rohitsangwan01/flutter_pocketbase_chat) ⭐ 74 | 🐛 2 | 🌐 Dart | 📅 2023-05-26 - A chat app using PocketBase in Flutter. Last commit May 2023. ![GitHub Repo stars](https://img.shields.io/github/stars/rohitsangwan01/flutter_pocketbase_chat)
* [pocketbase-queue](https://github.com/joseferben/pocketbase-queue) ⭐ 64 | 🐛 1 | 🌐 TypeScript | 📅 2024-03-31 - A type-safe queue for background tasks using PocketBase. Last commit Mar 2024. ![GitHub Repo stars](https://img.shields.io/github/stars/joseferben/pocketbase-queue)
* [C# SDK](https://github.com/PRCV1/pocketbase-csharp-sdk) ⚠️ Archived - PocketBase Client in C#. Archived. ![GitHub Repo stars](https://img.shields.io/github/stars/PRCV1/pocketbase-csharp-sdk)
* [PocketBase Drift](https://github.com/rodydavis/pocketbase_drift) ⭐ 61 | 🐛 7 | 🌐 Dart | 📅 2024-11-19 - A PocketBase client cached with Drift. Last commit Nov 2024. ![GitHub Repo stars](https://img.shields.io/github/stars/rodydavis/pocketbase_drift)
* [ORM and code generator](https://github.com/iluvadev/PocketBaseClient) ⭐ 58 | 🐛 13 | 🌐 C# | 📅 2024-06-16 - An ORM to manage your PocketBase Application. Last commit Jun 2024. ![GitHub Repo stars](https://img.shields.io/github/stars/iluvadev/PocketBaseClient)
* [PocketBase Next.js App Template](https://github.com/tsensei/nextjs-pocketbase-starter-template) ⭐ 36 | 🐛 1 | 🌐 TypeScript | 📅 2023-12-16 - PocketBase Next.js Template with server & browser client using cookies. Last commit Dec 2023. ![GitHub Repo stars](https://img.shields.io/github/stars/tsensei/nextjs-pocketbase-starter-template)
* [Vue 3 + Vite starter kit](https://github.com/StefanVDWeide/pocketbase-vue) ⭐ 31 | 🐛 0 | 🌐 Vue | 📅 2022-11-30 - A starter kit for Vue 3 + Vite + PocketBase. Last commit Nov 2022. ![GitHub Repo stars](https://img.shields.io/github/stars/StefanVDWeide/pocketbase-vue)
* [gobot](https://github.com/benallfree/gobot) ⭐ 26 | 🐛 5 | 🌐 TypeScript | 📅 2024-07-30 - PocketBase as an npm package. CLI and API. Last commit Jul 2024. ![GitHub Repo stars](https://img.shields.io/github/stars/benallfree/gobot)
* [pb-import](https://github.com/burggraf/pb-import) ⭐ 25 | 🐛 2 | 🌐 JavaScript | 📅 2024-01-09 - Import data from SQLite Databases as well as CSV and TSV files. Last commit Jan 2024. ![GitHub Repo stars](https://img.shields.io/github/stars/burggraf/pb-import)
* [ToDo](https://github.com/rajesh6161/pocketbaseTodo) ⭐ 25 | 🐛 1 | 🌐 JavaScript | 📅 2024-10-16 - React-based To-Do demo app. Last commit Oct 2024. ![GitHub Repo stars](https://img.shields.io/github/stars/rajesh6161/pocketbaseTodo)
* [pb\_hooks starter kit](https://github.com/benallfree/ts-pb-hooks-starter) ⭐ 24 | 🐛 0 | 🌐 TypeScript | 📅 2023-09-21 - Build PocketBase JavaScript hooks using TypeScript. Last commit Sep 2023. ![GitHub Repo stars](https://img.shields.io/github/stars/benallfree/ts-pb-hooks-starter)
* [svelte-query-pocketbase](https://github.com/goknsh/svelte-query-pocketbase) ⚠️ Archived - TanStack Query wrappers around PocketBase for Svelte and SvelteKit that updates the query cache in realtime. Archived. ![GitHub Repo stars](https://img.shields.io/github/stars/goknsh/svelte-query-pocketbase)
* [oAuth](https://github.com/rajesh6161/pocketbase-oauth-demo) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2022-10-22 - A React-based oAuth demo. Last commit Oct 2022. ![GitHub Repo stars](https://img.shields.io/github/stars/rajesh6161/pocketbase-oauth-demo)
* [Dart Generator](https://github.com/rodydavis/pocketbase_dart_generator) ⭐ 13 | 🐛 1 | 🌐 Dart | 📅 2023-10-31 - Generate type safe client SDKs for use in local SQLite, JSON or GraphQL resolvers. Last commit Oct 2023. ![GitHub Repo stars](https://img.shields.io/github/stars/rodydavis/pocketbase_dart_generator)
* [pocketbase-otp](https://github.com/benallfree/pocketbase-otp) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2024-09-13 - One-Time Passwords for <=v0.22.\*. Last commit Sep 2024. ![GitHub Repo stars](https://img.shields.io/github/stars/benallfree/pocketbase-otp)
* [Quasar starter kit](https://github.com/aaronblondeau/pocketbase_quasar_starter) ⭐ 9 | 🐛 3 | 🌐 Vue | 📅 2023-04-01 - Pocketbase with Quasar. Last commit Apr 2023. ![GitHub Repo stars](https://img.shields.io/github/stars/aaronblondeau/pocketbase_quasar_starter)
* [Solid-pocketbase-hooks](https://github.com/kirill-dev-pro/solid-pocketbase-hooks) ⭐ 6 | 🐛 0 | 🌐 TypeScript | 📅 2023-02-03 - Pocketbase hooks for Solid.js. Last commit Feb 2023. ![GitHub Repo stars](https://img.shields.io/github/stars/kirill-dev-pro/solid-pocketbase-hooks)
* [libpb](https://github.com/Hax-io/libpb) ⭐ 6 | 🐛 7 | 🌐 D | 📅 2023-06-18 - PocketBase client wrapper for D with automatic serialization and deserialization to and from JSON. Last commit Jun 2023. ![GitHub Repo stars](https://img.shields.io/github/stars/Hax-io/libpb)
* [Tutorial](https://studioterabyte.nl/en/blog/pocketbase-vue-3) - Vue 3 tutorial. Companion to the 2022 Vue 3 starter kit.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-11-27._
