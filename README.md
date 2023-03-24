------------------------------------------------------------------------------------------------------
--------------- ETL PIPELINE FOR PREPARING STOCK MARKET DATA IN AWS CLOUD USING KAFKA ----------------
------------------------------------------------------------------------------------------------------

python version == 3.9.13

STEPS:

    1. CREATE A RAPID API ACCOUNT AND GET YOUR API KEYS FOR ACCESING YAHOO FINANCE DATA.

    2. CREATE A EC2 INSTANCE IN AWS AND INSTALL KAFKA ON IT (FOLLOW prepare_kafka_in_ec2.txt).
    
    3. CREATE AN S3 BUCKET IN AWS FOR STORING THE DATA COMING FROM KAFKA.

    4. STORE ALL NEEDED CREDENTIALS IN A config.ini FILE.

    5. CREATE A CRAWLER IN AWS FOR THE S3 BUCKET CREATED IN STEP 3.

    6. ACCESING DATA USING AWS ATHENA.