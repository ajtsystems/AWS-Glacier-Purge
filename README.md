# AWS-Glacier-Purge
PowerShell Purge AWS Glacier Objects automatically
#On the bucket on AWS there is a lifecycle rule that runs on database backups older than 30 days.  
#It transitions them into Amazon Glacier where they stay indefinitely.  This script deletes all but the latest backups leaving only 1 backup (of each database if required) per month
#This yeilds a database backup going further back than the standard RDS backups can offer - at low cost.
