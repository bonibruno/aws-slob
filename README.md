## Oracle instance scripts

These scripts are provider so you can easily deploy an EC2 instance, install Oracle on the instance and then create database using either Lightbits or io2/io2.be EBS volumes.

**Note:** make sure to change the KEY, PSSH and PSCP in all the relevant scripts to point to the correct path of these files.

**Note:** if you are using 7.create_volumes to create EBS volumes, the clients running oracle **must** have the AWS cli installed, must have a proper configuration file to use the AWS cli and must be logged with the same account that created the EC2 instance. In EBS mode this script will create io2/io2.be volumes and attached to the instance. 

**Note:** In 6.copy_oracle_home, make sure to change the ORACLE_HOME_ZIP variable to the correct path file of your oracle zip download.
