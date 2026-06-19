# 🐘 Hadoop HDFS Commands

## 📌 Overview

This repository contains important **Apache Hadoop HDFS (Hadoop Distributed File System) commands** with explanations and practical examples.

It helps beginners understand Hadoop file system operations and Big Data basics.

## 🚀 Technologies Used

- Apache Hadoop
- Hadoop Distributed File System (HDFS)
- Linux Terminal
- Big Data

## 📚 Topics Covered

- Starting Hadoop Services
- Checking Hadoop Processes
- Creating HDFS Directories
- Managing Files in HDFS
- Uploading Files to HDFS
- Downloading Files from HDFS
- File Permission Management
- Replication Management
- Disk Usage Checking
- HDFS Health Checking


## 📝 Hadoop Commands

| Command | Description |
|---|---|
| start-dfs.sh | Starts Hadoop Distributed File System |
| jps | Displays Hadoop running processes |
| hdfs dfs -ls / | Lists files and directories |
| hdfs dfs -mkdir /Dir | Creates directory in HDFS |
| hdfs dfs chmod 777 /Dir | Provides read, write and execute permissions |
| cat > filename.txt | Creates and writes a file |
| hdfs dfs -put filename.txt /Dir | Uploads local file to HDFS |
| hdfs dfs -get /Dir/file.txt Desktop/ | Downloads file from HDFS |
| hdfs dfs -cat filename.txt | Displays file content |
| hdfs dfs -du -h /path | Checks disk usage |
| hdfs dfs -rm -r /path | Deletes files or folders |
| hdfs dfs -stat %r file.txt | Shows replication count |
| hdfs dfs -setrep 2 file.txt | Changes replication factor |
| hdfs dfs -count / | Counts directories and files |
| hdfs fsck / | Checks HDFS health status |


## ⚡ Basic Commands Examples


### Start Hadoop

```bash
start-dfs.sh
```

### Check Running Services

```bash
jps
```

### Create Directory

```bash
hdfs dfs -mkdir /Data
```

### Upload File

```bash
hdfs dfs -put sample.txt /Data
```

### View File Content

```bash
hdfs dfs -cat /Data/sample.txt
```

### Download File

```bash
hdfs dfs -get /Data/sample.txt Desktop/
```

### Delete File

```bash
hdfs dfs -rm -r /Data/sample.txt
```


## 📁 Repository Content

```
Hadoop-HDFS-Commands

├── HADOOP COMMANDS.docx
├── README.md
└── Output Screenshots
```


## 🎯 Learning Outcomes

By completing this practice:

✔ Understand Hadoop HDFS architecture basics  
✔ Perform file operations in HDFS  
✔ Manage directories and permissions  
✔ Work with replication settings  
✔ Check Hadoop cluster status  


## 👨‍💻 Author

**Mukeshkumar M**

### Skills

- Python
- SQL
- Hadoop
- HDFS
- PySpark
- Snowflake
- Power BI
- Data Analytics


⭐ If you like this repository, give it a star!
