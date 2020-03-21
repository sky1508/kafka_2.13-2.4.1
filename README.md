# kafka_2.13-2.4.1
Kafka Setup for Windows

This is running setup of kafka on windows 10.

After cloning/downloading, follow the below instructions to run the kafka on your local machine:

0. java should be configured in classpath, you should be able to run java cmd in cmd prompt from any folder in your system
  If not, then first fix that.

1. Go to config & open server.properties file (remember the slashes)
  Update the path of log.dirs=F:/Dev/Kafka/kafka-logs (update according to your system)
  
2. Go to config & open zookeeper.properties file (remember the slashes)
  Update the path of dataDir=F:/Dev/Kafka/zookeeper (according to your system)

3. Open cmd window in kafka dir (not in bin or any other folder, this is kafka dir outside of bin or config)
  Run the cmd - .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
  This will start the zookeeper, next follow the cmds in Kafka cmds.txt file in this project
