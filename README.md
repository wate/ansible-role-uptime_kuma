uptime_kuma
=================

Setup Uptime Kuma

OS Platform
-----------------

### Debian

- bookworm

Role Variables
--------------

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `uptime_kuma_version`

インストールするバージョン

### `uptime_kuma_cfg`

Uptime Kumaの環境変数

Dependencies
--------------

- nodejs

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
