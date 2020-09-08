This deals with generating Extent reports for Cucumber-JVM version 6 using the ExtentReports Cucumber Adapter Plugin. For more details refer to this [article](http://grasshopper.tech/2098/)

To build from source use ```install -Dmaven.test.failure.ignore=true``` or ```install -Dmaven.test.skip=true```. This ignores intentional test failures from stopping the build.

To work with the ExtentReports version 5, which includes support for latest Spark, Klov and Json reporters, add the below dependency. The HTML and Logger report, among other reporters, have been deprecated.

```
<dependency>
    <groupId>tech.grasshopper</groupId>
    <artifactId>extentreports-cucumber6-adapter</artifactId>
    <version>2.0.0</version>
</dependency>
```

To work with the older ExtentReports version 4, add the below dependency.

```
<dependency>
    <groupId>tech.grasshopper</groupId>
    <artifactId>extentreports-cucumber6-adapter</artifactId>
    <version>1.2.0</version>
</dependency>
```
