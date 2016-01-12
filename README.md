# spark-hello-world
A sample app demonstrating a word count example

1. Build using - mvn clean package
2. Create a topic - testtopic in kafka
3. Submit the jar to spark using - ./bin/spark-submit --class org.sparkexample.JavaKafkaWordCount --master local[2] /mnt/media/Projects/rnd/spark/spark-kafka-poc/target/first-example-1.0-SNAPSHOT-jar-with-dependencies.jar localhost default testtopic 1
4. Create a producer for above topic and submit messages.
