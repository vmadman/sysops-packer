Sysops-Packer
=============

This repository contains my personal Packer templates, which are used
to build various images (e.g. Vagrant Images) across my projects.

Additional project/repo information can be found in [docs/about.md](./docs/about.md).

## Using Public Boxes (todo)

Adding one of my boxes to Vagrant

```
$ vagrant box add vmadman/centos-7.3
```

Using one of my boxes in a Vagrantfile

```
Vagrant.configure("2") do |config|
  config.vm.box = "vmadman/centos-7.3"
end
```

Additional usage information can be found in [docs/usage.md](./docs/usage.md).

## Building Templates

### Prerequisites

Before you can use the resources provided by this repository, you must
first meet a number of [prequisites](docs/prerequisites.md), which
can be found in this repositories [documentation directory](./docs).

# License

See [LICENSE.md](./LICENSE.md)