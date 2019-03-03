# ansible-pull integration test repository

This repository is a simple inventory use to test ansible-pull CLI options. It is setup to use `local` `transport` by default and only localhost in the inventory list.

It has a fake role added as a `git` submodule to test ansible-pull's CLI options that pass through configuration to Ansible SCM modules (specifically wrt `git` recursive cloning and depth).

