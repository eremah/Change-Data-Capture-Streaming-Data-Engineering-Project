## OVERVIEW

Project about the simulation of generated financial transactions data using the faker python library. 
These data are then inserted into a PostgreSQL database.
Debezium is used to connect the store database data to Kafka which is controlled by the Control center and managed by Zookeeper.
Possibility of of using any of the spark technologies (Flink, Storm) for big data processing.
Notification of the change can be consumed by either slack or Telegram.




## Project Architecture

![ss-01](https://github.com/eremah/Change-Data-Capture-Streaming-Data-Engineering-Project/assets/75796623/648d97d5-d433-4e62-926c-c2700581a6da)
