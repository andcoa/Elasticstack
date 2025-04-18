# Elastic Stack

## Objective

To use the Elastic Stack (ELK)—Elasticsearch, Logstash, and Kibana for centralized log collection, analysis, and visualization in a SOC environment. Focused on using Kibana to identify and investigate security incidents through real-time dashboards and queries.

## Skills Learned

- 📈 Data Visualization with Kibana: Built dashboards and visualizations to monitor system activity, detect anomalies, and investigate security alerts.
- 🧠 Elasticsearch Querying: Queried indexed data using Kibana’s Lucene-based syntax to filter, analyze, and trace suspicious events.
- ⚙️ SIEM Integration: Leveraged Elastic Security features to simulate real-world SOC use cases such as user behavior monitoring and threat hunting.
- 🚨 Alert Investigation: Analyzed log patterns to identify potential IOCs (Indicators of Compromise) and respond to security events.

## Tools Used

- Kibana – Web UI for data visualization and querying logs stored in Elasticsearch.
- Elasticsearch – Scalable search and analytics engine for storing and indexing log data.

## Exercises

Finding the IP address with maximum number of connections.

![image](https://github.com/user-attachments/assets/d5626e57-4789-4abb-b120-10346430db1b)

Finding which user is responsible for the most traffic

![image](https://github.com/user-attachments/assets/c5eee2db-a0c3-4716-af83-84d699f33f81)

Filtering for user Emanda to find out which sourceIP has the most hits for said user:

![image](https://github.com/user-attachments/assets/21e94d36-6be5-4429-a5de-0d38b6dc6592)

Checking the number of connections from a specific IP in the New York state:

![image](https://github.com/user-attachments/assets/340922dd-f046-4535-87d4-9ef24bcaf296)

KQL (Kibana Query Language):
Created a chart to visualize the correlation between Source_Country and Source_IP.

![image](https://github.com/user-attachments/assets/79357fcc-a8e9-4893-99bf-2e9d6bc2f684)

