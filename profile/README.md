# Deku Foundation

**Independent open-source engineering across system software, developer tools, and Arabic-first computing.**

Deku Foundation is a multi-project open-source organization. We publish our designs, code, tests, and limitations so contributors can judge progress from evidence rather than promises.

## Our work

| Project | Focus | Current stage |
| --- | --- | --- |
| [Deku Linux](https://github.com/Deku-Foundation/deku-linux) | Linux distribution, system integration, KDE-first desktop | Experimental platform work; no official installable ISO yet |
| [Rukn — ركن](https://github.com/Deku-Foundation/deku-rukn) | Arabic-first programming language and Rust toolchain | Initial interpreter and language specification |
| [deku-pkg](https://github.com/Deku-Foundation/deku-pkg) | Rust-native package-management research | Prototype and architecture proposals |
| [deku-build](https://github.com/Deku-Foundation/deku-build) | Package build-plan validation and build tooling | Early tooling |
| [deku-recipes](https://github.com/Deku-Foundation/deku-recipes) | Declarative package recipe metadata | Schema and validation work |
| [deku-system](https://github.com/Deku-Foundation/deku-system) | System integration | Early-stage repository |
| [deku-infra](https://github.com/Deku-Foundation/deku-infra) | Repository and distribution infrastructure | Early-stage repository |
| [deku-profiles](https://github.com/Deku-Foundation/deku-profiles) | Declarative system profiles | Experimental profile specification |
| [deku-tests](https://github.com/Deku-Foundation/deku-tests) | Cross-repository and VM acceptance tests | Unit checks and an untested-against-Deku boot harness |
| [deku-release](https://github.com/Deku-Foundation/deku-release) | Release manifests and promotion gates | Contract proposal; no release pipeline |
| [deku-kernel](https://github.com/Deku-Foundation/deku-kernel) | Upstream kernel configuration and patch tracking | Bootstrap repository; not a kernel fork |
| [deku-desktop](https://github.com/Deku-Foundation/deku-desktop) | KDE Plasma integration | Bootstrap repository; no supported desktop image |
| [deku-themes](https://github.com/Deku-Foundation/deku-themes) | Licensed visual identity and desktop assets | Bootstrap repository |
| [deku-mirrors](https://github.com/Deku-Foundation/deku-mirrors) | Future package mirror policy and health | Planning only; no production mirrors |
| [deku-signing](https://github.com/Deku-Foundation/deku-signing) | Package and release trust policy | Trust-model proposal; no production keys/service |
| [deku-updater](https://github.com/Deku-Foundation/deku-updater) | Authenticated update orchestration | Future component; depends on package transactions |
| [Project website](https://deku-foundation.github.io/) | Documentation, status, architecture and community entry points | Public project portal |

## How we build

- **Evidence over claims.** A proposal is not an implementation; a passing unit test is not proof of production readiness.
- **Reuse before rewriting.** Prefer mature upstream components when they provide better security, compatibility, and maintenance economics.
- **Small, reviewable changes.** Define behavior, failure cases, tests and migration impact before broad refactors.
- **Security as a boundary.** Separate untrusted builds from privileged installation, verify publisher signatures as well as artifact digests, and document threat models.
- **Accessibility and language inclusion.** Arabic, French and English documentation are part of the project, not afterthoughts.
- **Long-term research.** Rukn may explore self-hosting after its grammar, runtime, standard library and bootstrap tests are stable. Self-hosting is a future milestone, not a current capability.

## Branch and promotion policy

Active repositories keep `main` and `dev` as the only persistent development branches. Work and run CI on `dev`; promote to `main` only after required checks and review pass. Avoid long-lived feature branches, do not force-push either persistent branch, and never delete `main` or `dev`. Short-lived review branches should be removed after their work is merged.

## Participate

1. Choose the repository closest to the problem.
2. Read its README, roadmap and contribution guide.
3. Open an issue before major language, architecture or compatibility changes.
4. Submit focused pull requests with tests and documentation.

Start at the [project website](https://deku-foundation.github.io/) or browse all [public repositories](https://github.com/orgs/Deku-Foundation/repositories).

## Security

Do not publish exploitable vulnerability details in public issues. Until a dedicated disclosure address is configured, contact maintainers through GitHub's private contact channels. Each repository's security policy describes known limitations.

## Project status

The foundation is actively developing early-stage open-source projects. We do not claim a production-ready Linux distribution, a universal package compatibility layer, or a self-hosting Arabic language compiler. Follow repository CI, reviewed pull requests and versioned releases for verifiable progress.
