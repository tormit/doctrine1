Tormi's fork of FriendsOfSymfony1/doctrine1
============================================

[![Build Status](https://travis-ci.org/tormit/doctrine1_5.svg?branch=master)](https://travis-ci.org/tormit/doctrine1_5)

Contains some small non-breaking updates.


UPDATES
--------

#### 29th October 2013

* Doctrine data load progress and debug information output


#### 14th November 2013(Martin Ojaste)

* Doctrine: Hack to disable fixture merge at table level

Example:
```yaml
# If __doNotMerge is appended, this fixture won't be merged with other fixtures for same table
# Used to allow project fixture to fully overwrite same fixture from plugins 
TableName__doNotMerge:
  row1:
    title: Client picture upload
    type: dynamic
    ....: ....
```

#### 17th December 2013

* Builder remove "object" from doc-block

#### 19th December 2013

* Doctrine_Query_Abstract E_NOTICE(PHP 5.4/5.5) fix

#### 13th April 2014

* Doctrine count query HAVING field fix (field aliases were stripped out)

#### 22nd April 2014

* Doctrine - allow SQL subqueries in select
* 
#### 6th August 2014

* doctrine array-diff issue(community fix)

#### 16th November 2015

* Updated Doctrine collection. Added _\Doctrine_Collection::filter()_ to filter records by callback.

