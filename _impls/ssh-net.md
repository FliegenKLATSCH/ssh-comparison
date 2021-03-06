---
title: SSH.NET
homepage: https://sshnet.codeplex.com/
source-repository: https://sshnet.svn.codeplex.com/svn
license: "[BSD style](https://sshnet.codeplex.com/license)"
#first-release:
#    date: YYYY-MM-DD
latest-release:
    version: 2014.4.6-beta2
    date: 2014-11-22
#changelog: TODO
client: no
server: no
library: client

# sftp; SOCKS4, SOCKS5 and HTTP Proxy
protocols:
    cipher:
        - aes256-ctr
        - 3des-cbc
        - aes128-cbc
        - aes192-cbc
        - aes256-cbc
        - blowfish-cbc
        - twofish-cbc
        - twofish192-cbc
        - twofish128-cbc
        - twofish256-cbc
        - arcfour
        - arcfour128
        - arcfour256
        - cast128-cbc
        - aes128-ctr
        - aes192-ctr
    compression:
        - none
    hostkey:
        - ssh-rsa
        - ssh-dss
    kex:
        - diffie-hellman-group-exchange-sha256
        - diffie-hellman-group-exchange-sha1
        - diffie-hellman-group14-sha1
        - diffie-hellman-group1-sha1
    mac:
        - hmac-md5
        - hmac-sha1
        - hmac-sha2-256
        - hmac-sha2-256-96
        - hmac-ripemd160
        - hmac-ripemd160@openssh.com
        - hmac-md5-96
        - hmac-sha1-96
    userauth:
        - publickey
        - password
        - keyboard-interactive
---
* Library for .NET.
