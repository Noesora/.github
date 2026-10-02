# Noesora

Noesora is a local-first project memory tool for developers and coding agents. It keeps records in files on one machine. SQLite is a rebuildable index, not the source of truth.

## What works today

The CLI can create a vault, show its status, and save notes with `noesora init`, `noesora status`, and `noesora note`. No binary release is available yet.

## What is planned

Cited search will return a source span or refuse when evidence is missing. Read-only queries and an MCP interface are planned. The engine will not generate answers or call a language model.

A desktop app and Cloud support for shared team context are planned. Neither is available today.

## Citadel and Noesora

[@sarthib7](https://github.com/sarthib7) built [Citadel](https://github.com/Noesora/Citadel) before Noesora. Noesora continues that work on source-backed project memory as a separate local-first product. The Citadel fork remains public, and we plan to keep developing it too.

## For developers

[noesora-cli](https://github.com/Noesora/noesora-cli) is the public command-line repository, licensed under Apache-2.0. Its vault engine is private. A source build of the CLI currently needs that engine, so there is no public install path yet.

The [product architecture map](https://noesora.xyz/architecture) shows the local path and labels unreleased interfaces. It does not show a live link from local records to Cloud.

You can follow development in the CLI repository. The status above will change as commands and releases land.
