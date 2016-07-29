# power-leech
One shoot tools to Migration FROM traditional SQL DB  to AWS RedShift

# Power Data Leech is a FORK of VivaReal Data Leech

### Why ?
Redshift is a good way to analysis a lot of data!
https://www.youtube.com/watch?v=AUvn49gey8Y

Ok amazing!!! But, if I've already a traditional relational data warehouse ?

That's point! Power Data Leech will be your friend in this time :)

This tool can do:
- Read all tables in you Source database
- Export to S3 Bucket in RedShift Format
- Create in RedShift all tables in compatible Format
- Import all data from S3 !!

Unbelievable!!!!

Who to use:

1) Clone this project using git command.
2) Install python3 with pre-requisite (se bellow in pre-req session)
3) configure the file config.py with your environment
4) run main.py (I recommended strongly use Linux in SCREEN session )
https://www.howtoforge.com/linux_screen


### Important.
Remember: Leech is not a ELT tool!! To this purpose, i suggest use Pentaho PDI or Luiggi (Spotify).
Leech will help you to make a first data load from your big database to empity RedShift (One shot)

### Features
- Create automatically table on RedShift based on source table.
- Export table from source to Bucket S3 with Manifest json file
- Connect on Redshift and run the COPY command for load from S3


### Pre-requisite:
- Python3  with additional packs: smart_open, boto3, psycopg2 and sqlalchemy (use the pip command to install)
For mysql datasource you need include the mysqldb

### RoadMap
- Work with Python log
- Export to Hadoop
