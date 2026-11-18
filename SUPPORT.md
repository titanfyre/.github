# Getting help

Start with the README and release notes of the exact project you are using. The [project guide](https://github.com/TitanCSA/TitanCSA/blob/main/PROJECTS.en.md) helps distinguish applications, SDK clients, physical-device filters and virtual-device tools. [Démarrer en français](https://github.com/TitanCSA/TitanCSA/blob/main/DEMARRER.md).

## Installation and integration

- Use the complete product release for the application or driver. A language package normally supplies a user-mode client, not its product driver or application.
- Match the release, SDK edition and CPU architecture. Renaming files does not make editions interchangeable.
- Read the selected project's licence and evaluation conditions. User-mode source, drivers and redistribution can have different terms.
- Follow the documented removal/recovery steps before changing an existing driver installation. Do not disable host security settings to make an unsupported configuration work.

## Report a reproducible problem

Open an issue **in the affected project's repository**, with:

1. The product/release and package version.
2. Windows build and architecture, if relevant.
3. Minimal steps, the expected result and the actual result.
4. Whether the result came from offline validation, a virtual fixture or physical hardware.
5. Relevant text logs, with secrets and personal information removed.

Do not attach customer keys, API tokens, passwords, personal input recordings or full kernel dumps publicly. A kernel dump may contain broad system state. For a suspected security issue, follow [SECURITY.md](SECURITY.md) instead of a public bug report.

## What an issue can establish

A successful install, a valid signature and an offline test prove different things. Describe what was actually observed; do not infer compatibility with every device or Windows build. [The evidence guide](https://github.com/TitanCSA/TitanCSA/blob/main/EVIDENCE.md) explains the available benchmark boundaries and open findings.

For full-driver, OEM or redistribution questions, the maintainer's documented Discord username is **titancsa**. Support availability and licence terms are project-specific; this guide does not promise a response time or paid service.
