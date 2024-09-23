uptime_kuma
=================

Setup Uptime Kuma

OS Platform
-----------------

### Debian

- bookworm

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `uptime_kuma_version`

インストールするバージョン

#### `uptime_kuma_cfg`

Uptime Kumaの環境変数

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `uptime_kuma_dependency_packages`

#### `uptime_kuma_repo`

#### `uptime_kuma_home`

#### `uptime_kuma_user`

#### `uptime_kuma_group`

Dependencies
--------------

- [nodejs](https://github.com/wate/ansible-role-nodejs)

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: uptime_kuma
```

License
--------------

Apache License 2.0
