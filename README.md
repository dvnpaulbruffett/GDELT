# GDELT Dataset Analysis

###Description
>Supported by Google Jigsaw, the GDELT Project monitors the world's broadcast, print, and web news from nearly every corner of every country in over 100 languages and >identifies the people, locations, organizations, themes, sources, emotions, counts, quotes, images and events driving our global society every second of every day, >creating a free open platform for computing on the entire world.

###Lab Description
This dataset is already hosted in Amazon Web Services for free, in this lab we will be accessing the data hosted in S3 and analyzing it using Amazon Athena

[AWS Dataset Description](https://aws.amazon.com/public-datasets/gdelt/)

For this lab we will use the SQL scripts in this repository to create dimension tables and access the GDELT data as the dimension tables.

To explore the dataset using the AWS CLI;
```
aws s3 ls gdelt-open-data/events/

aws s3 cp s3://gdelt-open-data/events/20171226.export.csv 20171226.export.csv
```