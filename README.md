ubuntu-systemd
--------------
[![Build Status](https://cloud.drone.io/api/badges/ouroboros8/ubuntu-systemd/status.svg)](https://cloud.drone.io/ouroboros8/ubuntu-systemd)

A build of the ubuntu docker images with systemd installed and set to run as
PID1 by default. This is primarily useful as a test environment for the
[Molecule](https://molecule.readthedocs.io/) test framework for
[Ansible](https://www.ansible.com/).

Must be run with `--privileged`.

Dockerfile partially stolen from [centos/systemd](https://hub.docker.com/r/centos/systemd/dockerfile).
