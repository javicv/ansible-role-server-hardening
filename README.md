Role Name: **server_harden**
=========

Harden a new server with a small list of general tasks

Role Variables
--------------

* _username_: The username for the user that will be created and make sudoer
* _public_key_: Public key to set in user's authorized keys
* _unnecessary_software_: List of Packages to be removed
* _unnecessary_services_: List of Services to be stopped and disabled

License
-------

MIT
