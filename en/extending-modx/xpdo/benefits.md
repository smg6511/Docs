---
title: "Why use xPDO?"
_old_id: "1227"
_old_uri: "2.x/overview/why-i-would-want-to-use-it"
note: "This document was written in or about 2008. While many of these benefits hold true, it could do with an update."
---

There are a number of reasons for using xPDO. Lets summarize the high-level features:

- Object-relational bridge (ORB) for mapping persistent objects to platform-optimized relational database structures

- Utilizes PDO (PHP Data Objects), a database access layer that provides lightning fast interaction with various relational database platforms.

- The code is ultra-light weight, and loads only what it needs on demand, so it adds virtually no overhead to your scripts. This was done by using generic methods and accessors and keeping all core code native PHP (i.e. no XML configuration parsing or other serialization involved).

- Promotes platform optimization in conjunction with object abstraction.

- Supports any database platform accessible with a PDO driver implementation. (NOTE: MySQL, PostegreSQL, and SQLite will be the initial driver implementations for the OpenExpedio-supplied PDO-implementations, for the initial release

- Fast generation of your classes and their metadata maps from an xPDO model definition. (NOTE: a model definition is simply an XML schema defining a specific object-relational map or model)

- Fast generation of xPDO model definitions from an existing database.
