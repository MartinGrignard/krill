# Krill

> Desired state configuration for [Docker][docker] images. 🦐

The goal of `krill` is to provide a simple way to create [Docker][docker] images and configure containers at runtime.

## Introduction

In the past decade, system administrators have moved from virtual machines configured with tools like [Ansible][ansible], [Puppet][puppet] or [Chef][chef], to lighter containers powered by [Docker][docker] and managed by orchestrators such as [Kubernetes][kubernetes] or [Docker compose][compose]. 

While this shift made services more scalable, and simplified the management of large fleets of containers, it has also been a huge setback in term of how the containers themselves are defined.
Indeed, [Ansible playbooks][playbooks] have been replaced by monolithic shell scripts, which not exactly known for their advanced error handling or expressive logging.

This is the gap `krill` aims at bridging by providing:

- [ ] An idempotent, maintainable, powerful and extensible *Domain Specific Language (DSL)*.
- [ ] A complete suite of builtin resources that ensure a small footprint and usage of best practice.

## Similar projects

| Project | Description |  |
|---------|-------------|--|
| [`bashible`][bashible] | Simple bash DSL framework for writing shell scripts safe and agile. | ![GitHub Repo stars](https://img.shields.io/github/stars/mig1984/bashible) |
| [`marionette`][marionette] | Something like puppet, for the localhost only. | ![GitHub Repo stars](https://img.shields.io/github/stars/skx/marionette) |
| [`idempotent-bash`][idempotent-bash] | Make your bash scripts idempotent. | ![GitHub Repo stars](https://img.shields.io/github/stars/metaist/idempotent-bash) |
| [`primer`][primer] | A flexible OS initialisation automator in pure POSIX shell for infrastructure as data. | ![GitHub Repo stars](https://img.shields.io/github/stars/efrecon/primer) |
| [`propellor`][propellor] | Property-based host configuration management in haskell. | ![GitHub Repo stars](https://img.shields.io/github/stars/tittoassini/propellor) |


---
*Built with* ❤️ *by [Martin Grignard](https://github.com/MartinGrignard).*

<!-- References -->
[ansible]: https://www.ansible.com
[bashible]: https://github.com/mig1984/bashible
[docker]: https://www.docker.com
[chef]: https://www.chef.io
[compose]: https://docs.docker.com/compose
[idempotent-bash]: https://github.com/metaist/idempotent-bash
[kubernetes]: https://kubernetes.io
[marionette]: https://github.com/skx/marionette
[playbooks]: https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_intro.html
[primer]: https://github.com/efrecon/primer
[propellor]: https://github.com/tittoassini/propellor
[puppet]: https://www.puppet.com
[vmware]: https://www.vmware.com