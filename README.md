# natgo/infra

An Ansible playbook that sets up an Ubuntu-based home media server/NAS with not reasonable security but my security, auto-updates.

It assumes a fresh Ubuntu Server 22.04 install, access to a non-root user with sudo privileges and a public SSH key on the user. This can be configured during the installation process.

The playbook is mostly being developed for personal use, so stuff is going to be constantly changing and breaking. Use at your own risk and don't expect any help in setting it up on your machine.

## Special thanks
* Wolfgang for his [infra](https://github.com/notthebee/infra) project. This is where I got the idea and "borrowed" a lot of concepts and implementations from.
