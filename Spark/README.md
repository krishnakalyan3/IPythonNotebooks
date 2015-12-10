# My Spark Code
Learning Spark : [Apache Spark Website](http://spark.apache.org/)  
[Code](https://github.com/zipfian/building-spark-applications-live-lessons) and [Data Download](https://s3.amazonaws.com/galvanize-example-data/spark-live-lessons-data.zip) can be found in the link.

###### Installing Spark and IPython Notebook    
Install Docker Machine for Mac
```
docker run -d -t -p 8888:8888 prabeeshk/pyspark-notebook 
docker ps
docker-machine ls
docker exec -it <Container Name to SSH> bash
docker stop 4bdb590703e4
```

IP can be obtained by docker-machine ls
Use your web browser with http://<IP>:8888 or http://<IP>:8888  
Check if your container is running  
More on Docker Machine @ https://docs.docker.com/v1.8/installation/mac/  
Docker Cheat Sheet https://github.com/wsargent/docker-cheat-sheet  

###### Alternative Install
Spark Download page prebuilt for Hadoop 2.6 and later    
Download [spark-1.5.2-bin-hadoop2.6.tgz](http://d3kbcqa49mib13.cloudfront.net/spark-1.5.2-bin-hadoop2.6.tgz)
