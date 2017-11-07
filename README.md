# mage.sovereign-mailstack

Splitted common task from the sovereign project. Depends on and is documented on https://github.com/Vaizard/mage.sovereign-common.

## Work in progress

Currently various rspam work is done. Inspiration stems from

- https://words.bombast.net/rspamd-with-postfix-dovecot-debian-stretch/
- https://www.c0ffee.net/blog/mail-server-guide
- https://thomas-leister.de/en/mailserver-debian-stretch/
- https://github.com/mailcow/mailcow-dockerized/tree/master/data/conf/rspamd/local.d

TODO:

- modify etc_dovecot_sieve_before.d_no-spam.sieve so that spam gets moved to JUNK but is kept unread
- mark infected mails differently then spam
- tweak redis configuration further
- add sieve learning