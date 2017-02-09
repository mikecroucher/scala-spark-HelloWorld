# scala-spark-HelloWorld
Hello word in scala+spark on Sheffield's HPC sluster

## Iceberg

```
module load /apps/binapps/sbt/0.13.13 
module load /apps/gcc/4.4.7/spark/2.0
```

Compile with 

```
sbt package
```

If this is successful, you'll have a file in the location `target/scala-2.11/hello_2.11-1.0.jar`.

Run with

```
spark-submit --master local[1] target/scala-2.11/hello_2.11-1.0.jar
```
