```
Status: active
Logging: on (low)
Default: deny (incoming), allow (outgoing), disabled (routed)
New profiles: skip

To                         Action      From
--                         ------      ----
80                         ALLOW IN    Anywhere
22322                      ALLOW IN    Anywhere
443/tcp                    ALLOW IN    Anywhere
80 (v6)                    ALLOW IN    Anywhere (v6)
22322 (v6)                 ALLOW IN    Anywhere (v6)
443/tcp (v6)               ALLOW IN    Anywhere (v6)
```
