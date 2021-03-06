# ansible-zabbix-server Release

Below an overview of all changes in the releases.

Version (Release date)

1.2.0   (2018-10-19)

  * Make it work with Zabbix 4.0

1.1.0   (2018-06-23)

  * typo in zabbix_proxy_cachesize variable #32 (By pull request: q1x (Thanks!))
  * Updated minimal Ansible version to 2.4 #28
  * Add support for Debian 9 #28
  * Fix for: Mysql database error #21
  * Various fixes #26 (By pull request: hatifnatt (Thanks!))
  * fix DBPort parameter in config template #23 (By pull request: maxim0r (Thanks!))
  * Using correct compare #22
  * set selinux policy to permissive for zabbix_t, needed for CentOS and others #18 (By pull request: andrzejwp (Thanks!))
  * Add TLS connection configuration #17 (By pull request: mgornikov (Thanks!))
  * Add support for sqlite3 DB #16 (By pull request: mgornikov (Thanks!))

1.0.0   (2017-09-10)

  * Changed from ini to yml style
  * Replace shell tasks with modules.
  * Installing default 3.4.
  * Prefixed all properties that started with `proxy_` with the value `zabbix_`.
  * Added upgrade part in documentation.

0.5.0   (2017-07-17)

  * Renaming docker-py to docker #10
  * [!] fix misspelling with property ListenIP #9 (By pull request: lebe-dev (Thanks!))
  * Add Amazon Linux support #7 (By pull request: kostyrev (Thanks!))
  * Add HistoryIndexCacheSize for zabbix 3.2 #6 (By pull request: kostyrev (Thanks!))
  * Molecule test #5
  * Fix bugs with LoadModule & add sqlite3 support #2 (By pull request: splitice (Thanks!))
  * Zabbix proxy 3.0 fixes #1 (By pull request: zbal (Thanks!))

0.4.0   (2016-08-24)

  * ?

0.3.0   (2016-02-08)

  * Added test-kitchen tests
  * Small bug fix for installation on RedHat/Debian

0.2.0   (2016-02-04)

  * Added travis-ci test.

0.1.0   (2015-02-01)

   * Updated readme
   * added double quotes on names
   * added var zabbix_repo
   * added var for database creation and load file

0.0.1   (2014-10-31)

  * Initial Creation
