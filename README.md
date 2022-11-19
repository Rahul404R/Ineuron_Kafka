# confluent-kafka-python


This repo help us to know how to 

## Process flow
To publish and consume data to and from kafka confluent in json format.

1. Gather CSV Data from sample directory for Topic
2. Create a schema structure from the csv file
3. Generate a json file using  json producer
4. Input the schema structure, json file & Kakfa producer config file to push the json file into Kafka producer
5. Insert the streamlined data into MongoDB using json consumer.
6. create a log file to track and monitor the flow and errors
