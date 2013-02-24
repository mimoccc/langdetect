langdetect
==========

Language Detection Library for Java.


This is a fork from the [language-detection](https://code.google.com/p/language-detection/)
library written by Nakatani Shuyo. It includes the following modifications:

* Maven support
* Storing the language profiles in the jar file (taken from this [project](https://code.google.com/r/kurzalkacon-fromzip/) )


Maven dependency
----------------

To install the library as a Maven dependency, first you have to add the 
following repository to your `pom.xml` file:  

    <repositories>
        ...
        <repository>
            <id>cavorite</id>
            <url>http://files.cavorite.com/maven/</url>
        </repository>
        ...
    </repositories>

Then, include the library dependency:
 
    <dependencies>
        ...
        <dependency>
            <groupId>com.cybozu.labs</groupId>
            <artifactId>langdetect</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>
        ...
    </dependencies>
    
    
TODO
----

* Add some micro-benchmarks to measure the running time of most common methods. 
* Add optimizations proposed by other people:
    * https://code.google.com/r/ionutcpaduraru-language-detection
    * https://code.google.com/r/armintor-language-detection
