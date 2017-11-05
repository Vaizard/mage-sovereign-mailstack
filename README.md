# mage.sovereign-mailstack

Splitted common task from the sovereign project. Depends on and is documented on https://github.com/Vaizard/mage.sovereign-common.

## Work in progress

Currently various rspam work is done. Inspiration stems from

- https://words.bombast.net/rspamd-with-postfix-dovecot-debian-stretch/
- https://www.c0ffee.net/blog/mail-server-guide
- https://thomas-leister.de/en/mailserver-debian-stretch/
- https://github.com/mailcow/mailcow-dockerized/tree/master/data/conf/rspamd/local.d

TODO:

- check if we have a well configured caching dns such as unbound
- don't mark spam as read when moving it to JUNK
- mark infected mails differently then spam
- drop memcached dependency for graylisting (reconfigure with redis)
- make redis less resources hungry