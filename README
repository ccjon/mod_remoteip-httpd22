## mod_remoteip Backport for Apache 2.2.x
This is a backport of Apache 2.4.1 mod_remoteip to Apache 2.2.x.

## Compile and Install
`apxs -i -c -n mod_remoteip.so mod_remoteip.c`
or
`make; make install`

## Build Source RPM
`make srpm`

## Configuration Example
```
LoadModule remoteip_module modules/mod_remoteip.so
RemoteIPHeader X-Forwarded-For
RemoteIPTrustedProxy 127.0.0.1
```
For more information, see: http://httpd.apache.org/docs/2.4/mod/mod_remoteip.html

## Author
* Original backport by Takashi Takizawa <taki@cyber.email.ne.jp>
* Original fork by Schlomo <schlomo.schapiro@immobilienscout24.de> who fixed segfaults and bugs

