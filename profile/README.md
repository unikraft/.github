<p align="center">
  <img src="https://unikraft.org/assets/imgs/unikraft.svg" width="215" alt="Unikraft - Fast, Secure and Open-Source Unikernel Development Kit" />
</p>
<p align="center">
  <img src="https://img.shields.io/github/contributors/unikraft/unikraft" />
  <img src="https://img.shields.io/static/v1?label=license&message=BSD-3&color=%23385177" />
  <a href="https://bit.ly/UnikraftDiscord">
    <img src="https://img.shields.io/discord/762976922531528725.svg?label=discord&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2" />
  </a>
</p>

**Unikraft is an automated system for building specialized POSIX-compliant OSes known as unikernels**; these images are tailored to the needs of specific applications.
Unikraft is based around the concept of small, modular libraries, each providing a part of the functionality commonly found in an operating system (e.g., memory allocation, scheduling, filesystem support, network stack, etc.).

Unikraft supports multiple target platforms (e.g., Xen, KVM, and Linux userspace) so that it is possible to build multiple images, one for each platform, for a single application without requiring the application developer to do any additional, platform-specific work.
In all, Unikraft is able to build specialized OSes and unikernels targeted at specific applications without requiring the time-consuming, expert work that is required today to build such images.


## Typical Use Cases

Unikraft is a new system for ultra-light virtualization of your services in the cloud or at the edge, as well as extremely efficient software stacks to run bare metal on embedded devices. Smaller, quicker, and way more efficient than conventional systems:

**⚡  Cold boot virtual machines in a fraction of a second**

While Linux-based systems might take tens of seconds to boot, Unikraft will be up in a blink.

**📈 Deploy significantly more instances per physical machine**

Don't waste CPU cycles on unneeded functionality – focus on your users' needs.

**📉 Drastic reductions in memory consumption**

With all your applications and data strongly separated into ultra light-weight virtual machines, scaling becomes a breeze.

**🛡️ Ready for mission critical deployments**

Focus your trust on a minimal set of required components, significantly reduce your service's attack surface, and minimize certification costs.

**🚀 Outstanding performance**

Specializing the OS to meet your application's needs is the key to achieving superior performance, making you ready to drive your infrastructure to the peak.


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
There are [weekly commnitiy meetings](https://unikraft.org/community/meetings) on [our Discord server](https://bit.ly/UnikraftDiscord) which follow [on-going projects](https://github.com/unikraft/unikraft/issues?q=is%3Aissue+is%3Aopen+label%3Alifecycle%2Factive).
There are also [unclaimed projects](https://github.com/unikraft/unikraft/issues?q=is%3Aissue+is%3Aopen+label%3Akind%2Fproject), [open issues](https://github.com/unikraft/unikraft/issues), and opportunities for [bachelors and masters theses](https://unikraft.org/community/contacts/).
