# Deku Foundation

Deku Foundation is an independent open-source engineering organization building software in public across system software, Arabic-first programming, Android applications, and developer tools.

Our work is organized as a portfolio, not a single product. Projects have separate scopes, repositories, release criteria, and security boundaries.

## Projects

- **[Deku Linux](https://github.com/Deku-Foundation/deku-linux)** — an experimental Linux distribution and system platform. It is not yet a production-ready general-purpose release.
- **[Rukn](https://github.com/Deku-Foundation/deku-rukn)** — an experimental Arabic-first programming language and Rust-based toolchain. The first milestone is a small interpreter and a testable language specification; self-hosting is a future research goal.
- **[Package management](https://github.com/Deku-Foundation/deku-pkg)** — a Rust-native package-management prototype and architecture proposals.
- **[Build tooling](https://github.com/Deku-Foundation/deku-build)** — package build-plan validation and build-system research.
- **[Recipes](https://github.com/Deku-Foundation/deku-recipes)** — declarative package recipe metadata and validation.
- **[System integration](https://github.com/Deku-Foundation/deku-system)** and **[infrastructure](https://github.com/Deku-Foundation/deku-infra)** — supporting system and repository work.
- **[Installation planning](https://github.com/Deku-Foundation/deku-installer)** — non-destructive plan validation only; no disk-writing or OS installation is implemented.
- **Android applications:** [Deku Keyboard](https://github.com/Deku-Foundation/deku-keyboard) is an independent FlorisBoard-based keyboard undergoing pre-release validation; [Deku Satr](https://github.com/Deku-Foundation/deku-satr) is an experimental on-device person-masking prototype, not guaranteed privacy protection.
- **[Project website](https://deku-foundation.github.io/)** — the foundation-wide portfolio, architecture notes, documentation and public status.

## How we work

- Prefer small, reviewable changes backed by tests over broad promises.
- Keep design proposals distinct from implemented and released capabilities.
- Reuse mature upstream projects when they are safer and more maintainable than a rewrite.
- Treat accessibility, internationalization, reproducibility, security, and clear failure behavior as engineering requirements.
- Do not execute untrusted package scripts or treat checksums alone as publisher authentication.

## Contributing

Start with the repository's `CONTRIBUTING.md`, open an issue before large changes, and include tests and documentation with behavior changes. Arabic-language contributions are welcome; code identifiers and diagnostics should remain consistent and documented.

## Security

Please do not publish exploitable vulnerabilities as public issues. Until a dedicated private disclosure process is established, contact the organization maintainers through GitHub's private contact channels and include reproducible details with the minimum necessary sensitive information.

## Status

Deku Foundation projects are early-stage open-source work. A repository, roadmap, or design document is not evidence of a finished release. Check each project's CI, releases, and issue tracker for current status.
