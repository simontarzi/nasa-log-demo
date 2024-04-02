# NASA Server Log Analytics Workshop
## Introduction
Security breaches happen. And when they do, your server logs may be your best line of defense. We take the server-log analysis to the next level by speeding and improving security forensics and providing a low cost platform to show compliance. The dataset which we are going to use in this demo is of NASA-HTTP. It has HTTP requests to the NASA Kennedy Space Center WWW server in Florida. 
The necessary files have been preloaded to the machine which is running the Cloudera Private Cloud Base one node cluster to the 

[source,shell]
----
/nasademo/NASALogs/NASA_access_log_Aug95 - raw log file
----

This could be directly fetched from the hosts as well, also we can use minifi on the servers to collect and also prepare the raw log files and then send it to nifi, however in this short workshop the intention is to showcase the capabilities of nifi and creating a dashboard to gather insights, logs collection from edge devices is not part of this session. 

