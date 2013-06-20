Automate the Oozie Installation
===============================
For On-Demand hadoop cluster launch, if you have to install Apache Oozie
on it, these scripts will help you with just a single command.


Pre-requisites
--------------
Note : This script is written for Cloudera's Distribution Including Apache Hadoop
and tested on CDH4 MRv1 with AWS EC2 instances.
- Hadoop cluster which is up and running with all the daemons
- Public IP of the Namenode of the Hadoop cluster
- Capistrano is installed on the client, to run a single command.
- Make sure your Hadoop cluster is running and is HEALTHY.
- Also, the port for Oozie 11000, should be made open in security groups
  of AWS -- this is for the Web UI of Oozie

Oozie operations
----------------





