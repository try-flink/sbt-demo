## How to run it

> 如果使用Java需要加载scala依赖包，注意是冒号相隔`:`。如果是scala，就不需要了。


```bash
sbt package

scala -classpath target/scala-2.12/scala-test_2.12-0.1.0-SNAPSHOT.jar org.example.Hi

java -classpath /Users/ydl/.sbt/boot/scala-2.12.10/lib/scala-library.jar:target/scala-2.12/scala-test_2.12-0.1.0-SNAPSHOT.jar org.example.Hi
```
