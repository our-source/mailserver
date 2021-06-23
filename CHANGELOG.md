# Changelog

## v1.4.1

* Trigger new build

## v1.4.0

* Update oursource/debian-mail-overlay:v1.11.0 base image
* Fixing some more log rotation warnings

## v1.3.0

* Fixes spelling errors and typos
* Disable TLS1.1
* Raise test images for databases and cache
* Fix env exports
* Make Zeyple work again
* DKIM update
* Added compression to Dovecot IMAP
* Update osixia/openldap:1.4.0
* Upgrade configs to traefik 2
* Fix certificate watching (auto renew)
* Optional vhosts directory ownership setup
* Update base image oursource/debian-mail-overlay:master

## v1.2.0

* Bump to new base image version 1.0.2 with rspamd 2.6
* Bump to new base image version 1.0.3 with updated Skalibs 2.9.3.0 and Execline 2.6.1.1
* `DISABLE_VHOSTS_OWNERSHIP_SET` configuration option

## v1.1.3

* Tests: updated osixia/openldap docker image to version [1.4.0](https://github.com/osixia/docker-openldap/releases/tag/v1.4.0).
* Upgrade configs to traefik 2 ([#17](https://github.com/mailserver2/mailserver/pull/17))
* Bump to new base image version 1.0.1 with new s6

## v1.1.2

### New features

* Added compression to Dovecot IMAP ([#13](https://github.com/mailserver2/mailserver/pull/13)).

## v1.1.1

* First version of the mailserver2 fork.
* Updated everything to latest versions.

## v1.1.0

* This is the last version of [hardware/mailserver](https://github.com/hardware/mailserver).
