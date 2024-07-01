<div align="center">
  <picture>
    <img alt="Unikraft logo" src="https://raw.githubusercontent.com/unikraft/docs/main/static/assets/imgs/unikraft.svg" width="40%">
  </picture>
</div>

<br />

<div align="center">

[![](https://img.shields.io/badge/version-v0.17.0%20(Calypso)-%23EC591A)](https://github.com/unikraft/unikraft/tree/staging)
[![](https://img.shields.io/static/v1?label=license&message=BSD-3&color=%23385177)](https://github.com/unikraft/unikraft/blob/staging/COPYING.md)
[![](https://img.shields.io/discord/762976922531528725.svg?label=discord&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://unikraft.org/discord)
[![](https://img.shields.io/github/contributors/unikraft/unikraft)](https://github.com/unikraft/unikraft/graphs/contributors)
[![](https://app.codacy.com/project/badge/Grade/454f62251d96413fac8024b28df2ce5b)](https://app.codacy.com/gh/unikraft/unikraft/dashboard)

</div>

<h1 align="center">The fast, secure and open-source <br /> Unikernel Development Kit</h1>

<div align="center">
	Unikraft powers the next-generation of cloud native, containerless applications by enabling you to radically customize and build custom OS/kernels; unlocking best-in-class performance, security primitives and efficiency savings.
</div>

<br />

<p align="center">
	<a href="https://unikraft.org">Homepage</a>
	·
	<a href="https://unikraft.org/docs">Documentation</a>
	·
	<a href="https://github.com/unikraft/unikraft/issues/new?assignees=&labels=kind%2Fbug&projects=&template=bug_report.yml">Report Bug</a>
	·
	<a href="https://github.com/unikraft/unikraft/issues/new?assignees=&labels=kind%2Fenhancement&projects=&template=project_backlog.yml">Feature Request</a>
	·
	<a href="https://unikraft.org/discord">Join Our Discord</a>
	·
	<a href="https://x.com/UnikraftSDK">X.com</a>
</p>

<br />

<div align="center">
	<img src="https://unikraft.org/assets/imgs/monkey-business.gif" width="80%" />
</div>

<br />

## Features

- **Instantaneous Cold-boots** ⚡
   - While Linux-based systems might take tens of seconds to boot, Unikraft will be up in milliseconds.

- **Modular Design** 🧩
   - Unikraft boasts a modular design approach, allowing developers to include only necessary components, resulting in leaner and more efficient operating system configurations.

- **Optimized for Performance** 🚀
   - Built for performance, Unikraft minimizes overheads and leverages platform-specific optimizations, ensuring applications achieve peak performance levels.

- **Flexible Architecture Support** 💻
   - With support for multiple hardware architectures including x86, ARM, (and soon RISC-V), Unikraft offers flexibility in deployment across diverse hardware platforms.

- **Broad Language and Application Support** 📚

  - Unikraft offers extensive support for multiple programming languages and hardware architectures, providing developers with the flexibility to choose the tools and platforms that best suit your needs.

- **Cloud and Edge Compatibility** ☁️
   - Designed for cloud and edge computing environments, Unikraft enables seamless deployment of applications across distributed computing infrastructures.

- **Reduced Attack Surface** 🛡️
   - By selectively including only necessary components, Unikraft reduces the attack surface, enhancing security in deployment scenarios.  Unikraft also includes many [additional modern security features][unikraft-security-features].

- **Developer Friendly** 🛠️
   - Unikraft's intuitive toolchain and user-friendly interface simplify the development process, allowing developers to focus on building innovative solutions.

- **Efficient Resource Utilization** 🪶
   - Unikraft optimizes resource utilization, leading to smaller footprints (meaning higher server saturation) and improved efficiency in resource-constrained environments.

- **Community-Driven Development** 👥
    - Unikraft is an open-source project driven by a vibrant community of over 100 developers, fostering collaboration and innovation from industry and academia.


## Quick Start

Install the companion command-line client [`kraft`][kraft]:

```shell
# Install on macOS, Linux, and Windows:
curl -sSfL https://get.kraftkit.sh | sh
```

> See [additional installation instructions][unikraft-cli-install].

Run your first ultra-lightweight unikernel virtual machine:

```
kraft run unikraft.org/helloworld:latest
```

View its status and manage multiple instances:

```
kraft ps --all
```

View the community image catalog in your CLI for more apps:

```
kraft pkg ls --update --apps
```

Or browse through one of the many [starter example projects][unikraft-catalog-examples].

## Get Started

Getting started with Unikraft is easy.
Yet, there are so many things to learn and explore!
We recommend to choose a focus area first to get started:

- [**Learn more about what a unikernel is**](https://unikraft.org/docs/concepts/)
- [**Build your first unikernel quickly and easily**](https://unikraft.org/docs/getting-started/)
- [**POSIX-compatibility with Unikraft**](https://unikraft.org/docs/features/posix-compatibility)
- [**Unikraft's inherent security benefits**](https://unikraft.org/docs/features/security/)
- [**Performance of Unikraft compared to other technologies**](https://unikraft.org/docs/features/performance/)
- [**Energy efficiency with Unikraft**](https://unikraft.org/docs/features/green/)


## Community

Looking to get involved? [Contributions are welcome](https://unikraft.org/docs/contributing)!
There are [weekly community events](https://unikraft.org/community/events) on [our Discord server](https://bit.ly/UnikraftDiscord) which follow [on-going projects](https://github.com/unikraft/unikraft/issues?q=is%3Aissue+is%3Aopen+label%3Alifecycle%2Factive).
There are also [unclaimed projects](https://github.com/unikraft/unikraft/issues?q=is%3Aissue+is%3Aopen+label%3Akind%2Fproject), [open issues](https://github.com/unikraft/unikraft/issues), and opportunities for [bachelors and masters theses](https://unikraft.org/community/contacts/).



## Affiliation

Unikraft is a member of the [Linux Foundation](https://www.linuxfoundation.org/) and is a [Xen Project](https://xenproject.org/)  Incubator Project.
The Unikraft name, logo and its mascot are trademark of [Unikraft GmbH](https://unikraft.io).

<br />

<div align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://www.linuxfoundation.org/hubfs/lf-stacked-white.svg">
    <img alt="LinuxFoundation logo" src="https://www.linuxfoundation.org/hubfs/lf-stacked-color.svg" width="20%">
  </picture>
	&nbsp;&nbsp;&nbsp;
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://xenproject.org/wp-content/uploads/sites/79/2018/09/logo_xenproject.png">
    <img alt="XenProject logo" src="https://downloads.xenproject.org/Branding/Logos/Green+Black/xen_project_logo_dualcolor_767x319.png" width="18%">
  </picture>
</div>
