cloud3rsio.swapfile
=========

Create swap file.

Installation
------------

```bash
$ ansible-galaxy install cloud3rsio.swapfile
```

Requirements
------------

Nothing.

Role Variables
--------------

| Key | Default Value | Type |
| ------------- | ------------- | ------------- |
| `swapfile_path` | `/swapfile` | String |
| `swapfile_size` | `1024` (Unit is MB) | Int |

Dependencies
------------

Nothing.

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: cloud3rsio.swapfile
```

License
-------

[MIT](LICENSE)

Author Information
------------------

- youyo
