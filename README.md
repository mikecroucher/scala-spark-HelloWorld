# scala-spark-HelloWorld
How to compile and run a 'Hello World' application on Sheffield's HPC clusters.

## Iceberg

Get the example

```
module load apps/gcc/5.2/git/2.5
git clone https://github.com/mikecroucher/scala-spark-HelloWorld
```

Enter the project directory

```
cd scala-spark-HelloWorld/
```

Load the module files for sbt and spark

```
module load apps/binapps/sbt/0.13.13 
module load apps/gcc/4.4.7/spark/2.0
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
