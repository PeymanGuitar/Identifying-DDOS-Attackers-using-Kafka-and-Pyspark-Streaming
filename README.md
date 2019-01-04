# Identifying Attackers using Kafka and Spark Streaming

This is an independent project where a customer runs a website and periodically is attacked by a botnet in a Distributed Denial of
Service (DDOS) attack. I used a log file in Apache log format from a given attack. I use
this log to build a simple real-time detector of DDOS attacks. The strategy is to find the potential attackers is 
to identifty the ips that log in to the system more than two times in every 30 seconds.
