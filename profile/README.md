 <div align="center">

# AdoOS

### An independent Linux distribution built on Alpine Linux.

**Built on foundations. Designed with purpose.**

[![Alpine Linux](https://img.shields.io/badge/BASE-Alpine%20Linux-0D597F?style=for-the-badge&logo=alpinelinux&logoColor=white)](https://alpinelinux.org/)
[![Architecture](https://img.shields.io/badge/ARCHITECTURE-x86__64-34495E?style=for-the-badge)](https://github.com/AdoOS-Systems/AdoOS-src)
[![Init System](https://img.shields.io/badge/INIT-OpenRC-477A91?style=for-the-badge)](https://github.com/OpenRC/openrc)
[![Status](https://img.shields.io/badge/STATUS-EXPERIMENTAL-C58B35?style=for-the-badge)](https://github.com/AdoOS-Systems/AdoOS-src)

[![Source](https://img.shields.io/badge/SOURCE-AdoOS--src-181717?style=for-the-badge&logo=github)](https://github.com/AdoOS-Systems/AdoOS-src)
[![Website](https://img.shields.io/badge/WEBSITE-Visit-267A78?style=for-the-badge&logo=googlechrome&logoColor=white)](https://adoos-systems.github.io/www)

</div>

---

## About

**AdoOS** is an independent Linux distribution built upon Alpine Linux.

The project focuses on simplicity, reproducibility, and system control. It extends established upstream foundations through its own system configuration, build infrastructure, tooling, and visual identity.

AdoOS is designed around a clear principle:

> **AdoOS adds layers. It does not fork the base.**

## Core Principles

- **Upstream-first:** Preserve upstream compatibility and avoid unnecessary modifications.
- **Minimalism:** Keep the system lean, understandable, and maintainable.
- **Reproducibility:** Make builds predictable and development workflows transparent.
- **User control:** Prioritize explicit configuration and system transparency.
- **Consistency:** Build a cohesive experience across system components and tooling.

## Technical Foundation

| Component | Technology |
| --- | --- |
| Base distribution | Alpine Linux 3.24.1 |
| Architecture | x86_64 |
| C library | musl |
| Init system | OpenRC |
| Package foundation | Alpine apk-tools |
| Build system | Alpine mkimage |
| Custom package tooling | `abo` (in development) |

## Project Structure

AdoOS development is organized into dedicated repositories.

| Repository | Purpose |
| --- | --- |
| [AdoOS-src](https://github.com/AdoOS-Systems/AdoOS-src) | Main source tree, ISO profile, overlays, and build scripts |
| [www](https://github.com/AdoOS-Systems/www) | Official project website |
| [.github](https://github.com/AdoOS-Systems/.github) | Organization profile and shared GitHub configuration |

## Development Status

<badge>Experimental — Not production-ready</badge>

AdoOS is under active development. Its build infrastructure and core components are evolving, and important milestones such as a verified bootable ISO and package repository remain in progress.

For implementation details, current limitations, and the development roadmap, refer to the main source repository.

## Contributing

Contributions and technical discussions are welcome.

Areas of interest include:

- Linux system development
- Alpine Linux and package tooling
- Build infrastructure
- Desktop environments and user experience
- Documentation and visual design

Please review the relevant repository documentation before opening an issue or submitting a pull request.

## Acknowledgements & Disclaimer

AdoOS is an independent, unofficial fan project inspired by the music and artistic identity of **Ado**.

AdoOS-Systems is not affiliated with, endorsed by, sponsored by, or officially associated with Ado, her management, or any related entities.

All third-party names, trademarks, artwork, and other intellectual property remain the property of their respective owners. Their inclusion does not imply any partnership, endorsement, or official association.

Project code, documentation, and original assets are governed by their respective licenses.

---

<div align="center">

**AdoOS — Built on foundations. Designed with purpose.**

<sub>Independent development · Open-source foundations</sub>

</div>
