# Vagrantfiles

A collection of `Vagrantfile`s for local pre-commit testing environments using 
VirtualBox as a provider.
 
## Prerequisites

- [Vagrant][vagrant]
- [VirtualBox][virtualbox]

Vagrant and VirtualBox are currently essential in running these environments.
Both of these are compatible with Windows, Mac OS X, and Linux. Both are free
software aswell.

## Getting started

Assuming you would like to run a vanilla debian 9 environment

- : `git clone https://github.com/janesmae/vagrantfiles.git`
- `cd vagrantfiles/vanilla-os/debian-9`
- `vagrant up`

## License
The content of this library is released under the **MIT License** by **Jaan Janesmae**.
You can find a copy of this license in [LICENSE][license] file 
or [https://opensource.org/licenses/MIT][license_web].


[license]:			./LICENSE
[license_web]:		https://opensource.org/licenses/MIT
[changelog]:		./CHANGELOG.md
[vagrant]:			https://vagrantup.com
[virtualbox]:		https://www.virtualbox.org
