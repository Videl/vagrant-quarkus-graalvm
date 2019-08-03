# Tool to develop with Quarkus/GraalVM

Use with Vagrant and Virtualbox (warning: image will request 2.5 Go of RAM, needed to build native applications)

```
vagrant up
vagrant ssh
sudo su
```

Every dependencies are present to develop Quarkus apps inside the VM, or to build a native application.
If you need extra dependencies, they can be added in the Vagrantfile, in the provisioning part.

PR appreciated!
