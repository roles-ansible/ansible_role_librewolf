[![Ansible Galaxy](https://ansible.l3d.space/svg/l3d.linux.librewolf_ansible-role.svg)](https://galaxy.ansible.com/ui/repo/published/l3d/linux/content/role/librewolf/)
[![BSD-3 Clause](https://ansible.l3d.space/svg/l3d.packages_license.svg)](LICENSE)
[![Maintainance](https://ansible.l3d.space/svg/l3d.packages_maintainance.svg)](https://ansible.l3d.space/#l3d.linux)

 Librewolf ansible role
=======================

This ansible role installs librewolf, a firefox fork, on linux. It is part of the l3d.liux collection

## Variable

| name | default | description |
| ---- | --- | --- |
| ``librewolf__keyring_hash`` | ``sha256:4f438df8a84241e921edd26f164d1926e200ec3e36b1b330285242777ea3c693`` | librewolf gpg hash |
| ``librewolf__keyring`` | ``https://deb.librewolf.net/keyring.gpg`` | Librewolf keyring location |
| ``librewolf__xdg_settings`` | ``false`` | Optionally set librewolf as default browser |
| ``librewolf__xdg_settings_user`` | ``[]`` | List of users to set default browser |
| ``librewolf__xdg_settings_user[].user`` | | Username to set default browser |
| ``librewolf__xdg_settings_user[].home`` | ``/home/ ~ user`` | Home of User to set default browser |
| ``submodules_versioncheck`` | ``false`` | Optionally run versionscheck |
