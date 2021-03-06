# Changelog

All notable changes to `db-dumper` will be documented in this file

## 2.5.1 - 2017-04-07

- prefix excluded tables with database name when dumping a MySql db

## 2.5.0 - 2017-04-05

- add `--default-character-set` option for MySql
- improve the preservation of the used charset when dumping a MySql db

## 2.4.1 - 2016-12-31

- fix bug where custom binary path with spaces on linux would not process correctly

## 2.4.0 - 2016-12-30

- add `skipComments`

## 2.3.0 - 2016-11-21

- add support for SQLite

## 2.1.1 - 2016-11-19

- made a change so the package can be used on Windows

## 2.1.0 - 2016-10-21

- added `getHost`

## 2.0.1 - 2016-09-17

- fix for dump paths with spaces

## 2.0.0 - 2016-09-07

- refactored all classes
- added the ability to add artribrary options

## 1.5.1 - 2016-06-14

-  Removed -d flag from pg_dump for compability with pgsql 7.3+

## 1.5.0 - 2016-06-01
- Added `includeTables` and `excludeTables`

## 1.4.0 - 2016-04-27

- Added --single-transaction option to Mysql dump command

## 1.3.0 - 2016-04-03

- Added the ability to use insert when dumping a PostgreSQL db

## 1.2.4 - 2016-03-24

- Added more details about a dump failure in the error message

## 1.2.3 - 2016-03-18

- Fixed an issue where paths containing spaces would cause problems

## 1.2.2 - 2016-03-16

- Added an option to set a timeout

## 1.2.1 - 2016-03-14

- Fixed PostgreSQL dump

## 1.2.0 - 2016-03-13

- Added support for PostgreSQL

## 1.1.0 - 2016-02-21

- Lowered PHP and symfony requirements

## 1.0.4 - 2016-02-14

- Fixed a bug when the backup has failed.

## 1.0.3 - 2016-02-01

- Added missing abstract `getDbName`-method

## 1.0.2 - 2016-02-01

- Added missing abstract `dumpToFile`-method

## 1.0.1 - 2016-01-19

- Fixed typo in `checkIfDumpWasSuccessFul`-method name
- Fixed bug running Process

## 1.0.0 - 2016-01-19

- Initial release
