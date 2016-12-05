## haveged

[![Build Status](https://travis-ci.org/Oefenweb/ansible-haveged.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-haveged) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-haveged-blue.svg)](https://galaxy.ansible.com/Oefenweb/haveged)

Set up [haveged](https://www.digitalocean.com/community/tutorials/how-to-setup-additional-entropy-for-cloud-servers-using-haveged) in Debian-like systems.

#### Requirements

None

#### Variables

* `haveged_install`: [default: `[]`]: Additional packages to install

* `haveged_daemon_args`: [default: `['-w 1024']`]: Options to pass to haveged

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - haveged
```

#### License

MIT

#### Author Information

Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-haveged/issues)!
