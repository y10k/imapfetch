imapfetch
========

A tool to fetch messages from IMAP server.
This tool doesn't change server messages or their flags at all, so it
works without affecting the behavior of your mail user agent at all.

Requrements
-----------

This tool is a script of ruby.
Ruby interpreter is required.

Usage
-----

```
imapfetch example.yml
```

Configration
------------

Tool's configuratin is YAML file.
See `example.yml`.

Files
-----

|file|description|
|----|-----------|
|`~/.imapfetchids`|UIDs of the last downloaded message for each mailbox of each user on each server are saved|

License
-------

BSD
