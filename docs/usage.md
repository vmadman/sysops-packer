Luke's Packer Templates: Usage
==============================

## Prerequisites

In order to use any of my images, you'll need Vagrant.

- [Vagrant](https://www.vagrantup.com/downloads.html) (~1.8.5)

## Basic Usage

I publish all of my Vagrant boxes to the [Vagrant Cloud](https://app.vagrantup.com/boxes/search)
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


## Further Reading

* [Project Readme](../README.md) - The project's README provides links to all other documentation.
