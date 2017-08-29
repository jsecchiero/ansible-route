# Route

Setup static route on your system.
Compatible with debian

## Role Install
```
ansible-galaxy install --roles-path ./roles jsecchiero.ansible-route
```

## Role Variables

For route to nets

```
role: jsecchiero.ansible-route:
routes:
- destination: 10.0.0.0/8
  gw:          192.168.1.1
- destination: 172.17.0.0/16
  gw:          192.168.1.1
- destination: 172.16.0.5/32
  gw:          192.168.1.1
```
