# 001 - Install AD and Join WS to domain

1. Use `sconfig` to:
    - Change the hostname
    - Change the IP address to static
    - Change the DNS server to our own IP address

2. Install AD Windows Feature

```shell
Install-WindowsFeature AD-Domain-Services -IncludeManagementTools
```

