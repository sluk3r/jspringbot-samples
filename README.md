jSpringBot Samples
=======

### Introduction

This project demonstrate how to use the jspringbot libraries.

#### selenium-google

This module shows a simple use of selenium library that has a simple test case for searching from google.

#### http-wundergroundapi

This module shows a sample restful api calls using http library.

#### db-h2database

This module shows a sample h2 database testing using db library.

### Quick Start

Initial Run to fetch all dependencies:

1. Install Maven 3 and JDK 6

2. To build source code go to `${sample.home}` and execute the following command:
```
    mvn clean install -DskipTests
```

Running per sample project

1. Go to project module `${sample.home}\${module.dir}`.

2. Execute the following command to run test.
```
    mvn clean integration-test
```

3. View the generated report and logs from browser.

## Author

Designed and built by [Shiela D. Buitizon](https://github.com/badong2210/).

Contributor: [Alvin R. de Leon](https://github.com/alvinrdeleon/).


## Copyright and license

Copyright 2012 JSpringBot

Code licensed under [Apache License v2.0](http://www.apache.org/licenses/LICENSE-2.0).
