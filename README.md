![image](https://github.com/LOKESH4884/ELK-integrated-with-Zeek/assets/111216649/ddfa397c-dc1e-4842-8098-d4874df5837d)
E = Elasticsearch
Elasticsearch is a distributed search and analytics engine built on Apache Lucene. Since its release in 2010, Elasticsearch has quickly become the most popular search engine and is commonly used for log analytics, full-text search, security intelligence, business analytics, and operational intelligence use cases.
L = Logstash
Logstash is an open-source data ingestion tool that allows you to collect data from various sources, transform it, and send it to your desired destination. With prebuilt filters and support for over 200 plugins, Logstash allows users to easily ingest data regardless of the data source or type. 
K = Kibana
Kibana is a data visualization and exploration tool used for log and time-series analytics, application monitoring, and operational intelligence use cases. It offers powerful and easy-to-use features such as histograms, line graphs, pie charts, heat maps, and built-in geospatial support. Also, it provides tight integration with Elasticsearch, a popular analytics and search engine, which makes Kibana the default choice for visualizing data stored in Elasticsearch

![image](https://github.com/LOKESH4884/ELK-integrated-with-Zeek/assets/111216649/eed9fa91-f60f-4a2b-a9b5-e46f30fea867)
Zeek is an open-source network intrusion detection system and a network traffic analyzer that uses a domain-specific scripting language. With Zeek you can detect suspicious signatures and anomalies, track DNS, HTTP, and FTP activity.

ELK integrated with Zeek
This is an integration for Zeek, which was formerly named Bro. Zeek is a passive, open-source network traffic analyzer. This integrations ingests the logs Zeek produces about the network traffic that it analyzes.

Zeek logs must be output in JSON format. This is normally done by appending the json-logs policy to your local.zeek file. Add this line to your local.zeek.

@load policy/tuning/json-logs.zeek


