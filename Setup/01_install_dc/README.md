# 01 Installing the DC

1. Use `sconfig` to:
    - Change the hostname
    - Change the IP address to static
    - Change the DNS server to our own IP address

2. Install the AD Windows Feature


```shell
Install-WindowsFeature AD-DOmain-Services -IncludeManagementTools
```