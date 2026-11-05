

<p align="center">
  <img src="https://img.shields.io/badge/ADOOS-SYSTEMS-016A95?style=for-the-badge&labelColor=101820&color=016A95" />
  <img src="https://img.shields.io/badge/ALPINE_LINUX-BASED-016A95?style=for-the-badge&logo=alpinelinux&logoColor=FFFFFF&labelColor=101820&color=016A95" />
  <img src="https://img.shields.io/badge/X86__64-ARCHITECTURE-016A95?style=for-the-badge&labelColor=101820&color=016A95" />
  <img src="https://img.shields.io/badge/OPENRC-INIT_SYSTEM-016A95?style=for-the-badge&labelColor=101820&color=016A95" />
  <img src="https://img.shields.io/badge/EXPERIMENTAL-IN_DEVELOPMENT-016A95?style=for-the-badge&labelColor=101820&color=016A95" />
</p>

<h1 align="center">AdoOS</h3>

<p align="center">
  <strong>An independent Linux distribution built on Alpine Linux.</strong>
  <br />
  <sub>Built on solid foundations. Designed with purpose.</sub>
</p>

<p align="center">
  <a href="https://github.com/AdoOS-Systems/AdoOS-src">Source Code</a>
  &nbsp; · &nbsp;
  <a href="https://adoos-systems.github.io/www">Website</a>
  &nbsp; · &nbsp;
  <a href="https://github.com/AdoOS-Systems">Organization</a>
</p>

---

## About

**AdoOS** is an independent Linux distribution built on top of [Alpine Linux](https://alpinelinux.org/).

The project explores a minimal, reproducible, and carefully structured operating system, combining Alpine's lightweight foundation with an independent identity and development direction.

Rather than maintaining a heavily modified fork of Alpine, AdoOS aims to build upon its existing ecosystem through its own system configuration, live environment, tooling, and visual identity.

AdoOS is also an unofficial fan project inspired by the artistic identity of **Ado**.

## Design Philosophy

AdoOS follows a few core principles:

- **Minimalism** — Keep the system lean and avoid unnecessary components.
- **Reproducibility** — Make builds predictable and transparent.
- **Upstream Compatibility** — Respect Alpine's ecosystem instead of unnecessarily duplicating it.
- **Simplicity** — Prefer straightforward solutions and maintainable architecture.
- **Identity** — Build a consistent visual and technical experience.

> AdoOS adds its own layer. It does not aim to reinvent the foundation.

## Technical Foundation

| Component | Current Foundation |
|:--|:--|
| Base Distribution | Alpine Linux 3.24.1 |
| Architecture | x86_64 |
| C Library | musl |
| Init System | OpenRC |
| Package Manager | apk-tools |
| Image Build System | Alpine mkimage |
| Build Approach | Rootless and reproducible |

AdoOS currently uses Alpine's package ecosystem and build infrastructure, with project-specific configuration layered on top.

## Project Structure

The organization hosts the components and resources that make up the AdoOS project.

| Repository | Description |
|:--|:--|
| [AdoOS-src](https://github.com/AdoOS-Systems/AdoOS-src) | Main source repository, build configuration, and system development |
| [www](https://github.com/AdoOS-Systems/www) | Official project website |

Additional components may be introduced as the project evolves.

## Development Status

<sub>EARLY DEVELOPMENT · EXPERIMENTAL</sub>

AdoOS is under active development and is not yet suitable for production use.

Current limitations include:

- The ISO image has not yet been successfully built and boot-tested from the current source tree.
- No official package repository is available.
- No dedicated installer is currently provided.
- Proprietary NVIDIA driver support is not currently included.

Features and implementation details are subject to change.

## Contributing

Contributions, technical discussions, bug reports, and suggestions are welcome.

Before submitting a contribution, please review the relevant repository documentation and existing issues.

For project-wide discussions and updates, visit the [AdoOS-Systems organization](https://github.com/AdoOS-Systems).

## Acknowledgements & Disclaimer

AdoOS is an independent and unofficial fan project inspired by the music and artistic identity of **Ado**.

AdoOS and AdoOS-Systems are not affiliated with, endorsed by, sponsored by, or officially associated with Ado, her management, or any related entities.

All third-party names, trademarks, logos, artwork, and other intellectual property remain the property of their respective owners.

**Third-party artwork and other assets are not owned by AdoOS and are not covered by the project's software license.** Their presence in this project does not grant permission to reuse, redistribute, or modify them. Permission must be obtained from the respective rights holders.

Original project code, documentation, and assets are governed by their respective licenses.

---

<p align="center">
  <sub>ADOOS SYSTEMS</sub>
  <br />
  <sub>Independent development. Distinct identity.</sub>
</p>

