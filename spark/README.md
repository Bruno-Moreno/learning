# SPARK

## Introduction

**Apache Spark** is an open-source data processing engine to store and process data in real-time across various clusters of computers using simple programming constructs. (Support various programming languages)

 - It's faster than Hadoop (within MapReduce) because is done in-memory. 
 - Performs batch processing & real-time processing. (Hadoop only performs batch processing)
 - Implemented in Scala (Hadoop in Java)

Important Spark features: 

 - Fast Processing: Using Resilient Distributed Datasets (RDD) witch saves times reading and writing. 
 - In-Memory Computing: Data is stored in RAM. 
 - Multiple programming languages. 
 - Loss of data reduced to 0 because of the RDD. 
 - Analytics supported. 

 ## Components

 - Spark Core: Contains the RDD for large scale parallel and distributed data processing. 
 - Spark SQL: Execute Querys 
 - Spark Streaming: Create streaming applications, transform and analyze the data. 
 - Spark MLlib: Machine learning algorithms & analytics. 
 - GraphX: Data that should be represented with graphs. 


On RDD we can perform two operations, Transformation (which yealds to a new RDD object) and Action (which results in a value after the computation). RDD are inmutable. 


## Instalation (MacOS)

Make sure that you have *homebrew* installed:

1. ```brew install openjdk@17```
2. ```brew install scala``` 
3. ```brew install apache-spark``` 

Spark gets instalated at (*/opt/homebrew/Cellar/apache-spark/*)

