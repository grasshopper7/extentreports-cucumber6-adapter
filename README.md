This deals with generating Extent reports for Cucumber-JVM version 6 using the ExtentReports Cucumber Adapter Plugin. For more details refer to this [article](http://grasshopper.tech/2098/). A sample usage of this adapter can be found [here](https://github.com/grasshopper7/cuke6-extent-adapter-report).

To build from source use ```install -Dmaven.test.failure.ignore=true``` or ```install -Dmaven.test.skip=true```. This ignores intentional test failures from stopping the build.

To work with the latest [ExtentReports version 5](https://github.com/extent-framework/extentreports-java/wiki), which includes support for latest Spark, Klov and Json reporters, add the below dependency. The HTML and Logger reporters, among others, have been deprecated.

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
