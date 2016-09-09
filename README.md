# CS2340 Project Repository for Team 48 
[![Build Status](https://circleci.com/gh/guyfleeman/CS2340.svg?&style=shield)](https://circleci.com/gh/guyfleeman/CS2340) 

## Build Prerequisites
Gradle must be installed either through your *nix package manager or by manual download. Gradle version 2.10 or greater is required.

## Building the Project
### Compile Java Source
`$ gradle compileJava`

### Run Tests
Tests will fail if code is not written to Sun Style standards.
`$ gradle test`

### JFX Jar
You can test the embedded JavaFX jar.
`gradle jfxJar`

### JFX Native
You can build a native deployment package for your platform (bundled with the test JVM for version). Note: building a native package has to compress the JVM and will take a few minutes even on a powerful machine.
`gradle jfxNative`

### Checkstyle
`gradle checkstyleMain`
