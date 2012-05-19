-*- markdown -*-

# OSS-JDBC v0.8.0

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
* MonetDB
* MckoiDDB
* Axion

For details on current version, check the CHANGES file.


## Usage

Maven/Leiningen dependency details are here: [http://clojars.org/oss-jdbc/oss-jdbc](http://clojars.org/oss-jdbc/oss-jdbc)

Just include the dependencies in your project and you are all set.


## Building/Installation

You will need Maven 2 to build from sources. Execute the following:

    $ mvn clean package  # packages up a JAR in "target" dir
    $ mvn install        # to install to your local Maven repo


## Getting in touch

On Twitter: [@kumarshantanu](https://twitter.com/#!/kumarshantanu)

By E-mail: [kumar.shantanu at gmail dot com](mailto:kumar.shantanu@gmail.com)


## License

Copyright (C) 2010-2012 Shantanu Kumar (kumar.shantanu at gmail dot com)

Distributed under the Eclipse Public License - v 1.0.
