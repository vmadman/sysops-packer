Luke's Packer Templates
=======================

This repository contains my personal Packer templates, which are used
to build various images (e.g. Vagrant Images) across my projects.
( [Read More](./docs/about.md) ).

## Basic Usage

I publish all of my Vagrant boxes to the [Vagrant Cloud](https://app.vagrantup.com/boxes/search),
and you are welcomed to use them for your own projects.

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

## Documentation

1. [About](./docs/about.md) - Basic project information.
2. [Usage](./docs/usage.md) - Information about using my Vagrant boxes
3. [Building](./docs/building.md) - Information about building these Packer Templates.
4. [Contributing](./docs/contributing.md) - How to contribute to this repo.

## License

* See [LICENSE.md](./LICENSE.md)