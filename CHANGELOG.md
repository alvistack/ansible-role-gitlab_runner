# Ansible Role for GitLab Runner

## 4.7.0 - TBC

### Major Changes

  - Migrate base Vagrant box from `generic/*` to `alvistack/*`

## 4.6.0 - 2020-12-28

### Major Changes

  - Simplify Molecule scenario for vagrant-libvirt
  - Prune GitLab Runner cache older than 1 day
  - Default with custom Vagrant executor
  - Migrate from Travis CI to GitLab CI

## 4.5.0 - 2020-11-16

  - Ininitial release for Ansible 2.10 or higher
  - This role was designed for:
      - Ubuntu 18.04/20.04/20.10
      - RHEL/CentOS 7/8
      - openSUSE Leap 15.2
      - Debian 10
      - Fedora 33
