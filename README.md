# Snowflake Snowpipe with AWSS3 and AWSSQS
Automating Snowpipe for Amazon S3

Reference : https://docs.snowflake.com/en/user-guide/data-load-snowpipe-auto-s3.html

Configuring Secure Access to Cloud Storage

See attached Document for screeshots of all the steps


Step 1: Configure Access Permissions for the S3 Bucket

Step 2: Create the IAM Role in AWS

Step 3: Create a Cloud Storage Integration in Snowflake

Step 4: Retrieve the AWS IAM User for your Snowflake Account

Step 5: Grant the IAM User Permissions to Access Bucket Objects

Determining the Correct Option

Option 1: Creating a New S3 Event Notification to Automate Snowpipe

Step 1: Create a Stage (If Needed)

Step 2: Create a Pipe with Auto-Ingest Enabled

Step 3: Configure Security

Step 4: Configure Event Notifications

Step 5: Load Historical Files
