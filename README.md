# Package `the application
```
$ sbt package
```

# Submit the job
```
$ YOUR_SPARK_HOME/bin/spark-submit --class "SimpleApp" --master local[4] target/scala-2.10/simple-project_2.10-1.0.jar
```
