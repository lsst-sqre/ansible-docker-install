ansible-docker-installation
===========================
[![Build Status](https://travis-ci.org/lsst-sqre/ansible-docker-installation.svg?branch=master)](https://travis-ci.org/lsst-sqre/ansible-docker-installation)

Installation of [Docker](https://www.docker.com/) using [Ansible](http://docs.ansible.com/).

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: lsst-sqre.ansible-docker-installation }

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-docker-install/blob/master/LICENSE).
