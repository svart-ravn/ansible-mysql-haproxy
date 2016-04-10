- No failback
- haproxy located on separated node

```
[haproxy]
192.168.174.145 mysql_master="192.168.174.144" mysql_slave_list='["192.168.174.146", "192.168.174.147"]
```
