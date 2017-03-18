# Software Architecture & Pattern Midterm Solution 2017

## How to build jar file ?

```
$ javac -cp hadoop-core-1.2.1.jar MaxTemperatureMapper.java MaxTemperatureReducer.java MaxTemperature.java
$ jar cvf MaxTemp.jar *
```

## How to run ?

```
$ export HADOOP_CLASSPATH=MaxTemp.jar
$ hadoop MaxTemperature 1901 output
```
