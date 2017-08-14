# Route

Compatible with debian

# Role Install
```
ansible-galaxy install --roles-path ./roles jsecchiero.ansible-route
```

## Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set
via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

```
jsecchiero.ansible-routes:
  - destination: 10.0.0.0/8
    gw:          192.168.1.1
  - destination: 172.17.0.0/16
    gw:          192.168.1.1
```
