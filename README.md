Ansible Role for Ubuntu Configuration
====================

[![Build Status](https://travis-ci.org/vitalied/ansible-role-ubuntu-config.svg?branch=master)](https://travis-ci.org/vitalied/ansible-role-ubuntu-config)
[![GitHub tag](https://img.shields.io/github/tag/vitalied/ansible-role-ubuntu-config.svg)](https://github.com/vitalied/ansible-role-ubuntu-config)
[![GitHub license](https://img.shields.io/github/license/vitalied/ansible-role-ubuntu-config.svg)](https://github.com/vitalied/ansible-role-ubuntu-config/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/ansible/role/12459.svg)](https://galaxy.ansible.com/vitalied/ubuntu-config)

Ansible Role for Ubuntu Configuration.

Requirements
------------

This role require Ansible 2.1 or higher.

This role was designed for Ubuntu Server 16.04 LTS.

Role Variables
--------------

<table>
<colgroup>
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
<col width="20%" />
</colgroup>
<thead>
<tr class="header">
<th>parameter</th>
<th>required</th>
<th>default</th>
<th>choices</th>
<th>comments</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>ubuntu_config_swappiness</td>
<td>yes</td>
<td>10</td>
<td></td>
<td>Adjust Ubuntu Swappiness.</td>
</tr>
</tbody>
</table>

Dependencies
------------

No additional role dependencies.

Example Playbook
----------------

    - hosts: all
      roles:
        - role: vitalied.ubuntu-config

License
-------

-   Code released under [MIT](https://github.com/vitalied/ansible-role-ubuntu-config/blob/master/LICENSE)
-   Docs released under [CC BY 4.0](http://creativecommons.org/licenses/by/4.0/)
