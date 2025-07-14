# AWS-ETL-PIPELINE
it is based on aws and python for etl and data pipeline process.
In this project i created s3 bucket in aws 
in s3 bucket i created two folder one for json file and second is for flatten file
after data i created lambda function and configure it and set trigger 
using python read json file from s3 bucket and extract the data and convert into flatten file using boto3 python library
after extra data i created trigger on lambda so that when json file is upload in s3 bucket then lambda function trigger and convert json file into flatten file and
save it in s3 bucket in second folder.
after that i use glue to perform some sql problems.
