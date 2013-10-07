failmail
========

Bash script to mail if command fails

Example:

```
failmail 'ls -lh /home/user_does_not_exist' user@server.net
```

Timeout and mail after 60 seconds:

```
failmail 'ls -lh /bin/longrunningproc' user@server.net 60
```
