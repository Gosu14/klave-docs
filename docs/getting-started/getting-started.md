---
layout: default
title: Getting started
nav_order: 2
has_children: true
permalink: docs/getting-started
---

# Getting started

The "Getting Started" section is to help new community members start developing on Klave Network using standard tools for trustless apps development. The goal is to provide an easy guide to follow with step-by-step instructions.

Topics covered:

-   Setting up a development Environment
-   Compiling and Deploying a trustless applications
-   Interacting with applications on the Klave Network

What **won't** be covered:

-   An in-depth guide to developing trustless applications
-   Klave Network architecture

## Prerequisites

Trustless applications are developed in [TypeScript] and compiled in [WebAssembly].
[nodejs] needs to be installed beforehand to be able to use the sdk.
The [Klave sdk package] provides the simplest, quickest, and easiest way to create a new trustless applications using typescript.

[Next: Create repository][Create-repo]{: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

---
[Klave sdk package]: https://www.npmjs.com/package/create-trustless-app
[TypeScript]: https://www.typescriptlang.org/
[WebAssembly]: https://webassembly.org/
[nodejs]: https://nodejs.org/
[Create-repo]: {% link docs/getting-started/create-repo.md %}