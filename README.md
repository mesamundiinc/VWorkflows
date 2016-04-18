VWorkflows
==============

[![Build Status](https://travis-ci.org/miho/VWorkflows.svg?branch=master)](https://travis-ci.org/miho/VWorkflows)

Workflow API with UI bindings for JavaFX.

<img src="https://github-camo.global.ssl.fastly.net/17875864fac438811e1b42cae32dec12fa2a88ae/687474703a2f2f6661726d342e737461746963666c69636b722e636f6d2f333732382f393936363336373836355f353438656634653331335f7a2e6a7067">

See [http://mihosoft.eu/?p=523](http://mihosoft.eu/?p=523) and [http://mihosoft.eu/?p=564](http://mihosoft.eu/?p=564) 
for an introduction.

Join the [Developer Group](https://groups.google.com/forum/#!forum/vrl-developers) if you'd like to contribute.

## Maven Coordinates

VWorkflows-Core:

    <dependency>
      <groupId>eu.mihosoft.vrl.workflow</groupId>
      <artifactId>vworkflows-core</artifactId>
      <version>0.2</version>
    </dependency>

VWorkflows-FX:

    <dependency>
      <groupId>eu.mihosoft.vrl.workflow</groupId>
      <artifactId>vworkflows-fx</artifactId>
      <version>0.2</version>
    </dependency>

## How To Build

### Reqirements

- Java >= 1.8.0_60
- Internet connection (other dependencies are downloaded automatically)
- IDE: [Gradle](http://www.gradle.org/) Plugin (not necessary for command line usage)

### IDE

Open the `VWorkflows` [Gradle](http://www.gradle.org/) project in your favourite IDE (tested with NetBeans 8.1) and build it
by calling the `assemble` task.

### Command Line

Navigate to the [Gradle](http://www.gradle.org/) project (e.g., `path/to/VWorkflows`) and enter the following command

#### Bash (Linux/OS X/Cygwin/other Unix-like OS)

    ./gradlew assemble
    
#### Windows (CMD)

    gradlew assemble
    
## Test It

Besides the tests defined in `VWorkflows-Core` (`test` task) it is also possible to run a graphical demo that comes with 
`VWorkflows-DEMO` subproject. To run it call the `run` task.
