Sysops-Packer
=============

This repository contains my personal Packer templates, which are used
to build various images (e.g. Vagrant Images) across my projects.

I started this repository by cherry picking files from the [Bento](https://github.com/chef/bento)
repository, which is Chef's official base-box library, and then customized
it for my purposes from there.  If you find my configurations to be
too limited or opinionated, and you'd like to use Chef in your base
boxes, then I highly suggest checking out the Bento project; it is a
very nice resource.

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

## Building Templates

## Prerequisites

Before you can use the resources provided by this repository, you must
first meet a number of [prequisites](docs/prerequisites.md), which
can be found in this repositories [documentation directory](./docs).

# License

See [LICENSE.md](./LICENSE.md)