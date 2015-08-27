# Grafana Ansible Role

Installs and configures Grafana.

# Configuration Options

Name                        | Default | Description
----------------------------|---------|------------------------------------------------
grafana_users_allow_sign_up | True    | Enables user signup / registration

# Usage example

```yaml
---
- hosts: all
  sudo: true
  roles:
    - role: grafana
      grafana_users_allow_sign_up: false
```

# License

[![GPLv3](http://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.html)

