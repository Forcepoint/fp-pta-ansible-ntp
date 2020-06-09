# ntp

Set the time and timezone appropriately.

For information about PTA and how to use it with this Ansible role please visit https://github.com/Forcepoint/fp-pta-overview/blob/master/README.md

## Requirements

None

## Role Variables

### REQUIRED

* ntp_server: The IP or DNS name of the NTP server to sync with.

### OPTIONAL

* ntp_timezone_name: The name of the timezone to use (EX: America/Denver).
* ntp_timezone_desig: The file name designating the timezone to use (see /usr/share/zoneinfo/).

## Dependencies

None

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: setup ntp
      hosts: servers
      roles:
         - { role: ntp }

## License

BSD-3-Clause

## Author Information

Jeremy Cornett <jeremy.cornett@forcepoint.com>
