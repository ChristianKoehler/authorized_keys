Description
===========

Creates the ubuntu user and adds ssh-public-keys to ~ubuntu/.ssh/authorized_keys

Requirements
============

Requires a databag called 'ssh-public-keys' with one entry per key, ie

    {
      "id": "me",
      "key": "ssh-rsa my-super-long-key== me@local"
    }

Attributes
==========

Usage
=====

