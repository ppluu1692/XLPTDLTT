# 1. Kafka
## Start Zookeeper:
```bash
KAFKA>.\bin\windows\zookeeper-server-start.bat
```

## Start Kafka server:
```bash
KAFKA>.\bin\windows\kafka-server-start.bat
```

## Start Kafka producer
```bash
python producer.py
```

# 2. Spark
```bash
SPARK>.\bin\spark-shell
python spark.py
```

# 3. Hadoop
```bash
HADOOP>.\sbin\start-all.cmd
python hadoop.py
```

Go to localhost:9870 and check

# 4. PowerBI
 
Create Power BI dashboard that read data from HDFS

# 5. Airflow
Run the Webserver

```bash
AIRFLOW_HOME>airflow scheduler
AIRFLOW_HOME>airflow webserver
```
Go to localhost:8080 and check
