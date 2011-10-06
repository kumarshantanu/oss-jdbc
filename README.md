-*- markdown -*-

# OSS-JDBC v0.5

OSS-JDBC is an empty Maven project that depends on several Open Source JDBC
drivers. The sole purpose of this project is to automatically pull in JDBC
driver JARs as Maven dependencies. The following JDBC drivers are supported:

* Apache Derby
* CUBRID
* Firebird (Type-4)
* HSQLDB
* H2
* jTDS (SQL Server, Sybase)
* MySQL
* PostgreSQL
* SQLite

For details on current version, check the CHANGES file.


## Usage

Maven/Leiningen dependency details are here: [http://clojars.org/org.bituf/oss-jdbc](http://clojars.org/org.bituf/oss-jdbc)

Just include the dependencies in your project and you are all set.


## Building/Installation

You will need Maven 2 to build from sources. Execute the following:

    $ mvn clean package  # packages up a JAR in "target" dir
    $ mvn install        # to install to your local Maven repo


## License

Copyright (C) 2010-2011 Shantanu Kumar (kumar.shantanu at gmail dot com)

Distributed under the Apache 2 License.
