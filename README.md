Sysops-Packer
=============

This repository contains my personal Packer templates, which are used
to build various images (e.g. Vagrant Images) across my projects.

* _Additional project/repo information can be found in [docs/about.md](./docs/about.md)._

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

* _Additional usage information can be found in [docs/usage.md](./docs/usage.md)._

## Building Templates

* Build information can be found in [docs/building.md](./docs/building.md).

## Developing & Contributing

* Information about developing and contributing can be found in [docs/contributing.md](./docs/contributing.md).

## License

* See [LICENSE.md](./LICENSE.md)