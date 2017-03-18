# Software Architecture & Pattern Midterm Solution 2017

## How to build jar file ?

```
$ javac -cp hadoop-core-1.2.1.jar MaxTemperatureMapper.java MaxTemperatureReducer.java MaxTemperature.java
```

## How to run ?

```
$ export HADOOP_CLASSPATH=hadoop-core-1.2.1.jar
$ hadoop MaxTemperature 1901 output
```
