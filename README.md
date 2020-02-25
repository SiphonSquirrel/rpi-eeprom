rpi-eeprom
==========

Ansible Task for Raspberry PI 4's eeprom updater.
Based on the official instructions here: https://www.raspberrypi.org/documentation/hardware/raspberrypi/booteeprom.md

**Note:** This role will reboot your PI automatically if the eeprom needs to be updated.

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: raspi
      become: yes
      roles:
        - rpi-eeprom

License
-------

MIT
