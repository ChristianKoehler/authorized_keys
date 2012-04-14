Description
===========

This cookbook has a definition to add ssh public keys to a user's ~/.authorized_keys

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

authorized_keys_for "username"
authorized_keys_for "username", home: "/var/apps"
authorized_keys_for "username", group: "staff", keys: "name-of-data-bag"

