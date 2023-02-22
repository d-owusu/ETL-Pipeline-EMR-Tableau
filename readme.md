# # ETL-Pipeline-EMR-Tableau
Analyse sales data using  Amazon S3, EMR , Tableau to derive metrics out of the existing data

1. Create an S3 bucket in AWS
2. Upload sales data into the S3
3. Spin an EMR cluster on AWS which has required services (1 master node 2 core nodes
m5.xlarge)
4. Create Hive external table to point to the data in S3
5. Perform ETLs on Hive table and store it in final Hive table
6. Connect Hive final table in AWS EMR to tableau in local and plot the graphs
