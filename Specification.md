# Specification

Massive Base provides support for manupulative massive databases on normal systems also. Theoritically your storage is the limit with most basic compute power required!

This is mainly done through disk operations rather than on memory operations.

> NOTE: Memory refers to RAM while disk refers to SSD's or HDD's.

## Specification 1

Provides support for these "Basic" types of data:
* Null
* Int
* Long Int
* Float
* Double

The following metadata be stored:
* Version
* num of rows
* num of cols
* coln types

The supported operations should be (CRUD):
* Creation of database tables
* Reading the tables
* Updating the tables
* Deleting entries in the table

Testing framework which performs:
* Unit tests in each situation
* Functional tests simulating working environments
