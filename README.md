# Instagram-data-analysis-using-hadoop-and-hive
    Analyzing instagram user data with the help of hadoop and hive

#   Project Description
    Tools used in the project are hadoop and hive in hortonworks sandbox
    The dataset used in this project is taken from kaggle.
    Initially I created a directory named instadb and uplodaed the instadatset into that directory
    After that I performed various analyzing operation with the help oh hive query language.
    
#   Technologies Used
    Hadoop-version 2.7
    hive-version1.2
#   Operations performed
 ##   Creating new directory named instadb in hdfs
       hdfs fs -mkdir /user/instadb
  ##  Getting started with hive
  ##  Creating a new table  named instadata in hive
                create table  instadata (id int,age int,day int,year int,month int,gender string,tenure int,followers int,follower_init int, likes int,likes_received int,mlikes int,mlikes_received int,wlikes int,wlikes_received int) row format delimited fields terminated by ',' stored as textfile location '/user/instadb/';
#   Problem statements
    Number of users in the age group of 25 to 30.
    Analyzing which gender getting more likes.
    Partioning based on gender column
    Performing bucket operation based on age colum
    Moving hive data to hdfs
    Number of users in the age group of 25 to 30.
    Analyzing which gender getting more likes.
    Partioning based on gender column
    Performing bucket operation based on age colum
    Moving hive data to hdfs.






  
    

    
    

