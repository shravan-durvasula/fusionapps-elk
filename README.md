# fusionapps-elk
ELK Stack for Log Analysis of fusionapps

# Stack Version
1. jdk1.8.0_251
2. elasticsearch-5.6.3
3. logstash-7.1.0
4. kibana-5.6.3-linux-x86_64

# Uptake Instructions
1. Install the ELK Stack and start Elastic Search and Logstash Servers
2. Copy the config files from logstash-7.1.0/config directory to target logstash directory 
3. Create "falogs" index in Elastic Search. Definition for "falogs" index isavailable at kibana-5.6.3-linux-x86_64/IndexPatterns/falogs.json 
4. Import "kibana-5.6.3-linux-x86_64/SavedObjects/SavedObjects.json" into Kibana for Dasboards
